# OBJECT-detection-using-Binary-Neural-Network
Welcome to the project repository for Object Detection using Binary Neural Networks (BNN)!
This project focuses on building an efficient, lightweight object detection model using Binary Neural Networks, ideal for deployment on resource-constrained devices such as mobile and edge devices.

Project Overview
Objective:
To develop an object detection model using a Binary Neural Network (BNN) that performs accurate detection while significantly reducing memory usage and computational requirements.
Why BNNs?
Binary Neural Networks replace standard 32-bit floating-point weights and activations with binary values (1 or -1), drastically reducing the model size and making it faster and more energy-efficient without sacrificing too much accuracy.

Project Structure
├── datasets/           # Dataset used for training and testing
├── models/             # Binary Neural Network model architecture
├── saved_weights/      # Trained model weights
├── utils/              # Utility scripts (data preprocessing, visualization, etc.)
├── results/            # Detection results and output images
├── train.py            # Training script
├── test.py             # Testing and evaluation script
├── README.md           # Project documentation
├── requirements.txt    # Required Python packages

Features

Lightweight and memory-efficient model
Rotation-invariant object detection (if you used rotation-invariant features)
Preprocessing and feature extraction techniques included
Trained on binary data representation for enhanced efficiency
Simple and modular code structure for easy customization

Results

Training Accuracy: 93.14%
Testing Accuracy: 65%
Achieved efficient binary object detection with significant memory and computational savings.
Model architecture: DeepBinaryNet with Tanh activations and Dropout layers.
Model weights saved after training (fc1.weight, fc1.bias, fc2.weight, fc2.bias).
Suitable for lightweight deployment and real-time inference on edge devices.

