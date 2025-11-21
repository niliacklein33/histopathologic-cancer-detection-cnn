# histopathologic-cancer-detection-cnn
CNN Cancer Detection Kaggle Mini-Project

This repo contains my mini-project for the Histopathologic Cancer Detection Kaggle competition. The goal is to classify 96×96 RGB tissue patches as cancerous or non-cancerous using convolutional neural networks.

## Contents

- `notebooks/histopathology_cancer_detection.ipynb`  
  Main notebook with EDA, model architectures (baseline CNN + ResNet18), training, results, and conclusions

- `requirements.txt`  
  Python dependencies used in the notebook (PyTorch, torchvision, pandas, matplotlib, etc.)

## Data

The dataset is not stored in this repo due to size. It can be downloaded directly from Kaggle:
- Histopathologic Cancer Detection: https://www.kaggle.com/c/histopathologic-cancer-detection

## How to Run

1. Download the dataset from Kaggle or run the notebook in a Kaggle notebook environment where it’s already mounted
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
