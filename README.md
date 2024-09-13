
**OVERVIEW**
This project demonstrates image classification using Convolutional Neural Networks (CNN) to classify images of dogs and cats. The CNN model is trained to distinguish between the two categories with high accuracy by processing the features of the images through multiple layers.

**Project Description**
In this project, I used a deep learning approach to build a model that can classify images of dogs and cats. The dataset consists of labeled images of both categories. The model was built using a CNN architecture, which is highly effective in image classification tasks due to its ability to learn spatial hierarchies of features.

**Model Architecture**
The CNN architecture includes the following layers:

Convolutional Layer: Extracts features from the input images.
Max-Pooling Layer: Reduces the spatial dimensions of the feature maps.
Dropout Layer: Prevents overfitting by randomly turning off neurons.
Dense Layer: Fully connected layers to make predictions.

**Model Summary:**
Input shape: (image_size, image_size, 3)
Output: 2 classes (Dog, Cat)

**LIBRARIES & TOOLS**
Python,TensorFlow,Keras,Numpy,Matplotlib
