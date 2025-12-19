# NAND
## REG NUM :25014334
## STUDENT NAME :SANTHIYA B
## EXPERIMENT 1 a - DESIGN AND VERIFY THE NAND GATE USING TRANSIENT AND OP ANALYSIS 

## Aim:
To design CMOS NAND gate and perform Transient and Operating Point (OP) analysis.
## Tools Used: 
Virtuoso Schematic Editor is used for the design and analysis. — gpdk045 Technology Library.
## Theory: 
A 2-input CMOS NAND gate is realized using two PMOS transistors in parallel and two NMOS transistors in series.
	When both inputs (A and B) are high, both NMOS conduct, and output goes LOW (0). 
	If either input is low, at least one PMOS conducts, pulling the output HIGH (1).
Thus, output Y=(A⋅B) ‾.
This gate offers low static power consumption and high noise margins like other CMOS logic.

## Procedure:
	Create a new library attached to gpdk045.
	Create a new cell view (e.g., CMOS_NAND).
Place components:
	2 × PMOS transistors (parallel connection)
	2 × NMOS transistors (series connection)
	Input voltage sources (VinA, VinB)
	Ground and VDD (1.8 V typical)
	Connect circuit as per schematic diagram.
Output is taken from the node between PMOS/NMOS network.
## For schematic:
A.TRANSISTOR DIAGRAM 

<img width="329" height="424" alt="image" src="https://github.com/user-attachments/assets/91ffe106-2b5b-4678-b857-084d6bdee339" />

FIG- NAND TRANSISTOR DIAGRAM 

B.IN CADENCE 

<img width="968" height="567" alt="image" src="https://github.com/user-attachments/assets/b9d0ab9e-7482-4269-bc68-56bb5d1f2c59" />

FIG- NAND CIRCUIT DIAGRAM 

Pick the components NMOS, PMOS, ground, VDD and voltage source. 
	Connect the wire as per the schematic diagram. 
  
C.FOR SYMBOL 

<img width="978" height="559" alt="image" src="https://github.com/user-attachments/assets/58d29c09-73c0-4e50-85c4-bd04edc5ea0e" />

FIG - ANND SYMBOL DIAGRAM

D.SIMUKATION DIAGRAM 

<img width="979" height="540" alt="image" src="https://github.com/user-attachments/assets/d09ae8b6-09de-4dd7-a0d3-4dbf3c03f441" />

FIG - NAND SYMBOL DIAGRAM 

## Transient Analysis and OP: 
a)	In the Analysis section, select transient. 
b)	In the stop time type 600n and click OK. 
c)	In the transient Analysis section, turn on Save transient Operating Point.  
d)	Check the enable button and then click Apply. 
                Click OK in the Choosing Analyses Form. 
                Click OK in the Choosing Analyses Form. 
## Execute Outputs: 
To be plotted – Select on Schematic in the simulation window.  
Follow the prompt at the bottom of the schematic window, Click on output net Vout, input net Vin of the Inverter.  
Execute Simulation: 
Net list and Run in the simulation window to start the Simulation.  
When simulation finishes, the transient automatically will be popped up along file. 

## WAVEFORM:
<img width="1128" height="660" alt="image" src="https://github.com/user-attachments/assets/676b219f-ce57-4f3f-823e-7e4c1df4d8ed" />

## RESULT :
CMOS NAND gate designed and verified using transient and OP analysis.



