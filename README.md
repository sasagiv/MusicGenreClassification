# MusicGenreClassification
Machine learning project for music genre classification. Uses MFCC features from audio files and a neural network for classification. Includes preprocessing, model training, and genre prediction.

# Music Genre Classification

This project is a deep dive into the field of music genre classification using machine learning techniques. It aims to classify music genres based on audio file inputs. The project uses a dataset of .wav files from various music genres, and the genres are predicted based on the MFCC (Mel Frequency Cepstral Coefficients) features extracted from these audio files.

## Methodology

The methodology followed in this project involves several steps:

1. **Data Preprocessing**: The audio files are loaded and preprocessed using the `librosa` library. The preprocessing involves extracting MFCC features from the audio files, which serve as the input features for our model.

2. **Model Training**: The extracted features are used to train a neural network model. The model architecture includes dense layers with 'relu' activation functions, and the output layer uses a 'softmax' activation function for multi-class classification.

3. **Genre Prediction**: Once the model is trained, it can be used to predict the genre of a new audio file. The audio file is preprocessed in the same way as the training data to extract MFCC features, which are then fed into the model to get the predicted genre.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have the following Python libraries installed:

- librosa
- numpy
- sklearn
- keras

You can install these using pip:

```bash
pip install librosa numpy sklearn keras
