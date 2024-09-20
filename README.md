# STUDY OF BASIC GATES

##### Developed by: Oswald Shilo
##### Reg No: 212223040139


## **AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

## **Equipments Required:**

Software – Quartus prime 

## **Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

## **AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

## **OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

## **NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

## **NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

## **NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

## **Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

## **Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

## **Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## **PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming:-

```
verilog
module Logic_gates(a, b, andgate, orgate, notgate, nandgate, norgate, xorgate, xnorgate);
input a, b;
output andgate, orgate, notgate, nandgate, norgate, xorgate, xnorgate;
and(andgate, a, b);
or(orgate, a, b);
not(notgate, a);
nand(nandgate, a, b);
nor(norgate, a, b);
xor(xorgate, a, b);
xnor(xnorgate, a, b);
endmodule
```


## **Timing Waveform:** 
![image](https://github.com/user-attachments/assets/007aadd9-e840-4a0e-970f-1a9e0556dd3d)



## **RTL:**

![image](https://github.com/user-attachments/assets/93a90a37-4333-4d1b-bbdb-e7f06afbb309)

## **Truth Table:**

### **AND Gate**:
![image](https://github.com/user-attachments/assets/73aaae51-c790-493e-9825-8191e4806101)

### **OR Gate**:
![image](https://github.com/user-attachments/assets/35f7c24e-52a0-4e13-ad7f-d827585e5338)

### **NOT Gate**:
![image](https://github.com/user-attachments/assets/c505ae07-00a4-4d17-9c0b-ddd94cafd3af)

### **NAND Gate**:
![image](https://github.com/user-attachments/assets/204211b9-01af-493e-a821-bec1e5dd8023)

### **NOR Gate**:
![image](https://github.com/user-attachments/assets/345f197b-9337-4f0e-9fc6-bfaa31c63c03)

### **XOR Gate**:
![image](https://github.com/user-attachments/assets/09247821-093f-4fb6-9c6d-ca3fe7863341)

### **XNOR Gate**:
![image](https://github.com/user-attachments/assets/6294b063-19d3-4e95-a07c-1ca94c036194)


## **Result:**
The program is verified successfully using the software quartus prime.


