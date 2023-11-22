# CSC219 Project 3: Multi-Modal Deep Learning for Fake News Detection

## Project Overview
This project focuses on developing a multi-modal deep learning framework to detect fake news on social media. It features two distinct models: a custom-built baseline model and an advanced model incorporating the VGG16 architecture, leveraging both textual and visual data.

## Models Description
### Baseline Model
- **Vision Model**: Utilizes Convolutional Neural Networks (CNNs) for image processing.
- **Language Model**: Employs LSTM and Embedding layers for text analysis.
- **Integration**: Combines outputs of both vision and language models using dense layers for final classification.

### VGG Model
- **VGG16 Base**: Leverages the pre-trained VGG16 model for advanced image feature extraction.
- **Language Processing**: Integrates LSTM for robust text processing.
- **Model Fusion**: Concatenates outputs from both models, applying classification layers for final decision-making.

## Dataset
The project utilizes the comprehensive Fakeddit dataset, comprising over 1 million multimodal samples that include text, images, metadata, and comments. 

**Download the dataset here**: [Fakeddit Dataset](https://github.com/entitize/Fakeddit)

## Usage
To train and evaluate both models:
1. Run the Jupyter Notebook `CSC219TeamProject_3.ipynb`.
2. Follow the steps within the notebook for model training and evaluation.

## Results
- **Baseline Model**: Establishes a foundational approach for multi-modal fake news detection.
- **VGG Model**: Enhances detection capabilities with state-of-the-art image processing techniques.

## Contributing
Contributions, feedback, and questions are welcome. Feel free to open issues or submit pull requests.

## Acknowledgements
- Thanks to the Fakeddit team for providing the dataset.
- Gratitude to the CSC 219-01 Machine Learning course instructors and peers for their support and insights.

