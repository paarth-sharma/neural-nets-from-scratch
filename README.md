# Nerual Nets
Neural networks, also known as artificial neural networks (ANNs) or simulated neural networks (SNNs), 
are a subset of machine learning and are at the heart of deep learning algorithms. Their name and 
structure are inspired by the human brain, mimicking the way that biological neurons signal to one another.

## Basic Structure and Working
**Structure** -\
ANNs are comprised of a node layers, containing an input layer, one or more hidden layers, and an output layer.\
**Working** -\
Each node, or artificial neuron, connects to another and has an associated weight and threshold. 
If the output of any individual node is above the specified threshold value, that node is activated, 
sending data to the next layer of the network. Otherwise, no data is passed along to the next layer of the network.

## How am I going to it ?
I am going to take [MNIST database](https://en.wikipedia.org/wiki/MNIST_database) as inspiration and attempt to make a similiar model that recongnises handwritten digits.\
Here is an example of sample images of the different ways digits amy be written\
![set of digits used for training](./assets/MnistExamples.png)

# Breakdown of my thought process
Broke the learning model's functions into 3 steps that repeat
- [Forward Propagation](https://en.wikipedia.org/wiki/Residual_neural_network#Forward_propagation) using suitable [activation functions](https://en.wikipedia.org/wiki/Activation_function) namely [ReLu(x)](https://en.wikipedia.org/wiki/Rectifier_(neural_networks)) for the middle layer and [Softmax(x)](https://en.wikipedia.org/wiki/Softmax_function) for the output layer

- [Backward Propagation](https://en.wikipedia.org/wiki/Backpropagation) 

- [Updating parameters and adjusting errors caused by weights and biases and minimising the loss function](https://en.wikipedia.org/wiki/Gradient_descent)


