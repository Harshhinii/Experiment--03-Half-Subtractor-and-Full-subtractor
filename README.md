# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure

1.Connect the supply (+5V) to the circuit.

2.Switch ON the main switch.

3.If the output is 1, then the led glows.

## Program:

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by : HARSHINI R

Register Number : 23002309

Code :

Full Subtractor : 

![Exp4 fs code](https://github.com/Harshhinii/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148633023/5e33b00a-7eda-4c55-b986-fa8b18e0bf4a)

Full Subtractor : 

![Exp4 hs code](https://github.com/Harshhinii/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148633023/3ea2cab2-8576-4da2-9e8e-e475990a8eab)

Truth Table :

Full Subtractor : 

![Exp4 truthtable fs](https://github.com/Harshhinii/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148633023/3afcfe9a-ecc6-4f56-89d8-5a10b151aef2)

Half Subtractor : 

![Exp4 truthtable hs](https://github.com/Harshhinii/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148633023/650c93ea-b54c-4968-ac5e-37bc5636692b)

RTL realization : 

Full Subtractor : 

![Exp4 fs RTL diagram](https://github.com/Harshhinii/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148633023/eb4310ac-58ef-4946-ba9b-8f2858066f11)

Half Subtractor : 

![Exp4 hs RTL diagram](https://github.com/Harshhinii/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148633023/339438eb-b02d-4f1e-88e1-c9f13878358a)

## Output :

Full Subtractor : 

![267701298-5ea55e95-6c55-44f9-a5f8-938858e6876f](https://github.com/Harshhinii/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148633023/9b0abaf2-5725-4053-be1f-9e6b2cb6e4ae)

Half Subtractor : 

![267701235-9a4af079-d35e-43e5-8690-9d390d041fb6](https://github.com/Harshhinii/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148633023/c6dfd947-fec8-451e-bdea-64ad928dad2d)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
