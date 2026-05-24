# 8.-Design-and-Simulation-of-Three-phase-full-wave-rectifier.
## AIM
To design, simulate and analyse a Three phase full wave rectifier controlled by thyristors using MATLAB Simulink.
## APPARATUS REQUIRED
•	MATLAB
## PROCEDURE
1.	Open MATLAB and click on the icon for SIMULINK as shown below
 <img width="522" height="376" alt="image" src="https://github.com/user-attachments/assets/ba3bbd3b-0d46-4156-a381-9ccd885a3365" />

Another way is to open is through START icon of MATLAB Start ⇒ Simulink ⇒ Library  browser. 

2.	Click on NEW MODEL or go to FILE ⇒ NEW ⇒ MODEL and a new blank model is created as shown below
 <img width="572" height="382" alt="image" src="https://github.com/user-attachments/assets/25522ebb-6b03-4922-994a-4f023304a07b" />

3.	After creating a blank model you need to open the SIMULINK component storeroom/library by going to View ⇒ Library Browser. Select SIMPOWER SYSTEMS then select Power Electronics library and by right clicking on Thyristor and click on add to the model will add the Thyristor in the blank model. Alternatively you can drag the component directly in the model page as shown below
 <img width="940" height="361" alt="image" src="https://github.com/user-attachments/assets/69984a9c-e017-44db-a207-e6ee9859c502" />

4.	Similarly go to ELECTRICAL SOURCES ⇒ AC Voltage Source and add it to the model. Select Elements and select “SERIES RLC BRANCH” and add it to the model. Simulink do not perform simulation unless and until a measurement block is present in a system. Since we need to measure the input and output voltages and the load current. To add them select Measurement in SIMPOWER SYSTEMS and then add current measurement and voltage measurement blocks to the model. Oscilloscope is not included in SIMPOWER SYSTEMS and is present in the top most block of the left column that is SIMULINK ⇒ Sinks ⇒ Scope. Also add PWM generator from sourced. We can join various blocks by clicking
on their edges and then drag the wire till the other connection terminal.
5.	Construct the circuit by joining them together in the form as given below
 <img width="940" height="379" alt="image" src="https://github.com/user-attachments/assets/dd36355d-efa2-4473-adc5-75c05c499b8a" />

6.	Now double click the three phase source to set the values of voltage and frequency.
 <img width="328" height="403" alt="image" src="https://github.com/user-attachments/assets/87fc101f-6dc4-4318-95e5-0da0bde5d3cd" />

7.	Double click on series RLC branch, Select the Branch type as R and set the values for R.
8.	Double click on PWM generator(T1 to T6), set the parameter as per the requirement.
 <img width="466" height="677" alt="image" src="https://github.com/user-attachments/assets/425ee8f3-81a8-4595-81de-8b932e4279e9" />

9.	Before running the simulation, we have to configure the parameters. Go to Simulation ⇒ Configuration parameters as shown
 <img width="542" height="399" alt="image" src="https://github.com/user-attachments/assets/148fcc71-082a-47a2-bedf-11ad70e1a8c3" />

10.	Select the ode23tb (Stiff/TR-BDF2) or ode15s (Stiff/NDS) or any suitable solver as
shown below 
 <img width="566" height="401" alt="image" src="https://github.com/user-attachments/assets/05f4906d-b45c-4d81-8dbc-1639157485c1" />

11.	Start the simulation by either clicking on Start Simulation icon as shown in below or
by going to Simulation ⇒ Start
 <img width="770" height="308" alt="image" src="https://github.com/user-attachments/assets/256b513a-0ff8-479b-96e9-9a050455ad48" />

12.	Double click on scope and observe the graphs.
13.	Save the file. ( It should be noted that Simulink do not allow to save files with spaces therefore usually is included in between two words.)
14.	Analyze and record your inference.

## Simulation
<img width="1795" height="814" alt="image" src="https://github.com/user-attachments/assets/1df9aed0-9432-46ed-926f-2f10880d86d5" />


## Output
<img width="1908" height="1026" alt="image" src="https://github.com/user-attachments/assets/f15223eb-6a80-4458-8048-a074f0b7ef99" />
<img width="1917" height="1049" alt="image" src="https://github.com/user-attachments/assets/4221b4fc-0104-4c27-958a-5904cc0e3ee3" />
<img width="1913" height="1047" alt="image" src="https://github.com/user-attachments/assets/92989767-d1ae-4ff2-83b1-d609ec450774" />




## Result
Thus the Design-and-Simulation-of-Three-phase-full-wave-rectifier is verified using MATLAB
