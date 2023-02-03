# Dog Breed Prediction System
This project aims to build a multi-class dog breed prediction system. The problem is a supervised classification problem, as the images are labeled.

1) Workflow
2) Import and clean the dataset containing the breed labels.
3) Convert labels into tensors by first converting them into bools, then into numbers, and finally into tensors.
4) Convert images into tensors by first creating the path names array and then converting the images into arrays of each image.
5) Split the data into train and validation sets and convert into batches of size 32.
6) Train the model and use the validation set to test and tune it. Callbacks are made to prevent overfitting.
7) Save the training logs using Tensorflow hub.
8) Test the model and convert the predictions into a more presentable format.

# Technologies used
Pickle
Pandas
Numpy
Tensorflow
Tensorflow hub
Keras
datetime
Tensorboard
Matplotlib

# Model Used
The model used in this project is mobilenet_v2_130_224.



