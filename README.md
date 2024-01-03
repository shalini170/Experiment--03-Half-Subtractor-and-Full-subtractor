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

![Screenshot 2024-01-03 025323](https://github.com/shalini170/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151901983/1007301e-194d-4df4-9274-d789db2f0847)


![Screenshot 2024-01-03 025332](https://github.com/shalini170/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151901983/083d61b7-860c-4a06-8e41-18b8df38acbd)



Developed by: shalini venkatesulu
RegisterNumber:23001992  
*/


## Truthtable

![Screenshot 2024-01-03 025340](https://github.com/shalini170/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151901983/5edac855-25c1-43d8-b044-ac37399437c5)



![Screenshot 2024-01-03 025347](https://github.com/shalini170/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151901983/70b5c564-bb9d-42f3-88ce-5dd3b68a0f62)






##  RTL 


![Screenshot 2024-01-03 025354](https://github.com/shalini170/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151901983/0d21edda-14e3-46db-8e03-f32fc9789770)


![Screenshot 2024-01-03 025403](https://github.com/shalini170/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151901983/45a737c6-0dff-4fe5-be56-a59e801dfccd)




## output

![Screenshot 2024-01-03 025411](https://github.com/shalini170/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151901983/2f6d8207-076b-4c4d-91d7-0e7de2a58a1e)


![Screenshot 2024-01-03 025421](https://github.com/shalini170/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151901983/149c527d-4090-4279-b79e-6f75a8aa8fba)




## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
