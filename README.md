# SpiderBot
Official repository of Project SpiderBot

 We decided to work on a robot arm and achieve the goal to move its end effector to the specified point.

To achieve this, we referred to the guide by Automatic Addison https://automaticaddison.com/how-to-move-a-simulated-robot-arm-to-a-goal-using-ros/
and used its script file so as to move the mobile_manipulator to the desired point. 

We found the library of tinyik https://github.com/lanius/tinyik
The reason to use it were :
 1)It was simple to use and focussed on inverse kinematics 

 2)Most other libraries were much more verstaile, but those       functions were not needed for our purpose.


 We applied it in the mobile_manipulator to calculate the joint angles from the end effector position , this can be found in the scripts in arm_to_goal.
 This was successful and we were able to move the end effector of the mobile_manipulator to the desired point.

 Next task was to apply this to our robot_arm_description , which was proceeded with the change of joint names in the script file.

 robot_arm_description failed to reach the goal due to multiple errors in the URDF.
 




