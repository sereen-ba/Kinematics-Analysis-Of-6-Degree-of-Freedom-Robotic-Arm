# Kinematics-Analysis-Of-6-Degree-of-Freedom-Robotic-Arm
________
This raspetroy contains the final kinematic analysis and the equations for a 6 degree of freedom robotic arm.

TO understand the movement of the six joint robotic arm watch this: https://www.youtube.com/watch?v=DdvBrKl3SHg

Below is the algorithm of the control panel for controlling 6DOF arm:

1- Start
 
  (1) Forward Kinematics.
  (2) Inverse Kinematics.
  2- Enter F for (1) or I for (2)
  
2.1- If the user entered F:
 
  2.1.1- The program will ask the user to promote the joint angles.
   The value of Theta1.
   The value of Theta2.
   The value of Theta3.
   The value of Theta4.
   The value of Theta5.
   The value of Theta6.
   
  2.1.2- The Program will calculate the positions and the rotations and the orientations for the final tranfromation.
  
  2.1.3- Output: Position(px,py,pz) and the rotation,orientation (ax,ay,az),(nx,ny,nz),(ox,oy,oz).
  
  2.1.4- robotics arm moves.
  
2.2- If the user entered I:
 
  2.2.1-  The program will ask the user to premote the Positions and the rotations and the orientations for the end effector.
  
    The value of Px.
    The value of Py.
    The value of Pz.
    The value of Ox.
    The value of Oy.
    The value of Oz.
    The value of ax.
    The value of ay.
    The value of az.
    The value of nx.
    The value of ny.
    The value of nz.
    
  2.2.2- The Program will calculate the joint angles.
  2.2.3- Output: joint angles (Theta1,Theta2,Theta3,Theta4,Theta5,Theta6).
  2.2.4- robotics arm moves.
3- End
