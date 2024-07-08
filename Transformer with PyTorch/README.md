# IMDB Movie Reviews Sentiment Analysis

This project aims to build a text classification model to classify IMDB movie reviews as positive or negative using natural language processing (NLP) and deep learning techniques. We leverage BERT embeddings and PyTorch to create and train the classification model.

**Introduction**
In this project, we preprocess IMDB movie reviews, build a BERT-based text classifier using PyTorch, train the model, and evaluate its performance. Additionally, we visualize the BERT embeddings using t-SNE to understand the separation between positive and negative reviews.

**Dataset**
We use the IMDB movie reviews dataset, which contains both positive and negative reviews. The dataset is downloaded from the following sources:

- Positive reviews: Positive Reviews
- Negative reviews: Negative Reviews

**Model Architecture**
Our classifier consists of the following components:

- BERT model for embedding generation.
- Fully connected layers for classification.
- Dropout layers for regularization.
- Batch normalization layers for stabilizing training.

**Training**
The model is trained using the following settings:

- Loss function: Binary Cross-Entropy Loss
- Optimizer: AdamW
- Number of epochs: 20
- Early stopping with patience: 5 epochs

**Evaluation**
We evaluate the model on the validation dataset and save the best model based on validation loss. The final accuracy of the model is printed and the best model is loaded for inference.

**Visualization**
We extract embeddings from the BERT model and reduce their dimensions using t-SNE. The 2D visualization helps in understanding the separation between positive and negative reviews.
