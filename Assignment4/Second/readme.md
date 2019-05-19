## Architectural Basics

Using the network defined in "First" section we explore different techniques and reduce the total number of parameters such that it is not more than 20K and the validation accuracy is above 99.2%.

![Proposed Network Archtecture](https://rashidmeras.github.io/images/eva/S4_Proposal2_Fig1.png)

Here in this "Second" section we propose Network Type3 as shown in the figure above.

These are the salient features of this network:

1. The network architecture is basically the same except that the number of layers are reduced. In this proposed network architecture we stop at Receptive Field of 7x7.
2. The channel size are reduced and now the largest channel size is 32 and the smallest channel size is 12
