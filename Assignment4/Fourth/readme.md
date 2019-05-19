## Architectural Basics

From using different networks discussed in previous sections in this section we define a Final Network in which the total number of parameters is less than 15K and the validation accuracy is equal to or above 99.4%.

Various networks so far:

![Channel Size Constarint Types](https://rashidmeras.github.io/images/eva/S4_Proposal3_Table1.png)

Using the technique of constraining the size of the channels in Block1 and Block2 we can see in the above table different variants of this network and its the performance.

In this Final Chapter we make use of **Network Type4** (refer Row No.4) and **Network Type5** (refer Row No.5) and we will push the limits of these networks and observe the performance. 

Inorder to do this we will make use these techniques mentioned below:
1. New optimizer known as SGD along with loss method known as binary_crossentropy.
2. Learning Rate Scheduler

Tune into the colab notebook for more details and to see how these Networks are pushed for their ultimate performance. 

> * **Network Type4**: With Total params=**11,336** and Validation Accuracy=**99.9%**
> * **Network Type5**: With Total params=**5,408** and Validation Accuracy=**99.8%**
