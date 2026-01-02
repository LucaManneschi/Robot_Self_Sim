# Robot Self model training and evaluation

This repository contains experiments and implementations for the paper: Scaffolded acquisition of a robot self-world distinction in a layered architecture model of the developing self.

## Dataset

The dataset for this project can be accessed here:
[Google Drive Dataset](https://drive.google.com/drive/folders/12DtuYUxjYo_AkGia4pSHvZUVkkNhb-e5?usp=sharing)

## Repository Structure

- **BPTT/**: Backpropagation Through Time experiments
  - `BPTT_through_with_Scaffolding.ipynb`: BPTT implementation with scaffolding
  - `BPTT_through.ipynb`: Standard BPTT implementation

- **Continuous_training/**: Continuous training experiments
  - `Continuous_training.ipynb`: Continuous learning approach

- **Layer_0_No_Scaffolding/**: Base layer experiments without scaffolding
  - `Layer0_No_Scaffolding.ipynb`: Layer 0 baseline implementation

- **No_proprioception_input/**: Experiments without proprioceptive input
  - `No_p_input.ipynb`: Implementation without proprioception data

## Requirements

The following Python libraries are required to run the experiments:

- **PyTorch**: Deep learning framework for neural network implementations
- **NumPy**: Numerical computing and array operations
- **Matplotlib**: Visualization and plotting
- **SciPy**: Scientific computing utilities
- **Torchvision**: Computer vision utilities for PyTorch

CUDA-compatible GPU is recommended for training the models.

## Getting Started

1. Download the dataset from the link above
2. Install the required libraries (see Requirements section)
3. Open any of the Jupyter notebooks in the respective directories
4. Follow the instructions within each notebook to run the experiments


