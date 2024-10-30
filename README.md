# Disaster-Tweet-Classification 🆘🌪️

This project classifies tweets as related or unrelated to disasters using Natural Language Processing (NLP) and Deep Learning. The goal is to build a predictive model that can help emergency response teams quickly identify critical tweets during a disaster.

## Project Overview
In this notebook, I experimented with various models to understand which architecture performs best on disaster tweet classification. The models tested include traditional baselines, RNNs, CNNs, and transfer learning approaches. Below is a brief summary of each model used:

- Model 0: Naive Bayes (Baseline)
- Model 1: Feed-forward Neural Network (Dense Model)
- Model 2: LSTM Model (RNN)
- Model 3: GRU Model (RNN)
- Model 4: Bidirectional-LSTM Model (RNN)
- Model 5: 1D Convolutional Neural Network (CNN)
- Model 6: TensorFlow Hub Pretrained Feature Extractor (Transfer Learning)
- Model 7: TensorFlow Hub with 10% of Training Data (Transfer Learning)

## Dataset
The dataset includes tweets labeled for whether they are disaster-related. The dataset is part of a previous Kaggle competition: https://www.kaggle.com/competitions/nlp-getting-started

## Results
Results for each model are analyzed based on accuracy, F1-score, and other relevant metrics to evaluate their suitability in real-world disaster situations. For a quick comparison:

## How to Use
Clone the repository.
Install the required dependencies: pip install -r requirements.txt
Run the notebook to train and evaluate each model.
