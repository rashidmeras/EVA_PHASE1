## Architectural Basics

In this "Third" section using the network defined in previous section we explore different techniques and reduce the total number of parameters such that it is not more than 15K and the validation accuracy is above 99.2%

![Proposed Network Archtecture](https://rashidmeras.github.io/images/eva/S4_Proposal3_Fig1.png)

The Figure1 above shows the network architecteure that we have established so far. We named this network as Network Type3. We will re-examine this network in this section and explore its characteristics.

As shown in the Figure we can divide this network into different blocks, namely Block1, Block2 and Transitional Block. Layer1-4 can be grouped into Block1, Layer6-9 can be grouped into Block2 and the remaining Max-Pooling layer5 can be called as Tranisitional Block. Also we can see the total number of channels in each layer.

One of the merits of doing this segmentation of the network is that now we can play around with channel size of each block and observe how the network performs. In this "Third" section we will see how changing the channel size in Block1 and Block2 we can redesign the network Type3 and create a new *Network Type4*

![Proposed Network Archtecture](https://rashidmeras.github.io/images/eva/S4_Proposal3_Fig2.png)


Compared to the network architecture proposed in the previous section, following are the changes proposed here in Network Type4:

> 1. At each layer of we perform Convolution followed by Batch Normalization and then Drop-Out as shown in Figure2.
> 2. The channel size are reduced only per block i.e only in Block1

Tune in to the colab notebook to see how Network Type4 performs.
