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



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/

## Output:
![hal sub pro - Copy](https://github.com/praveen2p/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151658061/523ceedb-b5d0-41a3-a247-9f4ae4a3dbaf)
![ful sub pro](https://github.com/praveen2p/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151658061/65c0f050-27c5-4f4f-aeb8-cd29a4688669)

## Truthtable
![TT SUB HAL](https://github.com/praveen2p/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151658061/6833c9c8-bb0b-4421-a758-7ba8f23c3995)

![TT SUB FULL](https://github.com/praveen2p/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151658061/e83f3eb8-0f70-4918-8d55-5212bf80f337)



##  RTL realization
![RTL SUB HAL](https://github.com/praveen2p/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151658061/4837750e-98df-4a65-b72e-040b7a226a96)
![RTL FULL SUB](https://github.com/praveen2p/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151658061/7a1867d9-90fb-4d27-b2e1-9fa5aae74619)


## Timing diagram 
![TIME SUB HAL](https://github.com/praveen2p/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151658061/4e96abc5-cc5b-4d48-8050-dc363bca6e2a)

![TT SUB FULL](https://github.com/praveen2p/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151658061/695304bb-0a37-4f7e-8226-94a3600fda6b)



## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
