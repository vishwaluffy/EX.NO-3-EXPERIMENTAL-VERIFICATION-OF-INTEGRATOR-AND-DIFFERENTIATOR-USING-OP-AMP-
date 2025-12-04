3. ##**EX.NO:
** 3  EXPERIMENTAL VERIFICATION OF INTEGRATOR AND DIFFERENTIATOR USING OP-AMP 
            
**DATE:**  
             3A INTEGRATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
INTEGRATOR
A circuit in which the output voltage waveform is the integral of the input voltage waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier configuration if the feedback resistor Rf is replaced by a capacitor Cf . The expression for the output voltage is given as,
Vo = - (1/Rf C1 ) ∫ Vi dt

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger than or equal to Rf Cf . That is,
T ≥ Rf Cf

The integrator is most commonly used in analog computers and ADC and signal-wave shaping circuits.
CIRCUIT DIAGRAM
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-30 at 16 54 40_2eb5add0](https://github.com/user-attachments/assets/a30729fc-fa3f-42ea-8a31-f1f1830c5d32)


## MODEL GRAPH
<img width="556" height="380" alt="image" src="https://github.com/user-attachments/assets/caa7461c-69f7-4636-8e31-eea6db6efbb5" />

<img width="847" height="553" alt="image" src="https://github.com/user-attachments/assets/d8d3e586-8e58-47ba-baae-2794c7955d51" />

---

## DESIGN

![WhatsApp Image 2025-12-04 at 11 03 03_89726d9e](https://github.com/user-attachments/assets/a6f8fc26-445a-4746-b31e-2d61b824449a)
 	
![WhatsApp Image 2025-12-04 at 11 38 33_08d9d426](https://github.com/user-attachments/assets/04728acf-5c3d-4461-ae88-bc0c6b835838)

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.


## TABULATION
![WhatsApp Image 2025-11-30 at 16 55 28_12088e97](https://github.com/user-attachments/assets/7fd5c143-9890-4ae6-a4bc-a1d5dfb85068)

		

---

![WhatsApp Image 2025-11-30 at 16 56 24_64e9fd99](https://github.com/user-attachments/assets/1c813445-59a4-4d99-ab7d-c569f95a7955)

---
**DATE:**  
             3 B DIFFERENTIATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,
Vo = - Rf C1 ( dVi /dt )

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:
1.	Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 µF, calculate the value of Rf.
2.	Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.

The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-30 at 16 57 20_8a5f4014](https://github.com/user-attachments/assets/d145ba7e-e267-458f-8072-2d9c9484aade)



## MODEL GRAPH

(i)	 SINE WAVE INPUT

<img width="687" height="479" alt="image" src="https://github.com/user-attachments/assets/c89226c0-c2bb-4544-b355-27fc0d923f1a" />
---

AND

(ii) SQUARE WAVE INPUT

![Uploading WhatsApp Image 2025-11-30 at 16.57.35_085be7ac.jpg…]()


---

## DESIGN

![WhatsApp Image 2025-12-04 at 11 37 55_17129c17](https://github.com/user-attachments/assets/3b82e514-4d70-449a-af6d-8688b4856b46)

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.

 ## TABULATION
![WhatsApp Image 2025-11-30 at 16 57 35_37401001](https://github.com/user-attachments/assets/f8ba07c2-7363-405e-813d-75a1a3b3c2fc)
	

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-30 at 16 58 00_d6da268f](https://github.com/user-attachments/assets/5c17f52a-84ec-4cca-8a5d-a7d041e3682b)

---

RESULT:
Thus an Integrator and Differentiator using op-amp are designed and their performance was successfully tested using op-amp IC 741.
---



