The Pulsar Star dataset is a well-known dataset used in machine learning and astronomy to distinguish pulsars from non-pulsars based on radio emissions. Pulsars are highly magnetized rotating neutron stars that emit beams of electromagnetic radiation. Identifying pulsars in astronomical data is a significant challenge and has applications in astrophysics.

# Dataset Overview
The Pulsar Star dataset typically contains several thousand observations, each representing a candidate signal detected by a radio telescope. The dataset includes features derived from the signals and a target label indicating whether the signal corresponds to a pulsar or not.

## Features
The dataset generally includes the following features:

Mean of the Integrated Profile: The mean value of the integrated profile.
Standard Deviation of the Integrated Profile: The standard deviation of the integrated profile.
Excess Kurtosis of the Integrated Profile: The kurtosis of the integrated profile.
Skewness of the Integrated Profile: The skewness of the integrated profile.
Mean of the DM-SNR Curve: The mean value of the dispersion measure signal-to-noise ratio curve.
Standard Deviation of the DM-SNR Curve: The standard deviation of the dispersion measure signal-to-noise ratio curve.
Excess Kurtosis of the DM-SNR Curve: The kurtosis of the dispersion measure signal-to-noise ratio curve.
Skewness of the DM-SNR Curve: The skewness of the dispersion measure signal-to-noise ratio curve.

## Target Variable
target_class: This binary variable indicates whether the candidate signal is a pulsar (1) or not (0).
