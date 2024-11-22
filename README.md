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

### Synthesis RTL Schematic :
![WhatsApp Image 2024-11-22 at 12 21 49_244b4ea1](https://github.com/user-attachments/assets/1dccc7ad-c1cc-447c-a836-4754a9276b9b)

### Area report:
![WhatsApp Image 2024-11-22 at 12 21 49_0f28587c](https://github.com/user-attachments/assets/06c49731-7e7f-4b7a-9de8-bf4fbdde98dd)

## Power Report:
![WhatsApp Image 2024-11-22 at 12 21 50_e392bc51](https://github.com/user-attachments/assets/cfbd1139-5de0-4bb0-8b2a-1e018e444a26)

## Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
