# DATE: 12/03/2025

# BOOLEAN_FUNCTION_MINIMIZATION

# NAME: NAVEEN JAISANKER
# REG. NO.: 21224110039
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

'''
module LOGIC_FUNCTION(w,x,y,z, f2);
input w,x,y,z;
output f2;
assign f2 = ((~y & z) | (w & y) | (x & y));
endmodule
'''

**Developed by:NAVEEN JAISANKER RegisterNumber: 212224110039**


**RTL realization**

![Screenshot 2025-03-18 112609](https://github.com/user-attachments/assets/5bde2af8-f3f3-4d2c-985e-697fc9051c8f)

![Screenshot 2025-03-18 113644](https://github.com/user-attachments/assets/f60b64ac-32ca-43bf-9af7-98db0c5b4bc7)


**Output:**

**RTL**

![Screenshot (1)](https://github.com/user-attachments/assets/6f95a955-4d62-4e8a-95aa-cccd8a99ba31)

![Screenshot (2)](https://github.com/user-attachments/assets/0cc16c12-a050-4f13-8b08-9ff057429b9e)



**Result:**

Thus, the given logic functions are implemented using and their operations are verified using Verilog programming.

