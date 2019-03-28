# Digital Communication Project
<p><b>Name: Ehab Rabie Amin<br>
Section: 1<br>
BN.:    14</b></p>
<hr>

## A) Binary Phase Shift Keying Modulation - BPSK
### = Definition:
<p>Binary Phase Shift Keying (BPSK) is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0 for binary 1 and θ=180 for binary 0.<br>
The channel used is an additive white gaussian noise (AWGN).</p> 

### = Reproducing Figures Steps:
<b>1. Random Integer Generator</b>
* Initial seed = 37
* Sample time = 0.1s
* Samples per frame = 100
* Number of bits = 2 bits
  
<b>2. AWGN Channel</b>
* Initial seed = 67
* Number of bits per symbol = 1
* Input signal power = 1
* Symbol period = 1s
* Simulation time = 1000s
  
<b>3. BER Diagram Range=[-10:0.5:10]</b>

<b>4. Modulation Type=PSK</b>
<b>4. Modulation Order=2</b>

### = Block diagram:
![](/BPSK/BPSK.png)
### = Modulated message before adding noise:
![](/BPSK/BPSK_Before_noise.png)
### = Modulated message after adding noise:
![](/BPSK/BPSK_After_noise.png)
### = Bit error rate diagram:
![](/BPSK/BER_BPSK.png)
#
## B) Quadrature Phase Shift Keying Modulation - QPSK
### = Definition:
The Quadrature Phase Shift Keying (QPSK) is a variation of BPSK, and it is also a Double Side Band Suppressed Carrier (DSBSC) modulation scheme, which sends two bits of digital information at a time, called as bigits.
<br>
Instead of the conversion of digital bits into a series of digital stream, it converts them into bit pairs. This decreases the data bit rate to half, which allows space for the other users.<br>
The channel used is an additive white gaussian noise (AWGN).

### = Reproducing Figures Steps:
<b>1. Random Integer Generator</b>
* Initial seed = 37
* Sample time = 0.1s
* Samples per frame = 100
* Number of bits = 4 bits
  
<b>2. AWGN Channel</b>
* Initial seed = 67
* Number of bits per symbol = 1
* Input signal power = 1
* Symbol period = 1s
* Simulation time = 1000s
  
<b>3. BER Diagram Range=[-10:0.5:10]</b>

<b>4. Modulation Type=OQPSK</b>
<b>4. Modulation Order=4</b>

### = Block diagram:
![](/QPSK/QPSK.png)
### = Modulated message before adding noise:
![](/QPSK/QPSK_Before_noise.png)
### = Modulated message after adding noise:
![](/QPSK/QPSK_After_noise.png)
### = Bit error rate diagram:
![](/QPSK/BER_QPSK.png)
#
## C) Frequency Shift Keying Modulation - FSK
### = Definition:
Frequency Shift Keying (FSK) is the digital modulation technique in which the frequency of the carrier signal varies according to the digital signal changes. FSK is a scheme of frequency modulation.<br>
The output of a FSK modulated wave is high in frequency for a binary High input and is low in frequency for a binary Low input. The binary 1s and 0s are called Mark and Space frequencies.<br>
The channel used is an additive white gaussian noise (AWGN).

### = Reproducing Figures Steps:
<b>1. Random Integer Generator</b>
* Initial seed = 37
* Sample time = 0.1s
* Samples per frame = 100
* Number of bits = 8 bits
  
<b>2. AWGN Channel</b>
* Initial seed = 67
* Number of bits per symbol = 1
* Input signal power = 1
* Symbol period = 1s
* Simulation time = 1000s
  
<b>3. BER Diagram Range=[-10:0.5:10]</b>

<b>4. Modulation Type=OFSK</b>
<b>4. Modulation Order=8</b>

### = Block diagram:
![](/FSK/FSK.png)
### = Modulated message before adding noise:
![](/FSK/FSK_Before_noise.png)
### = Modulated message after adding noise:
![](/FSK/FSK_After_noise.png)
### = Bit error rate diagram:
![](/FSK/BER_FSK.png)
#
## D) Quadrature Amplitude Modulation:
### = Definition:
The Quadrature Phase Shift Keying (QPSK) is a variation of BPSK, and it is also a Double Side Band Suppressed Carrier (DSBSC) modulation scheme, which sends two bits of digital information at a time, called as bigits.
<br>
Instead of the conversion of digital bits into a series of digital stream, it converts them into bit pairs. This decreases the data bit rate to half, which allows space for the other users.<br>
The channel used is an additive white gaussian noise (AWGN).
## D.1) 16QAM:
<b>1. Random Integer Generator</b>
* Initial seed = 37
* Sample time = 0.1s
* Samples per frame = 100
* Number of bits = 16 bits
  
<b>2. AWGN Channel</b>
* Initial seed = 67
* Number of bits per symbol = 1
* Input signal power = 1
* Symbol period = 1s
* Simulation time = 1000s
  
<b>3. BER Diagram Range=[-10:0.5:10]</b>

<b>4. Modulation Type=QAM</b>
<b>4. Modulation Order=16</b>

### = Block diagram:
![](/QAM/QAM_16.png)
### = Modulated message before adding noise:
![](/QAM/QAM_16_before_noise.png)
### = Modulated message after adding noise:
![](/QAM/QAM_16_after_noise.png)
### = Bit error rate diagram:
![](/QAM/BER_QAM_16.png)
## D.2) 64QAM:
<b>1. Random Integer Generator</b>
* Initial seed = 37
* Sample time = 0.1s
* Samples per frame = 100
* Number of bits = 64 bits
  
<b>2. AWGN Channel</b>
* Initial seed = 67
* Number of bits per symbol = 1
* Input signal power = 1
* Symbol period = 1s
* Simulation time = 1000s
  
<b>3. BER Diagram Range=[-10:0.5:10]</b>

<b>4. Modulation Type=QAM</b>
<b>4. Modulation Order=64</b>

### = Block diagram:
![](/QAM/QAM_64.png)
### = Modulated message before adding noise:
![](/QAM/QAM_64_before_noise.png)
### = Modulated message after adding noise:
![](/QAM/QAM_64_after_noise.png)
### = Bit error rate diagram:
![](/QAM/BER_QAM_64.png)