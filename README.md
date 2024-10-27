#OBJECTIVE
The goal is to build a multiclass classification model using Keras with TensorFlow backend to classify fashion items from the Fashion MNIST dataset. The dataset contains 28x28 grayscale images of 10 different fashion categories

#DATASET DESCRIPTION 
The Fashion MNIST dataset consists of 28x28 grayscale images of various clothing items, categorized into 10 classes:

T-shirt/top
Trouser
Pullover
Dress
Coat
Sandal
Shirt
Sneaker
Bag
Ankle boot
The dataset includes:

Training Set: 60,000 images
Test Set: 10,000 images

#Model Architecture 
The model is a deep Artificial Neural Network (ANN) created with the Keras Sequential API. The architecture includes:

Input Layer: Accepts a 784-dimensional flattened vector (28x28 pixels).
Hidden Layers: Five fully connected layers with ReLU activation, batch normalization, and dropout for regularization:
1024 neurons 
512 neurons  
264 neurons 
128 neurons 
64 neurons 
32 neurons 
Output Layer: 10 neurons with softmax activation to output probabilities for each class.
