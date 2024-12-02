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

```
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: STEFFI J
RegisterNumber: 24900405
```
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```

**RTL realization**
  
  ![picture](https://github.com/user-attachments/assets/51e4cb93-c8ac-45e4-9811-236f8d512851)


**Output:**
  
  ![logic](https://github.com/user-attachments/assets/f0186539-f832-490b-b50d-df7c1d903db3)


**RTL**

**Timing Diagram**
  
  ![diagram](https://github.com/user-attachments/assets/e64f3679-1733-4f65-a2f6-d43db9737cb1)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

