## Project Overview

This project implements a deep learning solution to automatically classify tomatoes as either ripe or unripe. The system consists of:

- A CNN model trained on tomato images
- A Streamlit web application for user-friendly interaction
- Model evaluation metrics and visualization

  ## Dataset

The model was trained on the [Tomato Ripeness Dataset](https://www.kaggle.com/datasets/sumn2u/riped-and-unriped-tomato-dataset?resource=download) from Kaggle.


## Install below Libraries in VS Code
streamlit==1.25.0
tensorflow==2.12.0
pillow==9.5.0
matplotlib==3.7.1
numpy==1.24.3


## How to Run train.py

## Run the Below Code in Google Colab

from google.colab import drive
drive.mount('/content/drive')

## Run the Below Code and upload the train.py file

from google.colab import files
files.upload()

## Make sure to pass the correct dataset path, My dataset is in Google Drive
 
!python train.py \
    --data_dir "/content/drive/MyDrive/Riped and Unriped Tomato Dataset" \
    --output_model "/content/drive/MyDrive/best_model.h5"
