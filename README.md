# Contributers
Peibin Rui(prui@wisc.edu)

Nolan Toole(ntoole@wisc.edu)

Nilay Varshney(nvarshney2@wisc.edu)

# Description
Initiated models on the data set from the Kaggle Facial Expression Recognition Challenge, which comprises 48-by-48-pixel grayscale images of human faces with 28709 training examples https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data


Shuffled and split the data set 80:10:10 for training set, validation set and test set and constructed AlexNet, VGG-19 and ResNet architectures to compare the performances based on the accuracy of test set which are 51.83%, 45.31%, 59.40% correspondingly and provided confusion matrices for each architecture which indicated that happy expression achieved highest accuracy


Launched the model on Google Colab using GPU with Pytorch being the main package used and each architecture was trained for 30 epochs with minibatches of size 64, Adam optimizer with an initial learning rate of 0.0003, exponential decay rates of 0.9, 0.999 and cross-entropy loss function
