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
</ol>