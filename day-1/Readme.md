# Day 1 – Logic Gates (8-Bit Computer Project)

This is **Day 1** of my **8-bit computer from scratch** project.

In this first day, I focused entirely on the **fundamental building blocks of digital systems**:  
👉 **Logic gates implemented at transistor level**

For each logic gate, I built and verified:
- The **real hardware implementation** using transistors
- The **electrical schematic**
- The **truth table**
- A **digital simulation** to validate the behavior

This step is essential before moving to more complex blocks like adders, registers, and control logic.

The following logic gates were implemented and tested:

- NOT
- BUFFER
- AND
- NAND
- OR
- NOR
- XOR
- XNOR

Each gate was tested in **all possible input states**, and the physical behavior was observed and documented.

## 🔍 Logic Gates

### 🔹 NOT Gate

**Truth Table**

| Input | Output |
|------:|-------:|
|   0   |   1    |
|   1   |   0    |

**Hardware States**  
<table>
  <tr>
    <td><img src="hardware-states/NOT_0.JPG" alt="AND 00" width="500"></td>
    <td><img src="hardware-states/NOT_1.JPG" alt="AND 01" width="500"></td>
  </tr>
</table>

**Schematic**  
![AND Gate Schematic](schematics/NOT_SCH.jpg)

---

### 🔹 AND Gate

**Truth Table**

| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   0    |
| 1 | 0 |   0    |
| 1 | 1 |   1    |

**Hardware States**  
<table>
  <tr>
    <td><img src="hardware-states/AND_00.JPG" alt="AND 00" width="450"></td>
    <td><img src="hardware-states/AND_01.JPG" alt="AND 01" width="450"></td>
  </tr>
  <tr>
    <td><img src="hardware-states/AND_10.JPG" alt="AND 10" width="450"></td>
    <td><img src="hardware-states/AND_11.JPG" alt="AND 11" width="450"></td>
  </tr>
</table>


**Schematic**  
![AND Gate Schematic](schematics/AND_SCH.jpg)

---

### 🔹 OR Gate

**Truth Table**

| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   1    |

**Hardware States**  
📂 See: `hardware-states/OR_00.jpg` → `OR_11.jpg`

**Schematic**  
📂 See: `schematics/OR_schematic.jpg`

---

### 🔹 XOR Gate

**Truth Table**

| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   0    |

**Hardware States**  
📂 See: `hardware-states/XOR_00.jpg` → `XOR_11.jpg`

**Schematic**  
📂 See: `schematics/XOR_schematic.jpg`

---

### 🔹 NAND, NOR, XNOR Gates

These gates were derived and implemented using transistor-level logic.

For each gate:
- ✅ Full truth table verified
- ✅ All input states tested on real hardware
- ✅ Electrical schematic documented

📂 **Hardware states:** `hardware-states/`  
📂 **Schematics:** `schematics/`

---

## 🎥 Logic Simulation

A digital simulation was created to validate the behavior of all logic gates.

📁 **Video:**  
