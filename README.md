# Image Classification with CNN
This submission specific for detect six human emotion, that is anger,fear,sad,happy,pain,disgust with image classification cnn

## Project Structure
- `saved_model` for tfserving
- `tfjs_model` for tfjs
- `tflite` for tflite
- `submission_imageclassification.ipynb` — The main script used for training and evaluating the CNN model.
- `requirements.txt` — Auto-generated list of required Python packages.
- `README.md` — This file.

## Requirements
You can install the dependencies with:
pip install -r requirements.txt


> Note: This project was originally developed and tested in Google Colab.

## Model Overview
- Architecture: CNN with Conv2D, MaxPooling2D, Flatten, Dense.
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Dataset: https://www.kaggle.com/datasets/yousefmohamed20/sentiment-images-classifier

## Dataset
Make sure to download the dataset from Kaggle and place it accordingly. The code expects the Kaggle API token (`kaggle.json`) to be set up for automatic downloading in Colab.

## Author
Shafly Khalifa Pamungkas - [https://github.com/shaflykhalifap]
