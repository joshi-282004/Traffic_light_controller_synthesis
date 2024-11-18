# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

## Synthesis RTL Schematic :
![image](https://github.com/user-attachments/assets/2c61e58f-5d23-4ddb-a08f-28cf0c0e101f)

## Area report:
![Screenshot 2024-11-18 192847](https://github.com/user-attachments/assets/2edd5114-b991-40cc-bd85-e5767f9d2b60)

## Power Report:
![Screenshot 2024-11-18 192912](https://github.com/user-attachments/assets/3ce7d0dc-26f7-4a0b-9da2-73c1a694f4b6)

## Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
