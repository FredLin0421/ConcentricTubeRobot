# ConcentricTubeRobot

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
<p float="center">
  <img src="https://github.com/FredLin0421/ConcentricTubeRobot/blob/master/images/Screen%20Shot%202020-01-13%20at%208.24.11%20PM.png" width="168" height="276" />
  <img src="https://github.com/FredLin0421/ConcentricTubeRobot/blob/master/images/Screen%20Shot%202020-01-13%20at%208.24.47%20PM.png" width="393" height="273" /> 
</p>



## Path planning for suturing
More informations are in the vedio below. Please click the image below. 
[![](https://github.com/FredLin0421/CTR/blob/ctr_opt_all/Pics/Tubes.JPG)](https://www.youtube.com/watch?v=q3hONNn4UwM) 
## Optimization problem
### Objective functions

### Constraints


## Documentations
