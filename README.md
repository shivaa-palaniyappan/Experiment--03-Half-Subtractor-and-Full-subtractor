# Experiment--04-Half-Subtractor-and-Full-subtractor
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

## Procedure :

STEP 1: Use module project name(input,output) to start the Verilog programmming.
STEP 2: Assign inputs and outputs using the word input and output respectively.
STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean
expression.
STEP 4: Use each output to represnt onre for differnce and the other for borrow.
STEP 5: End the verilog program using keyword endmodule.

## Program:

Developed by: SHIVAA PALANIYAPPAN V
RegisterNumber:  23007210
## CODE :
## HALF SUBRACTOR :
![Exp4 hs code](https://github.com/shivaa-palaniyappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/146915611/84f367f5-2b3d-4877-b0dc-be41d6e12200)

## FULL SUBRACTOR :
![Exp4 fs code](https://github.com/shivaa-palaniyappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/146915611/02425345-98fa-42a2-b4b6-dd0193b43765)

## Output:

## Truthtable ;
## HALF SUBRACTOR:
![Exp4 truthtable hs](https://github.com/shivaa-palaniyappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/146915611/8d65bf21-5ef4-4f50-b4d5-d30e3b828fb0)
## FULL SUBRACTOR :
![Exp4 truthtable fs](https://github.com/shivaa-palaniyappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/146915611/419de08d-c579-496c-8f5d-4da9e28e8b7e)

##  RTL :
## HALF SUBRACTOR :
![Exp4 hs RTL diagram](https://github.com/shivaa-palaniyappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/146915611/40a35303-e638-46d6-82be-db92fa436fe4)

## FULL SUBRACTOR:
![Exp4 fs RTL diagram](https://github.com/shivaa-palaniyappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/146915611/10042bb3-8aa3-4a3e-bb90-f6b80c732369)

## Timing diagram :

## HALF SUBRACTOR :
![hs wave](https://github.com/shivaa-palaniyappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/146915611/ca1383a3-a8ce-4345-96b0-403fdf908b77)
## FULL SUBRACTOR :
![fs wave](https://github.com/shivaa-palaniyappan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/146915611/1f77ae7c-73a5-49e9-a7a7-fe70e4fd76ac)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
