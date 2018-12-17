# arduino-maze-robot
Demonstration

1. PID  
  use reflectance sensors' values and position to calculate the adjustment to the motor speed, use differential instead of derivative
2. landscape
  1. use reflectance sensor values to judge left, right, T;
  2. use ultrasound sensor to detec the distance to the wall to tell left with left&straight;
3. detec cyinder with ultrasound sensors(use a range of the distance deteced by ultrasound sensors, stop, grasp, lift, release and u-turn )
4. hard code the path based on lanscape
  1. come to the first cylinder, return to home and travrse the whole maze
  2. use landscape's values to determine the location
5. gripper and lifter (how to work or why not work)
  1. 
6. differential drive 
  1. PID
  2. hard code to force the car to turn or go straight
