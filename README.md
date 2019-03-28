# Ahmed Mohamed Soliman
# Sec: 1, B.N: 9 
# Communications-project

## Simulation Environment
These instructions for all the modulation schemes 
- Open MATLAB, then click on "Simulink", then click on "Open".
- Choose the .slx file you want to open. 
- Open MATLAB command window and write "bertool", Open "Monte Carlo" tab, Choose the .slx file.
- Set BER variable name to "BER".
- Set Eb/N0 range to "-10:.5:10" dB.
- Click run.

Note: Scatter plots are produced at a noise level of 10 dB.
## **Binary Phase-Shift Keying Modulation (BPSK)**
### - Definition 
BPSK is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.

### - Schema
![BPSK schema](BPSK.PNG)
### - Scatter Plot (Before Noise)
![BPSK Before Noise](https://github.com/ahmedsoliman11/Communications-project/blob/master/BPSK%20before.jpg)
### - Scatter Plot (After Noise)
![BPSK After Noise](https://github.com/ahmedsoliman11/Communications-project/blob/master/BPSK%20after.jpg)
### - BER Plot
![BPSK BER Diagram](https://github.com/ahmedsoliman11/Communications-project/blob/master/BER%20BPSK.jpg)


## **Quadrature Phase-Shift Keying Modulation (QPSK)**
### - Definition 
QPSK is type of  phase shift keying. Unlike BPSK which is a DSBCS modulation scheme with digital information for the message, QPSK is also a DSBCS modulation scheme but it sends two bits of digital information a time (without the use of another carrier frequency).

### - Schema
![QPSK schema](QPSK.PNG)
### - Scatter Plot (Before Noise)
![QPSK Before Noise](https://github.com/ahmedsoliman11/Communications-project/blob/master/QPSK%20before.jpg)
### - Scatter Plot (After Noise)
![QPSK After Noise](https://github.com/ahmedsoliman11/Communications-project/blob/master/QPSK%20after.jpg)
### - BER Plot
![QPSK BER Diagram](https://github.com/ahmedsoliman11/Communications-project/blob/master/BER%20QPSK.jpg)


## **Frequency Shift Keying (FSK)**
### - Definition 
FSK is the digital modulation technique in which the frequency of the carrier signal varies according to the digital signal changes. FSK is a scheme of frequency modulation. The output of a FSK modulated wave is high in frequency for a binary High input and is low in frequency for a binary Low input. The binary 1s and 0s are called Mark and Space frequencies.

### - Schema
![FSK schema](FSK.PNG)
### - Scatter Plot (Before Noise)
![FSK Before Noise](https://github.com/ahmedsoliman11/Communications-project/blob/master/FSK%20before.jpg)
### - Scatter Plot (After Noise)
![FSK After Noise](https://github.com/ahmedsoliman11/Communications-project/blob/master/FSK%20after.jpg)
### - BER Plot
![FSK BER Diagram](https://github.com/ahmedsoliman11/Communications-project/blob/master/BER%20FSK.jpg)


## **Quadrature Amplitude Modulation (QAM)**
### - Definition
QAM is a modulation scheme that moderates two sinusoidal carriers 90 ° out-of-phase with each other. The components of each carrier are called inphase and quadrature. Both modulated carriers are summed to result in a signal with amplitude and phase modulation. 

### - Schema
* **QAM_16**
![QAM_16 schema](QAM_16.PNG)
### - Scatter Plot (Before Noise)
![QAM_16 Before Noise](https://github.com/ahmedsoliman11/Communications-project/blob/master/QAM_16%20before.jpg)
### - Scatter Plot (After Noise)
![QAM_16 After Noise](https://github.com/ahmedsoliman11/Communications-project/blob/master/QAM_16%20after.jpg)
### - BER Plot
![QAM_16 BER Diagram](https://github.com/ahmedsoliman11/Communications-project/blob/master/BER%20QAM_16.jpg)

* **QAM_64**
![QAM_64 schema](QAM_64.PNG)
### - Scatter Plot (Before Noise)
![QAM_64 Before Noise](https://github.com/ahmedsoliman11/Communications-project/blob/master/QAM_64%20before.jpg)
### - Scatter Plot (After Noise)
![QAM_64 After Noise](https://github.com/ahmedsoliman11/Communications-project/blob/master/QAM_64%20after.jpg)
### - BER Plot
![QAM_64 BER Diagram](https://github.com/ahmedsoliman11/Communications-project/blob/master/BER%20QAM_64.jpg)

