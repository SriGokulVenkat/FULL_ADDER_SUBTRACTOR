# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable:**
![Screenshot 2024-12-07 233949](https://github.com/user-attachments/assets/4979f553-0b15-49e6-a93c-9bc2efe5231e)
able**

**Procedure**
1.Type the program in Quartus software.
2.Complie and run the program.
3.Generate the RTL schmatic and save the logic diagram.
4.Create nodes for inputs and outputs to gernate the timing diaagram.
5.For different input combinations generate the timing diagram.


**Program:**

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
![Screenshot 2024-12-07 234331](https://github.com/user-attachments/assets/e6d4ed0b-0850-4d7f-b902-36ddf089ac42)





Developed by: Sri Gokul Venkat.M
RegisterNumber: 24901059


**RTL Schematic**
 
![Screenshot 2024-12-08 001824](https://github.com/user-attachments/assets/b3a14d58-8634-4184-af4e-a2bc6a4cd31c)

**Output Timing Waveform**

![Screenshot 2024-12-08 001914](https://github.com/user-attachments/assets/35e3cf53-e6e8-465d-9bf5-b88e2053736e)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



