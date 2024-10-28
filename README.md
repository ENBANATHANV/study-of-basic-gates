#### NAME : Enbanathan V
#### REG NO : 24001750
#### EXPERIMENT 1 : Study of logic gates
### AIM:

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

### EQUIPMENT REQUIRED:

Software – Quartus prime 

### THEORY

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

### AND GATE

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

### OR GATE

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

### NOT GATE

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

### NAND GATE

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

### NOR GATE

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

### Ex-OR GATE

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

### Ex-NOR GATE

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

### PROCEDURE

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


### PROGRAM


### module LOGICGATES_1(a,b,notgate,andgate,orgate,nandgate,norgate,xorgate,xnorgate);
### input a,b;
### output notgate,andgate,orgate,nandgate,norgate,xorgate,xnorgate;
### not (notgate,a);
### and (andgate,a,b);
### or (orgate,a,b);
### nand (nandgate,a,b);
### nor (norgate,a,b);
### xor (xorgate,a,b);
### xnor (xnorgate,a,b);
### endmodule


 
### LOGIC GATES & TRUTHTABLE
![Screenshot-2023-07-20-205854](https://github.com/user-attachments/assets/d78b570a-5c9a-4493-aef6-e87a5b4805c0)


### RTL OUTPUT:

![WhatsApp Image 2024-10-28 at 11 24 30 AM](https://github.com/user-attachments/assets/112c9f9f-b706-414e-997b-3e97c62bb1d9)


### OUTPUT WAVEFORM:

![WhatsApp Image 2024-10-28 at 11 24 40 AM](https://github.com/user-attachments/assets/68237c6e-902d-402b-b772-300071566943)

### RESULT:
### 
 study and verify the truth table of logic gates in Quartus II using Verilog programming implemented successfully


