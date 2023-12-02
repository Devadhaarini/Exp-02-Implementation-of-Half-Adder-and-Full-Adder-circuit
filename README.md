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

#### Figure -01 HALF ADDER 

![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -02 FULL ADDER 

![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.

### Program:

Half Adder: 
![Screenshot 2023-12-02 124808](https://github.com/Devadhaarini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145796552/b1dcb2af-5d52-499c-81a8-b80caedbc071)

Full Adder:
![Screenshot 2023-12-02 124815](https://github.com/Devadhaarini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145796552/a005a81c-3cc6-4b8d-8c44-96dd8b247ddb)


### Truth table:

Half Adder Circuit:
![image](https://github.com/Devadhaarini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145796552/82807561-fd4d-463c-b77d-4d5a77db1c41)

Full Adder Circuit:
![image](https://github.com/Devadhaarini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145796552/fe223a3c-d494-4406-b74b-b45b694c7f2e)


### RTL Realisation 

Half Adder Circuit:
![image](https://github.com/Devadhaarini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145796552/54ee96d6-f712-4272-b480-305ba3fd420c)

Full Adder Circuit:
![image](https://github.com/Devadhaarini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145796552/17f7e541-1665-4ca2-af48-60fd9ef6c621)

### TIMING DIAGRAM

Half Adder Circuit:
![image](https://github.com/Devadhaarini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145796552/cf050b56-4436-44c4-a3f9-1f4d81abfbb8)

Full Adder Circuit:
![image](https://github.com/Devadhaarini/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145796552/c44e57b3-17f6-4501-8ea4-827048c5aab4)


### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
