# RFID8051
A Door unlock system with 8051 Microcontroller and RC522 RFID Reader

Proteus project folder included. 
Open the folder in Proteus, and everything can be edited.

Main C file usd: [v1.c](https://github.com/souranild/RFID8051/blob/main/v1.c)
Main HEX file Used: [v1.hex](https://github.com/souranild/RFID8051/blob/main/Objects/v1.hex)


## Proteus:
![](https://github.com/souranild/RFID8051/blob/main/Images/Proteus.png)


## Hardware:
1. AT89C52 Microcontroller
2. AT89C52 Programming Board
3. Push Button
4. Capacitors
5. Resistors
6. LCD Display
7. RC522 RFID Reader Module
8. SG90 Servo Motor
9. Connecting Wires

![](https://github.com/souranild/RFID8051/blob/main/Images/Hardware.png)


## Demo
1. A list of RFIDs is saved in code, and the RFIDs are tested according to that.
If the RFID is wrong, then a message saying “UNAUTHORIZED” is printed in the LCD.

![](https://github.com/souranild/RFID8051/blob/main/Images/Demo1.png)

2. If the RFID is correct, the user’s predefined name is printed and the motor runs.

![](https://github.com/souranild/RFID8051/blob/main/Images/Demo2.png)


### Video:

![](https://user-images.githubusercontent.com/42074408/127742384-1bbc4c7b-90af-491c-9b67-6231d138031c.mp4)



## To Be Added

- Add an alarm system.
- Modify the commands, signaling exceeded the number of failed attempts.
- Replacing the DC Motor with Servo Motor for precise movement of latches and knobs.
