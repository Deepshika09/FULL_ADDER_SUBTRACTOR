![111](https://github.com/user-attachments/assets/4024d4f8-1997-4926-b701-6867b46c0e3c)# FULL_ADDER_SUBTRACTOR

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
**Full adder:**
![digi 1](https://github.com/user-attachments/assets/488be2a8-3502-4fce-ab5d-cbeb3d91f00f)
**Full Subractor:**
![digi 2](https://github.com/user-attachments/assets/1412ba83-6ad9-4de1-ac41-8db02c6269bf)

**Procedure**

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram.

**Program:**

**Full adder:**
![Screenshot 2025-04-17 115127](https://github.com/user-attachments/assets/dbd72c50-7e9c-47c5-a50a-c4d31c269c6c)
**full subractor:**
![Screenshot 2025-04-17 114610](https://github.com/user-attachments/assets/702b0094-eb00-4136-bf03-c8fceca8ab37)


**RTL Schematic**
**Full adder:**
![Screenshot 2025-04-17 111521](https://github.com/user-attachments/assets/cd8f8072-b483-4144-850c-31b9ddc8474c)
**full subractor:**
![Screenshot 2025-04-17 114629](https://github.com/user-attachments/assets/eaa00a13-0bc4-4cf2-9db6-ab34adebc375)

**Output Timing Waveform**
**Full adder:**

**full subractor:**
![![111](https://github.com/user-attachments/assets/550e0d79-8e9b-4eb7-a519-4ceb5880d8fa)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



