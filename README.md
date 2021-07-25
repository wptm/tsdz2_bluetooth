# tsdz2_bluetooth
Tongsheng TSDZ2 E-Bike - DIY - Bluetooth module

Limited warranty: "DIY - Bluetooth module" and documentation are "as is" without any warranty. The licensee assumes the entire risk as to the quality and performance of the module. In no event shall "DIY - Bluetooth module" or anyone else who has been involved in the creation, development, production, or delivery of this module be liable for any direct, incidental or consequential damages, such as, but not limited to, loss of anticipated profits, benefits, use, or data resulting from the use of this module, or arising out of any breach of warranty.

This is here a basic schematic. R1 and R2 is a voltage divider. We need this because TSDZ2 controller works on 5v logic level but HC-05 is 3.3v. More info on this: https://electronics.stackexchange.com/questions/280500/why-do-you-have-to-use-a-voltage-divider-with-hc-05-bluetooth-module-arduino/280532
![Alt text](tsdz2_bluetooth.JPG?raw=true)

The voltage regulator makes lots heat. Therefore you can also build it into the housing and connect it directly to the controller board. There you can find +5v as well the uart rx/tx. 
Below picture is from TSDZ2 Wiki: https://github.com/OpenSourceEBike/TSDZ2_wiki/wiki/How-to-install-motor-temperature-sensor .
![alt text](https://github.com/OpenSource-EBike-firmware/TSDZ2_wiki/raw/master/TSDZ2_motor_controller_without_throttle_wires.jpeg)


