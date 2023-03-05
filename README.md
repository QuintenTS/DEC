# DEC
Design Engineering Contest code sharing space
In this file, we'll explain how the code should work.

Driving
Controller sends message update: angle = new angle
Receiver gets message and;
  Calculates the speed the weels should turn
    Each wheel speed will be based on how far the pin is pushed forward and;
    in what direction
  Sends speed to each motor, in rotations per minute

Potentially: starts up slow and brakes slow?

Grabbing:
