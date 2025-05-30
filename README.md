# PyTorch Transfer Learning on Custom Dataset

This repository demonstrates how to apply **Transfer Learning** using **PyTorch** on a custom dataset derived from the **Fashion MNIST** dataset. The approach is ideal when working with limited data and aims to leverage pre-trained models for better performance and faster convergence.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Overview

Transfer learning allows us to use models pre-trained on large datasets (like ImageNet) and adapt them to new tasks. In this project, we:

- Load a custom dataset (Fashion MNIST subset)
- Preprocess and prepare data for training
- Fine-tune a pre-trained model using PyTorch
- Evaluate the model's performance on the custom dataset

## Dataset

- **File**: `fmnist_small.csv`
- **Description**: Contains a small sample from the Fashion MNIST dataset, converted to a CSV format for ease of use.
- **Classes**: A subset of standard fMNIST labels such as T-shirt/top, Trouser, etc.

You can replace the dataset with your own custom-labeled CSV or image files.

## Model

- Pre-trained model used: **ResNet / AlexNet / VGG (customizable)**
- Final classifier layer modified to match the number of classes in the dataset.
- Only selected layers are fine-tuned (transfer learning).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/BabluKumarJha/Pytorch-Transfer-Learning-custom-dataset.git
   cd Pytorch-Transfer-Learning-custom-dataset


2. Install required packages:

pip install torch torchvision pandas numpy matplotlib scikit-learn


3. Launch Jupyter Notebook:

jupyter notebook



## Usage

Open the notebook:

Transfer learning.ipynb

Follow the step-by-step instructions to:

Load the CSV dataset

Preprocess the data

Load a pre-trained model

Train and evaluate the model



## Results

The notebook will display:

Training and validation accuracy



These results help in visualizing how well the model generalizes to the custom dataset.

License

This project is licensed under the Creative Commons Zero v1.0 Universal – feel free to use, modify, and distribute it.


---

Author: Bablu Kumar Jha
