## fire_and_smoke_detection

### Libraries Required:
1. Tensorflow
2. Numpy

### Steps to perform data preprocessing, training, building the model and predicting the result:

1. Perform Data Augmentation (creating more data from existing data)
2. Divide the dataset into training and validation datasets to train and validate the results.
3. Initialize your CNN model.
4. Add first layer of CNN with Convolution 2D layer and MaxPool2D layer and set the activation function as Relu.
5. Repeat the same step to add 2nd and 3rd layers.
6. Now flatten these layers to connect it to dense layer.
7. Add a dense layer with activation function as Relu
8. Add Output Layer with activation function as Sigmoid.
9. Create a checkpoint to observe all the improvements of the model.
10. Train the model with Adam Optimizer and loss as Binary Entropy for 30 epochs on training and validation datasets.
11. Load the trained model. 
12. Predict the model on test data.


### Result
Achieved the result with 98% accuracy.

