#CapacitiveSensor Library#

CapacitiveSensor lets you create sensors that can detect touch or proximity. 

http://www.pjrc.com/teensy/td_libs_CapacitiveSensor.html

http://playground.arduino.cc/Main/CapacitiveSensor

http://www.youtube.com/watch?v=BHQPqQ_5ulc

CapacitiveSensor was originally written by Paul Badger and is now maintained by Paul Stoffregen.

![CapacitiveSensor Demo](http://www.pjrc.com/teensy/td_libs_CapacitiveSensor_1.jpg)

#Modification from original#

The methods **capacitiveSensor** and **capacitiveSensorRaw** are renominated in **read** and **readRaw**

This version doesn't require a receivePin on instance creation.

The receivePin will be necessary on read and readRaw.
 
