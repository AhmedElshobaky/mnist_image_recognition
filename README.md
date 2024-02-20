### image recognition practice with MNIST dataset loaded from tensorflow.keras

NN architecture: 
- sequential    

NN layers:  
- input layer with 28*28 nodes (x_train_reshaped.shape)
- two hidden layers:
  - 1st layer has 128 nodes
  - 2nd layer has 64 nodes
- output layer with 10 nodes (y_train_cat.shape)
- used dropout on hidden layers to reduce overfitting

Epochs:  
- 10 epochs

Accuracy:
- 95.15%

  
