# BOOLEAN_FUNCTION_MINIMIZATION
***Date:03/12/2025**


**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
Boolean Function
------------------------------------------------
F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: KANCHANA M
RegisterNumber:25016997
*/


**RTL realization**
<img width="964" height="497" alt="Screenshot 2025-12-03 161547" src="https://github.com/user-attachments/assets/a87e090a-4435-4403-8ac6-7327e7c5d068" />


**RTL**
**Output:**
<img width="1226" height="184" alt="Screenshot 2025-12-03 161606" src="https://github.com/user-attachments/assets/32edced1-8f70-4081-942f-d169ef31be36" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
.
.
.
.
.
.
.
.

.
.
.
.

.

.
.
.
.
.
.
.

.
.
.
.

.
.
.
.

.
.
.
.

.

