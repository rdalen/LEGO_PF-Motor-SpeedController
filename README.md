# Lego Power Function (PF) Motor speed controller

A DIY speed controller for LEGO Power Functions motors, based on the inexpensive HW-70 PWM motor controller module. 

### HW-70 motor controller module

<img width="40%" alt="image" src="https://github.com/user-attachments/assets/025a1fe9-c49a-44ab-ac2e-7b3156fc3fdb" />
<p align="center"><i>HW-70 PWM motor controller module</i></p>

This module  is based on the well known NE555 timer-IC to make a PWM ouput signal.  

![Image](https://github.com/user-attachments/assets/144847cf-f2c6-4271-a5c8-456ed3b9b372)


There are versions are provided: 
- a compact speed-only controller
- and a reversible version with a DPDT direction switch.

## Version 1 – compact speed-only controller

Compact version using the HW-70 module.
The output polarity is fixed, so the motor direction cannot be changed.

I made a small snapfit enclosure for it in FreeCad 

![Image](https://github.com/user-attachments/assets/31759234-456d-4af7-8029-7ed63e5ab469)

On AliExpress you can buy the PF connector and wire to make a DIY Lego PF connection cable.  
When assembling the PF cable, remove the C1 and C2 contacts from the Bottom part of the connector
so that only 1 connector is required to connect both the battery box and the motor.  

![Image](https://github.com/user-attachments/assets/0d40d8c7-a8f0-4172-9ac3-674145432b49)

Because the output voltage cannot be reversed it is more suitable as an LED dimmer  

![Image](https://github.com/user-attachments/assets/ed3f1727-a2c3-4208-9fcc-59caea6877c4)

---

## Version 2 – Reversible Speed Controller

Modified version with a DPDT switch that allows the motor direction
to be reversed while retaining speed control.
Below is a modified design where the motor can be changed direction using a DPDT switch.  
![Image](https://github.com/user-attachments/assets/1e96dd7b-d2d6-4f70-9284-a41b421fc728)

It fits in this larger snapfit enclosure  
![Image](https://github.com/user-attachments/assets/e7473693-421f-427c-b7ac-a56a24c6cb52)

First of all the screw connector on the HW-70 Module is replaced by a header connector, after that all connections are soldered and tested  
![Image](https://github.com/user-attachments/assets/82504dd4-9452-4436-aa28-c76d377cdb24)

and mounted into the enclosure  
![Image](https://github.com/user-attachments/assets/daf7bcd2-0a5a-4f4c-8ba2-4b5ef4e62d98)

To make the stripes on the potentiometer scale, color in the lines with a black marker and wipe it clean with alcohol, leaving the stripes.  
![Image](https://github.com/user-attachments/assets/ec54525e-5fb4-407b-928f-b9bb997c7182)

### DIY Guide
For a guide on how to build this project, check out the  tutorial at [Instructables](https://www.instructables.com/Lego-Power-Function-PF-Motor-Speed-Controller/). 
___
I also made a [version](https://github.com/rdalen/Lego_PF-Motor-SpeedController_Neopixel-version) based on an Arduino ProMini (or clone) and has a DRV8833 Motor driver module, a Rotary encoder and a 16 LED Neopixel Ring as forward/reverse speedindicator


