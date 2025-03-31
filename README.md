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
```
Developed by: G P Hariesh
RegisterNumber:212224040100
2A)
module exp2a(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~a&b&d)|(~b&~d)|(a&b&~c));
endmodule
2B)
module exp2b(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
**KMAP:**
![WhatsApp Image 2025-03-31 at 20 37 13_ea0e519b](https://github.com/user-attachments/assets/03cd0aef-5a71-4140-b722-e33fdbaeff1e)



**RTL**
![EXP2A](https://github.com/user-attachments/assets/9a789f40-6aaa-4ec5-a58a-337f7fe4c361)
![EXP2B](https://github.com/user-attachments/assets/394b20c6-3d1d-41b3-b8bc-21dbb72c7ee7)


**Timing Diagram**
![EXP2AD](https://github.com/user-attachments/assets/7b512a9a-54aa-4234-871b-8faa400c73ef)

![EXP2BD](https://github.com/user-attachments/assets/63c02a42-6e4f-4c46-9627-fb127ce4111a)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

