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
## Half Adder:
![Screenshot 2023-11-21 212625](https://github.com/bhuvan8903/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151444524/4976455d-557a-48f7-a52f-d80b48c90be7)

## Full Adder:
![Screenshot 2023-11-21 212632](https://github.com/bhuvan8903/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151444524/13de31d4-e929-4b8b-a1e3-6d1d1a5591ed)

### RTL:
## Half Adder:
![Screenshot 2023-11-21 212659](https://github.com/bhuvan8903/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151444524/4d74ff6a-e599-441b-b669-e297d1db72d0)

## Full Adder:
![Screenshot 2023-11-21 212712](https://github.com/bhuvan8903/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151444524/c30eb278-f9d6-449a-8e46-08a10157d4ed)

### TIMING DIAGRAM:
## Half Adder:
![Screenshot 2023-11-21 212722](https://github.com/bhuvan8903/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151444524/f61a43f8-8bdd-4583-9f9c-633c7daafdaf)

## Full Adder:
![Screenshot 2023-11-21 212728](https://github.com/bhuvan8903/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151444524/b18a34b4-10e0-4df6-aa94-85e28ce7c9bb)

### TRUTH TABLE :
## Half Adder:
![Screenshot 2023-11-21 212643](https://github.com/bhuvan8903/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151444524/292d3770-0a1f-4e62-b0d5-d1ea4420c485)

## Full Adder:
![Screenshot 2023-11-21 212650](https://github.com/bhuvan8903/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151444524/0b1c3ae0-1955-48fc-9eac-64f6d4c3f93a)

### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
