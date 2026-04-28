Autonomous Driving Behavior Prediction using CNN & RNN

 Overview

This project aims to predict driving behavior (acceleration, braking, and steering) using deep learning models trained on simulated data from CARLA.

## Models Used

* Convolutional Neural Network (CNN) for spatial feature extraction
* Recurrent Neural Network (RNN) for sequential behavior modeling

##  Technologies

* Python
* TensorFlow / Keras
* OpenCV
* CARLA Simulator

## Features

* Multi-output regression (3 driving controls)
* Custom accuracy metric based on prediction threshold
* Image-based learning from simulated driving data

## Results

* Model trained for 50 epochs
* Evaluated using MAE and custom accuracy
* Achieved stable performance on validation data

##  Demo
 screenshot will be added soon

## Future Improvements

* Use LSTM instead of SimpleRNN
* Integrate real-time CARLA control
* Add object detection (YOLO / CNN)
