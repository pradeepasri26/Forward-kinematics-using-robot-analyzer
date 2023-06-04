# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
1.Open the roboanalyzer software.
2.Select the robot and its degrees of freedom.
3.Change the values with the link lenght wherever necessary.
4.Stimulate the model for forward kinematics.
5.Plot the graph between the link and the joints.
6.Update the DH parameters of the link configuration and end effector configuration.




### SIMULATION 
4 DOF:
![kine 1](https://github.com/pradeepasri26/Forward-kinematics-using-robot-analyzer/assets/131433142/b92cff94-7442-46a7-a43f-b35542fd1a99)
6 DOF:
![kin 2](https://github.com/pradeepasri26/Forward-kinematics-using-robot-analyzer/assets/131433142/fec4c92a-fe4c-4b41-8b79-bdda0e83df2c)


 
 
 
 
 
 ### PLOT 
 4 DOF:
 ![kin 3](https://github.com/pradeepasri26/Forward-kinematics-using-robot-analyzer/assets/131433142/b1d528b0-903e-4f69-9a99-f7a86b7374ef)
 6 DOF:
 ![kin 4](https://github.com/pradeepasri26/Forward-kinematics-using-robot-analyzer/assets/131433142/9791919a-8b32-4ec8-83cc-38a69471299c)


 
 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS :  
