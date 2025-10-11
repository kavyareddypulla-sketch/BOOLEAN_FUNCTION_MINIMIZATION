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
**Program:**
EXPERIMENT 2:
i)
module EXPERIMENT2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module EXP2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/


**RTL realization**
<img width="1023" height="631" alt="image" src="https://github.com/user-attachments/assets/63e3dd36-abbb-4a70-8c8f-7121fb741141" />
<img width="1026" height="629" alt="image" src="https://github.com/user-attachments/assets/4b8eac96-459f-4f65-96b9-26d41f135eb7" />

**Timing Diagram**
<img width="1047" height="636" alt="image" src="https://github.com/user-attachments/assets/609a0482-a712-4f91-a9f8-316fdf3f782a" />
<img width="1037" height="653" alt="image" src="https://github.com/user-attachments/assets/561d6306-df86-4ff5-b284-e03cd168344a" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

