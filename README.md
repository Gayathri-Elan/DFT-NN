# Neural Network Implementation of Discrete Fourier Transform

This project implements the Discrete Fourier Transform (DFT) using a neural network (NN) approach. Instead of directly computing the DFT, a NN model is trained using DFT input and output data. Leveraging the linearity property of DFT, a linear NN is trained to model the transform.

### Key Features:

- Utilizes DFT input and output data to train a linear NN model.
- Provides a function for calculating the DFT of any given input data of length N using the trained NN model.
- Length N can be varied to fit user preference, must be varied before generation of input and output training data.
- calculate_DFT function defined can be used to calculate DFT of input data of length N.

### Dependencies:

- Python
- Neural Network Framework (PyTorch)
- Other libraries (Numpy, Matplotlib)
