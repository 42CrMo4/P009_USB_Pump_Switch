# P009 USB Pump Switch

Home Assistant controlled ESP32-c3 USB Switch for "dump" USB Pumps for small scale gardening. 

## Description

This PCB uses one USB Power input to enable and disable two USB power poutputs.
To controll the output there is a ESP32-c3 that is able to be flashed with ESPhome (or Arduino) to be controlled via Home Assisstant. 
To switch the Power to the USB A Sockets the AP22804A IC is used. 
Input is an USB type C connector. 
This should drive cheap Aliaxpress pumps that are powered by USB and have only static delay and runtime optins. 

## Picture and BOM

| Font                                                                    | Back                                                                      |
|-------------------------------------------------------------------------|---------------------------------------------------------------------------|
| ![PCB Top design](../../blob/documentation/Fabrication/PCBdraw_Top.png) | ![PCB Back design](../../blob/documentation/Fabrication/PCBdraw_Back.png) |

![Link to the current BOM](../../tree/documentation/Fabrication/BoM)