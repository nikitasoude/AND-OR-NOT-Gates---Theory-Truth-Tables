Concept Overview
In digital logic, basic gates like AND, OR, and NOT are the building blocks of complex digital circuits. Understanding their behavior is crucial for designing efficient systems.

Detailed Explanation
✅ AND Gate
Definition: The AND gate outputs 1 only when both inputs are 1.
Symbol: Represented by a D-shaped symbol with two or more inputs and one output.
Boolean Expression: Y = A • B
Truth Table:
A	B	Y (AND)
0	0	0
0	1	0
1	0	0
1	1	1
Example Application: Used in security systems that require multiple conditions to be true.

✅ OR Gate
Definition: The OR gate outputs 1 if any input is 1.
Symbol: Represented by a curved symbol with two or more inputs and one output.
Boolean Expression: Y = A + B
Truth Table:
A	B	Y (OR)
0	0	0
0	1	1
1	0	1
1	1	1
Example Application: Used in alarm systems where any condition can trigger an alert.

✅ NOT Gate (Inverter)
Definition: The NOT gate outputs the inverse of the input.
Symbol: Represented by a triangle with a small circle at the output.
Boolean Expression: Y = A'
Truth Table:
A	Y (NOT)
0	1
1	0
Example Application: Used for signal inversion and logic level shifting.

Code Explanation
assign Statements: These define combinational logic for AND, OR, and NOT gates.
$monitor Task: Tracks changes in signals and displays results in the console.
Test Cases: Each combination of inputs (00, 01, 10, 11) verifies correct gate behavior.
Execution Steps
Copy the Verilog code into your simulator (e.g., ModelSim, Xilinx Vivado, etc.).
Compile the code to ensure syntax correctness.
Run the simulation and observe the outputs match the corresponding truth tables.
Real-World Example for Practice
Design a 4-input AND gate that activates an alarm only when four conditions are true (e.g., all doors locked, windows closed, security mode enabled, and sensors activated).
