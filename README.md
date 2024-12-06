# CNN-LSTM DoS Attack Detection with Federated Learning

This repository contains the implementation of a federated learning-based framework for detecting Denial-of-Service (DoS) attacks in Wireless Sensor Networks (WSNs). It builds upon the research paper *“CNN-LSTM Based Approach for DoS Attacks Detection in Wireless Sensor Networks”* and enhances it by integrating federated learning techniques using **Flower** and **TensorFlow Federated (TFF)**.

## Project Overview

The primary goal of this project is to improve the security and efficiency of DoS attack detection in WSNs by leveraging a **CNN-LSTM model** within a **federated learning framework**. Federated learning enables decentralized training, ensuring data privacy by processing data locally on devices while reducing communication overhead in WSN environments.

### Key Features
- **CNN-LSTM Model**: Combines the strengths of Convolutional Neural Networks (CNNs) for feature extraction and Long Short-Term Memory (LSTM) networks for sequence modeling.
- **Federated Learning Integration**: Implements federated learning using:
  - **Flower**: A scalable framework for federated learning experiments.
  - **TensorFlow Federated (TFF)**: A platform for federated computations with TensorFlow.
- **WSN-DS Dataset**: Utilized for training and evaluating the DoS attack detection model.
- **Enhanced Privacy**: Local training ensures data remains on client devices, addressing privacy concerns.

## Future Work
- **Experiment with advanced federated optimization algorithms.**

- **Explore other datasets and attack scenarios.**

- **Optimize communication efficiency for larger-scale deployments.**


