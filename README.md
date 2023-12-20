# Facial Recognition System

This repository contains code for a Facial Recognition System implemented in Python using various libraries and frameworks. The system is designed to preprocess datasets, train classifiers, and perform facial recognition on test images. The code includes functionality for data augmentation, face detection and cropping, dataset preprocessing, and training and validation of classifiers.

## Usage
1. **Clone Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>

This code is designed to run in a Google Colab environment. Ensure you have the necessary dependencies installed.

## Edit Paths:
Open the code and edit the paths according to your dataset locations. Pay attention to the comments indicating important paths that need customization.

## Run Code:
Execute the code cells in a Colab environment. The code is organized into sections, and you can run the cells sequentially.

## Paths Customization:
Before running the code, ensure that you edit the paths according to your dataset locations. Update the paths for the training dataset, testing dataset, and saved models accordingly.

## Data Preprocessing:
The code includes functions for normalizing file types and labeling systems, splitting datasets for training and validation, and preprocessing images.

## Face Detection and Cropping:
Utilizes different methods for face detection, including Haar Cascade (fc) and DNN-based (dnn) models. The detected faces are cropped and normalized.

## Classifier Training:
Trains classifiers (Random Forest, K-Nearest Neighbors, Support Vector Machine) on the preprocessed dataset. Hyperparameter tuning is performed using GridSearchCV.

## Testing:
Normalizes the file types and labeling for the testing dataset. Performs face detection, cropping, and tests the trained classifier on the test dataset.

## Dependencies:
Python 3,
OpenCV,
NumPy,
PIL (Pillow),
TensorFlow,
Scikit-learn,
Joblib

## License
This code is provided under the MIT License. Feel free to customize and use it for your projects. If you find it helpful, consider giving it a star.

## Acknowledgments
This code was originally generated in a Google Colab environment.
