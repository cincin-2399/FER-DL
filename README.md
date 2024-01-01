# Face Emotion Recognition Project

This project focuses on the task of recognizing human emotions from facial expressions in images. The goal is to classify the emotion expressed by a human face into categories such as happiness, neutrality, sadness, anger, surprise, disgust, and fear.

## Folder Structure

### Dataset

This folder contains the datasets used for training and validation. It includes image data that the models will use to learn how to recognize and classify different facial expressions.

### Models

Here, you'll find all the Jupyter notebooks or equivalent scripts that were used for training the machine learning models. These notebooks include the implementation of various neural network architectures, data preprocessing, and training procedures.

### Trained_models

This folder stores the trained models that are ready for inference. These models have been trained on the dataset and can now be used to predict the emotion expressed in new images of human faces.
For VGGNet model  please see at
https://drive.google.com/file/d/16RwxXXAGNeUi0vdZyZJqlbpz-G0rABK0/view?usp=drive_link

## Getting Started

To use this repository:

1. Clone the repository to your local machine.
2. Install any necessary dependencies.
3. Explore the `Datasets` folder to understand the data structure.
4. Run the notebooks in the `Models` folder to train new models or understand the training process.
5. Use the trained models in the `Trained_models` folder for emotion recognition tasks.

## Usage

To perform emotion recognition on an image:

1. Ensure that you have the correct environment and dependencies installed.
2. Load the trained model from the `trained_models` folder.
3. Preprocess the input image as required by the model.
4. Use the model to predict the emotion expressed in the image.

