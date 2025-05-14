# BOOLEAN_FUNCTION_MINIMIZATION

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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:varshini G
RegisterNumber:212224050056
*/

```
module exp02(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```


**RTL realization**

![Screenshot 2025-05-14 101109](https://github.com/user-attachments/assets/b66e8d1e-b158-487c-b71a-d63f107b6df8)


**Output:**
![Screenshot 2025-05-14 101136](https://github.com/user-attachments/assets/49a4669e-c445-450f-ae3a-b3d7420141a5)
![Screenshot 2025-05-14 101158](https://github.com/user-attachments/assets/ca53a335-9e74-46a0-8488-22258c7182b4)


**Timing Diagram**

![Screenshot 2025-05-14 101217](https://github.com/user-attachments/assets/7d20e1ca-e158-410d-bf6c-c1f4d59e1eed)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

