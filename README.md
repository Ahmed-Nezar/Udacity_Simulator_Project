# Udacity_Simulator_Project
This Repo will contain Notebook for implementing a deep learning model for self driving car using Udacity Simulator.
## Architecture
You will find that I used the following architecture for my model:
1. 4 convolution Lyaers with 5x5 filter and 2x2 stride:
    a. Conv1 with 3 channels
    b. Conv2 with 24 channels
    c. Conv3 with 36 channels
    d. Conv4 with 48 channels
2. 2 Fully connected layers:
    a. FC1 with 100 neurons
    b. FC2 with 50 neurons
Activation functions is Relu for all layers except the last one which is linear.

Dataset link will be provided later.

Validation Loss for the last run of the notebook is 0.022975530475378036

## Made by: Ahmed Nezar