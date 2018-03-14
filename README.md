#niFFTy
Adventures in the non-uniform fourier space (NFFT).
Or more generally some lab experiments with power spectra

## Motivation:
In my [tempesp](https://github.com/randompirate/tempesp) repo, I receive a non-uniformly sampled signal (both noise and and drop-out on the sampling rate). Would still like to assess the dominant frequencies in the signal

## Approach:
I explore three approaches:
 - [Non-uniform fourier transform](https://en.wikipedia.org/wiki/Non-uniform_discrete_Fourier_transform) (NFFT, hence the repro name)
 - Uniform resampling of the signal via [cubic splines](https://en.wikipedia.org/wiki/Spline_interpolation)
 - [Lomb-scargle periodogram] (https://en.wikipedia.org/wiki/Least-squares_spectral_analysis#The_Lomb%E2%80%93Scargle_periodogram)

