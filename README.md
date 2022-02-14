micro:bit Teleporting Duck
--------------------
In this assignment you and a partner will program two micro:bits to make a duck (or something else) fly invisibly through the air from one micro:bit to another.

Like the previous Wireless Intruder program, this one uses the micro:bit’s radio function to send data from one micro:bit to another when the accelerometer detects a shake gesture. The program first configures the radio and sets its group. It doesn’t matter what group you pick as long as your partner’s micro:bit is using the same group number, and no-one else nearby is using the same group. When you shake your microbit, it sends the word ‘duck’ on that radio group and clears the screen. If either micro:bit receives the radio 'duck' message, a duck icon appears on its display, so you should only ever have 1 duck visible at any time. Since both micro:bits send and receive, the code for both micro:bits will be the same.

Program requirements
-----------------
* Your program must use the micro:bit's sensor and radio features
* Each person will submit the Python code for their program and an animated gif showing the two programs running to Google Classroom

Suggested steps to completing this assignment
----------
1. Add code to import the radio library, turn the radio on and set the group number
2. Inside of the `while True:` write an `if` statement that checks if the micro:bit was shaken. You can go back and look at the previous [dice assignment](https://github.com/Computer-Programming-B/MicrobitDice/blob/main/README.md#microbit-dice) to see how. If the microbit has been shaken, send the message `'duck' and clear the display
3. Inside of the `while True:` write another `if` statement that checks if the micro:bit has received the 'duck' message. If so, display the duck image.

Samples of Student Work
---------
[Theo](TheoDuck.gif)   
[Renzl](RenzlDuck.gif)   
[Jasmine](JasmineDuck.gif)   
[Owen](OwenDuck.GIF)   
