Problem 1 (20pts)

Let’s modernize LeNet as we did in the lectures. Implement and test the following changes over FashionMNIST

Replace the average pooling with max-pooling.
Replace the sigmoid layer with ReLU.

Start training from scratch based on FashinMNIST. Compare the training loss, training accuracy, and validation 
accuracy against the baseline we did in the lectures.

 

Problem 2 (40pts)

Try to change the size of the LeNet style network to improve its accuracy in addition to max-pooling and ReLU.

Adjust the convolution window size.
Adjust the number of output channels (width of each layer).
Adjust the number of convolution layers.
Adjust the number of fully connected layers.
Explore the learning rates.

For all training adjustments, restart training from scratch based on FashinMNIST. Compare the training loss, 
training accuracy, and validation accuracy against each other and the baseline in problem 1. Argue which adjustment
presents the better benefit and generalization. Measure and compare theoretical computation complexity (number of 
operations and parameters size) using ptflops https://pypi.org/project/ptflops/

 

Problem 3 (10pts)

Pick the best model from problem 2. Apply dropout to the best model. Does it improve the training? For all training 
adjustments, restart training from scratch based on FashinMNIST. Compare the training loss, training accuracy, and
validation accuracy against the best model in problem 2.

 

Problem 4 (30 pts)

AlexNet may be too complex for the Fashion-MNIST dataset, in particular, due to the low resolution of the initial 
images; try simplifying the model to make the training faster while ensuring that the accuracy stays relatively high.
Compare your training loss, training, and validation accuracy against the best model in Problem 3 and Problem 2. Also,
measure your computational saving in the number of operations as well as the number of parameters in your network using
ptflops https://pypi.org/project/ptflops/

 

Problem 5 (Extra 20 Bonus points)

Design a better model that works directly on 28 * 28 images with better accuracy than AlexNet, but with lower
theoretical computational complexity (operation and parameter size). 
