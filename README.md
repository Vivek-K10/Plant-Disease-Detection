# Plant Disease Detection Using Deep Learning

## Overview
This project uses transfer learning with MobileNetV2 to classify plant leaf images into disease categories. The model is developed using TensorFlow and Keras in a Jupyter Notebook.

## Objectives
- Classify plant leaf images into different disease categories.
- Apply transfer learning using a pretrained MobileNetV2 model.
- Use data augmentation to improve model generalization.
- Evaluate model performance on training, validation, and test datasets.

## Technologies Used
- Python
- TensorFlow and Keras
- MobileNetV2
- NumPy
- Matplotlib
- Jupyter Notebook
- split-folders

## Project Workflow
1. Download and extract the plant leaf disease dataset.
2. Split the dataset into training, validation, and test sets.
3. Resize images to 160 × 160 pixels.
4. Apply data augmentation and MobileNetV2 preprocessing.
5. Train the classification model using transfer learning.
6. Fine-tune selected layers of MobileNetV2.
7. Evaluate the model on the test dataset.
8. Save the trained model in Keras format.

## Dataset
The notebook downloads the Plant Leaves Diseases dataset from Mendeley Data.

Dataset source: https://data.mendeley.com/datasets/tywbtsjrjv

The notebook creates an 80% training, 10% validation, and 10% test split.

## Model Architecture
The model uses a pretrained MobileNetV2 feature extractor, global average pooling, dropout, and a dense output layer for classification.

## How to Run
1. Open `plant.ipynb` in Google Colab or Jupyter Notebook.
2. Run the cells in order.
3. Ensure the dataset download and extraction steps complete successfully.
4. Train and evaluate the model.
5. The trained model is saved as `plant_disease_rec_model.keras`.

## Current Status
The repository contains the model training notebook. The saved model and a deployable web application are not included in this repository.

## Future Improvements
- Validate class predictions and preprocessing.
- Improve the classification architecture and evaluation.
- Build a Streamlit interface for image-based predictions.
- Deploy the application online.

## Disclaimer
Predictions are experimental and may be incorrect. The model should not be used as the sole basis for agricultural treatment decisions.
