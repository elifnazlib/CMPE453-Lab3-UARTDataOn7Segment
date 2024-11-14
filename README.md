# CMPE453 Embedded Systems

## Lab 3 - Displaying UART Data on 7-Segment Display

> [!NOTE]
> [AVR Programming Library](https://github.com/hexagon5un/AVR-Programming/tree/master/AVR-Programming-Library) must be 
downloaded and added to the Arduino IDE to compile the code. The library can be added by going to 
Sketch -> Include Library -> Add .ZIP Library and select the downloaded library.

1.  Set up the following circuit with your breadboard, Arduino-Uno, 7-segment
display, 220Ω resistors (8), and jumpers.

![Figure 1 - Circuit](https://github.com/elifnazlib/CMPE453-Lab3-UARTDataOn7Segment/blob/main/circuit.png)

2.  Program the microcontroller by using C programming on Arduino IDE. Provide the 
connection between your computer and Arduino board. When your program runs, it 
should do the following task.

    1. 7-segment display will be ON at beginning. You will enter any positive integer by 
using Serial Port Screen of ArduinoIDE. Whatever youenter, it should be displayed 
on 7-segment display. If you enter a one-digit number, it should be shown as usual. 
If for example, you entered a 3-digits number, 127, then 1, 2 and 7 should be 
displayed on 7-segment display with 1 sec. delay. 

    2. When you write 5, the 7-segment display must be display 2. (For example, if you 
enter 15 it should be shown 1 and 2.) 

    3. When you write 4, 7-segment display will start from 4 and count down to 0. (For 
example if you write 845, then 8, 4, 3 , 2, 1, 0 and 2 should be displayed on the 7- 
segment display.) 

    4. If you want to clear the 7-segment display, you should enter the character ‘d’. When 
cleared, 7-segment display should be OFF.

    5. Note that once you run the code, you should be able to try it infinitely without 
needing upload the program again or reset it.

> [!NOTE]
> [This documentation](https://docs.arduino.cc/retired/hacking/software/PortManipulation/) has been used to understand which ports correspond to which pins on the Arduino Uno board when programming with C.
