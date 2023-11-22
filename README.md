# CSC219 Project 3: Multi-Modal Deep Learningfor Fake News Detection

## Project Overview
This project is part of theaimed at developing a multi-modal deep learning framework for detecting fake news on social media. Leveraging both textual and visual data, the project features two distinct models: a custom-built baseline model and an advanced model utilizing the VGG16 architecture.

## Models Description

### Baseline Model
- **Vision Model**: Utilizes Convolutional Neural Networks for image processing.
- **Language Model**: Processes text using LSTM and Embedding layers.
- **Integration**: Combines vision and language model outputs with dense layers for final classification.

### VGG Model
- **VGG16 Base**: Employs the pre-trained VGG16 model for image feature extraction.
- **Language Processing**: Integrates an LSTM-based language model.
- **Model Fusion**: Concatenates outputs from both models and applies classification layers.

## Dataset
The project uses a comprehensive dataset from the Fakeddit repository, featuring over 1 million multimodal samples including text, images, metadata, and comments.

## Usage
Execute the Jupyter Notebook CSC219TeamProject_3.ipynb to train both models and evaluate their performance.

## Results
- **Baseline Model**: Demonstrates the foundational approach to multi-modal fake news detection.
- **VGG Model**: Offers an enhanced approach with state-of-the-art image processing capabilities.
