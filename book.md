# Manipulator Maintenance Manual - HH4L / HH7 / HH7E / HH8

{% hint style="warning" %}
The information provided in this manual is the property of Hyundai Robotics.

The manual may not be copied, in part or in full, nor redistributed without a prior written consent from Hyundai Robotics. It may not be provided to any third party nor used for any other purposes.


The manual may be changed without prior notification.



**Copyright ⓒ 2023 by Hyundai Robotics**
{% endhint %}
# 1. Safety
# 1.1. Introduction

The main purpose of this chapter is to describe the safety precautions for users and operators who repair and manipulate the industrial robot. 

This manual describes safety precautions for robot manipulator and controller, in complies with the safety regulation of EU Machinery Directive 98/37/EC(2006/42/EC) and US OSHA. And the robot manipulator and controller is manufactured to comply with the safety standards EN ISO 10218-1:2011 and ANSI/NFPA 79:2021. 

Every operator, who installs, replaces, adjusts, manipulates, maintains, and repairs, must read thoroughly and fully understand the manipulation and maintenance manual, in particular, the special attention must be paid to the WARNING symbol, the most important marking related to the safety.

Installation, replacement, adjustment, manipulation, maintenance, and repair of robot system must be performed by the personnel who was duly trained for these purposes, following the indicated operating procedure.

This company is planning and carrying out the relevant training such as maintenance, repair, and manipulation for the above operations, so robot users make sure that robot operators should get the relevant training. And make sure that the robot handling work should be carried out only by the operators who completed this training course. 

Hyundai Robotics user of industrial robot has responsibility to observe the safety regulation related to robot adopted in corresponding countries and responsibility to design, install and operate safety equipment well in order to protect workers who work at robot system.

In high-risk areas concerning robot systems in which robots, tools, and accessories operate, there must be a method of protection to stop the workers or objects from entering the area according to ANSI/NFPA 79:2021.



![](../_assets/말머리이미지.png )  <font size = 3> **Applicable areas** </font><br>

It is applied to the industrial robot used by installing on the surface of wall or plane (axes addable). It is also appropriate for controlling operation in the dotted section or consecutive section.

Major application is 

*	Spot welding
*	Arc welding
*	Cutting
*	Handling
*	Assembly
*	Application such as Sealing
*	Palletizing
*	Grinding

For the other use than the above emergency application, make a contact with our company to consult on the robot use and possible applications. 


![](../_assets/말머리이미지.png )  <font size = 3> **Disable environment** </font><br>

Our robot must not be used in a highly explosive environment and the areas contaminated by oil, flammable materials or chemical materials. (Prohibited to be installed and manipulated.) 

# 1.2. Relevant Safety Regulations


The robot is designed as per ISO 10218-1:2011 safety standards for industrial robots, and furthermore in comply with ANSI/NFPA 79:2021 regulations. 

# 1.3. Safety Training

All the personnel who intend to teach, operate or inspect the robot must be trained in an approved robotic operation and safety training course before start-up. The safety training course includes the following details:

*	Purpose and functions of safety devices
*	Safety procedure to handle the robot
*	Performance of robot or the robot system and possible hazards
*	Tasks associated with any specific robot applications 
*	Safety concepts, etc. 

# 1.4. Safety Related Nameplate 
# 1.4.1. Safety Marking 

For the purpose of effective safety instructions, the following safety symbols are used in this manual. 



<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
.tg caption{caption-side: top;text-align: left;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-osmi{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-bav5{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
.tg .tg-0lax{text-align:left;vertical-align:middle}
</style>
<table class="tg">
<caption>Table 1-1 Safety marking</caption>
<thead>
  <tr>
    <th class="tg-osmi" colspan="2">Symbols</th>
    <th class="tg-bav5">Descriptions</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">Warning</td>
    <td class="tg-nrix"><img src="../../_assets/주의표시.png" width = 100 height = 100></td>
    <td class="tg-0lax">Indicate a highly dangerous situation, meaning that operating or handling in a wrong manner could result in death or serious injury to personnel, or damage to equipment. Attention should be paid to the operation and handling.</td>
  </tr>
  <tr>
    <td class="tg-nrix">Mandatory</td>
    <td class="tg-nrix"><img src="../../_assets/강제표시.png" width = 100 height = 100>  </td></td>
    <td class="tg-0lax">Indicate the compulsory measures that should be taken</td>
  </tr>
  <tr>
    <td class="tg-nrix">Prohibited</td>
    <td class="tg-nrix"><img src="../../_assets/금지표시.png" width = 100 height = 100></td>
    <td class="tg-0lax">Indicate the prohibited actions and/or operations that should not be performed.</td>
  </tr>
</tbody>
</table># 1.4.2. Safety Nameplate

Identification plates, warning label and safety symbols are attached to the robot and to the inside and outside of control panel. The designation labels and cable Mark for wire harness between the robot and control panel, and the cables inside/outside of control panel are provided. 

All of these plates, labels, symbols and marks constitute safety-relevant parts of the robot and the control panel. They must remain attached to the robot manipulator and control panel at their clearly visible positions all the time for the safety and their full performance. 

The painted markings on the floor and signs indicating dangerous zones must be clearly distinguished in form, color, and style from other markings on the machine near the robot system or inside the plant facilities where the robot system is installed. 

<blockquote>
<table border="0">
<thead>
  <tr>
    <td> 
    <div align="center">
     <img src="../../_assets/금지표시.png" width = 60 height = 60> 
    </div>
    </td>
    <td colspan="4">       
      It is forbidden to remove, cover, or paint over by way of spoiling the clearly visible identification plates, warning labels, safety symbols, designation labels and cable marks.
    </td>
  </tr>
</thead>
</table>  
</blockquote># 1.5. Definition of Safety Functions

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
The robot can be operated either in the manual mode or auto mode. In the manual mode, the robot can be operated only by using the teach pendant.# 1.6. Installation# 1.6.1. Safety Fence

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td>
            <td colspan="4">Install safety fence against the possible collision between the robot and workers, so that no worker may approach the robot.</td>
        </tr>
    </thead>
</table>  
</blockquote><br>


Install safety fence against the possible collision between the robot and workers, so that no worker may approach the robot. When operators or other personnel enter the robot's working envelope by accident, it may cause an accident. Install the safety fence to stop the robot when one, who intends to replace for TIP DRESSING or TIP changing replacement, or to inspect welding equipment, opens the fence gate and approaches the equipment during operation.

![](../../_assets/그림_1.1_권장펜스크기와_출입구크기.png)

Figure 1.1 Recommended size for safety net and entrance gate (slot type entrance gate)


![](../../_assets/그림_1.2_권장펜스크기와_출입구크기.png)

Figure 1.2 Recommended size for safety net and entrance gate (square type entrance gate)

<ol style="list-style-type:decimal" start="1">
<li>Enough space for safety net should be secured by covering robot operating area so as that workers would not have difficulty in teaching work or repairing work, and the safety net should have solid structure in order that it would not move easily and man cannot enter over easily.
</li><br>
    <li>
Safety net should be installed by static type in principle, and should not have hazardous parts such as prominence and depression or keen part, etc.
</li><br>
    <li>
Install the safety fence with an entrance gate, and register the safety plug at the gate so that it does not open unless pulling the plug out. Wiring should be carried out in a way that the robot should be in the operation ready OFF status as well as in the motor OFF status when the safety plug is pulled out or safety net is open.
</li><br>
    <li>
In order to operate the robot with the safety plug pulled out, wiring should be carried out in a way that will allow the playback to take place at a low speed.
</li><br>
    <li>
The emergency stop button should be installed at a place where it can be pushed quickly by the operator. 
</li><br>
    <li>
If no safety net is to be installed, devices such as photoelectric switches, and mat switches, should be installed, instead of the safety plug, to cover the overall area within the robot’s operation range in a way that the robot can be stopped automatically when a person enters the robot’s operation range.
</li><br>
    <li>
Operation area of robot (hazardous area) should be distinguished by the method like painting on floor. 
</li>
</ol>
# 1.6.2. Placement of Robot & Peripheral Equipment

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td>
            <td colspan="4">Please make sure that robot and peripheral equipment should be arranged by following method.</td>
        </tr>
    </thead>
</table>  
</blockquote><br>



<ol style="list-style-type:decimal" start="1">
<li>(1)	In case of connecting primary power of controller or peripheral devices, please work after checking whether supply power has been deleted. There is a possible danger of electric shock because the high voltage such as 220V and 440V is used as its primary power. 
</li><br>
    <li>
Post a sign [No enter during operation] up the safety fence gate, and inform the operators of its purport. 
</li><br>
    <li>
Arrange such devices as controller, interlock panel, and other manipulation panels to be handled outside of the safety fence. 
</li><br>
    <li>
When installing operation stand, install the emergency stop button on the stand. Make sure that stopping in an emergency situation can be initiated from any place from which the robot is operated.
</li><br>
    <li>
Make sure that the robot manipulator and the wiring and piping of controller, interlock panel, and timer should not be placed in the way of operator's working range so that they would not be directly stepped on by FORK　and LIFT. Otherwise, the operator may suffer electrocution or the wire may suffer disconnection. 
</li><br>
    <li>
Place the controller, interlock panel, and handling stand within the sight of robotic performance. It may cause a major accident to operate the robot while the robot is malfunctioning in an area where the robot’s activity can not be observed, or while the operator is working on it.
</li><br>
    <li>
Restrict the robot's working envelope by using the soft limits and the mechanical stopper if the necessary working envelope is narrower than the robot’s workable envelope. When the robot is to move beyond the restricted envelop due to abnormal operation, such as the robot being handled in a wrong way, the robot will be stopped automatically in advance thanks to the function that restricts the workable envelop.
</li><br>
    <li>
During the welding work, spatter could fall down to workers or the workers could be injured by burning, or fire could break out. Install such devices as a glare shield or a cover in the full sight of robot's working envelope.
</li><br>
    <li>
Make sure that the device indicating the robot's running condition, whether automatic or manual mode, can be noticeable even from a slightly distant location. In the case of automatic start-up, a buzzer or a warning lamp will be useful.
</li><br>
    <li>
Make sure that there is no projecting part in the robot's peripheral equipment. Cover it, if necessary. It usually could cause an accident if the operator comes in touch with it. And it may cause a major accident when the operator tumbles while being astonished at the sudden movement of the robot.
</li><br>
    <li>
Don't make the system designed to allow the workers to carry the Work in and out using their hands through the safety fence. It could be a cause of accident associated with compressing or amputating. 
</li>
</ol>



![](../../_assets/그림_1.3_LCD용로봇주변장치와_작업자의배치_원통형.png)
(Cylinder type)
![](../../_assets/그림_1.3_LCD용로봇주변장치와_작업자의배치_빔형.png)
(Beam type)

Figure 1.3 Arrangement of LCD robot peripheral devices and workers


![](../../_assets/그림_1.4_산업로봇주변장치와_작업자의배치.png)

Figure 1.4 Arrangement of general robot peripheral devices and workers# 1.6.3. Installing the Robot

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4">Please install the robot in accordance with following method surely</td>
        </tr>
    </thead>
</table>  
</blockquote><br>

Install the robot as per the planning and layout which has been previously reviewed and studied for its optimized performance and functionality. In case of poor conditions for robot installation, the serious problems can take place, including error of relative position between robot and workpiece during operation, bad performance quality of robot caused by vibration, shortening lifetime, and cause of serious accidents. Thus, pay attention to the following precautions when installing the robot.

<br><br>

![](../../_assets/말머리이미지.png )<font size = 3> **General Safety Precautions** </font><br>


<ol style="list-style-type:decimal" start="1">
<li>
Design and install the robot system properly in compliance with laws, regulations, and safety requirements enable in the country where the robot system is installed. 
</li><br>
    <li>
All the workers for the robot system must have the complete knowledge on the information specified in the application and supplementary manual, and proficiently operate and handle the industrial robot. 
</li><br>
    <li>
Installation workers of robot must follow the safety instructions and apply them to the installation when they face any safety problems.
</li><br>
    <li>
System provider must ensure that all the circuits utilizing safety functions perfectly perform in a safe way.
</li><br>
    <li>
Install main power supply to be disconnected from outside of the robot’s working envelope. 
</li><br>
    <li>
System provider must ensure that all the circuits utilizing emergency stop function perfectly perform in a safe way.
</li><br>
    <li>
or the immediate emergency stop, install emergency stop button within the accessible distance for the operator.
</li><br>      
</ol>

<br>

![](../../_assets/말머리이미지.png )<font size = 3> **Technical Safety Precautions** </font><br>

<ol style="list-style-type:decimal" start="1">
<li>
Eliminate any interference with peripheral equipment considering the dimension and working envelope. 
</li><br>
    <li>
Avoid such place for installing which is directly exposed to the sun, extremely humid, contaminated by oil or chemicals, and containing a large amount of metal powder and explosive gas.
</li><br>
    <li>
Install at the ambient temperature ranged 0~45℃. 
</li><br>
    <li>
Secure sufficient space for the easier disassembly and maintenance.
</li><br>
    <li>
Install safety fence with a gate, and prohibit any person from entering the robot's working envelope.
</li><br>
    <li>
Remove any obstacles out of the robot’s working envelope.
</li><br>
    <li>
Take a special measure, considering thermodynamics of controller, if the robot is installed near the heating elements or places exposed directly to the sun.
</li><br>
    <li>
Take a special measure if the robot is installed in a place of abundant dust such as metal powder in the air.
</li><br>
    <li>
Install the robot not to transmit welding electric current. In other word, insulate SPOT GUN with/from the robot’s wrist.
</li><br>
    <li>
Grounding is very critical in preventing electric shock and malfunction caused by noise, and thus install as following instructions. 
            <ol style="list-style-type:lower-roman" start="1">
                <li>
tall an exclusive grounding terminal using class 3 or higher. (For the input voltage of 400V of higher, use special class 3 or higher.) 
</li>
<li>
Connect grounding line into the grounding bus-bar inside of the control panel. 
</li>
<li>
In case of direct grounding on the floor by anchoring, two-point grounding both by robot manipulator and by controller can produce a “ground loop” and contrariwise cause abnormal operation. In this case, connect the grounding line to the base of robot manipulator and disconnect the second grounding point to the controller. If the robot vibrates even after stopping, double-check the grounding status because the possible main causes could be an incomplete grounding or “ground loop”.
</li>
<li>
In the use of internal transgun(GUN), there is a possible danger of dropping because the primary power cable is directly connected to the spot gun. In this case, directly connect the grounding line to the base of robot manipulator in order to prevent any electric shock and protect the control panel, but do not connect it to the controller.
</li>
</ol>
</li><br>   
</ol># 1.6.4. Space for Robot Installation

Install robot after securing sufficient space for maintaining the robot manipulator, controller, and other peripheral equipment. to install the main body and controller, please secure the above mentioned installation area. Install controller outside of the safety fence in order to monitor the robot manipulator and to operate in a safe way.
When installing, be sure to make it easier to perform the maintenance when opening the Controller door. Secure the available space. The specifications of the controller can change according to the type of the controller. (For more details, please refer to the “Maintenance manual”.)

# 1.7. Safety Operation for Robot Handling


Follow the safety instructions to prevent any accidents. Don't modify nor ignore safety devices or circuits at any time, and be careful of electric shock.

All the normal operations in an automatic mode must be performed outside of the safety fence. Check the robot's working envelope if anyone is inside before operating. 
# 1.7.1. Safety Precautions for Robot Handling

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            <div>
            </td> 
            <td colspan="4"> 
                Please observe following countermeasures because safety is very important for the test operation of the robot.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>



<ol style="list-style-type:decimal" start="1">
		<li>
Do not handle the robot other than such personnel as operators handling the robot and other possible operators and supervisors who were designated as whom duly trained in an approved robotic training course and become familiar enough with the proper operation of the safety and robotic functions. 
</li><br>
    <li>
Be sure to wear helmets, goggles, and safety shoes. 
</li><br>
    <li>
Perform the work in pairs. One person must be ready to press the emergency stop button in an emergency while the other must perform his work quickly but carefully within the robot’s working envelope. Always check the escape route before working. 
</li><br>
    <li>
Make sure that there is no one in the working envelope when the power source is on. 
</li><br>
    <li>
Operations such as teaching must be performed outside of the robot's working envelope. However, if the operation is performed within the working envelope after stopping the robot, enter the envelope with safety plug or key switch for converting to automatic mode. Make sure that other operators do not change it into automatic mode by accident. Also, pay close attention to the specific direction of robotic movement in case of abnormal operation and malfunction. 
</li><br>
    <li>
Supervisors should follow the instructions below. 
<ol style="list-style-type:lower-roman" start="1">
    <li>
Be located at a place where you could take an entire view of robot, and commit yourself to monitoring.
</li>
<li>
Press the emergency stop button immediately when abnormality is found. 
</li>
    <li>
Anyone is forbidden to be near the operating area other than those who are engaged in the operation.
</li>
</ol>
<li>
In a manual mode, the speed of teaching is limited to 250mm/sec. 
</li><br>
    <li>
In teaching, post a sign [Under Teaching]. 
</li><br>
    <li>
Operators must pull the safety plug out, and enter the safety fence with the plug. 
</li><br>
    <li>
Do not use any devices causing noise in and around the teaching area. 
</li><br>
    <li>
Handle the teach pendant button, while checking the teaching point with your naked eyes, and do not handle it just relying on your sense. 
</li><br>
    <li>
<img src="../../_assets/작은주의표시.png">It is a repairing part to be prepared for when you buy many sets. 
</li><br>
    <li>
In teaching, check and examine carefully under your feet. In particular, in high teaching for more than 2M, secure a safe zone on which you may step before teaching. 
</li><br>
    <li>
<img src="../../_assets/작은주의표시.png">Instructions for any abnormal operations. 
<ol style="list-style-type:lower-roman" start="1">
    <li> Press immediately the emergency stop button when any abnormal operations are found. 
</li><br>
    <li>
Be sure to check if the relevant equipment is stopped when checking the abnormality in an emergency stop. 
</li><br>
    <li>
In case that the robot stops automatically due to power failure, investigate possible causes and take actions after confirming that the robot completely stops. 
</li><br>
    <li>
In case of malfunction of emergency stop devices, immediately disconnect the main power and investigate possible causes to take necessary actions. 
</li><br>
    <li>
Investigation of the failure must be conducted only by a designated person. For the re-operation after emergency stop, operators must clarify the cause of failure and take necessary actions, and then operate the robot again following the proper procedure. 
</li></ol>
    <li>
Write out the operating rules proper to working details and installing location regarding the operation and handling method for the robot, and the necessary actions for robot's any failure. In addition, it is recommended to operate the robot in accordance with the operating rules. 
</li><br>
    <li>
Instructions when the robot stops 
Make sure not to approach the robot even when it seems to be stopped. Most accidents occur from a sudden movement of robot which seemed to be stopped when one approaches it. The conditions that the robot stops are as follows.
        </li><br> 
            <style type="text/css">
                .tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
                .tg caption{caption-side: top;text-align: left;}
                .tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
                overflow:hidden;padding:10px 5px;word-break:normal;}
                .tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
                font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
                .tg .tg-osmi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
                .tg .tg-bb96{background-color:#ccf1bc;color:#000000;text-align:center;vertical-align:middle}
                .tg .tg-nrix{text-align:center;vertical-align:middle}
            </style>
            <table class="tg">
                <caption>Table 1-2 State of Robot Stop</caption> 
                <thead>
                <tr>
                    <th class="tg-osmi">No.</th>
                    <th class="tg-osmi">State of Robot</th>
                    <th class="tg-osmi">Drive Power</th>
                    <th class="tg-osmi">Access</th>
                </tr>
                </thead>
                <tbody>
                <tr>
                    <td class="tg-bb96">1</td>
                    <td class="tg-nrix">Pause (Minor failure, Pause switch)</td>
                    <td class="tg-nrix">ON</td>
                    <td class="tg-nrix">X</td>
                </tr>
                <tr>
                    <td class="tg-bb96">2</td>
                    <td class="tg-nrix">Emergency stop (Major failure, Emergency stop switch, Safety gate)</td>
                    <td class="tg-nrix">OFF</td>
                    <td class="tg-nrix">O</td>
                </tr>
                <tr>
                    <td class="tg-bb96">3</td>
                    <td class="tg-nrix">Input signal standby of peripheral equipment (START INTERLOCK)</td>
                    <td class="tg-nrix">ON</td>
                    <td class="tg-nrix">X</td>
                </tr>
                <tr>
                    <td class="tg-bb96">4</td>
                    <td class="tg-nrix">Playback Completion</td>
                    <td class="tg-nrix">ON</td>
                    <td class="tg-nrix">X</td>
                </tr>
                <tr>
                    <td class="tg-bb96">5</td>
                    <td class="tg-nrix">Standby</td>
                    <td class="tg-nrix">ON</td>
                    <td class="tg-nrix">X</td>
                </tr>
                </tbody>
            </table><br>
            Even in the accessible state of robot, be watchful against any possible sudden movement of robot. Make sure to avoid approaching the robot without precautions for emergency under all circumstances.<br><br>            
</ol>

<ol style="list-style-position: outside; list-style-type:square;" start="1">
    <li>
        <b>
        During temporary halt, the entrance countermeasure same as entrance of teaching work should be considered at the case (nozzle contact, welded part detected, arc error, and so on) of opening entrance gate for simple management against error.
        </b>
    </li>
</ol><br>

<ol style="list-style-type:decimal" start="17">
    <li>
        Clean up any split oil, tools, and impurities in the safety fence after completing robotic operation. Accidents such as conduction may occur in the working envelope contaminated by oil, or scattered tools on its floor. Make a habit of organizing and cleaning things up. 
    </li>
</ol># 1.7.2. Safety Precautions for Operating Test 

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                Please observe following countermeasures because safety on robot operation is very important.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>



In case of operating test, errors in design or teaching and inferiority in manufacturing are possibly seen in the entire system such as teaching program, jig, and sequence. Thus, be more careful and safe in case of operating test. Accidents may occur by these combined causes. 

<ol style="list-style-type:decimal" start="1">
		<li>
            Before handling, check the stop buttons and signal functions to stop the robot such as emergency stop button or stop button. And then, check the abnormality - detective movements. Above all, it is the most critical to check all the stop signals. It would be the most important to stop the robot when any possible accidents are predicted. 
        </li><br>		
		<li>
            In case of operating test, start the robot at low speed(approximately 20%~30%) in the variable speed function, and repeat it more than one cycle to check the movements. If any errors are found, immediately correct them. After then, increase in speed (50% → 75% → 100%) gradually, and repeat more than one cycle respectively to check the movements. Operating at high speed from the very beginning may cause a serious accident. 
        </li><br>	
		<li>
           In case of operating test, it is hard to predict what problems would happen. Do not enter the safety fence during operating test. Unexpected accidents are likely to occur because of its low reliability. 
        </li><br>	          
</ol>
# 1.7.3. Safety Precautions for Automatic Operation

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                Please observe following countermeasures because safety on robot automatic operation is very important.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>


<ol style="list-style-type:decimal" start="1">
		<li>
hile posting a sign [Do Not Enter During Operation] up the safety fence gate, ask the operators not to enter during operation. If the robot stops, you may enter the safety fence under your full understanding of the situation. 
</li><br>
    <li>
<img src="../../_assets/작은주의표시.png">
Be sure to check if any operators are inside of the safety fence when starting the automatic operation. Operating without checking the presence of operators may cause a personal injury. 
</li><br>
    <li>
Before starting the automatic operation, check and confirm that the program number, step number, mode, and starting selection are in the possible state for automatic operation. If starting with the other programs or steps selected, the robot could move in an unpredicted way, and lead to an accident. 
</li><br>
    <li>
Before starting the automatic operation, check if the robot is properly located to get started. Check whether the program number or step number is identical with the location of robot. Even if it's all identical, accidents are still possible to occur due to an abnormal movement when the robot is differently located. 
</li><br>
    <li>
Be prepared to immediately press the emergency stop button when starting the automatic operation. Immediately press the emergency stop button in case of robot's unexpected movements or emergency. 
</li><br>
    <li>
Be sure to detect any abnormalities by checking the route, condition, or sound of robot movement. Sometimes the robot may be abnormally operated including a sudden break down. However, it will show a certain indication before the break down. Understand the robot's normal condition well in order to catch the symptom in advance. 
</li><br>
    <li>
<img src="../../_assets/작은주의표시.png">
When any abnormality is detected from the robot, immediately stop and take proper actions on it. Using the robot before any proper actions taken may cause an interruption of produce as well as serious failure leading to a very serious personal injury. 
</li><br>
    <li>
<img src="../../_assets/작은주의표시.png">
When checking the robot’s movement after the proper actions taken for the abnormality, do not operate the robot with operators inside of the safety fence. Unexpected accidents are possibly to occur because its low reliability may cause another abnormality. 
    </li><br>	 
</ol>
# 1.8. Safety Precautions for Access to Safety Fence

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../_assets/주의표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
               Please observe following countermeasures because safety on robot automatic operation is very important.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>

The robot is very heavy and strong, even at low speeds. When entering the safety fence, one must observe the relevant safety regulations of its pertinent country.

The operators always must be aware of the unexpected movements of robot. Robots are able to move fast shortly after being stopped. The operators should know that the robot is able to move in a different route, without any notice, by means of external signals. Thus, when trying to stop the robot during teaching or operating test, one should be able to stop the robot with a teach pendant or control panel.

When entering the working envelope through the safety gate, you must take the teach pendant with yourself so that other people can not operate the robot. Make sure to post up the control panel a sign indicating the state of robot handling. 

People must understand the followings when they are to enter the robot’s working envelope


<ol style="list-style-type:decimal" start="1">
		<li>
Do not enter the working envelope other than teaching person. 
</li><br>
    <li>
Operation set-up mode of controller must be a manual mode in the control panel. 
</li><br>
    <li>
Always wear the approved working suite.(Do not wear a loose clothes as you please) 
</li><br>
    <li>
Do not wear gloves when handling controller. 
</li><br>
    <li>
Do not leave innerwear such as underwear, shirts, or necktie out of the working suite. 
</li><br>
    <li>
Do not wear personal accessories such as big earrings, rings, or necklaces. 
</li><br>
    <li>
Make sure to wear safety shoes, helmet, and goggles and if necessary, wear other self-protective outfit such as safety gloves. 
</li><br>
    <li>
Make sure that the emergency stop circuit is working correctly and in its proper function, turns MOTOR OFF when pressing the emergency stop button in the control panel and teach pendant before handling the robot. 
</li><br>
    <li>
Make your posture face-to-face with the robot manipulator when performing your work. 
</li><br>
    <li>
Follow the predetermined working procedure.
</li><br>
    <li>
Be prepared for emergency exit or safe place considering that the robot may unexpectedly rush at you.
</li><br>	
</ol># 1.9. Safety Precautions for Maintenance and Repair # 1.9.1. Safety Precautions for Controller Maintenance and Repair

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td>   
            <td colspan="4"> 
                Please observe following safety countermeasures on repair and check for robot controller.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>


<ol style="list-style-type:decimal" start="1">
		<li>
Maintenance and repair of the robot must be performed by the personnel who was duly trained in the special maintenance training course and has a good knowledge of maintenance. 
</li><br>
    <li>
Perform your work following the maintenance procedures for controller. 
</li><br>
    <li>
Perform your maintenance and repair in a safe way by securing emergency exit or safe place. 
</li><br>
    <li>
Before the daily maintenance, repair, or changing parts, be sure to power down. In addition, post a warning sign [Do Not Input Power] up the primary power so that other operators may not input power by accident. 
</li><br>
    <li>
When changing parts, be sure to use the specified ones. 
</li><br>
    <li>
When you open the door of controller, you should turn off power, and please start working after 3 minutes. 
</li><br>
    <li>
If sufficient illuminance is not secured when you perform maintenance and inspection inside the controller, you should use external lights.
</li><br>
    <li>
Please do not touch heat radiating plate of servo AMP and recovery resistance because they are very hot. 
</li><br>
    <li>
After completing maintenance, be sure to close the door completely after checking if tools or other things are still remained in the controller.
</li><br>	
</ol># 1.9.2. Safety Precautions for Robot System & Manipulator Maintenance

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                Please observe following safety countermeasures on repair and check for robot controller.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>


<ol style="list-style-type:decimal" start="1">
		<li>
Refer to the safety precautions for Controller maintenance and repair. 
</li><br>
    <li>
Perform your maintenance and repair for the robot system and manipulator, following the indicated procedures. 
</li><br>
    <li>
Be sure to disconnect the primary power of controller. Post the warning sign [Do not input power] up the primary power to prevent other workers from connecting the power. 
</li><br>
    <li>
Make sure that the Arm is fixed and immovable before maintenance and repair since dropping or moving of the robot's Arm may cause a danger during maintenance and repair. (Refer to the 『Robot manipulator maintenance manual』.)
</li><br>	 
</ol># 1.9.3. Necessary Actions after Maintenance and Repair

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                Please install the robot in accordance with following method surely.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>


<ol style="list-style-type:decimal" start="1">
		<li>
Check if the cables or parts of controller are properly connected. 
</li><br>
    <li>
After maintenance is completed, carefully check that no tools are left around or inside of the controller and manipulator. Make sure that the door is firmly closed. 
</li><br>
    <li>
Do not turn on the power if any problems or critical failures are detected. 
</li><br>
    <li>
Be sure that there is no one within the working envelope, and that you are in a safe place before turning on the power. 
</li><br>
    <li>
Turn on the main circuit breaker on the control panel. 
</li><br>
    <li>
Check the current position and status of robot. 
</li><br>
    <li>
Operate the manipulator at low speed. 
</li><br>	 
</ol># 1.10. Safety Functions
# 1.10.1. Operating a Safety Circuit

![](../../_assets/그림_1.5_안전체인_구성도_.png)


Figure 1.5 Configuration for safety chain

<br>

The robot's safety system is based on a two-channel safety circuit that is continuously monitored. If an error is detected, the power supply to the motors is disconnected and the motor brake is applied. To return the robot to MOTOR ON mode, the switches of two-channel circuit must be connected. If one of the two-channel circuit switches shorts, the contactor of motor will be disconnected leading to the application of brake, and finally the robot will be stopped. Furthermore, when safety circuit is disconnected, the interrupting call will be sent automatically to the controller to find out the possible reason for the interruption. 

The safety control circuit of operation is based on dual safety electric circuit in which the controller and MOTOR ON mode are operated interactively. In order to be in MOTOR ON mode, the safety circuit consisted of several switches must be all connected. MOTOR ON mode indicates that drive power is supplied to the motors. If one of the contactors is disconnected, the robot will always return to MOTOR OFF mode.

MOTOR OFF mode indicates that drive power is removed from the robot's motors and the brakes are applied. The status of the switches is displayed on the teach pendant. (Refer to the I/O monitoring screen of "SERVICE" menu, 『Operation manual』.)

<font size = 3><b>Safety circuit</b></font>

The emergency stop buttons on the controller panel and on the teach pendant and external emergency stop buttons are included in the safety circuit of operation. Users may install the safety devices (safety plug, safety stop device for safe place) which are operated in the AUTO mode. In a manual mode, the signals of these safety devices are ignored. You can connect the general safety stop devices that is active in all operating modes. No one can enter the working envelope in an automatic operation mode due to the unconditional operation of the safety devices (door, safety mat, safety plug etc.). These signals are also generated in a manual mode, but the controller will keep the robot operating while ignoring the robot's teaching. In this case, maximum speed of robot is restricted to 250mm/s. Thus, the purpose of this safety stop function is to secure the safe area around the manipulator while one approaches the robot for maintenance and teaching. 

When the robot is stopped with the limit switch, change the robot’s position by operating it with the pendant key at the constant setting mode. (Constant setting mode refers to the state of entry into the menu『[F2]: System』 menu)


<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/주의표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                The safety circuits must never be by-passed, modified or changed in any way.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br># 1.10.2. Emergency stop

An emergency stop should be activated when people or equipment is located at the dangerous area. The emergency stop buttons are located both on the control panel and on the teach pendant. 
All safety control devices such as emergency stop buttons on the control panel must be located outside the working envelope and easily accessible at any time.


![](../../_assets/말머리이미지.png)<font size = 3> **Status of Emergency stop** </font><br>

When the button is pressed, the robot will operate as follows. 
Robot stops immediately in any cases.

<ol style="list-style-type:square" start="1">
		<li>
            Disconnect the servo system power.
        </li>		
		<li>
            Motor brake is activated.
        </li>	  
        <li>
        	Motor brake is activated.
        </li>
</ol>


For the emergency stop, the following two methods can operated simultaneously.

<ol style="list-style-type:decimal" start="1">
<li>
Emergency stop for control panel and teach pendant (Basic)<br><br>
Above the control and teach pendant console.
        </li><br>
		<li>
Emergency stop of external system<br><br>
External emergency stop device (button etc.) can be connected to the safety electric circuit in accordance with applied standard for the emergency stop circuit.
(Please refer to system board in “basic configuration of controller”) At this time, the emergency stop must be connected to be “Normal On” and it must be check for proper operation during test run.
</li><br>
</ol>


![](../../_assets/그림_1.6_시스템보드_터미널블록_TBEM를_통한_외부비상정지스위치의연결.png)

Figure 1.6 Connection with external emergency halt switch through system board terminal block TBEM# 1.10.3. Operating Speed

To teach the robot, the operating mode switch must be in a MANUAL mode. Then the maximum speed of robot is limited to 250mm/s. # 1.10.4. Connecting the Safety Devices

External safety devices such as light beams, light curtains, safety plug, and safety mats which can be adapted by the system builder execute interlocking the controller by way of connecting with safety circuit within the controller. These devices are used for safety device during execution of normal program in an automatic mode. 
# 1.10.5. Restricting the working Envelope

When the robot is not necessary to reach certain area for specific applications, working envelope of the robot can be limited to secure the sufficient safety working area. This will reduce the damage or loss in case of robot's collision with external safety devices such as safety fence, etc. The movement of axes 1, 2, and 3 of HR, HX, HS and HA can be limited by means of mechanical stopper or electrical limit switches. In this case, the corresponding software limitation parameters must be also changed. If necessary, movement of wrist 3 axes can be restricted, too. Limitation of working envelope for all the axes could be carried out by the user. The robot is delivered to customer as the status of full working envelope setting. 

<style type="text/css">
    .block {background-color:#f8f8be}
</style>
<blockquote class="block">
    <ol style="list-style-type:disc" start="1">
        <br>
		<li>
            <font size = 3><b>Manual mode: Maximum speed is 250mm/s. </b></font><br>
            In a manual mode, by means of worker’s selection, workers may enter the safeguard area. 
        </li><br>
		<li>
            <font size = 3><b>Auto mode : The robot can be operated via remote controller.</b></font><br>
            All safety devices such as safety door, safety mats, etc. are activated.<p>
            No one may enter the safety device area of robot.
           </li><br>
    </ol>
</blockquote># 1.10.6. Monitoring Function

<ol style="list-style-type:decimal" start="1">
		<li>
Motor monitoring function<p>
Motors are protected against overload by means of onboard sensors. 
    </li>	<br>
		<li>
Voltage Monitoring Function<p>
For the protection of, the servo amp module turns off the power switch when the voltage is too low or too high. 
</li>	  
</ol># 1.11. Safety Related to End Effectors

# 1.11.1. Gripper

<ol style="list-style-type:decimal" start="1">
		<li>
      When a gripper is used to grip a workpiece, there should be safety precautions for unexpected dropping of the loaded workpiece. 
    </li>	<br>
		<li>
      When any end effectors or devices are installed on the robot arm, use the required size and piece of bolt, and securely fasten as per the required torque using torque wrench. Do not use the bolt which has rust or dirt on its surface. 
    </li><br>
    <li>
      End effector must be designed and manufactured not to exceed the maximum allowable load at the wrist of robot. Even though power or air supply stops, the gripped workpiece must not be dropped from the gripper. In order to remove any risks and problems which may cause personal injury and/or physical damage, the sharp edge and projecting part of end effector must be made dull and smooth. 
    </li><br>
</ol># 1.11.2. Tool / Workpiece


<ol style="list-style-type:decimal" start="1">
    <li>
      It must be possible to replace tools such as milling cutters in a safe manner. Make sure that safety devices are working correctly until the cutters stop rotating. 
    </li>	<br>
    <li>
      Tool must be designed to keep in gripping workpiece securely even though a power failure or a control failure takes place. It must be possible to release workpiece from the gripper in a manual mode. 
    </li><br>
</ol># 1.11.3. Pneumatic and Hydraulic Systems

<ol style="list-style-type:decimal" start="1">
    <li>
      The special safety regulations will apply to pneumatic and hydraulic systems. 
    </li>	<br>
    <li>
      Since residual energy of pneumatic and hydraulic systems can be still remaining even after the robot stops, particular care and attention must be paid by users. Internal pressure of equipment must be removed whenever starting the repair work for pneumatic and hydraulic systems.  
    </li><br>
</ol># 1.12. Liabilities 

The robot system has been built in accordance with the latest technical standards and approved safety rules. Nevertheless, the serious accidents such as death or personal injury still may take place due to the collision between the robot system and peripheral equipment.

The robot system must be used by operator who has a full technical knowledge on its designated use and also pay his close attention to the possible dangers and risks involved in its operation. The use of robot system is subject to compliance with these operating instructions and the operation and maintenance manual supplied together with the robot system. The safety related functions of robot system must not be used for any purposes other than safety.

When you use the robot system for any other or additional purposes than its designated usage, you must review whether it is enable in accordance with design criteria. The manufacturers cannot take any responsibility for any damage or loss which resulted from such misuse or improper use. The users shall have the full responsibility for the risks caused by such misuse or improper use. When you use and operate the robot system for its designated use, you must have a good command of all the information contained at these operating instructions as well as the maintenance manual. 

The robot system may not be put into operation until it is ensured that the functional machine or plant into which the robot system has been integrated conforms to the specifications of the EU Machinery Directive 98/37/EC(2006/42/EC) and US OSHA. 

The following harmonized standards in particular were taken into account with regard to the safety of the robot system.



<ol style="list-style-type:square" start="1">
    <li>
ANSI/RIA R15.06-1999 
Industrial Robots and Robot Systems - Safety Requirements 
</li><br>
    <li>
ANSI/RIA/ISO 10218-1-2007 
Robots for Industrial Environment - Safety Requirements - Part 1 - Robot 
ISO 11161:2007 
</li><br>
    <li>
Safety of machinery - Integrated manufacturing systems - Basic requirements 
EN ISO 13849-1:2008
</li><br>
    <li>
Safety of machinery - Safety-related parts of control systems - Part 1: General principles for design (ISO 13849-1:2006) 
</li><br>
    <li>
EN 60204-1:2006 
Safety of machinery - Electrical equipment of machines - Part 1: General requirements (IEC 60204-1:2005 (Modified)) 
</li><br>
    <li>
EN ISO 10218-1:2006 
Robots for industrial environments - Safety requirements - Part 1: Robot (ISO 10218-1:2006) 
</li><br>
</ol>


Users must take the full responsibility for any accident caused by their negligence or non-observance of these instructions. The manufacturer will not take any liabilities and responsibilities for any damages or losses caused by the misuse or malfunction of such equipment which is not included in the contract between manufacturer and user and provided by user, or such equipment which is installed around the robot system arbitrarily by the user. User must take the full liabilities and responsibilities for any risks and damages caused by such equipment.


# 2. Specifications
# 2.1. Robot Machinery Part


![](../_assets/그림_2.1_로봇기구부형식.png)


Figure 2.1 Robot Machinery Part# 2.2. Location of Robot Identification Plate

The model name, serial number, and manufacturing date of robot are written down in the name plate.

Identification plate is located at the bottom of the main body (Left or right side) as shown in the following figure. 




![](../_assets/그림_2.2_로봇명판부착위치.png)


Figure 2.2 The location of identification plate # 2.3. Basic Specifications

Table 2-1 Specifications for Models
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-9wq8{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-c3xd{background-color:#f8f8be;border-color:inherit;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-mft0{background-color:#ccf1bc;border-color:inherit;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-c3xd" colspan="4">Item</th>
    <th class="tg-c3xd" colspan="4">Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3xd" colspan="4">Robot Model</td>
    <td class="tg-c3xd">HH4L</td>
    <td class="tg-c3xd">HH7</td>
    <td class="tg-c3xd">HH7E</td>
    <td class="tg-c3xd">HH8</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">Structure</td>
    <td class="tg-9wq8" colspan="4">Articulated</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">Degree of freedom</td>
    <td class="tg-9wq8" colspan="4">6</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">Drive system</td>
    <td class="tg-9wq8" colspan="4">AC SERVO MOTOR</td>
  </tr>
  <tr>
    <td class="tg-mft0" rowspan="6">Max. Working envelope</td>
    <td class="tg-mft0" rowspan="3">Arm</td>
    <td class="tg-mft0">S</td>
    <td class="tg-mft0">Swivel</td>
    <td class="tg-9wq8" colspan="4">±2.967rad (±170°)</td>
  </tr>
  <tr>
    <td class="tg-mft0">H</td>
    <td class="tg-mft0">Horizontal</td>
    <td class="tg-9wq8" colspan="4">+3.14 ~ -0.96rad(+180°~ -55°)</td>
  </tr>
  <tr>
    <td class="tg-mft0">V</td>
    <td class="tg-mft0">Vertical</td>
    <td class="tg-9wq8" colspan="3">+3.71 ~ - 1.22rad (+213°~ -70°)</td>
    <td class="tg-9wq8">+3.71 ~ - 1.15rad (+213°~ -66°)</td>
  </tr>
  <tr>
    <td class="tg-mft0" rowspan="3">Wrist</td>
    <td class="tg-mft0">R2</td>
    <td class="tg-mft0">Rotation 2</td>
    <td class="tg-9wq8" colspan="4">±3.316 rad (±190°)</td>
  </tr>
  <tr>
    <td class="tg-mft0">B</td>
    <td class="tg-mft0">Bending</td>
    <td class="tg-9wq8" colspan="2">±2.356 rad (±135°)</td>
    <td class="tg-9wq8">±2.094 rad (±120°)</td>
    <td class="tg-9wq8">±2.356 rad (±135°)</td>
  </tr>
  <tr>
    <td class="tg-mft0">R1</td>
    <td class="tg-mft0">Rotation 1</td>
    <td class="tg-9wq8" colspan="4">±6.283 rad (±360°)</td>
  </tr>
  <tr>
    <td class="tg-mft0" rowspan="6">Maximum speed</td>
    <td class="tg-mft0" rowspan="3">Arm</td>
    <td class="tg-mft0">S</td>
    <td class="tg-mft0">Swivel</td>
    <td class="tg-9wq8">5.235 rad/s (300°/s)</td>
    <td class="tg-9wq8" colspan="2">6.544 rad/s (375°/s)</td>
    <td class="tg-9wq8">7.941 rad/s (455°/s)</td>
  </tr>
  <tr>
    <td class="tg-mft0">H</td>
    <td class="tg-mft0">Horizontal</td>
    <td class="tg-9wq8">4.014 rad/s (230°/s)</td>
    <td class="tg-9wq8" colspan="2">5.497 rad/s (315°/s)</td>
    <td class="tg-9wq8">6.719 rad/s (385°/s)</td>
  </tr>
  <tr>
    <td class="tg-mft0">V</td>
    <td class="tg-mft0">Vertical</td>
    <td class="tg-9wq8">6.283rad/s (360°/s)</td>
    <td class="tg-9wq8" colspan="2">7.155rad/s (410°/s)</td>
    <td class="tg-9wq8">9.075rad/s (520°/s)</td>
  </tr>
  <tr>
    <td class="tg-mft0" rowspan="3">Wrist</td>
    <td class="tg-mft0">R2</td>
    <td class="tg-mft0">Rotation 2</td>
    <td class="tg-9wq8" colspan="4">9.599 rad/s (550°/s)</td>
  </tr>
  <tr>
    <td class="tg-mft0">B</td>
    <td class="tg-mft0">Bending</td>
    <td class="tg-9wq8" colspan="4">9.599 rad/s (550°/s)</td>
  </tr>
  <tr>
    <td class="tg-mft0">R2</td>
    <td class="tg-mft0">Rotation 1</td>
    <td class="tg-9wq8" colspan="2">9.599 rad/s (550°/s)</td>
    <td class="tg-9wq8">13.613 rad/s (780°/s)</td>
    <td class="tg-9wq8">17.453 rad/s (1000°/s)</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">Load Capacity</td>
    <td class="tg-9wq8">39.2 N (4 kg)</td>
    <td class="tg-9wq8" colspan="2">68.6 N (7 kg)</td>
    <td class="tg-9wq8">78.4 N (8 kg)</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="2" rowspan="3">Wrist torque</td>
    <td class="tg-mft0">R2</td>
    <td class="tg-mft0">Rotation 2</td>
    <td class="tg-9wq8" colspan="2">6 N·m (0.61 kgf·m)</td>
    <td class="tg-9wq8" colspan="2">17 N·m (1.73 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-mft0">B</td>
    <td class="tg-mft0">Bending</td>
    <td class="tg-9wq8" colspan="2">6 N·m (0.61 kgf·m)</td>
    <td class="tg-9wq8" colspan="2">17 N·m (1.73 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-mft0">R1</td>
    <td class="tg-mft0">Rotation 1</td>
    <td class="tg-9wq8" colspan="2">2.9 N·m (0.30 kgf·m)</td>
    <td class="tg-9wq8" colspan="2">10 N·m (1.02 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">Accuracy of position repeatability <sup>1)</sup></td>
    <td class="tg-9wq8" colspan="3">±0.03 mm</td>
    <td class="tg-9wq8">±0.02 mm</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">Ambient Temperature<sup>2)</sup></td>
    <td class="tg-9wq8" colspan="4">0 ~ 45 ℃ (273 ~ 318 K)</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">Relative humidity</td>
    <td class="tg-9wq8" colspan="4">20  ∼ 85 %RH</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">Robot's Weight</td>
    <td class="tg-9wq8">49 kg</td>
    <td class="tg-9wq8">49 kg</td>
    <td class="tg-9wq8">49 kg</td>
    <td class="tg-9wq8">47 kg</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">Operating range Cross-sectional area</td>
    <td class="tg-9wq8">3.45m²</td>
    <td class="tg-9wq8" colspan="2">1.98m²</td>
    <td class="tg-9wq8">1.46m²</td>
  </tr>
</tbody>
</table>

1)	Conforms to ISO 9283.
2)	In the event of a high-temperature usage environment and harsh operating conditions, kindly request a technical review from our company. 
# 2.4. Robot Dimension and Working Envelope



![](../_assets/그림_2.3_로봇_본체_외형_치수_및_동작_영역.png)

Figure 2.3 Robot Dimension and Working Envelope:[HH4L]


![](../_assets/그림_2.4_로봇_본체_외형_치수_및_동작_영역.png)


Figure 2.4 Robot Dimension and Working Envelope:[HH7]

![](../_assets/그림_2.5_로봇_본체_외형_치수_및_동작_영역.png)


Figure 2.5 Robot Dimension and Working Envelope:[HH8] 

![](../_assets/그림_2.6_로봇_본체_외형_치수_및_동작_영역.png)


Figure 2.6 Robot Dimension and Working Envelope:[HH7E]# 2.5. Axis Identification

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
.tg caption{caption-side: top;text-align: left;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-bgl2{background-color:#f8f8be;color:#000000; font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-jnja{background-color:#ccf1bc;text-align:center;color:#000000; font-weight:bold;vertical-align:top}
</style>
<table class="tg">
<caption>Table 2-2 Axis Motion</caption>  
<thead>
  <tr>
    <th class="tg-bgl2">Axis Name</th>
    <th class="tg-bgl2">Operation</th>
    <th class="tg-bgl2" colspan="2">Teach Pendant Button</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-jnja">S</td>
    <td class="tg-baqh">Arm Swivel</td>
    <td class="tg-baqh">LFT(S+)</td>
    <td class="tg-baqh">RHT(S-)</td>
  </tr>
  <tr>
    <td class="tg-jnja">H</td>
    <td class="tg-baqh">Arm Forward and Backward</td>
    <td class="tg-baqh">BWD(H+)</td>
    <td class="tg-baqh">FWD(H-)</td>
  </tr>
  <tr>
    <td class="tg-jnja">V</td>
    <td class="tg-baqh">Arm Upward and Downward</td>
    <td class="tg-baqh">Up(V+)</td>
    <td class="tg-baqh">Down(V-)</td>
  </tr>
  <tr>
    <td class="tg-jnja">R2</td>
    <td class="tg-baqh">Wrist Rotation 2</td>
    <td class="tg-baqh">Right(R2+)</td>
    <td class="tg-baqh">Reverse(R2-)</td>
  </tr>
  <tr>
    <td class="tg-jnja">B</td>
    <td class="tg-baqh">Bending</td>
    <td class="tg-baqh">Right(B+)</td>
    <td class="tg-baqh">Reverse(B-)</td>
  </tr>
  <tr>
    <td class="tg-jnja">R1</td>
    <td class="tg-baqh">Wrist Rotation 1</td>
    <td class="tg-baqh">Right(R1+)</td>
    <td class="tg-baqh">Reverse(R1-)</td>
  </tr>
</tbody>
</table>
<br><br>

![](../_assets/그림_2.5_본체_외관_및_동작_축.png)

Figure 2.7 Robot Dimension and Axis# 2.6. Details of Wrist Axis Attachment Surface


When attaching the work tool on the flange of the wrist end, use the bolt of the applicable model..


![](../_assets/그림_2.6_손목축_취부면_상세도.png)

Figure 2.8 Details of Wrist Axis Attachment Surface (HH4L/HH7/HH8)

![](../_assets/그림_2.6_손목축_취부면_상세도2.png)

Figure 2.9 Details of Wrist Axis Attachment Surface (HH7E)# 2.7. Details of Application Parts Attachment Surface

A tap for attaching a peripheral device and bracket is machined on the manipulator. 



![](../_assets/그림_2.10_응용부품_취부면_상세도.png)

Figure 2.10 Details of Application Parts Attachment Surface
# 2.8. Wiring and Piping Drawings for Application


로봇 본체에는 부가 장비를 연결하기 위한 콘넥터와 공기 유닛이 있습니다.

다음 그림들은 사용자 응용 콘넥터를 표시합니다.


![](../../_assets/그림_2.9_어플리케이션용_배선_및_배관도.png)

![](../../_assets/그림_2.11_어플리케이션용_배선_및_배관도.png)

Figure 2.11 Wiring and piping drawings for application 

<br>

# 2.8.1. Connector details for application


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
.tg caption{caption-side: top;text-align: left;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-baqh"><img src="../../_assets/그림_2.11_어플리케이션_커넥터_상세.png">
    </img></td>
    <td class="tg-baqh">< ASR 1 ><br>
    · cable: 0.2sq * 10P<br>
    · Connector type : LF13WBRB -20S(HIROSE) (M)<br>
    · Mating connector : LF13WBLP -20PA(HIROSE) (F/ELBOW TYPE)<br>
                 : LF13WBP -20P(HIROSE) (F/STRAIGHT TYPE)
  </td>
  </tr>
</thead>
</table>


Figure 2.12 Connector details for application# 2.9. Operating range limit

When installing the robot, consider the fact that you can adjust the operating range freely within the full operating area. 

The operating range limit is effective in the following environment.

*	When you want to limit the operating area while the robot is operating
*	When the robot can collide with the surrounding devices
*	When the length of applied cable or hose is limited

There are 2 methods to limit the operating area of the robot.

*	Software limit (Applied to the entire axis)
*	Mechanical stopper (1 axis)



<img src="../../_assets/작은주의표시.png"><b>[Caution]</b><br>
Mechanical stopper is a physical device. The robot cannot exceed the mechanical stopper. The mechanical stoppers of 1axes are fixed. For 2~6 axes, only the software limit can be applied.

When the mechanical stopper collides with the robot, it is deformed and the strength cannot be guaranteed. Therefore, you must replace the mechanical stopper in this case.

# 2.9.1. 1 axis (S axis)

By adding on more mechanical stopper, the working envelope of the 1st axis can be limited. (by 10°)
If one axis STOPPER BLOCK and STOPPER are subjected to severe shock, they must be replaced.
# 3. Instructions



# 3.1. Robot Component Name

Name of each part of the main body is as shown in [Fig. 3.1], [Table 3-1] 


![](../_assets/그림_3.1_본체_각_부위_명칭.png)

Figure 3.1 Name of Robot Components

<br>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
.tg caption{caption-side: top;text-align: left;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-bgl2{background-color:#f8f8be;color:#000000; font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-bav5{background-color:#f8f8be;text-align:center;color:#000000; font-weight:bold;vertical-align:top}
</style>
<table class="tg">
<caption>Table 3-1 Name of Robot Components</caption>  
<thead>
  <tr>
    <th class="tg-bgl2">No.</th>
    <th class="tg-bgl2">Name of each part</th>
    <th class="tg-bgl2">No.</th>
    <th class="tg-bav5">Name of each part</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">BASE BODY</td>
    <td class="tg-baqh">8</td>
    <td class="tg-baqh">S axis motor</td>
  </tr>
  <tr>
    <td class="tg-baqh">2</td>
    <td class="tg-baqh">LOWER FRAME</td>
    <td class="tg-baqh">9</td>
    <td class="tg-baqh">H axis motor</td>
  </tr>
  <tr>
    <td class="tg-baqh">3</td>
    <td class="tg-baqh">UPPER FRAME</td>
    <td class="tg-baqh">10</td>
    <td class="tg-baqh">V axis motor</td>
  </tr>
  <tr>
    <td class="tg-baqh">4</td>
    <td class="tg-baqh">ARM FRAME</td>
    <td class="tg-baqh">11</td>
    <td class="tg-baqh">R2 axis motor</td>
  </tr>
  <tr>
    <td class="tg-baqh">5</td>
    <td class="tg-baqh">ARM PIPE</td>
    <td class="tg-baqh">12</td>
    <td class="tg-baqh">B axis motor</td>
  </tr>
  <tr>
    <td class="tg-baqh">6</td>
    <td class="tg-baqh">WRIST BODY</td>
    <td class="tg-baqh">13</td>
    <td class="tg-baqh">R1 axis motor</td>
  </tr>
  <tr>
    <td class="tg-baqh">7</td>
    <td class="tg-baqh">WRIST HOLDER</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
  </tr>
</tbody>
</table>
# 3.2. Location of Safety Nameplate

In order to prevent any accidents, safety marking plates such as [Figure 3.2] is attached to the robot. Do not remove or replace it unnecessarily.

![](../_assets/그림_3.2.1_안전명판위치1.png)

![](../_assets/그림_3.2.1_안전명판위치2.png)

Figure 3.2 Location of Safety Nameplate# 3.3. Transportation method 
# 3.3.1. Using crane


![](../../_assets/그림_3.5_운반방법_크레인이용.png)

Figure 3.3 How to Transport: Using crane [HH7, HH7E] 

<br>

![](../../_assets/그림_3.6_운반방법_크레인이용.png)
![](../../_assets/그림_3.6_운반방법_크레인이용1.png)

Figure 3.4 How to Transport: Using crane [HH8, HH4L] 

<br>


![](../../_assets/작은주의표시.png)
*	Never walk under the robot.
*	Pose the robot as shown in the Figure.
*	Install the lifting bracket (option). (4-M6×12)
*	Fasten a wire rope or a hook to the lifting bracket.
*	Attach the protective hose (50cm) to prevent the damage to the main body of the robot.
*	Keep the safety regulations during lifting process.
*	Weight of manipulator : 47.5kg[HH8], 48.5kg[HH7], 49.2kg[HH4L], 49kg[HH7E]
*	Minimum crane capacity : 0.2 tons



![](../../_assets/작은주의표시.png)
※ Insert the wire rope into a protective hose to prevent damage to the painted parts of the robot at the contact area between the manipulator and the wire rope. Refer to the figure for the areas where the protective hose should be used# 3.3.2. Use of forklift


![](../../_assets/그림_3.7_운반방법_지게차이용.png)

Figure 3.5 Transportation method: Use of forklift 

<br>

When transporting the main body of the robot, you can use the forklift.

Follow the below procedure for safety purposes.

*	Refer to the figure and take the basic pose for each model.
*	Fixate the robot to the pallet and insert the fork of the forklift to transport the robot. The pallet must be able to sufficiently withstand the strength. 
*	Transport in low speed.
*	Follow the safety regulations.


<img src="../../_assets/작은주의표시.png"> <b>Caution</b>

*	Do not lean on the main body of the robot during the transportation work.
*	When loading/unloading the main body of the robot, make sure that the robot does not collide with the floor. 
*	Follow the safety rules when operating the forklift.
# 3.4. How to Install

<img src="../../_assets/작은주의표시.png"><b>NOTE:</b><br>
Before starting to unpack and install the robot, read the safety regulations and other instructions very carefully. 

<img src="../../_assets/작은주의표시.png"><b>Warning:</b><br>
The installation shall be made by qualified installation personnel and should conform to all national and local codes. 

When unpacking the robot, check if it has been damaged during transporting or unpacking. In addition, strictly keep the following installation instructions because installation method and foundation are very important to maintain a good robot performance.

# 3.4.1. Operating Conditions


(1)	Ambient temperature should range from 0℃ to 45℃.<br>

(2)	Ambient humidity should range from 20% to 85% RH, without dew condensation.<br>

(3)	Less dust, oil, or moisture.<br>

(4)	No flammable, corrosive liquid or GAS.<br>

(5)	No impact and shacking.<br>

(6)	No electrical noise generator near the robot.<br>

(7)	If the robot is not immediately installed, keep it in a dry area at an ambient temperature between -15℃~ and 40℃.
# 3.4.2. Installation the Robot Manipulator

The main body of the robot must be fixated firmly with 4ea M8 bolts. All 4 bolts must be used.

*	Bolt: M8(12.9) SOCKET HEAD BOLT
*	Washer : Spring washer, plain washer
*	Connection torque: 680 kgfcm

The base floor where the robot will be installed must be designed to have hardness to minimize the dynamic effect of the robot. 

When installing the robot on the concrete floor with thickness of 200mm or more, repair any uneven areas or cracks and fixate the mounting plate with M20 anchor bolts. And when installing the robot on the concrete floor with thickness of less than 200mm, make sure to review prior to the installation as it requires base construction.

 
# 3.4.3. Accuracy of Installation Surface

The flatness of the four installation surfaces on the plate attachment surface of the manipulator and their height errors should satisfy the designated specifications. Shims should be used when necessary.

*	Cautions

    ①	The flatness of the 4 mounting plates must be within 1.0 mm.

    ②	The error in the heights of the four plate attachment surfaces should be within 0.2mm(±0.1mm).



![](../../_assets/그림_3.6_로봇_설치면_정도.png)

Figure 3.6 Robot installation surface accuracy# 3.4.4. Emergency Stop time & Distance

The following items are the response time and distance for an emergency stop during the max speed operation of each axis (S, H, and V) with the standard load.

*	HH4L<p>
Max Time	: 0.43 seconds<br>
Max Moving Distance : 142.5 cm<br>

*	HH7<p>
Max Time	: 0.43 seconds<br>
Max Moving Distance : 163.3 cm<br>

*	HH8<p>
Max Time : 0.47 seconds<br>
Max Moving Distance : 146.3 cm<br>

*	HH7E<p>
Max Time	: 0.45 seconds<br>
Max Moving Distance : 176 cm
# 3.4.5. Dimension of Installation Surface

Assemble the main body of the robot on the common base, Refer to the following dimensions.


※ 주의사항 : 본체 설치 시 2개의 Ø6위치 결정용 PIN을 적용하여 주십시오.



![](../../_assets/그림_3.7_로봇_설치면_치수.png)

Figure 3.7 Robot installation surface dimension (HH4L/HH7/HH7E/HH8)# 3.5. Allowable Load of Wrist Axis



# 3.5.1. Permitted load torque, Permitted inertia moment estimation

The load, which will be applied to the mechanical interface of robot's wrist axis, is restricted by allowable weight, allowable load torque and allowable moment of inertia. The direction of coordinate system used to calculate the load torque and inertia moment is the same with the direction of robot base coordinate system.


*	Step 1

    Calculate the location of the weight center from the B axis rotation center (LX, LY, LZ)(L<sub>X</sub>, L<sub>Y</sub>, L<sub>Z</sub>.)

    L<sub>x</sub>: Location of weight center in X axis

    L<sub>y</sub>: Location of weight center in Y axis

    L<sub>z</sub>: Location of weight center in Z axis



*	Step 2

    Distance calculation from the axis B and R1 to the center of gravity.

    ![](../../_assets/3.6.1_수식1.png)

    L<sub>B</sub> : Length from B axis rotation center to weight center

    L<sub>R1</sub> : Length from R1 axis rotation center to weight center



*	Step 3

    계산된 거리로부터 부하 토크를 계산

    ![](../../_assets/3.6.1_수식2.png)


*	Step 4

    Check if the load torque calculated in the step 3 is the same with or smaller than the limit value, on the basis of allowed load torque table.

 
* Note : If the load mass is similar to the mass on the torque curve below, the torque can be alternatively validated by checking if the distance calculated in the step 2 is distributed in the torque curve, instead of the step 3 and 4. If it is in the torque curve, the calculated load torque is smaller than the allowed load torque but if it is out of the torque curve, the calculated load torque is bigger than the allowed load torque.


<br></br>

![](../../_assets/작은주의표시.png) <b>Allowable load torque</b>

Table 3-2  Allowable load torque
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm" rowspan="2">Robot model</th>
    <th class="tg-yhpm" colspan="3">Allowable load torque</th>
  </tr>
  <tr>
    <th class="tg-yhpm">R2 axis rotation</th>
    <th class="tg-yhpm">B axis rotation</th>
    <th class="tg-yhpm">R1 axis rotation</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-wa1i">HH4L</td>
    <td class="tg-nrix">6 Nm (0.61kgf·m) or less</td>
    <td class="tg-nrix">6 Nm (0.61kgf·m) or less</td>
    <td class="tg-nrix">3 Nm (0.30kgf·m) or less</td>
  </tr>
  <tr>
    <td class="tg-wa1i">HH7</td>
    <td class="tg-nrix" rowspan="3">17 Nm (1.73kgf·m) or less</td>
    <td class="tg-nrix" rowspan="3">17 Nm (1.73kgf·m) or less</td>
    <td class="tg-nrix" rowspan="3">10N·m (1.02kgf·m) or less</td>
  </tr>
  <tr>
    <td class="tg-wa1i">HH7E</td>
  </tr>
  <tr>
    <td class="tg-wa1i">HH8</td>
  </tr>
</tbody>
</table>

![](../../_assets/작은주의표시.png) <b>Allowable moment of inertia</b>

Table 3-3 Allowable moment of inertia
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm" rowspan="2">Robot model</th>
    <th class="tg-yhpm" colspan="3">Allowable moment of inertia</th>
  </tr>
  <tr>
    <th class="tg-yhpm">R2 axis rotation</th>
    <th class="tg-yhpm">B axis rotation</th>
    <th class="tg-yhpm">R1 axis rotation</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-wa1i">HH4L</td>
    <td class="tg-nrix">0.12 kgm²</td>
    <td class="tg-nrix">0.12 kgm²</td>
    <td class="tg-nrix">0.03 kgm²</td>
  </tr>
  <tr>
    <td class="tg-wa1i">HH7</td>
    <td class="tg-nrix" rowspan="3">0.5 kgm²</td>
    <td class="tg-nrix" rowspan="3">0.5 kgm²</td>
    <td class="tg-nrix" rowspan="3">0.2 kgm²</td>
  </tr>
  <tr>
    <td class="tg-wa1i">HH7E</td>
  </tr>
  <tr>
    <td class="tg-wa1i">HH8</td>
  </tr>
</tbody>
</table>

Loads must be kept below maximum conditions shown in [Table 3-2] ~ [Table 3-3]

*	Step 1

    Calculate the inertia moment value of the load at each wrist axis center (J<sub>a4</sub>, J<sub>a5</sub>, J<sub>a6</sub>)

    J<sub>a4</sub> - Inertia moment from R2 axis rotation center

    J<sub>a5</sub> - Inertia moment from B axis rotation center

    J<sub>a6</sub> - Inertia moment from R1 axis rotation center

*	Step 2

    Check if the inertia moment is under the thread according to the permissible inertia moment table# 3.5.2. Example of permitted torque and inertia moment calculation (HA006B Case)

[Figure 3.7, 3.8] shows the possible range of where the material point can be located when it is considered that the load to be attached is in the material point. However, since the actual load (End Effector) does not almost always exist at the material point, evaluate the moment of inertia of each axis. For example, when considering the load to be attached as the material point,


<b>(Example) The robot type is [HA006B] and the load weight is 5.74kg</b>

<br>

![](../../_assets/그림_3.8_2차원부하모델.png)

Figure 3.8 2-D load model

<br>

M - Load weight

J<sub>xx</sub> - Inertia moment in X direction from weight center of load

J<sub>yy</sub> - Inertia moment in Y direction from weight center of load

J<sub>zz</sub> - Inertia moment in Z direction from weight center of load

J<sub>a4</sub> - Inertia moment from R2 axis rotation center

J<sub>a5</sub> - Inertia moment from B axis rotation center

J<sub>a6</sub> - Inertia moment from R1 axis rotation center


 
<br></br>
☞ Load condition: Aluminum block (Mass 5.74kg) with a width of 100mm, a length of 100mm and a thickness of 200mm



①	Permitted torque limit

B-axis center of gravity position  L<sub>X</sub> = 155mm, L<sub>Y</sub> = 0mm, L<sub>Z</sub> = -25.5mm

Apply the B and R1 axis distance limits in the torque map as shown below.	

![](../../_assets/3.6.2_수식.png)


②	Permitted inertia moment limit

Inertia moment of load from the weight J<sub>xx</sub>=0.024kgm2, J<sub>yy</sub>=0.01kgm2, J<sub>zz</sub>=0.024kgm2

![](../../_assets/3.6.2_수식2.png)


 
③	Conclusion : It is safe because the weight, torque and inertia moment all satisfy the limited condition.

<br>

*	Permissible center position from the center of R1 axis

    ①	Permissible center position when viewed from the permissible torque

    L<sub>R1</sub> ≤ (Allowable torque) / (Load weight)

    L<sub>R1</sub> = 5.9 N·m / (5.74Kg×9.8 m/s<sup>2</sup>) = 0.104 m


    ②	Permissible center position when viewed from the permissible moment of inertia

    L<sub>R1</sub> ≤ (Permitted inertia moment / Load weight)<sup>1/2</sup>

    = (0.06 kg·m2 / 5.74kg)<sup>1/2</sup> = 0.102 m

    These results is restricted by the distance allowed torque in the shaft center in R1 it is within the 0.102 m.

<br>

*	Permissible center position at the center of B axis

    (This robot is located on the same axis as the B axis, and the permissible load torque and allowable moment of inertia are the same for the B axis and R2 axis. Therefore, when the allowable condition of the B axis is satisfied, the allowable condition of the R2 axis is also satisfied..)

    ①	Permissible  center position when viewed from permissible torque

    L<sub>B</sub> ≤ (Allowable torque) / (Load weight)

    L<sub>B</sub> = 9.8 N·m / (5.74Kg×9.8 m/s<sup>2</sup>) = 0.174 m


    ②	Permissible center position when viewed from the permissible moment of inertia

    L<sub>B</sub> ≤ (Permitted inertia moment /Load weight)<sup>1/2</sup> 

    = (0.27 kg·m2 / 5.74kg)<sup>1/2</sup> = 0.217 m

    These results are regulated by the distance allowed torque on the B axis in, it will be within 0.174m.

<br>

* <b>Torque Map</b>

![](../../_assets/그림_3.9_손목축_토크_선도.png)

Figure 3.9 Wrist axis Torque lead : (HH4L)                               

![](../../_assets/그림_3.10_손목축_토크_선도.png)

Figure 3.10 Wrist axis Torque lead : (HH7)

![](../../_assets/그림_3.11_손목축_토크_선도.png)

Figure 3.11 Wrist axis Torque lead : (HH8)

![](../../_assets/그림_3.12_손목축_토크_선도.png)

Figure 3.12 Wrist axis Torque lead : (HH7E)
 
# 4. Inspection

 This chapter provides the instructions for regular inspection and overhaul necessary for the prolonged lifetime of robot performance.# 4.1. Inspection Schedule

Inspection is positively necessary to continue and maintain the high performance of robot for long-term operation.
There are daily inspection and regular inspection. [Table 4-1] shows basic periods for regular inspections, so inspectors should make an inspection according to the indicated periods.
And overhaul every 35,000 operating hours.

The inspection periods have been reviewed for SPOT Welding. In case of high precision work such as handling, it is recommended to inspect at the half intervals of that period as shown in [Table 4-1].
If you have difficulty in understanding the inspection and adjustment methods, please contact the Hyundai Robotics A/S Center (Customer Support).



<br>
Table 4-1 Inspection Schedule 
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-jafi{background-color:#f8f8be;color:#000000; font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">Daily Inspection</th>
    <th class="tg-wa1i">Daily</th>
    <th class="tg-nrix">MANIPULATOR, MOTOR, REDUCER</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-jafi" rowspan="3">Regular Inspection</td>
    <td class="tg-wa1i">3months</td>
    <td class="tg-nrix">WIRING, BOLTS, REDUCER</td>
  </tr>
   <tr>
    <td class="tg-wa1i">1 year</td>
    <td class="tg-nrix">Brake</td>
  </tr>
</tbody>
</table># 4.2. Inspection Item and Period

Table 4-2 Inspection Items and Periods

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi" rowspan="2">No</th>
    <th class="tg-jafi" colspan="3">Inspection Intervals</th>
    <th class="tg-jafi" rowspan="2">Inspection Items</th>
    <th class="tg-jafi" rowspan="2">Inspection method</th>
    <th class="tg-jafi" rowspan="2">Standards</th>
    <th class="tg-jafi" rowspan="2">Remark</th>
  </tr>
  <tr>
    <th class="tg-jafi">Daily</th>
    <th class="tg-jafi">3months</th>
    <th class="tg-jafi">1year</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-wa1i" colspan="8">Robot Manipulator and Axes common</td>
  </tr>
  <tr>
    <td class="tg-wa1i">1</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Cleaning</td>
    <td class="tg-nrix">Examine dirt and dust with naked eyes</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">2</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Inspection wiring</td>
    <td class="tg-nrix">· Examine any cable damages<br>
· Examine cable fixing bracket tightening, paint marking with naked eyes<br>
· Examine any cable cover damages with naked eyes</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">3</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Main bolts</td>
    <td class="tg-nrix">Examine paint marking with naked eyes</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
   <tr>
    <td class="tg-wa1i">4</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Motor</td>
    <td class="tg-nrix">Check the abnormal heating<br>Check the abnormal sound</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">5</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">Brake</td>
    <td class="tg-nrix">Check the ON/OFF operation of brake release switch
Note) Turn the switch off in a second because the ARM of working axis may be dropped when the brake release switch is on</td>
    <td class="tg-nrix">When the brake release switch is OFF, ARM of End Effect will not be dropped.</td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i" colspan="8">Axis S, H, V</td>
  </tr>
  <tr>
    <td class="tg-wa1i">6</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Reducer</td>
    <td class="tg-nrix">Check the abnormal sound<br>Check the shaking(vibrating)</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
<tr>
    <td class="tg-wa1i" colspan="8">Axis R2, B, R1</td>
  </tr>
  <tr>
    <td class="tg-wa1i">7</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Reducer</td>
    <td class="tg-nrix">Check the abnormal sound<br>Check the shaking(vibrating)
</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">8</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">End Effect tightening bolts</td>
    <td class="tg-nrix">Examine paint marking with naked eyes</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">9</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Diversion</td>
    <td class="tg-nrix">There is any diversion by rotating each axis to the right and reverse direction</td>
    <td class="tg-nrix">Should not feel diversion by touch</td>
    <td class="tg-nrix"></td>
  </tr>
</tbody>
</table>


<br>

*	If the robot is utilized in adverse condition(such as spot welding, grinding, etc.), perform the inspection more frequently to ensure proper reliability of the robot system
*	Inspect all visible cabling, and replace them if damaged.
*	Check the mechanical bumper devices for deformation and damage. If the bumper or Dog is bent, replace it immediately.
*	Check the tightening torque of main bolts as shown in [Figure 4.1] ~ [Figure 4.2].
*	Check the abnormal noise in an automatic or teaching mode in order to ensure the condition of power transmission (such as motor, reducer, etc).
 

 


# 4.3. Inspection of Main External Bolts

The recommended bolt torque is shown in [Figure 4.1]

Apply the appropriate torque, where required, using the torque wrench and place the paint marking where the check-up is completed.




Table 4-3 Inspection part for main bolts

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-t1e1{background-color:#ccf1bc;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-1e26{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-baqh{text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-1e26">No.</th>
    <th class="tg-1e26">Inspection parts</th>
    <th class="tg-1e26">No.</th>
    <th class="tg-1e26">Inspection parts</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-t1e1">1</td>
    <td class="tg-baqh">S axis motor assembly bolt</td>
    <td class="tg-t1e1">7</td>
    <td class="tg-baqh">END EFFECTOR assembly bolt</td>
  </tr>
  <tr>
    <td class="tg-t1e1">2</td>
    <td class="tg-baqh">V axis motor assembly bolt</td>
    <td class="tg-t1e1">8</td>
    <td class="tg-baqh">R1 axis MOTOR BASE</td>
  </tr>
  <tr>
    <td class="tg-t1e1">3</td>
    <td class="tg-baqh">R2 axis motor assembly bolt</td>
    <td class="tg-t1e1">9</td>
    <td class="tg-baqh">B axis motor assembly bolt</td>
  </tr>
    <tr>
    <td class="tg-t1e1">4</td>
    <td class="tg-baqh">R2 axis MOTOR BASE</td>
    <td class="tg-t1e1">10</td>
    <td class="tg-baqh">For 2-arm fixturing (for HH4L, HH7)</td>
  </tr>
  <tr>
    <td class="tg-t1e1">5</td>
    <td class="tg-baqh">Baxis MOTOR BASE</td>
    <td class="tg-t1e1">11</td>
    <td class="tg-baqh">V axis MOTOR BASE</td>
  </tr>
  <tr>
    <td class="tg-t1e1">6</td>
    <td class="tg-baqh">R1 axis motor assembly bolt</td>
    <td class="tg-t1e1">12</td>
    <td class="tg-baqh">H axis motor assembly bolt</td>
  </tr>
</tbody>
</table>



![](../_assets/그림_4.1_주요_볼트_점검_부위.png)

Figure 4.1 Inspection part for main bolts (HH4L/HH7/HH8)

![](../_assets/그림_4.2_주요_볼트_점검_부위.png)

Figure 4.2 Inspection part for main bolts (HH7E)
# 4.4. Checking wiring in the manipulator

Although internal wiring of robot manipulator is resistant to bending, be sure to inspect everyday, because robot movement may be problematic in the case of disconnection or short circuit caused by damaged wiring and breakage. Then, prior inspection is required when work is done in the operation scope based on the following conditions of safety inspection
# 4.4.1. Condition of safety inspection

When users do work such as teaching robot (excluding the case where driving source of industrial robot is blocked) in the operation scope of industrial robot, be sure to check the following items before work. If any abnormality is found, correct immediately and take other necessary actions.

*	Check whether outer sheath and cable is damaged or not.
*	Check whether robot manipulator works abnormally or not.
*	Check the function of emergency stop
 

# 4.4.2. Inspection part



![](../../_assets/그림_4.3_케이블_점검_부위.png)


Figure 4.3 Cable inspection part# 4.5. Checking the timing belt

HH7 has a part where the timing belt is applied to the driving part.


For the operating assembly of the timing belt, check the tension of the belt after every 1,500 hours and when there is vibration/noise on the belt. If the tension of the timing belt is not appropriate, it may have a severely negative effect on the performance of the robot.



<ol style="list-style-type:decimal" start="1">
<li>Place the robot into the basic posture by manually operating it (2 axes: 90°, other axes: 0°).<br>
- Manually operate each axis to ensure uniform timing belt tension.
     </li><br>
<li>Turn off the power.
    </li><br>
<li>Disassemble the cover of the inspection section.

![](../_assets/그림_4.4_b Axis_타이밍벨트_장력체크부위.png)

Figure 4.4 Timing Belt Inspection Location for Each Axis

</li><br>
    <li>Check the timing belt with a tension meter.  
</li><br>
    <li>Adjust the belt tension if it is not appropriate.<br> 
- Measure the tension at the belt’s central point.<p>


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-nrix">Model</th>
    <th class="tg-nrix">Classification</th>
    <th class="tg-nrix">Tension(N)</th>
    <th class="tg-nrix">Span(mm)</th>
    <th class="tg-nrix">Mass(g/m)</th>
    <th class="tg-nrix">Width(mm/R)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix" rowspan="3">HH4L/HH7/HH8/HH7E</td>
    <td class="tg-nrix">H Axis (2 Axis)</td>
    <td class="tg-nrix">55~65</td>
    <td class="tg-nrix">155</td>
    <td class="tg-nrix">4</td>
    <td class="tg-nrix">9</td>
  </tr>
  <tr>
    <td class="tg-nrix">V Axis (3 Axis)</td>
    <td class="tg-nrix">55~65</td>
    <td class="tg-nrix">195</td>
    <td class="tg-nrix">4</td>
    <td class="tg-nrix">9</td>
  </tr>
  <tr>
    <td class="tg-nrix">R2 Axis (4 Axis)</td>
    <td class="tg-nrix">29~36</td>
    <td class="tg-nrix">49</td>
    <td class="tg-nrix">2.5</td>
    <td class="tg-nrix">6</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="2">HH4L/HH7/HH8</td>
    <td class="tg-nrix">B Axis (5 Axis)</td>
    <td class="tg-nrix">29~36</td>
    <td class="tg-nrix">183</td>
    <td class="tg-nrix">2.5</td>
    <td class="tg-nrix">6</td>
  </tr>
  <tr>
    <td class="tg-nrix">R1 Axis (6 Axis)</td>
    <td class="tg-nrix">29~36</td>
    <td class="tg-nrix">117</td>
    <td class="tg-nrix">2.5</td>
    <td class="tg-nrix">6</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="2">HH7E</td>
    <td class="tg-nrix">B Axis (5 Axis)</td>
    <td class="tg-nrix">29~36</td>
    <td class="tg-nrix">184.5</td>
    <td class="tg-nrix">2.5</td>
    <td class="tg-nrix">6</td>
  </tr>
  <tr>
    <td class="tg-nrix">R1 Axis (6 Axis)</td>
    <td class="tg-nrix">29~36</td>
    <td class="tg-nrix">120</td>
    <td class="tg-nrix">2.5</td>
    <td class="tg-nrix">6</td>
  </tr>
</tbody>
</table>

![](../_assets/그림_4.5_hv축_타이밍벨트_장력체크부위.png)

Figure 4.5 H/V Axis Timing Belt Tension Checking Location

![](../_assets/그림_4.6_r2br1축_타이밍벨트_장력체크부위.png)

Figure 4.6 R2/B/R1 Axis Timing Belt Tension Checking Location
</li><br>
    <li>Referring to the tightening torques in Figures 4.1 and 4.2, fasten the motor flange with bolts to which Loctite 243 is applied.
</li><br>
    <li>Assemble the cover of the inspection section. 
</li><br>
    <li>Turn on the power. 
</li>
</ol>

# 5. Maintenance
# 5.1. Battery Replacement


The position data of each axis is preserved by the backup batteries. The batteries need to be replaced every two years. To replace batteries observe the following procedure.


<ol style="list-style-type:decimal" start="1">
    <li>
With the power of the control in on condition, press the emergency stop button.
<p>
<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">Replacing the batteries with the power supply turned off causes all current position data to be lost. Therefore, zeroing will be required again</td>
  </tr>
</thead>
</table>  
</blockquote>
    </li><br>
    <li>
Separate the cover of the battery location by each axis.
    </li><br>
    <li>
Remove the old battery.
    </li><br>
    <li>
Insert the new battery. Pay attention to the direction..
<p>

* Battery manufacturer and specifications<br>

  1)	MAXWELL : ER6C<br>
  2)	TOSHIBA  : ER6V-T1

</li><br>
<li>
Install the cover to its original location.
</li>
</ol>


![](../../_assets/그림_5.1_배터리_교환위치.png)

Figure 5.1 Battery replacement location

<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
    <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">
    -	Do not dispose the batteries. Dispose of the battery with industrial waste according to the laws and other rules in the country where the controller is installed.<p>
-	Do not recharge the batteries, otherwise batteries may result in exploding or overheating.<p>
-	Do not use any batteries other than the recommended one.<p> 
-	Change the batteries only with the specified one.<p> 
-	Do not short circuit the +/- of the battery.<p>
-	Do not expose batteries to high temperature or flame
</td>
  </tr>
</thead>
</table>  
</blockquote>
# 5.1.1. Instructions for Battery Storage

<ol style="list-style-type:decimal" start="1">
    <li>
Do not keep the batteries at a high temperature and humidity. Keep it in the well-ventilating place without dew condensation. 
</li><br>
    <li>
Keep it in a normal temperature, at relatively constant temperature (20±15℃) and at relative humidity of less than 70%. 
</li><br>
    <li> 
Check the battery storage every six months, and manage them with first-in-first-out.
</li>
</ol>
# 5.2. Internal Wiring  

Replacement cycle of internal wiring depends on follows.

-	Continuous operation
-	Operating speed
-	Atmosphere/environment


Inspect on a regular basis, every three months and check any damage on the cables or cable protect spring. If any damage, replace it. 

Replace the cable every 16,000 operating hours regardless of working condition.




<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 80 height = 80>
    </div>
    </td>
    <td colspan="4">
   -	As all the wires are flexible type, do not use any wires other than specified one.<p>
-	Wiring replacement must be done by unit.<p> 
-	Do not use any Cable, protective spring, and Hose that have external damage as they may cause future problems.<p> 
-	When purchasing robot cables, make inquiry of our service office about wiring type.<p>
-	Specify the length of wiring for connecting the robot with the controller.
</td>
  </tr>
</thead>
</table>  
</blockquote>


# 5.2.1. Connection drawing of wire extension

Refer to [Figure 5.2] for the part mark for the wiring inside the manipulator.


![](../../_assets/그림_5.2_본체내_배선기호설명.png)

Figure 5.2 Explanation of mark of wiring in the manipulator

![](../../_assets/그림_5.3_본체배선접속도.png)

Figure 5.3 Connection drawing of manipulator extension (HH4L/HH7/HH7E/HH8)# 6. Troubleshooting



# 6.1. Troubleshooting Procedure 

If a failure occurs during robot's operation, but it does not stem from the controller, it must be caused by damage on machine parts. The way to troubleshoot as quick and easy as possible should be to diagnose the problem. In addition, it is necessary to determine which parts cause the problem.

<ol style="list-style-type:decimal" start="1">
	<li>Step 1: Which axis occurs the problem?

First of all, check which axis causes the malfunction. In case that it is hard to detect the problem, check the following possible mechanical defaults,

*	Is there any parts making noise?
*	Is there any parts generating an overheating?
*	Is there any parts have a play or backlash? 
</li><br>
    <li>
Step 2: Which parts have been damaged?

If the abnormal axes are determined, investigate which parts cause trouble. There could be many causes for one phenomenon. Refer to [Table 6-1] for the cause and phenomenon of the trouble.
</li><br>
    <li>
Step 3: Dealing with malfunction parts

If the malfunction parts are confirmed, conduct relevant repair procedure based on the chapter 6.3 Diagnostics and Resolutions for Major Parts Failure. Contact our service office if you have any difficulties in dealing with problems. 
</li>
</ol> 

# 6.2. Trouble Symptoms and Possible Causes

As shown in [Table 6-1], there may be many parts as the cause of one phenomenon. 
Refer to next page to determine which part is malfunction.


<br>
Table 6-1 Trouble phenomenon and cause

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">Defect parts/<br>Trouble phenomenon</th>
    <th class="tg-jafi">Reducer</th>
    <th class="tg-jafi">Brake</th>
    <th class="tg-jafi">Motor</th>
    <th class="tg-jafi">Encoder</th>
    <th class="tg-jafi">Fulcrum bearing<br>at each point</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-wa1i">Overload [Note 1]</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>


  </tr>
  <tr>
    <td class="tg-wa1i">Displacement</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>

  </tr>
  <tr>
    <td class="tg-wa1i">Abnormal sound occurrence</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>

  </tr>
  <tr>
    <td class="tg-wa1i">Noise in operation [Note 2]</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>

  </tr>
    <tr>
    <td class="tg-wa1i">Staggering at stop [Note 3]</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>

  </tr>
    <tr>
    <td class="tg-wa1i">Irregular twitching [Note 4]</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>

  </tr>
  <tr>
    <td class="tg-wa1i">Abnormal deviation</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
 
  </tr>
  <tr>
    <td class="tg-wa1i">Free fall of an axis</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
 
  </tr>
  <tr>
    <td class="tg-wa1i">Overheating</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>

  </tr>
  <tr>
    <td class="tg-wa1i">Incorrect action and out of control movement</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>

  </tr>
</tbody>
</table>

<br>

[Note 1] Overload ----------------- Phenomenon occurring when a load exceeds the rated motor load.<br>
In specific, thermal relay of circuit protector is tripped.<br>
[Note 2] Noise in operation ----- Phenomenon which occurs vibration on operation.<br>
[Note 3] Staggering at stop ----- Phenomenon which gives oscillating motion when the robot stops<br>
[Note 4] Irregular twitching ----- Phenomenon which gives sporadic twitching when the robot is not in motion.<br>
<br>

The noise may be caused by following reasons.
1.	Operation after greasing or replacing the reducer
2.	Operation after long-term storage
3.	Operation at a low speed
4.	Operation at a low temperature


# 6.3. Diagnostics and Resolutions for Major Parts Failure # 6.3.1. Fulcrum bearing at each point

If the fulcrum bearing itself at each point is damaged, vibration, abnormal sound and overload could be caused. In addition, if the bearing fixing nuts are loosened, diversion will occur to the bearing. If diversion occurs in that way, the bearing could be damaged.



*	Diagnostics

    ①	Check if there is diversion with the bearing by applying force to the first and second arms.<br>
    (If the chain block is used, keep the postures of the first and second arms, and then check if there is diversion with the bearing while no load is applied to the reducer)

    ②	Before abnormality occurs, check if the robot contacts any peripheral device.

*	Solutions

    Replace the bearing. In this process, equipment such as a chain block is needed to hang the robot arm. Contact our service office if you have any difficulties.
 





# 6.3.2. Reducer


Vibration and abnormal sound will be occurred when a reducer is damaged. In this case, it causes overload and abnormal deviation disturbing normal operation. Sometimes overheating may result. The robot may also become completely immovable, or a position offset error may occur.


<img src="../../_assets/작은주의표시.png"> <b>[Main Axes (S, H, V)]</b>

When turning [ON][OFF] the brake release switch of axis H and axis V, be sure to take necessary precautions to prevent the ARM from dropping, and then switch the brake release [ON][OFF].

*	Diagnostics

①	Check if there is vibration and abnormal sound during operation and also whether there is abnormal heating with the reducer during operation.<br>
②	To see whether there is diversion and wear with the reducer, check if any abnormality can be felt, by holding the first arm and rotate the robot while the S axis brake release switch in [On] state.<br>
③	Check if peripheral equipment has been contacted with the robot before the abnormality<br>
(In some cases, the reducer may be damaged due to the shock from contact)

*	Resolution

Replace the reducer. A chain block is needed to lift and hang the robot ARM. Contact our service office for any difficulties



<img src="../../_assets/작은주의표시.png"> <b>[Wrist Axes (R2, B, R1)]</b>

When turning [ON][OFF] the brake release switch, be sure to take necessary precautions to prevent the ARM from dropping, and then switch the brake release [ON][OFF].

*	Diagnostics

①	Check out any vibration, abnormal sound, or overheating of the reducer when the robot is in operation.<br> 
②	Check out any play in the reducer by shaking the End Effector (such as spot gun and hand devices, etc.) back and forth.<br> 
③	Turn motor off, with the brake release switch [ON], and check that the axis can be rotated by hand. If not, the reducer is in bad condition.<br> 
④	Check if peripheral equipment has been contacted with the robot before the abnormality.<br>
(Damage may occur to the reducer due to the contacting impact)

*	Resolution

①	Replace the reducer.<br>
②	Replace the entire wrist section.<br>
(The replacement of entire wrist should be a quick and reliable resolution as it takes time and necessary equipment for reducer replacement)




# 6.3.3. Brake

In case of brakes failure, each axis possibly drops with the motors [OFF]. Or, in reverse, brakes possibly operate even with the motors [ON]. The latter causes overload and noise.

When intending to operate the entire robot without the motors [ON], operate it with the brake release switch [ON]. Before turning the switch [ON], take necessary precautions to prevent the ARM from dropping as the robot ARM will drop by gravity.




*	Diagnostics

    Check if the brake can be heard in operation, by turning the brake release switch [ON] [OFF] alternately with the motors [OFF]. If not heard, the brake cable may be broken. (When operating the brake release switch [ON] [OFF], be careful of ARM dropping. The brake release switch is located on the panel in the controller cabinet door.)

*	Resolution
    If cables turn out to be good condition, replace the motor.





# 6.3.4. Motor

Motor failure causes abnormal operation of robot such as staggering at stop, irregular twitching and noise in operation. Besides, It may cause overheating and abnormal sound. 

Check the reducer and fulcrum bearing as well in order to determine which part causes the abnormality. It is because that similar phenomenon is observed when the reducer is damaged.

*	Diagnostics

    Check for overheating and abnormal sound.

*	Resolution
    Replace the motor.

# 6.3.5. Encoder

Position offset, malfunction, and out of control movement as well as staggering at stop, irregular twitching may occur when the Encoder is in bad condition. This case has nothing to do with such phenomena as mechanical abnormal sound, overheating, and vibration.

*	Diagnostics

    ①	Check for any encoder data failure.<br>
    ②	Use reference pins and blocks to check the positional data is correct at pin position.<br> 
    ③	Check for any irregular variations in the encoder data when moving each robot axis.v 
    ④	Replace the servo amp board(BD542) to check errors. 
 
*	Resolution

    ①	If cabling turns out to be in good condition without any damage, replace the encoder.<br>
    ②	If there is no error after replacing the servo amp board(BD542), replace the servo amp board.



# 6.4. Encoder Zero Setting

It is necessary to reset the origin when encoder data has been corrupted due to some problems and when the motor is replaced.

Scale is used to determine the standard posture and position of each axis of the robot. Considering that there must be structural interference with the wrist axis, the zero must be set in the order of Axis 4, Axis 5 and Axis 6.





![](../../_assets/작은주의표시.png) <b>Warning</b>

In this work, there is a part performing in the state of motor [ON]. Therefore, this work must be performed in pairs. One must always be ready to activate an emergency stop. The other must perform the work quickly but carefully.

An escape route should be determined before starting work.
# 6.4.1. Zero Setting

(1)	Set the controller to teaching mode and set the robot to standby [ON] condition.
If the robot cannot be set to standby [ON] condition due to issues, use the brake cancel switch to set the reference location of the robot.

(2)	Move respective axes to the basic posture, then set them by the scale mark.

(3)	Reset the Encoder. Refer to 『6.4.2 Encoder Reset』for the method of encoder reset.

(4)	Correct the encoder. Refer to 『Controller Operation Manual』.

(5)	Confirm that there is no problem in robot motion.
# 6.4.2. Encoder Reset

(1)	Turn off the motor.

(2)	Open the serial encoder reset window. (『[F2]: System』 → 『5: Initialize』 → 『4: Serial encoder reset』)


![](../../_assets/그림_6.4_시리얼_엔코더_리셋.png)
 

(3)	Use keys like [↓], [↑], [SHIFT]+[←][→] to move to a desirable axis, then press the [Execute] key.

(4)	After the encoder is reset, please make sure the controller power is turned on.
 

# 6.4.3. Encoder offset and Selection


*	It is necessary to compensate encoder data for the basic position of each axis.
*	Refer to 『Encoder offset』in the Controller Manual for details.



<b>[Encoder offset Screen]</b>

![](../../_assets/그림_6.5_엔코더_보정.png)



(1)	Select the axis, move the axis to a standard position using the [Axis operation] key, and press the 『[F1]: Apply』key. 

(2)	Place the robot’s entire axis as the standard position using the [Axis operation] key and press the 『[F2]: Apply all』 key to carry out encoder offset correction for the entire axis.

(3)	To save the set data, press the 『[F7]: Complete』 key. The [ESC] key will prevent the changes being saved.


<table>
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4"><b>Warning</b><br>
    In case of encoder DATA compensation after replacing motor, check if the motor power is on with the power 『ON』.</td>
  </tr>
</thead>
</table>  


# 7. Recommended Spare Parts

The recommended spare parts for robot are as follows. Please check robot serial number and manufacturing date when purchasing, and contact our service office.

<b>[Category]</b>

A : Regular maintenance parts(what is replaced regularly)

B : Essential spare parts (what is of high frequency)

C : Essential component parts

D : Machine parts


<br></br>
Table 7-1 Spare Parts List I (HH7/HH4L/HH7E/HH8)
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">Category</th>
    <th class="tg-jafi">Robot Applied</th>
    <th class="tg-jafi">PLATE No.</th>
    <th class="tg-jafi">Part Name</th>
    <th class="tg-jafi">Quantity</th>
    <th class="tg-jafi">Application</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">A</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R7900015261</td>
    <td class="tg-nrix">SK-1A</td>
    <td class="tg-nrix">2.5kg/CAN</td>
    <td class="tg-nrix">Common</td>
  </tr>
  <tr>
    <td class="tg-nrix">A</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R1001-6202-P2</td>
    <td class="tg-nrix">ECODER BATTERY</td>
    <td class="tg-nrix">6EA</td>
    <td class="tg-nrix">Common</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7111-P02</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">S-axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P03</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">H-axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P04</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">V-axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P02</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R2-axis</td>
  </tr>
   <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P03</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">B, R1-axis Common</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7111-P01</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">S-axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P01</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">H-axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P02</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">V-axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P01</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R2-axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P01</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">B-axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P02</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R1-axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P01</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">B-axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P02</td>
    <td class="tg-nrix">REDUCER</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R1-axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7511-001</td>
    <td class="tg-nrix">S-axis Wiring ASS'Y</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">CABLE ASSY</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7111-P03</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">S-axis GEAR(2ND)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7111-P04</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">S-axis REDUCER</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7111-P05</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">S AXIS SHAFT</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7111-P06</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">S AXIS MOTOR</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P05</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">H-axis REDUCER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P06</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">V-axis REDUCER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P07</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">UPPER FRAME</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P08</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">H-axis REDUCER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P09</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">V-axis REDUCER</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P10</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">UPPER FRAME</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P11</td>
    <td class="tg-nrix">TIMING BELT</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">H-axis motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P12</td>
    <td class="tg-nrix">TIMING BELT</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">V-axis motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P03</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">ARM FRAME (V-axis)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P04</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">ARM FRAME (R2 -axis)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P05</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">ARM PIPE</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P06</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">ARM FRAME (V-axis)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P07</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">ARM FRAME (R2 -axis)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P08</td>
    <td class="tg-nrix">TIMING BELT</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R2-axis motor</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P04</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">B-axis REDUCER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P05</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">B-axis REDUCER</td>
  </tr>
      <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P06</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">GEAR(R1 1st)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P07</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">WRIST HOLDER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P08</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">GEAR(R1 2nd)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P09</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">R1-axis REDUCER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P10</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">GEAR(R1 1st)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P11</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R1 REDUCER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P12</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">WRIST HOLDER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P13</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">HOLDER(R1 AXIS)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P14</td>
    <td class="tg-nrix">TIMING BELT B</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">B-axis motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P15</td>
    <td class="tg-nrix">TIMING BELT R1</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R1-axis motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P05</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">B-axis REDUCER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P06</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">B-axis REDUCER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P07</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">GEAR(R1 1st)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P08</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">GEAR(R1 1st)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P09</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">WRIST HOLDER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P10</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">WRIST HOLDER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P11</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">GEAR(R1 2nd)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P12</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">MECHANICAL INTERFACE</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P13</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">WRIST HOLDER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P14</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">WRIST HOLDER</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P15</td>
    <td class="tg-nrix">TIMING BELT B</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">B-axis motor</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P16</td>
    <td class="tg-nrix">TIMING BELT R1</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R1-axis motor</td>
  </tr>
</tbody>
</table># 8. Internal Wiring Diagram






