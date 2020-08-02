# Neural-network_bikesharing-project
It is a course project using simple neural network to predict the hourly active users for bike-sharing company.
1. The raw data is provided by Udacity under the folder \Bike-Sharing-Dataset, while the training input with the preprocessing stpes id under main category (greatures.csv and targets.csv).
2. The network has two layers, a hidden layer and an output layer. The hidden layer will use the sigmoid function for activations. The output layer has only one node and is used for the regression, the output of the node is the same as the input of the node. 
3. The .ipynb is for data preprocessing and unite test. the training and predicting steps are on the 'my_answer.py', which is loaded as package.
4. The experimentlal results:
### Training loss: 0.063 , Validation loss: 0.146 (MSE)
#### iterations = 4000
#### learning_rate = 0.7
#### hidden_nodes = 20
#### output_nodes = 1


