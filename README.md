# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME: SHARON ARUL BHARATHI J.F
# REGISTER NUMBER:212224100056
# DEPARTMENT: CSE(CS)
# YEAR:1st year
## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:
Arithmetic Operations: Verify that the output shows correct results for addition, subtraction, multiplication, and division.
Logical Operations: Confirm that the output behaves as expected based on the logical conditions (AND, OR, NOT).
##  Simulation Screenshots:
Addition
![image](https://github.com/user-attachments/assets/7a32f692-5613-4162-8111-5e49ef20364c)
![image](https://github.com/user-attachments/assets/c1ad9b5f-fabe-4c60-a9ce-3f47f39ebd49)
![image](https://github.com/user-attachments/assets/1374ede4-8b53-495b-a7fe-7b7224f8843e)
![image](https://github.com/user-attachments/assets/e09f3333-dde6-43b8-94bb-64005c4cbf60)
Subtraction
![image](https://github.com/user-attachments/assets/a20bdc2f-c770-484c-ba52-fb43bd08ac87)
![image](https://github.com/user-attachments/assets/2c7c9e13-1c26-4c21-a14c-66f699b1c59b)
![image](https://github.com/user-attachments/assets/6b2e38c6-9c9f-40d1-b291-a3df95a456c9)
![image](https://github.com/user-attachments/assets/b96041d0-4255-4277-aedd-938a3f286194)
Multiplication
![image](https://github.com/user-attachments/assets/5c7c23d2-390d-4f18-a85c-3f95091b8a7f)
![image](https://github.com/user-attachments/assets/becf152a-749a-4cb3-a2d7-a8f7cf731a47)
![image](https://github.com/user-attachments/assets/bdac5bc4-f9c5-4d06-8787-217f26b5b3d4)
![image](https://github.com/user-attachments/assets/7bcd55fe-87ce-4a3f-b645-4ccfb42c69c0)
Division
![image](https://github.com/user-attachments/assets/f4ad6dc1-e774-493b-926e-a498d3585792)
![image](https://github.com/user-attachments/assets/7146cb03-acd4-438e-af45-18fd91044f59)
![image](https://github.com/user-attachments/assets/e5a04c02-6095-4286-9da6-52d86e1b5892)
![image](https://github.com/user-attachments/assets/37382d32-ed35-42eb-a79b-b5102e6f1d62)

## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
