# Driver Behavior Classification Project

## Overview
In this project, I was provided with images of drivers, each taken inside a car with a driver performing a specific action (texting, eating, talking on the phone, applying makeup, reaching behind, etc). The goal is to build a model that can accurately predict the action that the driver is performing in each picture.

The model should classify actions into the following 10 classes:
- c0: safe driving
- c1: texting - right
- c2: talking on the phone - right
- c3: texting - left
- c4: talking on the phone - left
- c5: operating the radio
- c6: drinking
- c7: reaching behind
- c8: hair and makeup
- c9: talking to passenger

## Project Structure
The project involves several stages:

1. **Building a Neural Network from Scratch**: A Convolutional Neural Network (CNN) model was built using Keras, achieving a training accuracy of 73.74% and a validation accuracy of 88.55%.

2. **Building a Neural Network Using Transfer Learning**: A transfer learning model based on ResNet-18 and ResNet-50 was implemented using PyTorch. The ResNet-50 model was trained with different optimizers (Adam and SGD) and for different epochs to compare performances.

3. **Hyperparameters Experimentation**: Various hyperparameters such as learning rate, batch size, and optimizer type were experimented with to understand their impact on the model performance.

## Notebooks
This repository contains Jupyter notebooks that detail the process, parameters, hyperparameters, and justifications for the choices made during the project. 

## Results
The Keras-based CNN model achieved a validation accuracy of 88.55%, while the PyTorch-based ResNet models achieved validation accuracies up to 77%. These results demonstrate the effectiveness of both custom CNN models and transfer learning in classifying driver behavior.
