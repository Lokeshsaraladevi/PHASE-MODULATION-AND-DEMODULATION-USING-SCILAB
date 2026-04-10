# PHASE-MODULATION-AND-DEMODULATION-USING-SCILAB
AIM

To write a program for Phase Modulation and Demodulation using SCILAB and to observe and measure the phase deviation and modulation index.

APPARATUS REQUIRED

Computer with i3 Processor or higher
SCILAB Software

THEORY

Phase Modulation (PM) is a modulation technique in which the phase of the carrier signal is varied in accordance with the instantaneous amplitude of the modulating signal, while the amplitude of the carrier remains constant.

Phase Deviation (Δφ)

Phase deviation represents the maximum change in phase of the carrier signal.

Δφ = kp * Am

Where:

kp = Phase sensitivity (rad/volt)
Am = Amplitude of modulating signal
Modulation Index (mp)
mp = Δφ

For sinusoidal signals:

mp = kp * Am
PM Signal Equation
s(t) = Ac cos(2πfc t + kp m(t))

For sinusoidal modulating signal:

s(t) = Ac cos(2πfc t + mp sin(2πfm t))

Where:

Ac = Carrier amplitude
fc = Carrier frequency
fm = Modulating frequency
kp = Phase sensitivity
mp = Modulation index

ALGORITHM

Define parameters:
Sampling frequency Fs
Time duration T
Carrier frequency fc
Modulating frequency fm
Phase sensitivity kp
Generate signals:
m(t) = sin(2πfm t)
c(t) = cos(2πfc t)
PM Modulation:
s(t) = cos(2πfc t + kp * m(t))
PM Demodulation:
Differentiate the PM signal
Apply envelope detection:
|s(t)|
Use low-pass filter to recover the original signal
Plot all signals:
Modulating signal
Carrier signal
PM signal
Demodulated signal

PROCEDURE

Refer to the algorithm and write the SCILAB code.
Open SCILAB software.
Create a new script file.
Enter the program and save it.
Execute the code.
Debug errors if any and re-run.
Observe the generated waveforms.

PROGRAM 
![WhatsApp Image 2026-04-10 at 7 25 54 AM](https://github.com/user-attachments/assets/7c692b40-0fec-4c4c-b1eb-ad2a05d0201b)
![WhatsApp Image 2026-04-10 at 7 25 55 AMF](https://github.com/user-attachments/assets/cc2da2fc-cc9f-4a21-baec-b506bf29b0fd)

MODEL GRAPHS
![WhatsApp Image 2026-04-10 at 7 25 55 AM](https://github.com/user-attachments/assets/129fd87a-1de7-4206-b172-a0a6311d868b)

TABULATIONS
![WhatsApp Image 2026-04-10 at 7 25 56 AM](https://github.com/user-attachments/assets/d60734ef-a270-4283-910d-dd84b560bf05)

RESULT
![WhatsApp Image 2026-04-10 at 7 25 55 AMF](https://github.com/user-attachments/assets/cc2da2fc-cc9f-4a21-baec-b506bf29b0fd)
