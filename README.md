**NAME:**
S ABISHEK

**REG NO:**
24900833

**EXPERIMENT NO 4:** IMPLEMENTATION OF FULL ADDER AND FULL SUBTRACTOR

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full ADDER**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)



**Full SUBTRACTOR**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**TRUTH TABLE**

**FULL ADDER:**

![image](https://github.com/user-attachments/assets/f4f4d096-4ee2-445f-88d2-7d96cecf1131)



**FULL SUBTRACTOR:**

![image](https://github.com/user-attachments/assets/2c53fa00-f0a4-43dc-929c-909ce1dedc8d)





**PROGRAM:**

![image](https://github.com/user-attachments/assets/7db5b3b5-9ffe-4941-9fc4-7c7fd5d07598)



**RTL VIEWER:**

![image](https://github.com/user-attachments/assets/6c99b400-6ded-46dd-99c1-ca0e96cfef1d)


**OUTPUT TIMING WAVEFORM:**

![image](https://github.com/user-attachments/assets/75b28e79-475a-4dcc-aa50-44db1ff942a7)

**RESULT:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



