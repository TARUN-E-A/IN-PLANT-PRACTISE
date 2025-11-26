# IN-PLANT-PRACTICE
**SCHEMATIC ENTRY AND SIMULATION OF CMOS INVERTER, CMOS NAND and CMOS NOR USING CADENCE TOOL**
## IN-PLANT PRACTISE
**AIM:**

To design and simulate the CMOS inverter and observe the DC and transient responses using cadence tool.

**APPARATUS REQUIRED:**
 
1.	Laptop with MobaXterm

2.	Cadence tool
	

**ANALOG SIMULATION WITH SPECTRA:**

**Starting the simulation environment:**

1.	In the Inverter-test schematic window execute launch – ADEL. The variable virtuoso analog design environment (ADE) simulation window appears.

**Choosing a simulator:**

1.	In the simulation window (ADE) execute setup – simulator / directory / host.
2.	In the choosing simulator form, set the simulator field to specra and click ok.
3.	In the simulation window (ADE) execute the setup model libraries.

To complete, move the cursor and click ok.

**Choosing Analysis:**

1.	Click the choose- Analysis icon in the simulation window (ADE).
2.	The choosing analysis form appears.
3.	To Setup the transient analysis.
a.	In the analysis section select tron.
b.	Set the stop time as 100ns
c.	Click at the moderate or enabled button and the bottom and then click apply.
4.	To set for DC analysis
a.	In the analysis section select DC.
b.	Turn on save DC operating point.
c.	Turn on the component parameters.
d.	Double click the select Vpulse source or Type V0 (capital V zero).
e.	Select the DC voltage in the select window parameter and click in the form start and stop voltages are 0 to 1.8.
f.	Select the enable button and click apply and then click ok.

**SELECTING OUTPUT FOR PLOTTING:**

1.	Execute the o/p’s to be plotted  -select on sschematic in the simulation window.
2.	Follow the prompt at the bottom. Click on the o/p net vout input vin of the inverter. Press esc with the cursor after selecting.

**RUNNING THE SIMULATION:**

1.	Execute the simulation Netlist and run in the simulation window to start the simulation on the icon. This will create the netlist as well as run the simulation.
2.	When the simulation finishes the transient and DC plots automatically will be popped up along with netlist.
 
**CMOS INVERTER:**

**CMOS INVERTER SCHEMATIC:**

![image](https://github.com/TARUN-E-A/VLSI-LAB-EXP-6/assets/163630871/d08dd1a1-5ccc-43d8-af1f-1c8abdbcf000)

**SPECIFICATIONS:**

Vpulse 	V1 = 0	Vdc	= 1
V2 = 1
td = 0,tr=tf=1 n, ton= 100n ,T=200n

**SIMULATION SETTINGS:**

Setup for transient analysis:

1.	Stop time =400n

Setup for D.C analysis:

1.	Component to be selected in schematic is	for d.c analysis
2.	Start = -1 Stop = 1 resp.


**CMOS INVERTER TEST CELL VIEW:**

![image](https://github.com/TARUN-E-A/VLSI-LAB-EXP-6/assets/163630871/5e003dbc-7db4-47dc-8256-6f43d40cdc16)

**CMOS INVERTER SIMULATION WITH SPECTRA:**

**TRANSIENT RESPONSE:**

![image](https://github.com/TARUN-E-A/VLSI-LAB-EXP-6/assets/163630871/5740a826-69ad-47ff-a40e-01cb34546e1d)

**DC RESPONSE:**

![image](https://github.com/TARUN-E-A/VLSI-LAB-EXP-6/assets/163630871/50bc1d84-49bc-486a-a5e0-2331db6f2892)

**CMOS NAND GATE:**

**NAND SCHEMATIC:**

![image](https://github.com/TARUN-E-A/VLSI-LAB-EXP-6/assets/163630871/ce04e997-3f5c-4217-9a21-da54d59ce0ae)

**NAND TEST CELL VIEW:**

![image](https://github.com/TARUN-E-A/VLSI-LAB-EXP-6/assets/163630871/89b1200e-478a-4019-827d-7e12f3f4ba88)

**NAND SIMULATION WITH SPECTRA:**

![image](https://github.com/TARUN-E-A/VLSI-LAB-EXP-6/assets/163630871/148f6919-9f9b-43f3-9e79-3a3d1f5ee01f)

**CMOS NOR GATE:**

**NOR SCHEMATIC:**

![image](https://github.com/TARUN-E-A/VLSI-LAB-EXP-6/assets/163630871/973a590b-e2cd-41ff-a079-b57e740f06c5)

**NOR TEST CELL VIEW:**

![image](https://github.com/TARUN-E-A/VLSI-LAB-EXP-6/assets/163630871/dff58105-f4a8-4054-bed1-3ad86283d586)

**NOR SIMULATION WITH SPECTRA:**

![image](https://github.com/TARUN-E-A/VLSI-LAB-EXP-6/assets/163630871/f199bab2-b56e-4057-98de-8d32c517bd1b)

**RESULT:**

The Implementation of CMOS inverter, CMOS NAND and CMOS NOR gate waveforms are verified.
