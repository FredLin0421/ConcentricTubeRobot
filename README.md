# Concentric Tube Robot

## Installation
Use the package manager pip to install OpenMDAO
```bash
pip install openmdao
```
## Kinematic model
Tortionally rigid model has been used in this application. We consider straight-curve-straight tube as our robot design.
<p align="center">
  <img width="460" height="300" src="https://github.com/FredLin0421/CTR/blob/ctr_opt_all/Pics/Tubes.JPG">
</p>
The concentric tube robot can be devided into 4 links since the interaction between the outer straight tube and the curved second tube. We then use link 3 to represent the interaction part. Therefore, the curvature of the link 3 could be derived from the formula below.

<p align="center">
   <img src="https://github.com/FredLin0421/ConcentricTubeRobot/blob/master/images/Screen%20Shot%202020-01-13%20at%208.24.47%20PM.png" width="300" height="200" /> 
</p>

## Path planning for suturing
We also developed a simple GUI to generate the trajectory of the suturing task. 

More informations are in the vedio below.
https://youtu.be/3CcIXEhnT74


## Optimization problem
The optimization problem we were trying to solve is to optimize the tube parameters(diameter of all tubes, curvature of the second tube, stiffness) and the joint values(6 DOF).
<p align="center">
   <img src="https://github.com/FredLin0421/ConcentricTubeRobot/blob/master/images/Screen%20Shot%202020-01-09%20at%204.45.25%20PM.png" width="500" height="200" /> 
</p>

### Objective functions
Our objective is to minimize the swept volume and total surface area by the body of the concentric tube robots.
<p align="center">
   <img src="https://github.com/FredLin0421/ConcentricTubeRobot/blob/master/images/Screen%20Shot%202020-01-13%20at%2012.29.31%20PM.png" width="400" height="200" /> 
</p>

## Documentations
More information are in the document below.
https://github.com/FredLin0421/ConcentricTubeRobot/blob/master/Final_Project__Open_MDAO%20(2).pdf

