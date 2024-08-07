# 8T SRAM Circuit Simulation 

This repository contains an LTspice simulation of an 8T SRAM cell. 

## What is an 8T SRAM?

An 8T SRAM (Static Random Access Memory) is a type of memory cell that uses eight transistors to store a single bit of data. It is an improvement over the traditional 6T SRAM design, offering several advantages: 

* **Enhanced Stability:** The additional transistors provide greater control over the voltage levels in the memory cell, making it less susceptible to noise and variations in temperature.
* **Reduced Leakage Current:** The 8T design can minimize leakage currents, which is crucial for maintaining data integrity in low-power applications.
* **Improved Read Performance:** The extra transistors can facilitate a faster and more reliable read operation, contributing to better overall performance.


## Conditions for Correct Operation 

To ensure the proper operation of an 8T SRAM, the following conditions must be met:

* **Power Supply:** An appropriate power supply (VDD) must be provided to energize the circuit.
* **Voltage Levels:** The voltage levels of the control signals (read and write signals) should be properly defined and compatible with the transistors used.
* **Transistor Characteristics:** The transistors should exhibit appropriate characteristics (e.g., threshold voltage, drive current) for reliable switching and data retention.
* **Load Capacitance:** The load capacitance (CL) should be carefully considered to ensure sufficient signal strength during read operations.


## Analysis and Simulation 

The LTspice simulation in this repository demonstrates the functionality of an 8T SRAM cell, including:

* **Write Operation:** Demonstrates how data is written into the cell by applying appropriate control signals.
* **Read Operation:** Shows how data is read from the cell by applying the read signal.
* **Data Retention:** Illustrates how the data is retained within the cell even without any external control signals.


The Circuit should look like :
![image](https://github.com/user-attachments/assets/9f0b5203-8184-4bfa-8dfe-08f1341248cd)



## Simulation Settings

The LTspice simulation uses the following settings:

* **Simulation Type:** Transient analysis.
* **Simulation Time:** 10ns.
* **Step Size:** 1ps.
* **Transient Analysis Parameters:** Set to default values.

  And the simulation output will approximately be like
![image](https://github.com/user-attachments/assets/fe25d5bc-d23a-469b-8d29-83307d768c11)

## Running the Simulation 

1. Download and open the LTspice project file (`8T_SRAM.asc`) in LTspice.
2. Ensure the simulation settings are configured as described above.
3. Run the simulation by clicking "Run" or pressing F11.

## Github Repository

This repository is organized as follows:

* **8T_SRAM.asc:** The LTspice circuit file containing the 8T SRAM design.
* **Readme.md:** This file providing information about the simulation and the 8T SRAM design.

## Contributions

Feel free to fork this repository, experiment with the design, and contribute to its improvement. 

