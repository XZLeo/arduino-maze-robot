# arduino-maze-robot
Demonstration

* PID
  * use reflectance sensors' values and position to calculate the adjustment to the motor speed, use differential instead of derivative
* landscape
  * first introduce 9 types of intersections, return to 1-9;
  * use reflectance sensor, have 6 sensors values to judge left, right, T;(1 example: left {1000, 1000, 1000, 1000, 0, 0} 
  * use ultrasound sensor to detec the distance to the wall to tell left with left&straight;
* detec cyinder with ultrasound sensors(use a range of the distance deteced by ultrasound sensors, stop, grasp, lift, release and u-turn )
* hard code the path based on lanscape
  * come to the first cylinder, return to home and travrse the whole maze;
  * use landscape's values to determine the location;
  * 
* gripper and lifter (how to work or why not work) 
* differential drive 
  * PID
  * hard code to force the car to turn or go straight

Problem
* lifter is broken;
* We count the times of T-junction to decide when to detect the cylinder;but it keeps giving us more values while turning, thus it didn't rget to set a limit so that landscape will return to more values while turning, no time to test it;
