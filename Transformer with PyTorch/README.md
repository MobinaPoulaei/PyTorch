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

For more detailed steps and a comprehensive guide to implementing a model like this, you can refer to this [blog post](https://cafetadris.com/blog/%D8%A2%D9%85%D9%88%D8%B2%D8%B4-%DA%AF%D8%A7%D9%85%D8%A8%D9%87%DA%AF%D8%A7%D9%85-%D9%BE%DB%8C%D8%A7%D8%AF%D9%87%D8%B3%D8%A7%D8%B2%DB%8C-%D9%85%D8%AF%D9%84%D9%87/), which provides a step-by-step guide to building similar models.
