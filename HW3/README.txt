Problem 1 (30pts)

For this homework, we will use CIFAR-10, which comes with all three RGB input channels. 
Here is the link for loading CIFAR-10:

https://www.datascienceweekly.org/tutorials/cifar10-pytorch-load-cifar10-dataset-from-torchvisionLinks 
to an external site.

Train the based line VGG model we need for FashinMNIST on CIFAR-10 and report your classification 
accuracy for validation set, as well as training loss and training accuracy. For this training resize 
the network input to 64*64 resolution.

Use Table 1 in the VGG paper (Simonyan and Zisserman, 2014) to construct other common models, such as 
VGG-16 or VGG-19. Train them on CIFAR-10, compare the accuracies, computational complexity and model size.


Problem 2 (30pts)

Use the CIFAR-10 to train a baseline classifier based on the GoogleNet model we did in lectures for 64*64 
input resolution. Report your classification accuracy for the validation set, as well as training loss 
and training accuracy.

Add batch normalization layer to GoogleNet (think about what is the best way of adding it). Train it again.
Report your classification accuracy for the validation set, as well as training loss and training accuracy. 
Compare your accuracy against Problem 2.1.
 

Problem 3 (40pts)

The baseline model we did in homework is called ResNet-18. Train that for CIFAR-10 and report and compare 
your validation accuracy against GoogleNet and VGGNet architectures you did. Can you compare the training 
time, model size and computation complexity across these three networks for CIFAR-10? Use 64*64 resolution 
across all training.

Build two new versions of ResNet (ResNet-26, and ResNet-32). Train them on CIFAR-10. Plot the training loss, 
training accuracy and validation accuracy. Compare the classification accuracy, computation complexity, and
model size across these three versions of ResNet (18, 26, 32). How does the complexity grow as you increase
the network depth?
