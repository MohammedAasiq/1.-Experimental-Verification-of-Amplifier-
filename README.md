**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS

---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 100K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM

![IMG-20251204-WA0021 1](https://github.com/user-attachments/assets/13a5b941-b44a-4528-9a7f-39b696a69517)


CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![IMG-20251204-WA0021 1](https://github.com/user-attachments/assets/85f2da5f-ffde-4d28-9efa-5533c97db890)


MODEL GRAPH 

![IMG-20251204-WA0022 1](https://github.com/user-attachments/assets/795e134f-52cd-4bfb-a0ff-359c4ed62fd0)



DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 10kΩ, Rf=100kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

| S.No | Vin (V) | Time (ms) | Theoretical | Practical |
|------|----------|-----------|--------------|------------|
| 1 |300 mv | 1|-3|-3|
| 2 |400 mv | 1|-4|-4.08|
| 3 |500 mv | 1|-5|-5.28|		
 


---
## OUT PUT WAVEFORM AND DISCUSSION 


![IMG-20251204-WA0009 1](https://github.com/user-attachments/assets/0d94f04f-8c57-4d37-9bab-8e0c7b51698a)




![IMG-20251204-WA0010 1](https://github.com/user-attachments/assets/8dcc8850-493b-4756-8a24-3edd6b513265)








---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1



## CIRCUIT DIAGRAM



![IMG-20251204-WA0022 1](https://github.com/user-attachments/assets/5929eee2-8455-45a5-826e-7ec739d3a339)

---

## MODEL GRAPH


![IMG-20251204-WA0023 1](https://github.com/user-attachments/assets/bfb0f144-589d-4289-b909-89aa367c5630)


---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

| S.No | Vin (V) | Time (ms) | Theoretical | Practical |
|------|----------|-----------|--------------|------------|
| 1 |300mv |1ms | 3.3 |3.25 |
| 2 | 400mv|1ms | 4.4|4.1 |
| 3 |500mv |1ms | 5.5| 0.4|

---
## OUT PUT WAVEFORM AND DISCUSSION 

![IMG-20251204-WA0011 1](https://github.com/user-attachments/assets/670e1326-e789-4ae5-9a11-a8364e1beae4)





![IMG-20251204-WA0012 2](https://github.com/user-attachments/assets/d79a5265-ea88-40ef-8e85-2e38d520340b)







---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM

![IMG-20251204-WA0023 1](https://github.com/user-attachments/assets/cb66f05c-b5dc-4953-94dc-3292d2af579e)


## MODEL GRAPH

![IMG-20251204-WA0024 1](https://github.com/user-attachments/assets/815f8d3e-dd45-4303-aa96-7d50e4a99e27)



---

## DESIGN
vo=(-Rf/R1)(v1-v2)volts
v1=0.5
v2=1
Rf=100
Ri=10

### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 10kOhm, Rf = 100kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

| S.No | V1 (V) | V2 (V)| Theoretical | Practical |
|------|---------|---------|--------------|------------|
| 1 |0.5 | 1| 0.5 |0.48 |
| 2 | 0.5| 1.5|  1.0| 0.10|
| 3 | 0.5| 2| 1.5 |0.10 |

---
## OUT PUT WAVEFORM AND DISCUSSION 


![IMG-20251204-WA0013 1](https://github.com/user-attachments/assets/2f8c545b-8a97-4bee-bc15-3f57a6d5b1d6)



---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER


![IMG-20251204-WA0037 1](https://github.com/user-attachments/assets/4a5a5b4d-a9ed-49fa-a25f-d39786e75162)



PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)

| S.No | V1 (V) | V2 (V)| Theoretical | Practical |
|------|---------|---------|--------------|------------|
| 1 |1.5 | 2.0| -2.7 |-2.80 |
| 2 |2.0 | 3.0| 5.4 | 8.58|
| 3 | 2.5| 3.5| 8.4 |5.52 |

---
## OUT PUT WAVEFORM AND DISCUSSION 


![IMG-20251204-WA0019 1](https://github.com/user-attachments/assets/ca8229f6-3c26-494a-8af6-1de145097cb8)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.
