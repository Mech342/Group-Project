## Ball and Plate 

![Model_Image](https://user-images.githubusercontent.com/65363589/82133838-4ae2d880-97a5-11ea-9ba0-2c7557ba91b6.JPG)

# Group Members

## Rebecca Allan, Dana Fisk, Carl Quicksall, Samuel Wright, Alyssa Zuniga





# Project Summary 
The group chose the ball and plate control algorithm project unanimously, as all members were interested in creating this control algorithm. 
The challenge of this project is to demonstrate the ability to balance a ball on a moving plate using a PID-based controller that can sense the movement of the ball and plate while using an algorithm to balance and eventually stabilize the ball in a desired position on the plate. 
This will be accomplished using two rotary servo base units in conjunction with two degrees of freedom. A camera will be implemented to sense and record the location of the ball and pass that information to the controller, giving it the data it needs to compensate and adjust the plate.

The four main platforms used to build this system were: MATLAB, Simulink, CoppeliaSim, and Quarc.  MATLAB is used as the primary computation engine. 
CoppeliaSim is our simulation platform that allows us to build a virtual model of our robot. Simulink acts as the go between MATLAB and CoppeliaSim and Quark is a watchdog that provides additional features. Together these four systems make up our full PID system.

In regards to our requirements, we were able to derive a transfer function, to properly model the physical system. We were able to generate a simulated model of the physical system as well as create a control system prototype that is ready to be implemented in Simulink. We were not however successful in our attempts to integrate the transfer function with the virtual system.




# Project Links

[Design Report](https://github.com/Mech342/Group-Project/files/4640779/Design.Report.pdf)
- Presentation

[Simulation File](https://github.com/Mech342/Group-Project/files/4640815/Ball.and.Plate.pptx)

[Our Software Files](https://github.com/Mech342/Group-Project/files/4640847/Software-20200517T191412Z-001.zip)

[Code Source - Software ](https://github.com/Mech342/Group-Project/files/4640839/Software-20200517T191224Z-001.zip)

[Code Source - Documentaton ](https://github.com/Mech342/Group-Project/files/4640841/Documentation-20200517T191250Z-001.zip)

