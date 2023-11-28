# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: HARINI R
RegisterNumber:23000779  
*/
Logic symbol & Truthtable
![CODE HA](https://github.com/raja-harini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037372/23ca168d-b630-422e-a392-2cb21894a35e)
![WAVE FORM HA](https://github.com/raja-harini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037372/7cac7da1-2271-4663-8ca8-1fa3bde301f7)
![CODE FA](https://github.com/raja-harini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037372/4a7754f1-faad-423f-b537-e7c1c8840fe7)
![WAVE FORM FA](https://github.com/raja-harini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037372/82f8e8b7-cd6b-490d-81c2-da63897a7855)

RTL realization
![LOGIC DIAGRAM HA](https://github.com/raja-harini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037372/d1c4e39d-d54a-4b58-b24a-b36bd2ab94ab)
![LOGIC DIAGRAM FA](https://github.com/raja-harini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037372/7602face-ef3e-407f-b430-e2857aaae6bc)

### Output:
![TIMING DIAGRAM  HA](https://github.com/raja-harini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037372/cfe372ce-023f-454c-8c06-df6f31803873)
![TIMING DIAGRAM FA](https://github.com/raja-harini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149037372/9983a652-4afa-4451-b616-f6ed2a6c2492)

### RTL
### TIMING DIAGRAM

### TRUTH TABLE 

### Result:
