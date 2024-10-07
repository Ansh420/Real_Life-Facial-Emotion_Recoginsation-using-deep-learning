# Introduction

This repository contains a Python implementation of a real-time facial emotion recognition system using deep learning. The system leverages a pre-trained convolutional neural network (CNN) model to accurately detect and classify facial emotions from live video feeds or images.

## Prerequisites
**Before running the code, ensure you have the following installed**:

- Python 3.x
- OpenCV
- TensorFlow or Keras
- NumPy
- Matplotlib (for visualization)

  
## Installation

Bash
$ **git clone https://github.com/Ansh420/facial-emotion-recognition**
Use code with caution.

## Install dependencies:
Bash
$ pip install opencv-python tensorflow numpy matplotlib


## Prepare a dataset:

- Collect a dataset of images or videos containing faces with various emotions (e.g., happy, sad, angry, neutral).
- Label each image or video with the corresponding emotion.
- Organize the dataset into appropriate directories.

## Train the model:

- Modify the train.py script to load your dataset and configure the training parameters.
- Run the script to train the CNN model on your dataset.

## Test the model:

- Use the test.py script to evaluate the model's performance on a separate test dataset.
- The script will output accuracy, precision, recall, and F1-score metrics.

## Real-time recognition:

- Run the realtime.py script to capture video from your webcam or load a video file.
- The script will detect faces in the video and predict their emotions in real time.
  
## Configuration

**Model architecture**: The model.py file defines the CNN architecture. You can customize it to suit your needs.

**Training parameters**: Adjust the learning rate, batch size, epochs, and other parameters in the **train.py** script.

**Dataset paths**: Update the dataset paths in the **train.py** and **test.py** scripts.
