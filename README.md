# Garden Automation using Arduino

### 				Work in Progress

### Team Members

- Sriram R 
- Eshaan Arora
- Adity
- Shruti Sharma



### Objective 

In this project, we will be developing a completely automated gardening system. 

By  "_completely automated_", we ensure that this Arduino circuit can take care of the growth of a plant without the need for any human intervention inside the house. 

### Materials needed

- [Arduino Uno](https://www.amazon.in/Generic-ATmega328P-Compatible-ATMEGA16U2-Arduino/dp/B015C7SC5U/ref=sr_1_4?s=industrial&ie=UTF8&qid=1521280305&sr=1-4&keywords=arduino)
- [Breadboard](https://www.amazon.in/Generic-Elementz-Quality-Solderless-Piecesb/dp/B00MC1CCZQ/ref=pd_bxgy_328_img_2?_encoding=UTF8&psc=1&refRID=2G7A7Y9HZF62ZM33Q7S9)
- [Jumper Wires](https://www.amazon.in/gp/product/B072FLQBQ4/ref=ox_sc_act_title_1?ie=UTF8&psc=1&smid=AT95IG9ONZD7S)
- [Soil Moisture Sensor](https://www.amazon.in/gp/product/B00XU8MJ4E/ref=ox_sc_act_title_2?ie=UTF8&psc=1&smid=A3II2Q67VJD3XT)
- [Temperature and Humidity Sensor](https://www.amazon.in/gp/product/B00YCF0NMY/ref=ox_sc_act_title_3?ie=UTF8&psc=1&smid=AT95IG9ONZD7S)
- [Photo Resistor](https://www.amazon.in/Robo-India-LDR-Ldr-Dependent/dp/B00WO3VCD0/ref=sr_1_1?ie=UTF8&qid=1521280519&sr=8-1&keywords=photoresistor)
- [DC 12V Mini Water Pump + Pipe](https://www.amazon.in/Pump-Water-Priming-Spray-Mini/dp/B01GBDBOEA/ref=pd_sbs_328_1?_encoding=UTF8&psc=1&refRID=5240V4QHBVFFBB52H97T)
- [Yellow LED array](https://www.amazon.in/PGSA2Z-3mm-LED-Yellow-PCs/dp/B074L4QCQG/ref=sr_1_6?s=industrial&ie=UTF8&qid=1521280678&sr=1-6&keywords=yellow+led)
- Box with soil
- Enclosure

### Overview

This project can be split into 3 conditions

1. Soil Moisture
   Soil moisture is necessary for the plants to grow and we measure this using the soil moisture sensor. So when this analog input value goes below the `minimum_soil_moisture` constant, the water pump turns on pumping water to the soil.
2. Incoming Light
   The incoming light is measured in terms of **lux** by the Photo Resistor. We keep adjusting the value to keep the light optimal.
3. Air temparature 
   If the air temperature gets high, the leaves start drying up, so to prevent that when the sensor reading crosses the `max_air_tempature` constant, the water pump sprays water in air from the top of the enclosure.

### Circuit Diagram 

W.I.P

### Source code

W.I.P

