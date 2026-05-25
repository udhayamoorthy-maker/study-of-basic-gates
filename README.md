### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**
```

module dnew1(a, b, c, d, e, x, y, z);
input a, b;
output c, d, e, x, y, z;
and (c, a, b);
or (d, a, b);
xor (e, a, b);
nand (x, a, b);
nor (y, a, b);
xnor (z, a, b);
endmodule
```

 Developed by:Udhayamoorthy A RegisterNumber: 212225040477
 
**Logic symbol & Truthtable**

<img width="1000" height="595" alt="595955829-1f3bfca1-c1b4-4ea8-afc8-a7234f6a9c1f" src="https://github.com/user-attachments/assets/ad232a37-b3bc-427f-9d71-25beae01e526" />


**RTL realization Output:** 
<img width="685" height="860" alt="image" src="https://github.com/user-attachments/assets/0dc9ec09-9432-4ea0-894f-1df74cc7529d" />


**RTL**
<img width="1376" height="460" alt="595956004-549d13fd-f54c-405a-a468-125d7a42497a" src="https://github.com/user-attachments/assets/6bba8207-d6d4-449f-b9a5-47bb267a4925" />

**Result:**

Thus the truth table of logic gates in Quartus II using Verilog programming is studied and verified successfully
