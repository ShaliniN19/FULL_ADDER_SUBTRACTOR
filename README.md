# EXP4:FULL_ADDER_SUBTRACTOR

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

**Truthtable**
![FA truth table](https://github.com/user-attachments/assets/767d7411-0685-43ee-8025-277077c3b14b)



![FS truthtable](https://github.com/user-attachments/assets/33464cf9-2ad3-455f-9a44-a11e1c51bf19)

**Procedure**

Write the detailed procedure here
1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
![FA code](https://github.com/user-attachments/assets/b5652185-54f9-4b00-836b-94643aa54133)


![FS code](https://github.com/user-attachments/assets/02c5edc5-da23-4b0d-b71f-4facbccdd4ba)



**RTL Schematic**
![FA diagram](https://github.com/user-attachments/assets/be937da2-7ea8-4d3e-9c3e-5c598147d9b4)

![FS diagram](https://github.com/user-attachments/assets/b0d49eb7-6cb8-4476-8d75-5081af1493a3)




**Output Timing Waveform**
![FA waveform](https://github.com/user-attachments/assets/f5836c9f-bad9-4eed-89c2-a0be32e41bb4)

![FS WAVEFORM](https://github.com/user-attachments/assets/fb700bf5-90fe-45de-890d-d3d2616cccfe)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



