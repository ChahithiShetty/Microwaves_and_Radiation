**********Experiment 9 – Rayleigh Fading Channel Performance Analysis
This experiment is divided into two parts:

Part 1: Statistical Properties of Rayleigh Fading
Generate and visualize the statistical nature of a Rayleigh fading channel.

-Creates 20,000 random values that follow the Rayleigh distribution.
-A histogram (empirical view).
-The theoretical Rayleigh Probability Density Function (PDF).
-Compares Bit Error Rate (BER) performance for BPSK, BFSK, and DPSK 
-Mathematical modeling of Rayleigh PDF.
-Analytical BER expressions for each modulation scheme.

Part 2: Monte Carlo Simulation of BPSK in Rayleigh Fading
Perform a practical simulation (Monte Carlo) of how BPSK performs under Rayleigh fading.

-Generates a long bitstream, modulates it using BPSK.
-Simulates Rayleigh fading + AWGN noise on the signal.
-Demodulates and compares received bits to calculate the simulated BER.
-Plots this BER and compares it to theoretical curves.
-Rayleigh fading modeled using exponential distribution.
-Coherent detection assuming fading is known at the receiver.
-BER estimated from real errors across different SNR values.


**********Experiment 10 – Simulation of an OFDM Transmitter and Receiver
Simulate an entire OFDM (Orthogonal Frequency Division Multiplexing) system using BPSK modulation.

-Transmitter: Random bits → BPSK → IFFT → Cyclic Prefix
-Channel: Adds complex Gaussian noise (AWGN)
-Receiver: Remove prefix → FFT → Demodulate BPSK
-Calculates Bit Error Rate (BER) for a range of Eb/N0 values.
-Plots simulated BER vs theoretical BER for BPSK in AWGN.



