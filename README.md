# Biped Robot

A simple model to mimic some human leg movement using servo motors.

## prerequisite

* Basic knowledge of c++
* Familiarity with Arduino
 
### Hardware required

* An arduino uno
* 6 SG-90 micro servo motors 
* 4 high discharge AA cells (must be more then 2000 mah per cell)
* Connector wire
*  2 on/off push switch
* Power supply circit 5-volt( Either self made or purchased)

### Software required

* SerialServoControl
* Arduino IDE (obviously)

## Set-up
Connect servos in pin no. 3,5,6,9,10 and11 of the arduino board.Connect the arduino to the battries through power supply circuit and, the servos directly to the battry set.Now simulate the movement of different servos using Serial servo control software and note down the respective values to simulate a motion. Start with standing position then alternate leg bending and note the sequential order.

## Programming 
For this part we have the use the values which we obtained in previous step.Use these values with for loop and to control speed of rotation use delay fuction.An example program of walking is attached with this repository, which is working for my mini biped robot.You can use it as a reference.
