# Lab 2 - Basic Circuits

# By: Noah Lane & Lily Schlaug
# Summary
Lab goal; summary of work performed; summary of outcome
Lab 2's focus is to develop a better understanding of the three major laws of basic circuit analysis: Kirchhoff's voltage Law, Kirchhoff's current law and Thevenin's theorem. Lab 2 began with an introduction to proper soldering and circuit building techniques by making and soldering a series circuit onto a solder breadboard and then measuring the voltage drop across each of the components in the circuit. After summing the voltage drops across the resistors the value was equivalent to that of the voltage supplied by the DC power supply. For the second part of the lab, two circuits were constructed on a solderless breadboard that consisted of five resistors with three in series and two in parallel for Part 2.1 and four resistors, three in series and one in parallel, for Part 2.2 and 2.3. **Outcome of measured vs calculated data for 2.1,2.2,2.3.**

# Materials

DigiKey SolderFul BreadBoard

Solderless breadboard

Solder

Wires

1kΩ, 2x 2.2 kΩ, 4.7 kΩ, 5.1 kΩ, 6.8 kΩ, 15 kΩ, 220 kΩ Resistors

# Assembly Procedures
Provide basic summary of steps performed in lab (Do not copy and paste from lab assignment.) The important part here is to provide detail that you had to develop in the lab which will be more important in later labs.
You must include Schematics, Engineering Drawings, and Programming if appropriate in this section.

**Part 1-Series circuit**
1. Place the 1kΩ, 2.2 kΩ and 5.1 kΩ in series on the solder breadboard
2. Solder the resistors into place on the back of the solder breadboard
3. Clip exposed excess leads from the back of the solder breadboard

**Schematic of part 1**
**Image of Part 1 circuit:**

![IMG_8359](https://github.com/npla225/BAE305-SP24-Lab2/assets/156371043/12556cc0-ec97-4a10-a547-0fbee14bf457)


**Part 2.1-Parallel circuit**
1. Using the 2.2 kΩ, 4.7 kΩ, 6.8 kΩ, 15 kΩ, and 220 kΩ resistors construct the parallel circuit with the 4.7 kΩ, 6.8 kΩ, and 15 kΩ resistors in series and the 2.2 kΩ and 220 kΩ resistors in parallel 
2. Place the power wire in the same row as the 4.7 kΩ resistor and the ground wire in the same row as the 
3. For step 5, remove the 5.5 kΩ resistor

**Schematic of part 2.1**
**Image of Part 2.1 circuit:**
![IMG_8362](https://github.com/npla225/BAE305-SP24-Lab2/assets/156371043/79a6401b-f1c9-4485-b8b5-b999d448749f)

**Part 2.2 and 2.3-Parallel circuit**
1. Use the same circuit from Part 2.1 - step 5
**Schematic of part 2.2 and 2.3**
**Image of Part 2.2 circuit:**
![IMG_8360](https://github.com/npla225/BAE305-SP24-Lab2/assets/156371043/b5765ccc-0f97-47e6-afd2-e8aace88f390)


# Test Equipment

Digital Multimeter

Global Specialties 100W Triple Output Switching DC Power Supply

# Test Procedures
How did you test the system to get your results
**Part 1-Series Circuit**
**1. voltage in parallel**

**Part 2.1-KCL**
**1. Current in series with resistor**

**Part 2.2-KVL**
**1. voltage in parallel**

**Part 2.3-Thevenin**
**1. equivant resistor/voltage**

# Test Results

**Add descriptions**

Below is the table of labeled resistor values compared to the measured resistor value that was taken at the time of the lab. 

**Part 1 - Series Circuit**
| Labeled resistor value(kΩ) | Measured resistor value(kΩ) |
| ---------------------------| ----------------------------|
| R1(1)  | 0.981  |
| R2(2.2)  | 2.169  |
| R3(5.1)  | 5.013 |
|Sum|8.18|

Below is the measured voltage drop across each of the resistors. 

| Resistor   | Voltage Drop (V) |
| -----------| -----------------|
| R1| 1.203  |
| R2  | 2.66  |
| R3  | 6.142 |
|Sum|10.005|

**Part 2.1**

Below is the verification that the DCPS provided the same measured voltage as it displayed.  

| Displayed Power (V) | Measured Power (V) |
| --------------------| -------------------|
|12|12|

Below is the measured resistor value that was taken of each resistor at the time of building the circuit. 

| Labeled resistor value(kΩ) | Measured resistor value(kΩ) |
| ---------------------------| ----------------------------|
| R1(4.7)  | 4.6  |
| R2(6.8)  | 6.79  |
| R3(15)  | 14.74 |
| R4(220)  | 219.3  |
| R5(2.2)  | 2.188  |

Below is the voltage drop across Rl/R5 and the current through Rl/R5. 

| Resistor | Voltage drop (V) | Current(mA) |
| ---------| ----------------|---------|
|R5|3.57|1.66|

Below is a comparison of the measured current and calculated current after removing R5 from the circuit. 

| Current   | Measured Current (mA)| Calculated Currents (mA)|
| ----------| ---------------------|-------------------------|
| I1(R1)| 0.51  | 2.5 |
| I2(R2)  | 0.46  | 0.23 |
| I3(R4)  | 0.06 | 2.27 |

**Part 2.2**

Below is the measured magnitude and calculated values of voltage drop across resistors R1, R2, R3, & R4. At this point, R5 is still removed from the circuit. 

| Voltage | Measured Magnitude (V) | Calculated Voltage (V)|
| --------| -----------------------|-----------------------|
| V1| 2.286  | 2.4 |
| V2  | 3.064  | 3.13|
| V3  | 6.65 | 0.9 |
|V4,V5|9.72||

**Part 2.3**

| Thevenin Component   | Calculated |
| ---------------------| -----------|
| Vth| 1.203  |
| Rth  | 2.66  |
| I n | 6.142 |
|Vl|10.005|
|Il||

# Conclusion 
**Add conclusion**
# Discussion
Did you make any design decisions that had an impact on the results? How did they impact the results? What do the results mean?
Discussion Question 1: How much power does each resistor dissipate? Each branch? Total power? Is the power in equal to the power out? 
**ans**
Discussion Question 2: Does ITH = IL? 
**ans**
