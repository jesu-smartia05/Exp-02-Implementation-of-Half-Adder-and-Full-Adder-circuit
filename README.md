# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

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
# Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: JESU SMARTIA A
RegisterNumber: 212223110016

1.Program to design a half adder:

![image](https://github.com/jesu-smartia05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514819/13f562d8-bee6-475e-8ba2-0fe05f4499f3)


2.Program to design a full adder:

![image](https://github.com/jesu-smartia05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514819/e872b03f-7235-4bc2-8447-db4106ad1d99)

*/
# Output:
### RTL Realisation:
#### HALF ADDER

![image](https://github.com/jesu-smartia05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514819/6b0cd5da-65ed-46de-8fde-3c5ef3e20f9b)

#### FULL ADDER

![image](https://github.com/jesu-smartia05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514819/5ff5b03b-c4e1-48d8-9147-702b8061a36d)

### TIMING DIAGRAM
#### HALF ADDER

![image](https://github.com/jesu-smartia05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514819/019a8238-1fe8-4c48-a142-ab08d990acf1)

#### FULL ADDER

![image](https://github.com/jesu-smartia05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514819/f47349fe-098e-42ae-928a-6433af60f83b)


### TRUTH TABLE 
#### HALF ADDER
![image](https://github.com/jesu-smartia05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514819/b677e24d-943c-40ed-aed4-787812d82599)

#### FULL ADDER
![image](https://github.com/jesu-smartia05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148514819/4d76f935-215c-4ec5-b52e-53873db1789f)

### Result:
Thus the half adder and full adder circuit are designed and the truth table for half adder and full adder are verified.
