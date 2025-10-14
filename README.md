# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

*AIM:*

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

*Equipments Required:*

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

*Full Adder and Full Subtractor*

*Full Adder*

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

*Figure -1 FULL ADDER*

*Full Subtractor*

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

*Truthtable*

![image](https://github.com/user-attachments/assets/bd9d58e5-3874-4240-8dad-7f439008e2e5)

![image](https://github.com/user-attachments/assets/61346f23-3c5f-4635-8472-425d217e4a11)

*Procedure*

Write the detailed procedure here

*Program:*

![image](https://github.com/user-attachments/assets/b4a3fb39-8fce-41ce-86cf-73ee6da3290c)

![image](https://github.com/user-attachments/assets/63f0a271-35ff-4d25-a1e9-14c9a2ec9b1c)


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:Mithul Piranav RegisterNumber:212224050019
*/

*RTL Schematic*

![image](https://github.com/user-attachments/assets/97eec3ad-a769-43d8-a7de-8c57228a4027)

![image](https://github.com/user-attachments/assets/df8f8059-f71f-455b-8ec9-5ec36c714827)


*Output Timing Waveform*

![image](https://github.com/user-attachments/assets/45cbab01-4242-41aa-ba15-e7aeab6a377a)

![image](https://github.com/user-attachments/assets/12020ab2-3feb-46ce-ad77-67699314da23)


*Result:*

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.

