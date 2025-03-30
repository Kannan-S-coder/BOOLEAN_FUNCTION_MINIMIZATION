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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

#### Developed by: Kannan S  
#### RegisterNumber: 212223230098

#### 2a
```
module ex2a(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~a&b&d)|(~b&~d)|(a&b&~c));
endmodule
```

#### 2b
```
module ex2b(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

**Output:**
#### 2a
![WhatsApp Image 2025-03-30 at 12 15 12_83fdbcc9](https://github.com/user-attachments/assets/4647f918-2a2e-4db2-81cf-765620d24b13)

#### 2b
![WhatsApp Image 2025-03-30 at 12 15 12_926bbac2](https://github.com/user-attachments/assets/f2a3720c-8a18-4987-87e8-56786f15f4d4)
![WhatsApp Image 2025-03-30 at 12 15 13_9305b8c2](https://github.com/user-attachments/assets/37f4ba04-b84f-4a40-94a9-d6b3a86fc675)




**RTL realization**
#### 2a
![ex2a](https://github.com/user-attachments/assets/7e81e3d0-a02f-4866-9b21-e3848c789032)

#### 2b
![ex2b](https://github.com/user-attachments/assets/adf7c15e-9709-4f98-ae26-c38704af1e0b)



**RTL**
#### 2a
![Screenshot 2025-03-17 135932](https://github.com/user-attachments/assets/ecbdb491-3a4f-4b84-a880-7cc8be923b76)

#### 2b
![Screenshot 2025-03-17 143423](https://github.com/user-attachments/assets/07b65b9a-c07e-4235-a1fc-336b87a9b8d4)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

