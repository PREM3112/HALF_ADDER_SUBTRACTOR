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

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

## Developed by:PREM.R 
## RegisterNumber:212223240124
HALF ADDER:
![Screenshot 2024-04-01 184914](https://github.com/PREM3112/HALF_ADDER_SUBTRACTOR/assets/145449383/b2c39ec0-14c0-466a-8312-7e552402fa25)
HALF SUBRACTOR:
![Screenshot 2024-04-01 184927](https://github.com/PREM3112/HALF_ADDER_SUBTRACTOR/assets/145449383/2087cd4d-d563-455d-a91a-11d3e7ad4855)



**RTL Schematic**
HALF ADDER:
![Screenshot 2024-04-01 184942](https://github.com/PREM3112/HALF_ADDER_SUBTRACTOR/assets/145449383/683b74f3-3798-420c-8834-7f44a6e2b19f)
HALF SUBRACTOR:
![Screenshot 2024-04-01 184953](https://github.com/PREM3112/HALF_ADDER_SUBTRACTOR/assets/145449383/ddfd6da5-9edc-479d-ba41-846dd32b96e1)



**Output/TIMING Waveform**
![Screenshot 2024-04-01 185008](https://github.com/PREM3112/HALF_ADDER_SUBTRACTOR/assets/145449383/9867930b-ebeb-44fb-93f2-34853a357954)
![Screenshot 2024-04-01 185019](https://github.com/PREM3112/HALF_ADDER_SUBTRACTOR/assets/145449383/63a9e198-68bc-4543-b793-82854e472e4e)




**Result:**
