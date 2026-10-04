# Movie Review Sentiment Analysis using LSTM

## Project Overview

This project performs movie review sentiment analysis using a Long Short-Term Memory (LSTM) neural network.

The model is trained on the IMDB movie review dataset available through TensorFlow/Keras.

The model classifies movie reviews into two sentiment categories:

- Positive
- Negative

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- LSTM
- Word Embeddings
- IMDB Dataset

## Project Workflow

The project follows these steps:

1. Load the IMDB movie review dataset.
2. Consider the 10,000 most frequent words.
3. Decode sample reviews from numerical sequences into words.
4. Pad reviews to a maximum length of 200 words.
5. Create an LSTM-based deep learning model.
6. Train the model for 3 epochs.
7. Evaluate the model on test data.
8. Predict the sentiment of a test review.
9. Compare the predicted sentiment with the actual sentiment.

## Model Architecture

```text
Movie Review
     ↓
Embedding Layer
     ↓
LSTM Layer
     ↓
Dense Layer
     ↓
Sigmoid Activation
     ↓
Positive / Negative