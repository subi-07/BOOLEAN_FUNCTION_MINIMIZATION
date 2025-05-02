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
Truth Table 1
![image](https://github.com/user-attachments/assets/24e01215-cc95-4ca2-9556-065b8b3ea077)
Truth Table 2
![image](https://github.com/user-attachments/assets/6a5dd904-dce1-449d-b7c0-693680a0e538)

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
module EX2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d|a&b&~c|~a&b&d));
endmodule

module exp2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z|x&y|w&y));
endmodule 
```


**RTL realization**
**Output:**
![image](https://github.com/user-attachments/assets/abce4c13-5598-4370-900f-3c381dbb6910)
![image](https://github.com/user-attachments/assets/fac1cc00-3dd2-4edc-a0c7-0f7d1d9df52f)

**RTL**
![image](https://github.com/user-attachments/assets/19072ca8-4b3f-4e5d-948a-9d1eb7379db1)
![image](https://github.com/user-attachments/assets/04be55ea-4eb3-401d-bdfd-b46e941a0375)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

