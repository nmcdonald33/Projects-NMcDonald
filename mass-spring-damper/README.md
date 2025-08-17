PID Controller for a Mass Spring Damper System<br>


**Objectives:**
   1) model a mass spring damper system and derive its transfer function and state space form
   2) Simulate free and forced repsonses in Simulink using open and closed systems
   3) analyze key metices: natural response frequency, damping ratio, overshoot repsonse, etc.
   4) control position by implementing a PID controller<br>
	 
<br>
<br>
<br>

**System Model**<br>
<br>
Governing equation

<img width="250" height="126" alt="image" src="https://github.com/user-attachments/assets/61aa27fc-1c5c-4792-9c02-8f281fe84646" />
<br>
<br>

Taking Laplace Transfrom creates

<img width="315" height="124" alt="image" src="https://github.com/user-attachments/assets/4a9a7c15-cf5e-45d7-b744-a78ae518fa1e" />
<br>
<br>

 Simplifying, 
 
<img width="200" height="100" alt="image" src="https://github.com/user-attachments/assets/37e7d7f9-b1f1-48fd-b643-ef1771d63a67" />

where G is the transfer function of the system
<br>
<br>
<br>

**Initial Parameters:**<br>
m = 5kg<br>
k = 200 N/m<br>
c = 4 N*s/m<br>




