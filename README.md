## Robotic Arm (without fingers) 
* built with PIC MCU, servo motors, PIC BASIC PRO language
* Electronic Boards (PCB ) Design with Proteus
* Arm with 3 servo motors to hold end effector. End effector has a DC motor (simulates a cleaning tool)

for completion of project in Mechatronics and Robotics
BS Computer Engineering - STI College Rosario Batch 2012

- Dimanalata, Lenmor L.
- Dones, Agustin Ace, P.
- Legaspi, Jon Jon, R.
- Mojillo, Chona E.
- Paderna, Romeo III, B.
- Portuguez, Jan Paul R.
- Salatandre, Walter S.
- Tolentino, Armeo A.

#### Objectives
Specifically, this study aims to:
1. Design and develop the articulated jointed arm and base that will hold the end effector.
The arm utilizes three servo motors to hold the end effector. The motors
are connected by brackets.
2. Design and develop a cleaning tool as the end effector.
The arm utilizes a DC motor as a cleaning tool.
3. Design and develop a circuit that can control the robotic arm‟s
movement.
A circuit, with an MCU as its main chip, contains pushbuttons that can control the movement of each of the motor bracket clockwise and counter clockwise.
4. How to create a microcontroller program that can efficiently utilize the robotic arm?
The MCU program efficiently sends pulses to the servo motor for every movement. The program is written and compiled using PICBASIC PRO.

The servomotor controllers use the PicBasic Pro pulsout command. The command format is as follows:
```basic
pulsout pin, period
```

The pulsout command generates a pulse on the pin specified for the period of time specified. The time is in 10us (microsecond) increments. So to send a 1.5ms pulse out on port B pin 0, you could use one of the following command for the PicBasic Pro compiler:
```basic
pulsout portb.0, 150
```
The angles of each servo is declared using its pulse counterpart

- SEE .pdf for more details
- SEE RoboticArm.pbp to see entire code


## Testing Video

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/https://www.youtube.com/watch?v=jMQax1Go3Xs/0.jpg)](http://www.youtube.com/watch?v=jMQax1Go3Xs)

## Final Video

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/https://www.youtube.com/watch?v=udQL3pQedeg/0.jpg)](http://www.youtube.com/watch?v=udQL3pQedeg)
