# Fish-Feeder
Set up a hydroponic garden / fish tank installation using a hardware such as sensors that could measure the temperature pH and water depth in the fish tank and help determine when the pump needs to be turned on.
# Problem Statement:
For our team project, the group was tasked to set up a hydroponic garden / fish tank installation using a hardware such as sensors that could measure the temperature pH and water depth in the fish tank and help determine when the pump needs to be turned on. Using Python, the group has interacted an Arduino to dynamically collect sensor data and record the temperature over a set amount of time with the temperature displayed at regular intervals.


## Hardware Setup
### Bill of Materials

|component|vendor|
|---|---|
|Arduino|[SparkFun RedBoard - Programmed with Arduino](https://www.sparkfun.com/products/13975)|
|Breadboard|[Connect Circuit	Breadboard - Self-Adhesive](https://www.sparkfun.com/products/12002)|
|Base|[Hold Boards	Arduino and Breadboard Holder](https://www.sparkfun.com/products/11235)|
|USB Cable|[Connect to Computer	SparkFun USB Mini-B Cable - 6 Foot](https://www.sparkfun.com/products/11301)|
|Jumper Wires|[Circuit Connections	Jumper Wires Standard 7" M/M - 30 AWG (30 Pack)](https://www.sparkfun.com/products/11026)|
|Stepper|[Motor	Drive Feeder	Stepper Motor with Cable](https://www.sparkfun.com/products/938)|
|Motor Driver|[Control Motor	EasyDriver - Stepper Motor Driver](https://www.sparkfun.com/products/12779)|
|Photocell	Light|[Sensor	Mini Photocell](https://www.sparkfun.com/products/9088)|
|Green LED|[Ready Indicator	LED - Basic Green 5mm](https://www.sparkfun.com/products/9592)|
|Yellow LED|[	Run Indicator	LED - Basic Yellow 5mm	](https://www.sparkfun.com/products/9594)|
|Red LED|[Error Indicator	LED - Basic Red 5mm	](https://www.sparkfun.com/products/9590)|
|3 x 330 Ω Resistor|[	Limit Current	Resistor 330 Ω 1/6th Watt PTH](https://www.sparkfun.com/products/8377)|
|1 x 10k Ω Resistor|[	Divide Voltage	Resistor 10k Ω 1/6th Watt PTH](https://www.sparkfun.com/products/8374)|


### Fritzing Diagram

![Alt-text](/doc/fritzing_temp_sensor_redboard.png "Alt-title")



![Alt-text](/doc/temp_sensor1.jpg "Alt-title")

Arduino is connected to the computer via a mini-USB 

## Arduino Code
The [mapo.ino](mapo.ino) sketch was uploaded on the Arduino using the Arduino IDE.

## Python Code

The [mapo.py](mapo.py) script was run in MATLAB.

## Results

![Alt-text](/Results - Thingspeak Status.png"Alt-title")

## Future Work

This project was quite interesting to set up the hydroponic fish garden. While using Python, the program was taking time initialize the code itself to get some values of the temperature vs time. For future work, another group could write a program that can control not only the temperature but other aspects such as the lighting, water flow/waste inside the fish garden. And all of these could be fully automated and controlled remotely using a smartphone.
Results:
 

## License
The MIT License Copyright <2019> <Team Fish Food>










