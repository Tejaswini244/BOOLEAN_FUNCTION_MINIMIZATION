# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

F2=xy’z+x’y’z+w’xy+wx’y+wxy

module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule

Developed by: TEJASWINI R

RegisterNumber:24009408

**Truth Table**

![WhatsApp Image 2024-12-20 at 5 07 56 PM](https://github.com/user-attachments/assets/faff5b68-1a98-4775-aaad-4464d5c26f8e)

**RTL**

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

![experiment 2 f1](https://github.com/user-attachments/assets/99b7400d-eb67-425b-b409-f5d55cbf3183)

F2=xy’z+x’y’z+w’xy+wx’y+wxy

![experiment 2 f2](https://github.com/user-attachments/assets/475ad4ff-1d3f-4dcb-8ad2-14f0032756e0)

**Output:**

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

![exp 2 f1output](https://github.com/user-attachments/assets/4bca4fe2-2707-49cf-a650-79402c0d6533)


F2=xy’z+x’y’z+w’xy+wx’y+wxy

![exp2 f2 out](https://github.com/user-attachments/assets/e196acd7-d822-4265-a062-00d7200d306a)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

