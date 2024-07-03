# CNN with PyTorch

**Introduction**

This notebook demonstrates how to create and train a Convolutional Neural Network using PyTorch. CNNs are particularly effective for image recognition tasks, and this example focuses on classifying images from the CIFAR-10 dataset.

**Dataset**

The CIFAR-10 dataset is used in this notebook. It consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images.

**Model Architecture**

The CNN model implemented in this notebook has the following architecture:

- Convolutional layers
- Max-Pooling layers
- Fully Connected layers
- Activation functions (ReLU)
- Dropout layers

**Training the Model**

The training process involves:

- Defining the loss function and optimizer
- Iterating over the training dataset
- Performing forward and backward passes
- Updating the model parameters

**Evaluation**

The model is evaluated using the test dataset to assess its performance. Key metrics such as accuracy are computed and CCE loss displayed.
