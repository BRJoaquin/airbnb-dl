# Airbnb Price Prediction Project

## Overview
This project focuses on developing a deep learning model to predict Airbnb rental prices. It employs advanced neural network techniques, including wide and deep architecture, to capture complex patterns in the data.

## Features
- **Data Preprocessing**: Includes one-hot encoding, missing value indicators, and text vectorization.
- **Model Architecture**: A blend of wide and deep networks, utilizing layers like Dense, Dropout, and BatchNormalization.
- **Training and Evaluation**: Utilizes Keras for model training, with callbacks like EarlyStopping and WandbCallback for monitoring.
- **Hyperparameter Tuning**: Conducted using Weights & Biases (wandb) for systematic optimization.

## Installation
Clone the repository and set up the environment using Conda:
```bash
git clone https://github.com/BRJoaquin/airbnb-dl
cd airbnb-dl
conda env create -f environment.yml
conda activate airbnb
```