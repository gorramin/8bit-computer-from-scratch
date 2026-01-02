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


### 🔹 BUFFER Gate

**Truth Table**

| Input | Output |
|------:|-------:|
|   0   |   0    |
|   1   |   1    |

**Hardware States**  
<table>
  <tr>
    <td><img src="hardware-states/BUFFER_0.JPG" width="400"></td>
    <td><img src="hardware-states/BUFFER_1.JPG" width="400"></td>
  </tr>
</table>

**Schematic**  
<img src="schematics/BUFFER_SCH.jpg" width="825">

---

### 🔹 NOT Gate

**Truth Table**

| Input | Output |
|------:|-------:|
|   0   |   1    |
|   1   |   0    |

**Hardware States**  
<table>
  <tr>
    <td><img src="hardware-states/NOT_0.JPG" width="400"></td>
    <td><img src="hardware-states/NOT_1.JPG" width="400"></td>
  </tr>
</table>

**Schematic**  
<img src="schematics/NOT_SCH.jpg" width="825">

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
    <td><img src="hardware-states/AND_00.JPG" alt="AND 00" width="400"></td>
    <td><img src="hardware-states/AND_01.JPG" alt="AND 01" width="400"></td>
  </tr>
  <tr>
    <td><img src="hardware-states/AND_10.JPG" alt="AND 10" width="400"></td>
    <td><img src="hardware-states/AND_11.JPG" alt="AND 11" width="400"></td>
  </tr>
</table>


**Schematic**  
<img src="schematics/AND_SCH.jpg" width="825">

---

### 🔹 NAND Gate

**Truth Table**

| A | B | Output |
|---|---|--------|
| 0 | 0 |   1    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   0    |

**Hardware States**  
<table>
  <tr>
    <td><img src="hardware-states/NAND_00.JPG" width="400"></td>
    <td><img src="hardware-states/NAND_01.JPG" width="400"></td>
  </tr>
  <tr>
    <td><img src="hardware-states/NAND_10.JPG" width="400"></td>
    <td><img src="hardware-states/NAND_11.JPG" width="400"></td>
  </tr>
</table>


**Schematic**  
<img src="schematics/NAND_SCH.jpg" width="825">

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
<table>
  <tr>
    <td><img src="hardware-states/OR_00.JPG" width="400"></td>
    <td><img src="hardware-states/OR_01.JPG" width="400"></td>
  </tr>
  <tr>
    <td><img src="hardware-states/OR_10.JPG" width="400"></td>
    <td><img src="hardware-states/OR_11.JPG" width="400"></td>
  </tr>
</table>


**Schematic**  
<img src="schematics/OR_SCH.jpg" width="825">

---

### 🔹 NOR Gate

**Truth Table**

| A | B | Output |
|---|---|--------|
| 0 | 0 |   1    |
| 0 | 1 |   0    |
| 1 | 0 |   0    |
| 1 | 1 |   0    |

**Hardware States**  
<table>
  <tr>
    <td><img src="hardware-states/NOR_00.JPG" width="400"></td>
    <td><img src="hardware-states/NOR_01.JPG" width="400"></td>
  </tr>
  <tr>
    <td><img src="hardware-states/NOR_10.JPG" width="400"></td>
    <td><img src="hardware-states/NOR_11.JPG" width="400"></td>
  </tr>
</table>


**Schematic**  
<img src="schematics/NOR_SCH.jpg" width="825">

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
<table>
  <tr>
    <td><img src="hardware-states/XOR_00.JPG" width="400"></td>
    <td><img src="hardware-states/XOR_01.JPG" width="400"></td>
  </tr>
  <tr>
    <td><img src="hardware-states/XOR_10.JPG" width="400"></td>
    <td><img src="hardware-states/XOR_11.JPG" width="400"></td>
  </tr>
</table>


**Schematic**  
<img src="schematics/XOR_SCH.jpg" width="825">

---

### 🔹 NXOR Gate

**Truth Table**

| A | B | Output |
|---|---|--------|
| 0 | 0 |   1    |
| 0 | 1 |   0    |
| 1 | 0 |   0    |
| 1 | 1 |   1    |

**Hardware States**  
<table>
  <tr>
    <td><img src="hardware-states/NXOR_00.JPG" width="400"></td>
    <td><img src="hardware-states/NXOR_01.JPG" width="400"></td>
  </tr>
  <tr>
    <td><img src="hardware-states/NXOR_10.JPG" width="400"></td>
    <td><img src="hardware-states/NXOR_11.JPG" width="400"></td>
  </tr>
</table>


**Schematic**  
<img src="schematics/NXOR_SCH.jpg" width="825">

---

## 🎥 Logic Simulation

A digital simulation was created to validate the behavior of all logic gates.

📁 **Video:** 
[Watch the simulation video](simulation/logic_simulation.mp4)

This simulation confirms that the transistor-level implementations behave exactly as expected according to the truth tables.

## 📦 Resources

The complete simulation project file is available for further inspection and modification.

📂 **Proteus Simulation File:**  

