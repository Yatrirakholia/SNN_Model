# SNN_Spikejelly.py File
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Spiking Neural Network (SNN) Training on MNIST using SpikingJelly

This project implements a simple Spiking Neural Network (SNN) using [SpikingJelly](https://github.com/fangwei123456/spikingjelly) to classify digits from the MNIST dataset. 
The network uses **Poisson spike encoding**, **LIF neurons**, and **surrogate gradients** for training. The script also visualizes **raster plots**, **accuracy vs energy consumption**, 
and **spike dynamics** over epochs.

## Features

- Poisson spike encoding of input data  
- Two-layer feedforward SNN with LIF (Leaky Integrate-and-Fire) neurons  
- Training using surrogate gradient descent  
- Spike activity monitoring and raster plot visualization  
- Plots of accuracy and energy (spikes per sample) over epochs  
- Spike dynamics visualization over time

##  Requirements

- Python 3.8+
- PyTorch
- SpikingJelly
- NumPy
- Matplotlib
- TorchVision

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# SingleNeuron.ipynb
## LIF Neuron Simulation using Brian2

This project simulates a **single Leaky Integrate-and-Fire (LIF) neuron** using the [Brian2](https://brian2.readthedocs.io/en/stable/) simulator. The membrane potential dynamics and spike train are 
visualized under a constant input current.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# snn-for-encoded-iris-dataset-test-accuracy-100.ipynb
##  Spiking Neural Network (SNN) on Encoded Iris Dataset

This repository contains a Jupyter Notebook that demonstrates the use of a **Spiking Neural Network (SNN)** to classify samples from the **Iris dataset** using a pre-encoded version of the data. The model 
achieves **100% test accuracy** using simple feedforward SNN architecture.

## Dataset

- **Dataset:** Iris dataset from scikit-learn
- **Encoding:** The original continuous features are encoded into spike-based representations suitable for SNN input.
- **Classes:** 
  - Setosa
  - Versicolor
  - Virginica


License
This project is licensed under the MIT License.

Let me know if you'd like a version customized for GitHub, or one that includes more technical details like spike encoding functions or specific neuron models (e.g., LIF, IF).


