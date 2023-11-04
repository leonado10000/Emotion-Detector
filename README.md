# Emotion-Detector

# Facial Emotion Recognition with MobileNet

## Overview

Facial Emotion Recognition with MobileNet is a deep learning project that aims to identify and classify human emotions from images and live video feeds. The project consists of two main parts: model training and real-time emotion recognition from a webcam feed.

The trained model can efficiently recognize seven different emotions: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise. This README provides an overview of the project, instructions for usage, and project highlights.


## Key Features

- Trained a deep learning model for facial emotion recognition using MobileNet.
- Implemented real-time emotion recognition from a webcam feed.
- Utilized OpenCV for face detection.
- Integrated early stopping and model checkpoint for efficient model training.
- Achieved an accuracy of 59% on the validation dataset.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/leonado10000/Emotion-Detector.git
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the main application:

   ```bash
   python emotion_recognition.py
   ```

## Usage

- Launch the application by running `emotion_recognition.py`.
- Point your webcam at a face, and the application will detect and classify the emotion in real-time.

## Project Structure

- `emotion_recognition.py`: The main application for real-time emotion recognition.
- `model_training.ipynb`: Jupyter Notebook for training the emotion recognition model.
- `best_model.h5`: The trained deep learning model.

## Acknowledgments

- The project utilizes the MobileNet architecture for transfer learning.
- The Haar Cascade classifier from OpenCV is used for face detection.
