Objective:

Create a Vanilla network for MNIST data set and define the network architecture such that:
1. It has 3x3 convolution
2. It has 1x1 convolution
3. It has a transitional layer (i.e. MaxPooling)
4. Use ReLU for activation function
5. Use SoftMax at the final layer

The main objective at this level is to define the architecture of the network and then work towards tuning the network using different techniques. Here in the First scetion we are not concerned about the number of parameters or the validation accuracy of the network.

The proposed network Architecture:

![Basic Archtecture](https://github.com/rashidmeras/rashidmeras.github.io/blob/master/images/eva/S4_Proposal1_Fig1.png)

The above figure shows the propsed network architecture. As shown in the figure there are a total of 11 layers in the network. Starting from 32 channels at Layer1 the cahnnel size is doubled at each layer and at Layer9 the channles size increses maximum upto 1024 channels.

Using this architecture we derive two Network Type1 and Network Type2 which are explored in detail.
