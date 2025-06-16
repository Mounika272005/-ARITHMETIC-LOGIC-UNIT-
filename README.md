# -ARITHMETIC-LOGIC-UNIT-

*COMPANY*: CODTECH IT SOULTIONS

*NAME*:  Byreddy Mounika 

*INTERN ID*: CT06DM672

*DOMAIN*: VLSI

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

The objective of this mini-project was to design, implement, simulate, and verify a 4-bit Arithmetic Logic Unit (ALU) using Verilog HDL (Hardware Description Language). An ALU is a fundamental building block in digital systems and is responsible for carrying out arithmetic and logic operations within microprocessors and embedded systems.

In this task, I created a Verilog module that performs the following basic operations:

Addition

Subtraction

Bitwise AND

Bitwise OR

These operations are selected using a 2-bit input selector (ALU_Sel). The operands (A and B) are 4-bit input values, and the output is also 4-bit (ALU_Out). In addition to the result, the module also computes a CarryOut bit to handle overflow in addition or subtraction.

Tools and Platform Used
1. Verilog HDL
The ALU was coded in Verilog, a hardware description language used for modeling electronic systems at various levels of abstraction (gate, register-transfer, and algorithmic level).

2. Icarus Verilog
This open-source Verilog simulator was used to compile (iverilog) and simulate (vvp) the Verilog code. It is lightweight, beginner-friendly, and works well with other tools like GTKWave.

3. GTKWave
GTKWave is a waveform viewer used to visualize digital signal transitions and debug the design. The ALU testbench generates a .vcd (Value Change Dump) file which can be opened in GTKWave to observe how input signals and outputs change over time.

4. Visual Studio Code (VS Code)
All coding was done using Visual Studio Code, which provided a clean interface and support for Verilog extensions. It also allowed easy access to an integrated terminal to run simulation commands directly.
