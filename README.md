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

**Truthtable**
## FULL ADDER:
![Screenshot 2024-04-04 102054](https://github.com/Dharanya2005/FULL_ADDER_SUBTRACTOR/assets/145742468/012e4ca9-a78c-42d7-a5fc-65fa47ee5f1b)
## FULL SUBRACTOR:
![Screenshot 2024-04-04 111811](https://github.com/Dharanya2005/FULL_ADDER_SUBTRACTOR/assets/145742468/5c3d5d64-ef80-4854-b3d7-b61c9534993c)

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
Developed by:DHARANYA.N
RegisterNumber:212223230044
*/
## FULL ADDER:
![Screenshot 2024-04-04 102238](https://github.com/Dharanya2005/FULL_ADDER_SUBTRACTOR/assets/145742468/d7149c8e-6bc2-4a4f-a8a7-5b463934edef)
## FULL SUBRACTOR:
![Screenshot 2024-04-04 113758](https://github.com/Dharanya2005/FULL_ADDER_SUBTRACTOR/assets/145742468/3b09b17a-6f81-411a-a252-bee1a75af6e2)

**RTL Schematic**
## FULL ADDER:
![Screenshot 2024-04-04 094103](https://github.com/Dharanya2005/FULL_ADDER_SUBTRACTOR/assets/145742468/33937e74-f28a-41a7-b16a-093c21ba6db8)

## FULL SUBRACTOR:
![Screenshot 2024-04-04 113629](https://github.com/Dharanya2005/FULL_ADDER_SUBTRACTOR/assets/145742468/480d4aa1-2c25-44b4-8b5c-919dbcff3741)


**Output Timing Waveform**
## FULL ADDER:
![Screenshot 2024-04-04 094653](https://github.com/Dharanya2005/FULL_ADDER_SUBTRACTOR/assets/145742468/2ce85ea4-fc53-4430-96ac-b310d820fdd1)

## FULL SUBRACTOR:
![Screenshot 2024-04-04 124522](https://github.com/Dharanya2005/FULL_ADDER_SUBTRACTOR/assets/145742468/b9a56b8d-dd75-45c1-83f0-c6d4fc8d6abc)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



