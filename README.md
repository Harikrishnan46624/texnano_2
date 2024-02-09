

##Task 2: SimCLR Implementation with PyTorch

Description
This repository contains the implementation of a deep learning framework, SimCLR, for contrastive learning using PyTorch. The code follows the methodology and loss described in the SimCLR paper and is designed for self-supervised learning. The implementation uses small backbones like ResNet18 or ResNet50 and is trained on a vision dataset of your choice.

Contents
Code Files:
Task_2.ipynb: Main Python script containing the SimCLR model, loss, training, and evaluation functions.

Training and Evaluation:
The code trains the SimCLR model using the specified loss and evaluates its performance on a vision dataset.
Metrics such as loss, accuracy, etc., are reported during training.

Hyperparameters:
Hyperparameters such as batch size, projection dimension, learning rate, and epochs are defined in the main function.
Visualization of Augmentations:

The code includes a function (visualize_augmentations) to visualize augmentations applied to the dataset.
Getting Started:

Update the hyperparameters in the main function according to your preferences.


Run the SimCLR implementation script: Task_2.ipynb.
Dependencies
PyTorch
torchvision
matplotlib
Dataset
The code is designed to work with a vision dataset, and for this implementation, it uses the CIFAR-10 dataset. You can easily modify the dataset by changing the transform in the main function.

Experimentation
Conduct experiments to compare SimCLR performance against training a vanilla CNN for classification. Report relevant metrics and analyze the advantages of using SimCLR.

Contact
For any questions or issues, please contact Harikrishnan at harikrishnan46624@gmail.com.
