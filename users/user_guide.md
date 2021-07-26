Using the robot sensors and actuators
=====================================

Disclaimer: This purpose of this document is to explain and showcase some of the
sensors and actuators that the https://github.com/FRUK-Simulator/Simulator robot
offers.  Given that this project is under active development any information given
here might be out of date by the time you read this.

How can I find out which sensors and actuators the robot has?
-------------------------------------------------------------

The source of truth for this information is the `StdWorldBuilder`.  Its `build` method
creates the robot's specification:
https://github.com/FRUK-Simulator/Simulator/blob/1c22f92dcdc500bc9b11348f2ff3a46da8d0aa9a/src/RobotSimulator/StdWorldBuilder.ts#L21-L107 

In particular we can see the following:
1. A (analog) distance sensor on channel 0.
2. A grabber that can be instructed to close by sending 'off' on the digital channel 0. The grabber can be instructed to close by sending 'on' on the digital channel 0.
3. A (analog) gyroscope sensor on channel 2.

Demo program distance sensor
----------------------------
Import the [demo](sample_programs/DistanceSensorDemo.json)

Demo program grabber actuators
------------------------------
Import the [demo](sample_programs/GrabberDemo.json)


Demo program gyroscope sensor
-----------------------------
Import the [demo](sample_programs/GyroSensorDemo.json)
