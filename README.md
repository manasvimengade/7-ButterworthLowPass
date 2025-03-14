# 7-ButterworthLowPass
This script applies a Butterworth low-pass filter to an image using FFT. It transforms the image to the frequency domain, filters out high frequencies, and converts it back, resulting in a smoother image with reduced noise.
The script reads a grayscale image and applies a Butterworth low-pass filter to smooth it by reducing high-frequency noise. It uses the Fast Fourier Transform (FFT) to convert the image into the frequency domain, applies the filter, and then transforms it back using the inverse FFT. The result is a filtered image with reduced sharp edges and noise.
