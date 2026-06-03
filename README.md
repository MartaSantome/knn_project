# Classification of Gravitational Wave Progenitors by the ”K Nearest Neighbors” method (Machine Learning)

This project builds a classification model to identify the source of gravitational wave events, distinguishing between BH–BH, BH–NS, and NS–NS mergers.

The model is trained on simulated data using chirp mass, luminosity distance (dL), and signal-to-noise ratio (SNR), and then applied to real observed events.

## Objective

The goal of this project is to classify gravitational wave events according to their astrophysical source, distinguishing between black hole–black hole (ABH–ABH), black hole–neutron star (ABH–NS), and neutron star–neutron star (NS–NS).

## Dataset

- Simulated gravitational wave events for training.
- Features:
  - Chirp mass
  - Luminosity Distance (dL)
  - Signal-to-Noise Ratio (SNR)
- Real observed events used for inference and validation.

## Methodology

The work flow consists of:

1. Exploratory data analysis
2. Preprocessing
3. Model training
4. Evaluation
5. Inference

## Libraries

The project developed in Python using the following libraries:

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
