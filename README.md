# HALF_ADDER_SUBTRACTOR

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


  ![image](https://github.com/user-attachments/assets/b95bb4e9-facc-4107-b06f-7502a6156f41)


**Procedure**

![image](https://github.com/user-attachments/assets/2940f1b2-9365-4fca-9065-e311e811e980)


5. Different input combination generate the timing diagram


**Program:** 



![image](https://github.com/user-attachments/assets/73927f42-80dd-47c1-b909-089df24e1679)

Developed by : priyesh.S 


RegisterNumber:24008184
 
**RTL Schematic**

![image](https://github.com/user-attachments/assets/9c103235-4383-4c63-bdbf-54bd36de1e97)


![image](https://github.com/user-attachments/assets/c17e4826-d248-4901-a3b9-6c01200e93b1)


**Output/TIMING Waveform**
![image](https://github.com/user-attachments/assets/3ab0cdb7-c9b9-485a-9fcb-dde2dfed79d4)


**Result:**

The Half adder and Half subtractor are designed and their truth table is verified
