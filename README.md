# EX NO 04 - DESIGN & IMPLEMENTATION OF 6T SRAM CELL USING CADENCE EDA TOOLS

## AIM:
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## TOOLS REQUIRED:
### CADENCE EDA SUITE
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### PROCESS DESIGN KIT (PDK)
- CMOS technology library (45nm node)  

### COMPUTER SYSTEM
- Minimum **4GB RAM** and a **multi-core processor**

## PROCEDURE:
### 1. Launch Cadence Virtuoso Environment:
~~~
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.
~~~
### 2. Schematic Design:
~~~
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.
~~~
### 3. Simulation:
~~~
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.
~~~
## CIRCUIT DIAGRAM:

![Screenshot 2025-03-24 122239](https://github.com/user-attachments/assets/c22930fc-f396-4787-807d-51088ad7959e)


## 6T SRAM TRUTH TABLE:

![Screenshot 2025-03-24 123041](https://github.com/user-attachments/assets/29a8a036-d65d-4a25-ba18-3f1f0e358576)


## SCHEMATIC DIAGRAM:

#### 1. SCHEMATIC OF 6T SRAM CELL:

  ![Screenshot (235)](https://github.com/user-attachments/assets/b1895326-884f-40e7-b6f2-80da4609b0d1)

   ![image](https://github.com/user-attachments/assets/c28aea2b-9e73-48e6-abdb-11c430321b86)


## OUTPUT:
#### 1. TRANSIENT ANALYSIS OUTPUT:

   ![Screenshot 2025-03-24 121615](https://github.com/user-attachments/assets/2805525e-1f0d-4ef8-b131-79a3153b7127)
![Screenshot (234)](https://github.com/user-attachments/assets/a19f4604-ed4d-48e4-8e72-5ff560b86680)


## RESULT:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


