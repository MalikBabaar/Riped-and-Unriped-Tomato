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

Open a terminal (or command prompt) and navigate to the directory where train.py is saved. Then run

python train.py --data_dir /path/to/Riped_and_Unriped_Tomato_Dataset \
               --img_size 128 \
               --batch_size 32 \
               --epochs 30 \
               --output_model best_model.h5
