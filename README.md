# Experiment 02  Implementation-of-combinational-logic
Implementation of combinational logic gates
 #### REGISTER NUMBER:23005860
 #### NAME:MASINA SREE KARSH
### AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 ### EQUIPMENT REQUIRED:

 Hardware PC Cyclone II, USB flasher Software - Quartus prime 


### Theory:
 
A combinational circuit is a circuit in which the output depends on the present combination of inputs. Combinational circuits are made up of logic gates. The output of each logic gate is determined by its logic function. Combinational circuits can be made using various logic gates, such as AND gates, OR gates, and NOT gates.

### Procedure:
1. Create a New Project:
   - Open Quartus and create a new project by selecting "File" > "New Project Wizard."
   - Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).
2. Create a New Design File:
   - Once the project is created, right-click on the project name in the Project Navigator and select "Add New File."
   - Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.

3. Write the Combinational Logic Code:
   - Open the newly created Verilog or VHDL file and write the code for your combinational logic.
     
4. Compile the Project:
   - To compile the project, click on "Processing" > "Start Compilation" in the menu.
   - Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.

5. Analyze and Fix Errors:*
   - If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window.
   - Review and fix any issues in your code if necessary.
   - View the RTL diagram.

6.Verification:
   - Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".
   - Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All.
   - Give the Input Combinations according to the Truth Table amd then simulate the Output waveform











### Program:
![image](https://github.com/vignesh-777/Experiment--02-Implementation-of-combinational-logic-/assets/139842402/0137e83a-d23b-4127-99b2-01e41dfe2325)



### RTL REALIZATION:

![image](https://github.com/vignesh-777/Experiment--02-Implementation-of-combinational-logic-/assets/139842402/9f7536a1-6786-457f-85dd-a48dbe2207e3)

### TIMING DIAGRAM:
![image](https://github.com/vignesh-777/Experiment--02-Implementation-of-combinational-logic-/assets/139842402/57944421-cebe-4b08-9372-91451b75641f)

### TRUTH TABLE:
![image](https://github.com/vignesh-777/Experiment--02-Implementation-of-combinational-logic-/assets/139842402/65e244e3-e7ea-495f-9a4f-8de8f2a2b0b8)

### Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
