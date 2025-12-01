# MQ2 Gas detector 

The MQ2 is a gas sensor that detects the presence of certain gases by changing its internal resistance.
It’s a chemiresistor, meaning its electrical resistance changes when exposed to specific gases.

Commonly used in safety and home automation projects for detecting leaks and smoke.

*Note: The sensor becomes very **hot** after a while, don’t touch it!*

### HOW IT WORKS? 

THE MQ2 can detect gases when their concentrations are between 200 and 10,000 parts per million (ppm).

Reference image : [here](https://github.com/kingston-hackSpace/MQ2_Gas_detector/blob/main/smokepicture.webp)

### WHICH GAS?
It can detect:
- LPG (liquefied petroleum gas)
- smoke
- alcohol
- propane
- hydrogen
- methane
- carbon monoxide

*NOTE! The MQ2 can detect many gases, but it cannot identify which one specifically. It only tells you that gas concentration has changed.*

### MORE INFO : 

[How MQ2 Gas Sensor works?](https://www.youtube.com/watch?v=SqONrFwa4PA&t=386s) 

[In depth: How MQ2 Gas/Smoke Sensor Works?](https://lastminuteengineers.com/mq2-gas-senser-arduino-tutorial/)


----
# TUTORIAL
----
### HARDWARE

- ARDUINO UNO
- MQ2 Gas detector

----
### WIRE
Diagram reference image : [here](https://github.com/kingston-hackSpace/MQ2_Gas_detector/blob/main/GasDetec.png)

----
### CODE AND INSTRUCTIONS

- Upload [this code](https://github.com/kingston-hackSpace/MQ2_Gas_detector/blob/main/MQ2.ino) to your Arduino board
  
- Open the Arduino's Serial Monitor, you can now see the sensor's incoming data.

----
### FURTHER LEARNING
[Tutorial : Arduino UNO with MQ-2 Gas Sensor and LED Indicator](https://docs.cirkitdesigner.com/project/published/525709eb-07ba-45ef-baf3-ba602e1b8e00/arduino-uno-with-mq-2-gas-sensor-and-led-indicator)

[Tutorial : MQ2, LED and Buzzer](https://www.bing.com/videos/riverview/relatedvideo?q=mq2+arduino+led&mid=BF3F8CBF0B9CA3BC9FA4BF3F8CBF0B9CA3BC9FA4&FORM=VIRE)


