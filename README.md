## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** | Manoj N | **Reg. No.:** | 26000161|
|---|---|---|---|
| **Date:** | 7/11/2026| **Batch / Section:** | 305-26ODJ153|

---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 3 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram

<img width="1367" height="722" alt="image" src="https://github.com/user-attachments/assets/ec9bf1e6-c1a3-492a-86a5-61674177245b" />


**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="972" height="448" alt="697367061-304b4301-b7f4-432c-9966-3d86b957af5e" src="https://github.com/user-attachments/assets/6447ddc9-4c11-4ca5-a437-946d40ea522f" />


**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="1367" height="722" alt="image" src="https://github.com/user-attachments/assets/ec9bf1e6-c1a3-492a-86a5-61674177245b" />

**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="972" height="448" alt="697367061-304b4301-b7f4-432c-9966-3d86b957af5e" src="https://github.com/user-attachments/assets/6447ddc9-4c11-4ca5-a437-946d40ea522f" />

**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

<img width="970" height="432" alt="image" src="https://github.com/user-attachments/assets/a04b389d-360e-4e7b-85e0-3dbf1fd57d02" />


### B. KCL – Current measurements

<img width="827" height="342" alt="image" src="https://github.com/user-attachments/assets/cc2ab526-91ed-4f10-af87-141f2b4d901b" />


## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.
<img width="552" height="742" alt="image" src="https://github.com/user-attachments/assets/4c11bcd6-7efd-44d7-82ce-33b62a84c029" />



**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="646" height="891" alt="image" src="https://github.com/user-attachments/assets/d524c6c5-769a-4079-9c9b-b6a9fc4a545d" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
