# Sampling App
Android app to sample a function and reconstruct it with different interpolations

## Abstract
A user can enter a function, a sampling frequency and view the output. The frequency spectrum and
the phase response can be viewed for both the original and the sampled signal. For reconstruction of the original signal with the sampled signal as 
the input, three interpolations are available: zero order, first order and si-interpolation.

## Screenshots
Main screen. A function is entered here
<p align="center">
	<img src="img/screenshot1.png" width="250">
</p>

Frequency plot of sin(2*Pi*t) sampled with 5Hz, first order interpolation 
<p align="center">
	<img src="img/screenshot2.png" width="500">
</p>

## Third party libraries
[Androidplot](http://androidplot.com/)