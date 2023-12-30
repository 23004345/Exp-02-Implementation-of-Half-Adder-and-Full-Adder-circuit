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

HALF ADDER:



![Exp3 ha code](https://github.com/23004345/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138849203/d0375291-b9a6-4424-9391-0a0789ac279e)


FULL ADDER:

![Exp3 fa code](https://github.com/23004345/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138849203/87531b36-3052-4947-949a-718796c5de83)



OUTPUT:

/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: DEVESH.S
RegisterNumber:  23004345
*/




### RTL
HALF ADDER:



![Exp3 ha RTL diagram](https://github.com/23004345/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138849203/c8873a5d-8fc5-4068-a2bd-bab4af0bb9b4)


FULL ADDER:



![Exp3 fa RTL diagram](https://github.com/23004345/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138849203/2fe48dea-8d79-4664-9570-b37e702d1087)





### TIMING DIAGRAM


HALF ADDER:



![exp3 ha wave](https://github.com/23004345/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138849203/caad081c-611f-429d-98a6-d952ea9de5b2)



FULL ADDER:



![exp 3 fa wave](https://github.com/23004345/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138849203/1a3ad49f-f64d-4ad6-a57a-187b02a3aa6a)


### TRUTH TABLE 

HALF ADDER:



![Exp3 truthtable (ha)](https://github.com/23004345/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138849203/7f6f206f-40e8-4a10-930a-a1cc20aff6a8)



FULL ADDER:



![Exp3 truthtable (fa)](https://github.com/23004345/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/138849203/6b84b583-34d9-4ec5-b5ac-13ad209e42af)



### Result:





Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus
using Verilog programming
