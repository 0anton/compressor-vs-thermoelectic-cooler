# How it is started

Several days a go I was on the camp site with friends. I was used to autonomous style hiking in Alps, where you limited to the weight you can carry, so the food is very basic. On the camp site you come with the car (or friends car) and can carry much more with you and allow much bette food ration. I like fresh milk products a lot, grilling fish and meat on the nature is also a great delight. I started using a 8l cool box from Decathlong with two 1,5l frozen bottles. I liked it a lot - now I can take my jogurts, quark, fresh fruits and even meat. Previously it all get trashed, sometimes even during the ride to the campsite, e.g. in Austria, after 4h ride. Now it stayed fresh for 1.5 days! And the enjoyment from staying on nature increased a lot, because you have good healthy food with you. But one day I had to stay longer than 2 days, the frozen water in bottles has melted and the fruits and meat get spoiled. That‘s a pity! It smells, it is inconvenient, because you rely that you have some food with you, but instead you have to look for the shops in the time, where you just wanted to eat.

I noticed that many of my friends are using cool boxes, which are connected to electricity. I was not experienced that time in such campaign equipment, so I‘ve start asking. The idea of having a fridge on the campsite amazed me: no longer playing lottery with frozen bottles, no more smelly wasted food in the cooling compartment, delicious healthy food is always with you. Isn’t that cool?

I‘ve started asking, checking forums and found out there are two systems (okey there is also one „absorbing“ cooling system, which can also operate from gas, but since I don‘t carry large gas balloons with me I discarded this idea): thermoelectric and compressor. The first I met already in hotels - it is really absolutely quiet. It is a semiconductor plate, which get’s cold on one side and hot on the other side, when the current is applied to it. The second - is a typical fridge system with a circulating coolant, which compressed to liquid, transported to a radiator and evaporated their, acting as a heat pump.

100% of my friends had thermoelectric devices. Those devices were also affordable (some under $100), of convenient size and with handy carry handle. So, it was obviously a best choice, considering that a lot of other campers were using them too.

But I was a bit unsure after I read some forums, where experienced campers exchanged on ideal cooler for the campsite. Many of them complained that thermoelectric devices were too weak to cool down food or beverages on the warm day if they were warm and placed into compartment in the reasonable time. Some complained that the thermoelectric system cannot maintain temperature different over 15 degrees below the ambient temperature. Remembering that we had weeks of over +35 °C and up to +40 
     

 
Mobicool MCF40 Compressor Cooler
Campingaz Powerbox Plus Thermoelectric 12 V/230 V Cool Box, 24 liter


# Candidates

### Campingaz Powerbox Plus Thermoelectric 12 V/230 V Cool Box, 24 liter

From Amazon [1] description:

- Very quiet, powerful electric cool box can be operated either via the normal 230 V socket or the 12 V connection of a vehicle
- Efficient insulation: with PU full foam core filling, tight-fitting lid with recessed grip for easy opening; cooling capacity up to 18° below ambient temperature
- Large capacity: 24 litre capacity for food and drinks, 1.5 litre bottles can be stored standing
- Stable, movable handle; ultra-quiet fan (36 dB); power control by adjusting dial with 4 modes: off, night mode, eco mode, max mode; energy efficiency class A++


### Mobicool MCF40 Electric Compressor Mini Fridge 32l

From Amazon [2] description:

- Continuous temperature adjustment from +10°C to -10°C, digital display
- 31 litre volume, space for upright 1 litre bottles
- Electric cool box for 12 V DC, 24 V DC and 230 V AC connection


# Measurement results

## Cooling efficiency

## Noise levels

## Power consumption




# 2. Measurement system

## Temperature measurement

For temperature measurement I've took [Aqara temperature sensor](https://www.aqara.com/us/temperature_humidity_sensor.html) for its preciseness (0.3°C according to manufacturer) and low inertion. Sensor polls data frequently (at least every 10 seconds) and sends the update if the value has changed above the threashold.

## Power measurement

For power measurement I've took [Aqara Smart Plug](https://www.aqara.com/eu/smart_outlet.html). It has accumulating, increasing counter for energy use and momentary power consumption sensort. Poll times upto 1s (1HZ) if the measured value change comes other the threashold.

## Noise level measurement

I took app DecibelX v.9.5.0 running on my iPhone 11 Pro Max iOS 15.6.

# Results & conclusion

![](assets/bottles_setup.jpg)![](assets/compressor_cooler_label.jpg)![](assets/compressor_cooler_look.jpg)![](assets/cooling_mode.jpg)![](assets/noise_compressor.jpg)![](assets/noise_thermoelectric.jpg)![](assets/noise_thermoelectric_eco_mode.jpg)![](assets/smart_plug_aqara.jpg)![](assets/thermoelectirc_spec.jpg)![](assets/thermoelectric_cooler_look.jpg)![](assets/thermometer_aqara.jpg)


# Appendix 1. Links

1. [Campingaz Powerbox Plus Thermoelectric 12 V/230 V Cool Box, 24 liter](https://www.amazon.de/gp/product/B01M3UUO36/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)

2. [Mobicool MCF40 Electric Compressor Mini Fridge 32 liter](https://www.amazon.de/gp/product/B07ZTPGY9R/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1) ~ €300.

3. [Aqara Temperatur- und Feuchtigkeitssensor](https://www.amazon.de/-/en/WSDCGQ11LM/dp/B07D37FKGY/ref=sr_1_10?keywords=aqara&qid=1660485019&sprefix=aq%2Caps%2C104&sr=8-10) ~ €117.

4. [Aqara Smart socket](https://www.amazon.de/requires-programming-control-monitoring-Assistant/dp/B087M8LF63/ref=sr_1_6?keywords=aqara&qid=1660485019&sprefix=aq%2Caps%2C104&sr=8-6)


5. [Quiet level measurement](https://youtube.com/shorts/rjtmXLIjEfA).
6. [Noise level Campingaz Powerbox Plus Thermoelectric running Eco Mode](https://youtube.com/shorts/fag9p1yz-V4)
7. [Noise Level recording for Mobicool MCF40 Compressor Cooler 32 l](https://youtube.com/shorts/PUXMgJ_BR3w?feature=share)


# Feedback and corrections

# Disclamer & copyright

I'm not affiliated with any vendor of used equipment. I bought all equipment on my own money. I publish this results for my later self and anybody who may find it useful. Attribution and source link is required to this original work is required.


If you found any inaccuracy 
