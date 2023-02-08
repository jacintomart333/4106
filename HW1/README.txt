Problem 1 (60 points)

Develop a multi-layer perceptron with two hidden layers (you pick the dimensions of the hidden layers) for Fashionmnst dataset.

1.a. train the model from scratch (with randomized parameters) and plot the results (training loss and accuracy, validation accuracy) 
after 20 epochs. Does your network need more epochs for full training? Do you observe overfitting? Make sure to save the trained parameters 
and model.  (10pts)

1.b Report section a; this time add weight penalties (weight decays). Report and plot your training results. how do the training results 
change compared to the baseline? (15pts)

1.c Report section a; this time add dropout (dropout = 0.3). Report and plot your training results. how do the training results change
compared to the baseline? How the training results change compared to the weight penalties. (15pts)

1.d. repeat problems 1.b and 1.c; this time, load the pre-trained parameters from the storage. Plot the training results, and compare the 
training time and number of epochs needed against 1.b and 1.c. (20pts)

 

Problem 2  (60 points)

For the housing dataset, we overviewed during the lectures; please implemt the following steps.

2.a What happens if we need to standardize the continuous numerical features like what we have done in this section? (10pt)

2.b Improve the score by improving the model complexity. Please plot the training results and compare them against the baseline model we 
did in the lectures. How about the model complexity comparison and training time? (15pt)

2.c How about exploring options for weight decay and dropout over the more complex model? Please plot the results and compare them against 2.b (10pt)

2.d Submit your best predictions to Kaggle. How good are your predictions? (5pts)
