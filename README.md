# Neural_networks
Implementing Neural Networks

<img width="556" alt="Screenshot 2024-06-04 at 11 19 41 AM" src="https://github.com/ChiranjeeviChennoju/Neural_networks/assets/164058790/b7532b4b-a33d-4edc-8973-42e0c548a657">

Let us condiser a neural network with one hidden layer shown in the Figure 1. We have a dataset that has 128 input features for our input layer x = [x1, x2,....,x128], these input features determine a digit from 0 to 9, the hidden layer has 10 nodes z = [z1,z2,...z10] and the output layer is a probability distribution y = [y1,y2,..,y10] over 10 classes [0,1,2,3,4,5,6,7,8,9]. We also have bias to the input, x0 = 1 and the hidden layer z0 = 1, both of which are fixed to 1.

α is a matrix of weights from the inputs to the hidden layer and β is the matrix of weights from the hidden layer to the output layer. We use a sigmoid activation function for the hidden layer and a softmax for the output layer.



