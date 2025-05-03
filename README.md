# ZigBee Fenster- Türsensor Überwachung - Node-RED Flow

## Overview
This Node-RED flow is designed to monitor a ZigBee-based WC (restroom) window sensor. It detects the window status (open/closed) and monitors the sensor's battery level. Relevant state changes trigger Pushover notifications.

## Features
Window Status Detection: Identifies whether the window is open or closed.  
Battery Status Monitoring: Keeps track of the sensor's battery level.  
Notification System: Sends Pushover notifications when the window is opened or the battery level is low.  

## Requirements
Node-RED installed
ZigBee sensor compatible with Node-RED
Pushover credentials to use the notification feature

## Installation
Install Node-RED on your desired system.  
Import the flow into Node-RED.  
Enter your Pushover credentials.  
Activate and test the flow.  

## Usage
The flow runs automatically in the background and monitors the sensor.  
A push notification is sent if the window is opened or the battery is low.

## License
This project is licensed under the MIT License.

## Contact
For questions or improvements, feel free to open an issue on GitHub or submit a pull request.
