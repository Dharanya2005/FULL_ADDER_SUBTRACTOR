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
## FULL ADDER
![Screenshot 2024-04-04 102054](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/145742468/cf0d9c37-8aa7-4478-b7f7-bdfef1f8eda1)
## FULL SUBRACTOR
![Screenshot 2024-04-04 111811](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/145742468/c6414db4-63c1-4f9e-b094-e372a920bf17)

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
``
Developed by: DHARANYA.N
RegisterNumber:212223230044
``
*/

## FULL ADDER
![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/145742468/75191b74-b779-4660-84c1-6ecbb1050648)
## FULL SUBRACTOR
![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/145742468/f8cdfd4b-420a-4af2-b0e1-e93472615b0f)

**RTL Schematic**
## FULL ADDER:
![Screenshot 2024-04-04 094103](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/145742468/aae74abf-488c-4475-849a-ca48c5b62204)
## FULL SUBRACTOR:
![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/145742468/7e4591b4-e7c0-499c-a3c5-0db9c546ed55)


**Output Timing Waveform**
## FULL ADDER:
![Screenshot 2024-04-04 094653](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/145742468/e32e9366-7c7a-4a6e-b006-e3482d6e343b)
## FULL SUBRACTOR:
![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/145742468/38367d44-8ce6-4da6-b557-bb0243970585)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



