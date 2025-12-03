# Face Classification Project

This repository contains a simple face-classification project using a deep learning model based on MobileNetV2.  
The project includes a notebook for training/testing and a small sample dataset organized by folders.

## Repository Structure

Five_Faces/
- gates/
- jack/
- modi/
- musk/
- trump/

Face_classification.ipynb

face_recognition_mobilenetv2.h5

README.md


## Project Overview

This project demonstrates how to build and train a facial classification model using:

- MobileNetV2 (pre-trained on ImageNet)
- Custom dataset (images organized in class folders)
- TensorFlow / Keras

The model learns to classify images based on the person in the picture.

## Features

- Pre-trained MobileNetV2 backbone  
- Transfer learning  
- Simple dataset folder structure  
- Jupyter Notebook used for training  
- Pre-trained model included (face_recognition_mobilenetv2.h5)


```bash
pip install tensorflow keras numpy matplotlib
