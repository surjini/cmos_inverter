# cmos_inverter
## REG NUM :25013883
## NAME :V.Sakthi Narayanan
## EXPERIMENT 2.a Design CMOS inverter and transient and OP analysis

## Aim: To Design CMOS inverter and transient and OP analysis.

## Tools Used: 
Virtuoso Schematic Editor is used for the design and analysis.

## Theory:
CMOS inverter consists of a p-channel MOSFET(PMOS)and an n-channel MOSFET(NMOS)connectedinseriesbetweenthepowersupply(V_DD)andground.Whentheinputvoltage is low, the PMOS transistor turns ON, pulling the output to high (V_DD),while the NMOS is OFF. When the input is high, the NMOS turns ON, pulling the output to low (ground), and the PMOS turns OFF. This complementary action produces an output that is the logicalInversion  of the input. CMOS inverter shave low static power consumption and high noise margins, making them ideal for digital logic circuits.

## Procedure:
•	Click new->libraryattachtoanexistingtechnologylibrarygpdk045(in technology file)
•	New cell view(name of the layout)

## For schematic:
A.TRANSISTOR DIAGRAM 

<img width="183" height="159" alt="cmos INVERTER DIAG" src="https://github.com/user-attachments/assets/39d612ee-9e60-4251-988b-636cd430038d" />

Fig: CMOS inverter Transistor Schematic

B.IN CADENECE

•	Pick the components NMOS, PMOS, ground, VDD and voltage source.
•	Connect the wire as per the schematic diagram.

<img width="907" height="381" alt="image" src="https://github.com/user-attachments/assets/7b163321-1720-4eac-8bb2-3b5ded9e7834" />

Fig: CMOS inverter Schematic

## FOR SYMBOL :
<img width="952" height="483" alt="image" src="https://github.com/user-attachments/assets/689685b4-2cff-4c49-a079-8d2dc444d2c0" />

Fig: CMOS inverter symbol

## Transient Analysis and OP:
a)	In the Analysis section, select transient.
b)	In the stop time type 600n and click OK.
c)	In the transient Analysis section, turn on Save transient Operating Point.
d)	Check the enable button and then click Apply. Click OK in the Choosing Analyses Form.
Click OK in the Choosing Analyses Form.

## Execute Outputs:
To be plotted– Select on Schematic in the simulation window.
Follow the prompt at the bottom of the schematic window, Click on out put net Vout, input net Vin of the Inverter.
## Execute Simulation:
Netlist and Run in the simulation window to start the Simulation.
When simulation finishes, the transient automatically will be popped up along file.
 
## Waveforms:
<img width="975" height="609" alt="image" src="https://github.com/user-attachments/assets/ea203447-c528-4ed5-8efe-3b97efac5f38" />



## RESULTS:
Design of CMOS inverter and transient performed and output waveforms are obtained.
 


