# covariate-shift-in-image-similarity-tasks


Data Set used: https://www.kaggle.com/crawford/emnist
Data Files Used: emnist-letters-train.zip, emnist-letters-test.zip

# Task

Train a Siamese Network on EMNIST Dataset. 
The letters section of the dataset has 26 classes.
Train the network on any of the 20 classes, and test it on the remaining 6.
The final evaluation should contain code to compare any two images from the 6 test classes and predict them to be belonging to the same or different classes.

So this can clearly be seen that out test data is entirely different from our train data and has a differerent distribution from train data.

# Results
able to achieve train_accuracy: 97.46% and val_accuracy: 95.90% in 30 epochs. (on 20 classes)
on the test data, able to achieve 72% Accuracy on test data that includes totally unseen classes(rest other 6 classes) to model.

Here I have attached my google colab notebook for your reference. It includes every detail of steps taken.
