Project 1: QAM Modem

Design & Implementation in Python

Objective:

Design and implement a QAM (Quadrature Amplitude Modulation) modem using Python, including symbol generation, constellation mapping, noise simulation, and performance evaluation.

Specifications:

1. General Design for M symbols

Input: number of symbols or number of bits per symbol.

2. Gray Code Option

Add an option to encode using Gray code.



3. Mapping Table Generation

For each symbol: display its bits, decimal value, I/Q values, energy, and phase.



4. Compute Energy and Phase Balances

Calculate total energy and analyze phase distribution.
5. Transmit IQ Constellation (TX)

Input: allow choice of the starting position of the first symbol.



6. Receive IQ Constellation (RX)

Add noise: AWGN (Additive White Gaussian Noise), phase noise, etc.



7. Compute BER and SNR

Evaluate Bit Error Rate (BER) and Signal-to-Noise Ratio (SNR).

8. Plot BER vs. SNR

Show how BER changes with respect to different SNR levels.



9. Apply QAM Modem to Image Transmission

Attempt to transmit and recover an image using the QAM modem.
