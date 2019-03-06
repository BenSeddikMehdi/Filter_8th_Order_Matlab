# Filter_8th_Order_Matlab
Create a 8th order filter in Matlab and pass a noisy sinus pulse through it and see the result in Frequency Domain.

inputSignal : is a sinus pulse with :

                                      ** Frequency : 20 Khz
                                      ** Amplitude : 1 V
                                      ** Phase : 0 rad/s
                                      ** samples : 128

The filter that I've designed is lowpass Butterworth filter with 22 KHz cutoff frequency, wich, for data samples at 48 KHz, corresponds to rad/sample.

Additionally, I influenced my inputSignal (sinusPulse) with an AWGN (Additive White Gaussian Noise) with an SNR of 12dB, and attack it in the input of the filter.


In the end I plotted the output of the filter in the Frequency Domain using FFT (Fast Fourier Transform) and figure out how does the filter works in function with several SNR values and sinuPulse samples.

By BENSEDDIK El Mehdi

02/27/2019
