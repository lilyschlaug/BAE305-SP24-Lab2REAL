# Lab 2 - Basic Circuits

# By: Noah Lane & Lily Schlaug
# Summary

Lab 2's focus is to develop a better understanding of the three major laws of basic circuit analysis: Kirchhoff's voltage Law, Kirchhoff's current law and Thevenin's theorem. Lab 2 began with an introduction to proper soldering and circuit building techniques by making and soldering a series circuit onto a solder breadboard and then measuring the voltage drop across each of the components in the circuit. After summing the voltage drops across the resistors the value was equivalent to that of the voltage supplied by the DC power supply. For the second part of the lab, two circuits were constructed, a five resistor circuit with three in series and two in parallel, and a four resistor circuit with three in series and one in parallel. These circuits would be used to verify the accuracy of KCL, KVL, and Thevenin's Theorem equations when compared to lab-measured data. It was distinguished that the equations matched the collected data across lower value resistors and began to separate from the data while the current across the resistors had the opposite effect, registering the greatest difference in lower value resistors and similar across ones with higher values.

# Materials

DigiKey SolderFul BreadBoard

Solderless breadboard

Solder

Wires

1kΩ, 2x 2.2 kΩ, 4.7 kΩ, 5.1 kΩ, 6.8 kΩ, 15 kΩ, 220 kΩ Resistors

# Assembly Procedures

**Part 1-Series circuit**
1. Place the 1kΩ, 2.2 kΩ and 5.1 kΩ in series on the solder breadboard
2. Solder the resistors into place on the back of the solder breadboard
3. Clip exposed excess leads from the back of the solder breadboard

**Image of Part 1 circuit:**

![IMG_8359](https://github.com/npla225/BAE305-SP24-Lab2/assets/156371043/12556cc0-ec97-4a10-a547-0fbee14bf457)


**Part 2.1-Parallel circuit**
1. Using the 2.2 kΩ, 4.7 kΩ, 6.8 kΩ, 15 kΩ, and 220 kΩ resistors construct the parallel circuit with the 4.7 kΩ, 6.8 kΩ, and 15 kΩ resistors in series and the 2.2 kΩ and 220 kΩ resistors in parallel 
2. Place the power wire in the same row as the 4.7 kΩ resistor and the ground wire in the same row as the 
3. For step 5, remove the 5.5 kΩ resistor

**Image of Part 2.1 circuit:**
![IMG_8362](https://github.com/npla225/BAE305-SP24-Lab2/assets/156371043/79a6401b-f1c9-4485-b8b5-b999d448749f)

**Part 2.2 and 2.3-Parallel circuit**
1. Use the same circuit from Part 2.1: Step 5

**Image of Part 2.2 circuit:**
![IMG_8360](https://github.com/npla225/BAE305-SP24-Lab2/assets/156371043/b5765ccc-0f97-47e6-afd2-e8aace88f390)

# Test Equipment

Digital Multimeter

Global Specialties 100W Triple Output Switching DC Power Supply

# Test Procedures

**Part 1-Series Circuit**
1. Using the DMM find the measured resistance of all three resistors and verify them with their labeled values
2. Set the DC power supply to 10V and 0.250A and connect the positive and negative leads to their corresponding soldered wires on the breadboard
3.Using the DMM probes measure the voltage drop across the resistors in parallel on the soldered side of the circuit board

**Part 2.1-KCL**
1. Using the DMM find the measured resistance of all five resistors and verify them with their labeled values
2. Connect the DC power supply to the circuit and run the same voltage and current though the circuit as in Part 1
3. Measure the voltage drop across R5 using the DMM in parallel with the resistor
4. Measure the current through R5 by placing the DMM in series with the resistor
5. After removing R5, measure the currents across R1,R2, and R3 individually and record the results

**Part 2.2-KVL**
1. Using the same circuit from Part 2.1: Step 5, measure and record the voltage drop across R1,R2,R3,R4 separately with the DMM in parallel with the resistor and record the results

**Part 2.3-Thevenin**
1. (See Part 2.1: Step 1)

# Test Results

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

Below is a comparison of the measured current and calculated current after removing R5 from the circuit. It is likely that a mistake was made in the calculated currents due to the vast difference from the measured. 

| Current   | Measured Current (mA)| Calculated Currents (mA)|
| ----------| ---------------------|-------------------------|
| I1(R1)| 0.51  | 2.5 |
| I2(R2)  | 0.46  | 0.23 |
| I3(R4)  | 0.06 | 2.27 |

**Part 2.2**

Below is the measured magnitude and calculated values of voltage drop across resistors R1, R2, R3, & R4. At this point, R5 is still removed from the circuit. It is likely that a mistake was made in the calculated voltage due to the vast difference from the measured. 

| Voltage | Measured Magnitude (V) | Calculated Voltage (V)|
| --------| -----------------------|-----------------------|
| V1| 2.286  | 2.4 |
| V2  | 3.064  | 3.13|
| V3  | 6.65 | 0.9 |
|V4,V5|9.72| 4.7 |

**Part 2.3**

Below are the calculations for the components based on Thevenin's Theorem. 

| Thevenin Component   | Calculated |
| ---------------------| -----------|
| Vth| 1.203  |
| Rth  | 2.66  |
| I n | 6.142 |
|Vl| 10.005 |
|Il| 3.76 |

# Conclusion 

This lab focused on measuring current, voltage and resistance in a variety of circuit arrangements. This allowed us to see how circuits change based on the arrangement of elements. Practicing using the DMM to measure values provided a comparison to the values that are able to be calculated with Ohm's Law. Finally, the circuit was analyzed based on Thevenin circuit analysis principles. 

# Discussion

Did you make any design decisions that had an impact on the results? How did they impact the results? What do the results mean?

Discussion Question 1: How much power does each resistor dissipate? Each branch? Total power? Is the power in equal to the power out? 

Based on the equation Power=Current*Voltage, the amount of power can be calculated for a number of scenarios. The power each resistor dissipates is as follows (units are in mW): P1= 1.17, P2= 1.41, P3= 1.9 and P4= 0.399. Each branch dissipates the sum of the power dissipated in each resistor. So, P1=1.17, P2= 3.31, and P3=0.399. Summing all the values, the total power is 4.88. So, the power in is greater than the power out. 

Discussion Question 2: Does ITH = IL? 

Yes, according Thevenin's Theorem, these values should be equal to one another. If both of these values were measured and calculated correctly, they should equal one another. 
