# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

software-Quartus prime
**Software – Quartus prime**
cyclone v verilog program
**Theory**
Boolean function minimization is a process used in digital logic design to simplify Boolean expressions while maintaining their functionality. This is crucial for optimizing the design of digital circuits, as simpler expressions translate to fewer logic gates and reduced hardware complexity.


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24900674 P.DHARANI SREE
'''i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule'''






**RTL**
![Uploading Screenshot (11).png…]()

**Timing Diagram**
![Screenshot (12)](https://github.com/user-attachments/assets/de118542-875b-47bc-9bb6-f6926a4521fa)

**Output:**
![Uploading Screenshot (12).png…]()

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

