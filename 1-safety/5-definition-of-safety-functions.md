# 1.5. Definition of Safety Functions

![](../_assets/말머리이미지.png )<font size = 3> **Emergency Stop Functions – IEC 204-1,10,7** </font><br>
There is one emergency stop button on the controller and teach pendant respectively. If necessary, additional emergency buttons can be connected to the robot's safety chain circuit. The emergency stop function, which overrides all other robot controls, can bring the current operation to a halt by cutting off the power supply to the motors of individual axes. This function will also shut down the power supply to other dangerous functions, which are controlled by the robot, to prevent them from being used

![](../_assets/말머리이미지.png )<font size = 3> **Safety Stop Function - EN ISO 10218-1:2011** </font><br>
A safety stop circuit needs to be configured, and, through this circuit, each robot should be connected with the safeguards and interlocks. The robot should have a number of electrical input signals which can be used to connect external safety devices, such as safety gates, safety pads, and safety lamps. These signals allow the robot's safety functions to be activated by all equipment, including peripheral equipment and the robot itself. 

![](../_assets/말머리이미지.png )<font size = 3> **Speed Limitation Function - EN ISO 10218-1:2011** </font><br>
In a manual mode, the maximum speed of the robot is limited to 250 mm per second.
The speed limitation applies not only to the TCP(Tool Center Point), but to all parts of manual mode robot. The speed of equipment mounted on the robot should be possibly monitored. 

![](../_assets/말머리이미지.png )<font size = 3> **Restricting working Envelope - ANSI/NFPA 79:2021** </font><br>
Operation area of each axis is restricted by soft limit and hardware limit. Axis 1, 2, and 3 can also be restricted by means of mechanical stopper.

![](../_assets/말머리이미지.png )<font size = 3> **Operation Mode Selection - ANSI/NFPA 79:2021** </font><br>
The robot can be operated either in the manual mode or auto mode. In the manual mode, the robot can be operated only by using the teach pendant.