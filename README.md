# Simple Garage Control and Status Monitoring

Control and automate your Garage Doors.
This is a simple solution to control your garage door using an ESP microcontroller and ESPHome  The intent of this is to monitor and automate a regular motorized garage.
The motivation of this really simple solution was to have local control via Home Assistant.  I was using the myQ integration which is dependent on the cloud and also no longer has a working external API ans of October 2023
This is really simple, but it is documented here for you to do. 

## Features
- Monitor your garage door status (open/closed)
- Control remotely your garage door
- Integrate to home assistant via ESPhome
- Full local control - no cloud dependency
- Works with old and new garage door openers

## Hardware Requirements
- ESP32 or esp8266 microcontroller with a power adapter
- An unused garage opener that you can devote to this - it will be modified.  You can use it again, but it needs to be connected all the time to the ESP32
- A contact sensor to detect the state of the garage door (any zigbee or zwave contact/door sensor will do!)

## Software requirements
- Ability to flash ESPhome on a microcontroller - see ESPhome website
- Home assistant installed and working in your environment

## Hardware Skills
- Very basic soldering skills

# Theory of operation
