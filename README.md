# EX 3 HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**


![tt A](https://github.com/user-attachments/assets/357037d4-c9db-4316-995f-88c6739eb5f7)


![tt B](https://github.com/user-attachments/assets/78c91420-7800-421a-97c3-f2d847fee63f)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**


![halfadder code](https://github.com/user-attachments/assets/adbad201-cc4d-4ee0-8c40-d9850c2ea3d9)


![halfsubtractor code](https://github.com/user-attachments/assets/df2ffecb-96cf-4f47-a1a3-c2e324e57f6e)



**RTL Schematic**

![halfadder diagram](https://github.com/user-attachments/assets/35c1547c-3025-438f-9347-6210b46569ef)


![halfsubtractor diagram](https://github.com/user-attachments/assets/bc133b96-883d-49d4-bf76-8c68f80c1511)


**Output/TIMING Waveform**

![halfadder waveform](https://github.com/user-attachments/assets/979ecae3-b79b-41fd-829c-6572fa130d12)


![halfsubtractor waveform](https://github.com/user-attachments/assets/e7d2c379-90db-4d67-806d-ca6febba1fe8)


**Result:**
Thus, the half adder and half subtractor are studied and the truth table,logic diagram and waveform are verified.
