# eurosat-regularization-tutorial

This repository contains all code, data, figures and the PDF for the Deep learning tutorial:

# Understanding Regularization in CNNs Using the EuroSAT Dataset

## Contents
1. Jupyter Notebook with full experimental analysis
2. Tutorial PDF
3. Generated Plots
4. Requirements file
5. Open-source licence

## How to Run the Code

1. Install Python 3.9+
2. Install dependencies:   pip install -r requirements.txt
4. Run the notebook: ML_Assignment_Regularization_Gowtham.ipynb
   
All figures used in the tutorial will be reproduced automatically.

## Load the EuroSAT Dataset(Tensorflow Datasets)

import tensorflow_datasets as tfds

dataset, info = tfds.load("eurosat/rgb", with_info=True, as_supervised=True)

## License
This project is released under the MIT License and may be reused with attribution.

