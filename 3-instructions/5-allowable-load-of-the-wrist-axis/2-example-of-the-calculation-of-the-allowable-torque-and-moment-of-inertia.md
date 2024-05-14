# 3.5.2. Example of permitted torque and inertia moment calculation (HA006B Case)

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
 
