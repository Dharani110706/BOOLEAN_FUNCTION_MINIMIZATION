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

**Minimization:**
F1
![image](https://github.com/user-attachments/assets/20203fca-6fef-4616-953e-bf3d898d06f8)
F2
![image](https://github.com/user-attachments/assets/5f8db17d-7653-437a-8124-311a32380971)

**Truthtable**
   
![image](https://github.com/user-attachments/assets/7afefff3-3cb0-41da-a8f3-2231ed0c9642)

**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24900674 P.DHARANI SREE
```
F1
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

F2
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

**RTL**
  ![image](https://github.com/user-attachments/assets/0bbcd3cf-4cac-4e17-8a20-91785ee083c8)
  ![funct2](https://github.com/user-attachments/assets/fa6eddae-544c-4f83-8699-e19649915c0a)



**Output**
![image](https://github.com/user-attachments/assets/a139d20c-5ebb-48bd-b4f1-04c76c5467b9)
![image](https://github.com/user-attachments/assets/0c559a90-d3a5-4028-8c2c-3ba6de73777f)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

