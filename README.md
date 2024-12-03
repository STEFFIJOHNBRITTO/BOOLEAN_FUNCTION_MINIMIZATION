# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![image](https://github.com/user-attachments/assets/ee2dc496-7ec4-4db9-bf53-fd60761f6938)

![image](https://github.com/user-attachments/assets/23f03fa4-ac28-41ff-bc00-0317937b134b)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

```
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: STEFFI J
RegisterNumber: 24900405
```
```
 module exp2f1(a,b,c,d,f1,w,x,y,z,f2);
 input a,b,c,d,w,x,y,z;
 output f1,f2;
 assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
 assign f2=((~y&z)|(x&y)|(w&y));
 endmodule

```

**RTL realization**
  
**Output:**
  
**RTL**

![image](https://github.com/user-attachments/assets/95bf16c2-f02e-4a56-ac83-3906d7f7ed56)


**Timing Diagram**
  
  ![image](https://github.com/user-attachments/assets/33e650ff-1d32-4f44-a2da-bcba343d1a66)

  ![image](https://github.com/user-attachments/assets/dab398f7-819d-4ef7-ac38-b2476a9c09b4)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

