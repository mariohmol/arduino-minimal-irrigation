# arduino-minimal-irrigation
How to use minimal resources in Arduino to configure a widget to make irrigation in your house

This uses arduino, RTC and a relay. This is not using water sensors, temperature or humidity. If is a rain day/period, just turn off the arduino.

## Arduino

You will need just:

* Arduino Uno or similar (with power cabble + USB cable to configure )
* Relay : Turn the water for irrigation on/off. I will use 4 in this example.
* Solenoid : Change the water register to open or close the water for irrigation, activated by the relay. I will use 4 in this example. 
* RTC: Is possible to use without that, simulating hours using EEPROM/Software, but i will use on in this example. If you would like to see how to make it, check this link : https://github.com/mariohmol/arduino-minimal-heating-solar
* Wires and breadboard

Project is:

![alt tag](https://raw.github.com/mariohmol/arduino-minimal-irrigation/master/irrigation.png)



## Libs

You have to install those libraries:

* https://github.com/PaulStoffregen/Time
   * DateTime and DatetTimeStrings

## Install

Load MinIrrigation that can be found here


## Runnning

TODO


### Configuration

TODO
