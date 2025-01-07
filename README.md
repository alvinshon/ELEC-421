# ELEC-421
Digital Signal and Image Processing

Objective
The goal of this project is to provide hands-on experience with implementing the Discrete Fourier Transform (DFT) and the Fast Fourier Transform (FFT) algorithms, specifically focusing on the Decimation-in-Time (DIT) and Decimation-in-Frequency (DIF) approaches. You will compare the performance of these algorithms against the naive DFT and apply them to analyze an audio signal.

Tasks
1. Naive DFT Implementation:
  o Write a MATLAB function to compute the DFT of a given signal using the naive formula (O(N²) complexity).
  o Analyze the computational cost by measuring the execution time for different signal lengths.
2. DIT FFT Implementation:
  o Implement the Decimation-in-Time (DIT) FFT algorithm recursively.
  o Visualize the block diagram for N = 8, clearly indicating the stages of decomposition and the butterfly operations.
  o Demonstrate the use of twiddle factors in the implementation.
3. DIF FFT Implementation:
  o Implement the Decimation-in-Frequency (DIF) FFT algorithm.
  o Compare the results and computational cost with the DIT FFT.
4. Frequency Analysis of Audio Signal:
  o Use the provided noisy audio signal (noisy_signal.wav) and clean audio signal (clean_signal.wav) for analysis.
  o Apply your FFT implementations to the audio signals and plot the magnitude spectrum.
  o Identify the dominant frequency components and discuss any differences observed between the noisy and clean signals.
5. Comparative Analysis:
  o Compare the performance of the naive DFT, DIT FFT, and DIF FFT in terms of computational cost (O(N²) vs O(N log₂ N)).
  o Provide a brief analysis of the efficiency and accuracy of each method.
