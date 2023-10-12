# Introduction
This repository provides the codes used to reproduce the results shown in the following paper: Ultrasound Brain Tomography: Comparison of Deep Learning and Deterministic Methods.

The provided MATLAB script performs the following actions:

1. Data Loading:
  Loads training data from 'trainData.mat'.
  Segregates 4,000 images for network validation and testing.

2. Network Training:
  Sets parameters including input and output sizes.
  Transforms input variables to cell type.
  Defines a CNN+LSTM network architecture.
  Specifies training options including the number of epochs, mini-batch size, and learning rate.
  Trains the network using the trainNetwork function.

3. Generate Simulated Reconstruction:
  Loads a FEM mesh of a head model.
  Iterates over the validation data to generate image reconstructions and visualizes them alongside pattern images.
  Displays reconstruction and pattern images side by side, setting the mesh transparency to 0.1 for better visualization.

4. Visualization:
Generates and visualizes reconstructed and pattern images side by side in a loop, adjusting the visualization settings for better clarity.

# Follow the steps below:
1. Start Matlab R2023.
2. Place the files in one folder
3. Open and run the train_CNN_LSTM.mlx script
