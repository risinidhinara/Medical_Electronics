# BM4112 Medical Electronics and Instrumentation
## MATLAB Assignment Signal Estimation
ECG Denoising Using Wiener and Kalman Filters

## Assignment Description
This project is part of the BM4112 Medical Electronics and Instrumentation module.  
The objective is to perform ECG signal denoising using Wiener filtering and Kalman filtering techniques in MATLAB and to compare their performance in both time domain and time frequency domain.

## Repository Contents
ECG_rec.mat  Noisy ECG signal  
idealECG.mat  Clean reference ECG signal  
Q1_210321X.mlx  Task 01 Wiener Filter implementation  
Q2_210321X.mlx  Task 02 Kalman Filter implementation  
MATLAB Assignment on Signal Estimation.pdf  Assignment brief  
Signal_Estimation.pdf  Report documentation  
README.md  Project overview  

## Task 01 Wiener Filter for ECG Denoising
Objective  
To design and implement a Wiener filter to reduce noise from a recorded ECG signal using statistical estimation.

Implementation  
The task is implemented in Q1_210321X.mlx.  
The script loads ECG_rec.mat as the noisy ECG signal and idealECG.mat as the reference ECG signal.  
A Wiener filter is applied to estimate the clean ECG signal.

Analysis and Plots  
Time domain comparison between noisy ECG and Wiener filtered ECG.  
Time frequency domain analysis using spectrogram or STFT.  
Observations are included to discuss noise reduction and ECG feature preservation.

## Task 02 Kalman Filter for ECG Denoising
Objective  
To apply a Kalman filter for adaptive ECG signal estimation and compare its performance with the Wiener filter.

Implementation  
The task is implemented in Q2_210321X.mlx.  
Wiener filter weights from Task 01 are used as the initial transition matrix.  
Kalman filter parameters are updated recursively.

Analysis and Plots  
Time domain comparison between noisy ECG and Kalman filtered ECG.  
Time frequency domain comparison of input and output signals.  
Performance comparison between Wiener and Kalman filters.

## Comparison and Discussion
The following aspects are evaluated  
Noise suppression capability  
Preservation of ECG morphological features  
Adaptability to time varying noise  
Overall signal enhancement quality  

A clear justification is provided on which filtering method enhances the ECG signal better and why.

## Software Requirements
MATLAB R2020a or later  
Signal Processing Toolbox  

## Submission Information
Assignment type Individual  
Submission method Moodle upload  
Report PDF submission  
MATLAB files submitted as a single ZIP file

## Conclusion
This assignment demonstrates the application of classical and adaptive filtering techniques for biomedical signal processing.  
The results highlight the differences between Wiener and Kalman filters in ECG denoising performance.
