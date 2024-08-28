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

For more detailed steps and a comprehensive guide to implementing a model like this, you can refer to this [blog post](https://cafetadris.com/blog/%d9%be%db%8c%d8%a7%d8%af%d9%87%d8%b3%d8%a7%d8%b2%db%8c-%d8%b4%d8%a8%da%a9%d9%87-%d8%b9%d8%b5%d8%a8%db%8c-%da%a9%d8%a7%d9%86%d9%88%d9%84%d9%88%d8%b4%d9%86%db%8c-%d8%af%d8%b1-pytorch/), which provides a step-by-step guide to building similar models.
