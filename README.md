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

Developed by:SUBITHRA R

RegisterNumber:212224110050
```
module funct1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
 endmodule

 module funct2(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y&z)|(w&y)|(x&y));
 endmodule
```


**RTL realization**
![Screenshot 2025-04-15 113126](https://github.com/user-attachments/assets/f5bcceec-838d-48bc-b635-723cfe2373ce)


**Output:**

![Screenshot 2025-04-15 113155](https://github.com/user-attachments/assets/57e52143-c85e-4c85-9045-a6de7a7f91f9)

**Timing Diagram**

![Screenshot 2025-04-15 113155](https://github.com/user-attachments/assets/57e52143-c85e-4c85-9045-a6de7a7f91f9) 


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

