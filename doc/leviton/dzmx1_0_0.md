---
layout: documentation
title: DZMX1 - ZWave
---

{% include base.html %}

# DZMX1 Scene Capable Push On/Off
This describes the Z-Wave device *DZMX1*, manufactured by *Leviton* with the thing type UID of ```leviton_dzmx1_00_000```.

The device is in the category of *Wall Switch*, defining Any device attached to the wall that controls a binary status of something, for ex. a light switch.

The DZMX1 does not permanently listening for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. The wakeup period can be configured in the user interface - it is advisable not to make this too short as it will impact battery life - a reasonable compromise is 1 hour. The wakeup period does not impact the devices ability to report events or sensor data. The device can be manually woken with a button press on the device as described below - note that triggering a device to send an event is not the same as a wakeup notification, and this will not allow the controller to communicate with the device.

## Overview

No device information is provided in the database. Consider [updating the database](http://www.cd-jackson.com/index.php/zwave/zwave-device-database/zwave-device-list/devicesummary/196) to improve the documentation.

## Channels

The following table summarises the channels available for the DZMX1

| Channel | Channel Id | Category | Item Type |
|---------|------------|----------|-----------|
| Dimmer | switch_dimmer | DimmableLight | Dimmer | 
| Scene Number | scene_number |  | Number | 

### Dimmer

The brightness channel allows to control the brightness of a light.
            It is also possible to switch the light on and off.
        

The ```switch_dimmer``` channel supports the ```Dimmer``` item and is in the ```DimmableLight``` category.

### Scene Number

Triggers when a scene button is pressed

The ```scene_number``` channel supports the ```Number``` item.



## Device Configuration

The device has no configuration parameters configured.

## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The device does not support associations.
## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V1| |
| COMMAND_CLASS_SWITCH_ALL_V0| |
| COMMAND_CLASS_SCENE_ACTIVATION_V1| Linked to BASIC|
| COMMAND_CLASS_SCENE_ACTUATOR_CONF_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_POWERLEVEL_V1| |
| COMMAND_CLASS_NODE_NAMING_V1| |
| COMMAND_CLASS_HAIL_V1| |
| COMMAND_CLASS_VERSION_V1| |
| COMMAND_CLASS_MANUFACTURER_PROPRIETARY_V1| |

### Documentation Links

* [Installation Instructions](https://www.cd-jackson.com/zwave_device_uploads/196/installation-instructions.pdf)
* [Product Overview](https://www.cd-jackson.com/zwave_device_uploads/196/Leviton-DZMX1.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](http://www.cd-jackson.com/index.php/zwave/zwave-device-database/zwave-device-list/devicesummary/196).