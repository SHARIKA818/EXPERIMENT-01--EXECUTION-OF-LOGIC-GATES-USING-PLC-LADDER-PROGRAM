# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM

 ### NAME : SHARIKA R
 ### REGISTER NUMBER : 212223230204
 ### DEPARTMENT : B.TECH(AI&DS)
 ### YEAR : IV
 ### DATE : 24.07.2026

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH. Ladder Logic: Represented by two or more normally open contacts in series. OR Gate:

Function: Outputs HIGH when at least one input is HIGH. Ladder Logic: Represented by two or more normally open contacts in parallel. NOT Gate:

Function: Outputs the inverse of the input signal. Ladder Logic: Represented by a normally closed contact. NAND Gate:

Function: Outputs LOW only when all inputs are HIGH. Ladder Logic: An AND gate followed by a NOT gate. NOR Gate:

Function: Outputs LOW when at least one input is HIGH. Ladder Logic: An OR gate followed by a NOT gate. XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH. Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:

AND Gate:

<img width="327" height="250" alt="image" src="https://github.com/user-attachments/assets/a14c1e93-0361-4da8-829f-426fa29d459d" />

OR Gate:

<img width="324" height="254" alt="image" src="https://github.com/user-attachments/assets/ab21345a-e879-4bee-a70a-e24d5708c697" />

NOT Gate:

<img width="214" height="159" alt="image" src="https://github.com/user-attachments/assets/38e962b3-3b38-4372-8e5b-129b7ee460ff" />

NAND Gate:


<img width="333" height="250" alt="image" src="https://github.com/user-attachments/assets/ed63c7e3-e134-4f73-901a-913277d13bc7" />


NOR Gate:



<img width="330" height="249" alt="image" src="https://github.com/user-attachments/assets/dbdcfa87-c9af-4a6d-b6ff-5e5e6afcd7c0" />


XOR Gate:



<img width="326" height="248" alt="image" src="https://github.com/user-attachments/assets/4fb511df-cd55-4c50-aa20-c5c1f7fe603c" />


 
# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 
### AND GATE:



<img width="560" height="116" alt="Screenshot 2026-01-30 181631" src="https://github.com/user-attachments/assets/6fff56ad-e505-4667-bbe6-c190625d96c9" />

### OR GATE:




<img width="544" height="164" alt="Screenshot 2026-01-30 181638" src="https://github.com/user-attachments/assets/93adedf3-3f02-4d4e-911a-8b7ab0ec93a0" />

### NOT GATE:





<img width="516" height="117" alt="Screenshot 2026-01-30 181645" src="https://github.com/user-attachments/assets/cd08d546-145c-4546-b9e2-f6f9c669f8a6" />

### NAND GATE:





<img width="549" height="127" alt="Screenshot 2026-01-30 181653" src="https://github.com/user-attachments/assets/193d7c67-c4f1-4994-ae98-947c16af653c" />
<img width="551" height="117" alt="Screenshot 2026-01-30 181659" src="https://github.com/user-attachments/assets/8c39baab-7298-4599-a642-16f45b8bf153" />

### NOR GATE:




<img width="536" height="115" alt="Screenshot 2026-01-30 181704" src="https://github.com/user-attachments/assets/a0ec5a03-826a-4979-919f-ce248aa63121" />
<img width="514" height="106" alt="Screenshot 2026-01-30 181711" src="https://github.com/user-attachments/assets/512f99cb-ec2e-4275-ab5f-803854f39bec" />

### XOR GATE:




<img width="566" height="179" alt="Screenshot 2026-01-30 181722" src="https://github.com/user-attachments/assets/f80c1124-f33d-45f6-ae9f-5c6065cec19b" />


### DEVICE MONITOR TABLE:

<img width="1919" height="1028" alt="Screenshot 2026-01-30 183001" src="https://github.com/user-attachments/assets/4ac41dfa-7c5e-4104-88f7-90ee510d01b4" />
<img width="1916" height="1034" alt="Screenshot 2026-01-30 183023" src="https://github.com/user-attachments/assets/4d9db4d4-5ff4-45de-9a35-e8403e367c03" />
<img width="1884" height="1034" alt="Screenshot 2026-01-30 183048" src="https://github.com/user-attachments/assets/3bdb550a-0c28-4672-9006-9cb8557fbab9" />
<img width="1910" height="1034" alt="Screenshot 2026-01-30 183101" src="https://github.com/user-attachments/assets/e516d8a5-008b-4aeb-8706-23ade2bf3e60" />






# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
