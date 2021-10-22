# Robot Control Lite Library for Arduino

The Arduino Robot has a number of built in sensors and actuators. The library is designed to easily access the robot's functionality.

For more information about this library please visit Arduino at:
http://www.arduino.cc/en/Reference/RobotLibrary

Robot_Control_Lite is the stripped down version of the Arduino Robot Library. It saves memory space of the ATMEGA32u4 MCU on the Robot Control Board. A lower memory footprint of the robot base system allows for example the use of the *rosserial_client* for Arduino: http://wiki.ros.org/rosserial_arduino

The robot features that are no longer supported in this library are:
* LCD screen
* Squawk sound synthesizer
* FAT16 file system support for SD cards

For the Robot_Control_Lite library, now use:

`#include <ArduinoRobotLite.h>`


RobotControl Constructor
```    
    begin()
    setMode()
    pauseMode()
    isActionDone()
    lineFollowConfig()
    digitalRead()
    digitalWrite()
    analogRead()
    analogWrite()
    updateIR()
    knobRead()
    compassRead()
    keyboardRead()
    waitContinue()
    motorsWrite()
    motorsStop()
    turn()
    pointTo()
    *beginSpeaker()
    *playMelody()
    beep()
    *playFile()
    *tuneWrite()
    *tempoWrite()
    *beginTFT()
    *text()
    *drawBMP()
    *debugPrint()
    *clearScreen()
    *displayLogos()
    *drawCompass()
    *beginSD()
    userNameRead()
    userNameWrite()
    robotNameRead()
    robotNameWrite()
    cityNameRead()
    cityNameWrite()
    countryNameRead()
    countryNameWrite()
```
*) methods no longer exists.

== License ==
Copyright (c) Arduino LLC. All right reserved.
Copyright (c) Bill Porter. All right reserved.
Copyright (C) 2008 by William Greiman. All right reserved.
Copyright (c) 2013 Adafruit Industries.  All rights reserved.

This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301 USA
