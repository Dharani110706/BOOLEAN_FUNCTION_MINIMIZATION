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
endmodule
ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule'''






**RTL**
![funct1](https://github.com/user-attachments/assets/5a017b6d-7316-4811-86a7-6ec7d83dd318)

![Screenshot (13)](https://github.com/user-attachments/assets/1177c979-6645-44b4-918d-b1102a4d063a)

**Timing Diagram**
![Screenshot (12)](https://github.com/user-attachments/assets/de118542-875b-47bc-9bb6-f6926a4521fa)
![Screenshot (14)](https://github.com/user-attachments/assets/f4a63d9b-16fb-4387-9e7d-6fc7a93d6864)

**Output:**
![Uploading Screenshot (12).png…]()
![Uploading Screenshot (14).png…]()

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

