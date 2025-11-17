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

module exp2(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

module exp2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Nanditha shaji 

RegisterNumber: 25012970
*/


**RTL realization**
<img width="582" height="515" alt="Screenshot 2025-11-17 181333" src="https://github.com/user-attachments/assets/3dd55313-c212-4b2b-9a5c-940ff337ede7" />

**Output:**

<img width="765" height="384" alt="image" src="https://github.com/user-attachments/assets/ce84c007-3e4e-4319-98bf-384ee32e3925" />


**RTL**

<img width="770" height="469" alt="image" src="https://github.com/user-attachments/assets/2f417039-a6a6-4971-bb15-05c975879a51" />


**Timing Diagram**

<img width="768" height="363" alt="image" src="https://github.com/user-attachments/assets/216a3e24-e135-4ba5-90ad-6eda194386b4" />
<img width="771" height="187" alt="image" src="https://github.com/user-attachments/assets/45bb9af3-4ff7-4769-9f57-e743d2284ace" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

