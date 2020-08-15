---
title: IIoT based ICS rig (CloudRail)
parent: IoT Devices
has_children: false
nav_exclude: true
---

# IIoT based ICS rig (CloudRail)

This document serves as a guide for the rig installation with brief description of the devices associated in this setup. It also provides an overview on what hacks are possible and how these devices can be hacked. For detailed description of ICS architecture and hacking, please refer to [Industrial Control Systems](**Link**)

## Rig setup

This setup shows a convergence of legacy Operational Technology (OT)and Internet of Things (IoT) devices. In an Industrial Internet of Things (IIoT) environment, legacy devices such as Programmable Logic Controllers (PLCs) and Remote Terminal Units (RTU) interact and exchange data with the IoT devices via IIoT gateways [A Reference Architecture for IIoT and Industrial Control Systems Testbeds](https://research-information.bris.ac.uk/ws/portalfiles/portal/186781375/CameraReady_A_Reference_Architecture_for_IIoT_and_Industrial_Control_Systems_Testbeds.pdf). There is very little understood / known about the attack surfaces and potential vulnerabilities of these covergent OT/IoT environemnts, which is also a big motivation for this setup. 

The setup consists of the following:

1. [IoT Starter Kit CloudRAIL.Box Set](https://www.automation24.se/iot-startkit-cloudrail-box-set) - 
This kit contains:
a. [CloudRail.box](https://cloudrail.com/cloudrail-iot-box/) - It is based on the Revolution Pi connect hardware technology. The industrial sensors and actuators are connected to the desired cloud platform through IO--Link master. It is great for beginners as it doesn't need any special configuration and is managed via a central device management cloud. For datasheet, please refer to the [technical data](https://iot.cloudrail.com/wp-content/uploads/2019/01/datasheet_cloudrail_box.pdf)
b. [M12 Y connection cable in connection with electronic EVC510](https://www.automation24.se/m12-y-anslutningskabel-ifm-electronic-evc510) - It is a type of splitter cable useful for connecting 2 sensors to a port on the IO-Link Master. There are many different variants of M12 connectors but here we have the A-coded ones uses for connecting sensors or IO devices.
c. [M12 connection cable with male connector in connection with electronic EVC184](https://www.automation24.se/m12-anslutningkabel-med-hankontakt-ifm-electronic-evc184)
d. [IO-Link master DataLine IoT ifm electronic AL1350](https://www.ifm.com/de/en/product/AL1350?tab=details)
e. [M12 Connection cable in connection with electronic EVC010](https://www.automation24.se/m12-anslutningskabel-ifm-electronic-evc010)
f. [Temperature sensor in connection with electronic TN7511](https://www.automation24.se/temperaturgivare-ifm-electronic-tn7511) - For datasheet, please refer to the [technical data](https://media.automation24.com/manual/en/80231575UK.pdf)

2. [AC1365 - AS-Interface Profibus DP Gateway with PLC](https://www.ifm.com/se/sv/product/AC1365?tab=details) -



3. [Central Device Management]() - 

4.  

## Rig installation


## Types of possible attacks


## References

