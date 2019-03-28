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
BPSK is modulation scheme makes the phase of the output signal gets shifted depending upon the input. It works on binary inputs, thus the output phase different is 180 degree.

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
QPSK is modulation scheme makes the phase of the output signal gets shifted depending upon the input. Exactly like BPSK but the input is 2-bits (4 values), thus the output phase will be shifted (0, 90, 180, or 270) degree.

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
FSK is modulation scheme makes the frequency of the output signal will be either high or low, depending upon the input data applied. The simplest FSK is binary FSK which I used here.

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
QAM is modulation scheme makes the output signal get both ampltiude and phase shifting into a single channel, thereby it uses the bandwidth efficiently. It especially in wireless applications. Depending on number of symbols, another phases and amplitudes appear/disappear. 

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
### - Transmitter Scatter Plots (Before Noise)
![QAM_64 Before Noise](https://github.com/ahmedsoliman11/Communications-project/blob/master/QAM_64%20before.jpg)
### - Receiver Scatter Plots (After Noise)
![QAM_64 After Noise](https://github.com/ahmedsoliman11/Communications-project/blob/master/QAM_64%20after.jpg)
### - BER Plot
![QAM_64 BER Diagram](https://github.com/ahmedsoliman11/Communications-project/blob/master/BER%20QAM_64.jpg)

