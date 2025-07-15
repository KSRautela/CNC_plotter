# CNC_plotter
Simple and high quality CNC drawing machine

![WhatsApp Image 2025-07-15 at 09 29 29 (2)](https://github.com/user-attachments/assets/2982228c-0700-473a-996d-37c2f134767a)

## List of items used

■ 8 x15 x 45mm Linear Bearing (x2)

■ 8 x 15 x 25mm Linear Bearing (x1)

■ 12v Nema 17 stepper motors (x2)

■ GT2 Timing belt and pulleys

■ Micro servo (x1)

■ Arduino Uno (x1)

■ Nuts, bolts and screws (See list below)

■ Stepper drivers-DRV8825 (x2)

■ Contact switch (x2)

■ Arduino CNC Shield (x1)

■ 30mm 5V Fan (x1)

■ 8mm Chromed Steel Rod (35cm x2 & 5.5cm x1)

■ 30cm long linear rail with block (x1)

■ Electrical wire

■ 12v power supply - 2A or greater (x1)

■ 6mm Idler Wheel - 3mm Bore (1)

■ Wooden panel to mount project at least 40x45cm 

## Nuts, bolts and screws needed:

■ M5 x 25mm (x2)

■ M3 x 18 (x3)

■ M3 x 12 (x2)

■ M3 x10 (x3)

■ M3 x 6 (X14)

■ M3 nuts (x9)

■ M5 nut (x1)

■ Short wood screws (x8)


https://github.com/user-attachments/assets/7d5b39cc-11db-47ee-aa22-920289276872


## Code

Code that be uploaded to the arduino to enable it to receive GRBL instructions is in examples of grbl-mi which is to be upladed to Arduino IDE as a library 

## Connections

![WhatsApp Image 2025-07-15 at 09 29 29 (1)](https://github.com/user-attachments/assets/70359dd6-f3ac-4cc6-9f72-661567d0cb03)

■ Arduino Uno to stepper motor driver shield

■ 12V 2A power supply to power in on stepper motor driver shield

■ 6 jumpers on microstepping of X axis and Y axis

■ 1 jumper on EN/GND

■ DRV8825 on X and Y axis accoring to pins

■ X motor pins to X motor out

■ Y motor pins to Y motor out

■ X end stop to X-/GND on shield 

■ Y end stop to Y-/GND on shield 

■ Servo 5v and GND to 5V/GND on shield

■ Servo signal to Z+

## How to run

Now any Gcode sender on the users PC can be used to control the CNC plotter 

https://github.com/user-attachments/assets/133c555b-2a7e-4263-94ef-4a708261389a
