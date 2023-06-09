# Building a light model with high accuracy on MNIST data

The objective is to reach 99.4% Validation accuracy on MNIST dataset with less than 20k parameters & less than 20 Epochs

Method used to reach a Model with an maximum of 16 kernels with barch normalizations are used. We also used an adaptive average pooling in the last layer. Here is the code block with the model

![image](https://github.com/KartikS07/ERAV1S6/assets/135399864/7d28b71b-4707-4472-baa7-16791d27672d)


Using Pytorch summary, we can identify that the total number of parameters are 11,050.
![image](https://github.com/KartikS07/ERAV1S6/assets/135399864/ccabcaf3-ca5e-4961-82f3-90a711e580c6)


We were able to reach a test accuracy of 99.44 on the 17th epoch using an LR scheduler at the end of every 6 epochs decreasing the LR to 10% of previous value starting from 0.01. We also used a batch size of 32.
![image](https://github.com/KartikS07/ERAV1S6/assets/135399864/42549b7d-e1f3-4ec2-b4bd-543c40972c2c)

