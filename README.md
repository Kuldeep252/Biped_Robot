# Biped Robot

A simple model to mimic some human leg movement using servo motors.Click [here](https://www.youtube.com/watch?v=q-qTm7lYGRk) to watch the video ![](3d%20view.png)

## prerequisite

* Basic knowledge of c++
* Familiarity with Arduino
 
### Hardware required

* Arduino uno
* 6 SG-90 micro servo motors 
* 4 high discharge AA cells (must be more then 2000 mah per cell)
* Connector wire
*  2 on/off push switch
* Power supply circit 5-volt( Either self made or purchased)

### Software required

* [SerialServoControl](https://github.com/Soshimo/Serial-Servo-Controller)
* [Arduino IDE](https://www.arduino.cc/en/Main/Software)

## Set-up
Connect servos in pin no. 3,5,6,9,10 and 11 onto the Arduino board. Connect the Arduino to the batteries via the power supply circuit and, the servos directly to the battery set. Now simulate the movement of different servos using Serial servo control software and note down the respective values to simulate motion. Start with the standing position then alternate leg bending and note the sequential order.

## Programming 
For this part, we have to use the values which we obtained in the previous step. Use these values with for loop and to control the speed of rotation of servos using delay function.An example program of walking is attached to this repository. Click [here](https://github.com/Kuldeep252/Biped_Robot/blob/master/walking%20code) to view the sample walking code
