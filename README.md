# CIFAR-10
Initially, the model consisted of 2 convolution layers, the training accuracy and validation accuracy were as low as 60%. 
But, increasing the learning_rate increased the training accuracy, but validation accuracy didn't have any improvement due to overfitting. 
Adding a new layer, reducing kernel size of filter increased the performance. 
Finally, data augumentation allowed significant increase in the validation accuracy and reducing overfitting.(Transforms in keras)
