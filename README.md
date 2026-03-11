# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

![expt6_and_sch](https://github.com/user-attachments/assets/ef0ba723-f9ad-4796-9c49-0caac9162383)


![expt6_and_sym](https://github.com/user-attachments/assets/f09b3cf8-e0e3-498b-81e1-f236becf3703)


### Schematicand Symbol of 2-Input EX-OR Gate:

![exor_sch](https://github.com/user-attachments/assets/d643e1f4-1102-43f9-9362-ed6eaf50a981)


![exor_sym](https://github.com/user-attachments/assets/f7d4b666-69e5-49f1-8d3a-eb50eb529c27)


### Schematicand Symbol of Half Adder:
![ha_sch](https://github.com/user-attachments/assets/fca38cd2-7ed3-431b-9871-b0a49a000b61)


![ha_sym](https://github.com/user-attachments/assets/c8bf2f7c-ba88-4de3-9f10-eff3987758a8)


### Schematic of 2-Bit Multiplier:
![2bit multiplier ckt](https://github.com/user-attachments/assets/250e8f52-ee5c-4c78-b43f-546aa9604678)


## Output
### Transient Analysis Output:
![analysis 2bit mul](https://github.com/user-attachments/assets/764b8661-31b7-4c5d-9cd5-a2fd02a1dab5)


![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)


![graph 2 bit mul](https://github.com/user-attachments/assets/f696bce4-9be1-4b90-9e7f-b99aa86acbf2)


#### Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
