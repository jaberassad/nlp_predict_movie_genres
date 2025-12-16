# Movie Genre NLP Transformer Classifier with RoBERTa-BiLSTM

This project implements a hybrid **RoBERTa Transformer + BiLSTM model** for classifying movie genres from plot summaries. The model leverages pretrained RoBERTa embeddings, a bidirectional LSTM to capture sequential dependencies, and multi-head attention pooling across transformer layers. Focal loss is used to handle class imbalance, and the architecture is optimized to keep trainable parameters under 600M for efficient deployment.

## Features

- Hybrid RoBERTa Transformer + BiLSTM architecture for sequence classification.
- Multi-head attention pooling over the last N transformer layers.
- Focal loss for handling class imbalance across genres.
- Efficient architecture with under 600M trainable parameters.
- Trained on plot summaries to predict multiple movie genres.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/jaberassad/nlp_predict_movie_genres.git
cd nlp_predict_movie_genres
