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
![Screenshot 2023-11-26 141707](https://github.com/NagalapuramHasif/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365567/9ba03b0f-6315-4225-af7a-67623c6e0688)


#### Figure -01 HALF ADDER 
![Screenshot 2023-11-26 142950](https://github.com/NagalapuramHasif/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365567/e3f57fcb-2e9a-43ba-852f-33c2ec9f02d6)



#### Figure -02 FULL ADDER 

### Procedure
![Screenshot 2023-11-26 144617](https://github.com/NagalapuramHasif/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365567/bada1d20-cd86-41b5-a247-f76ea33ccbb2)

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*![Screenshot 2023-11-26 144724](https://github.com/NagalapuramHasif/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365567/d1ff4835-334f-433f-adea-703f90c7e03c)

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL
### TIMING DIAGRAM
![Screenshot 2023-11-26 142029](https://github.com/NagalapuramHasif/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365567/9240dc4f-731a-47cd-9990-148de3c98ee8)

![Screenshot 2023-11-26 142848](https://github.com/NagalapuramHasif/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365567/095d4e3f-bb59-432a-8d98-d95813034913)

### TRUTH TABLE 

![OIP](https://github.com/NagalapuramHasif/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365567/96254bf3-e429-4782-b908-502322a89242)

![OIP](https://github.com/NagalapuramHasif/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149365567/0b39854a-d021-4979-9138-ca91c1a578e6)




### Result:
