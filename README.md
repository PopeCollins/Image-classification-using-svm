# Image-classification-using-svm
Image classification

In this project i used SVM in a convolutional neural network to do image classification

After import tensorflow library, I initate a command to use 50% of my GPU for the classificaion 

Then imported ImageDataGenerator for data augumentation. I did this data augumentation of train data set  to add noise (systemaically or randomly alter the image) to increase the size of the data to make it robust enough to cover any aspect or possible ways the data could be generated. This will as well help our model to be trained enough to produce an outcome that incoporate different data from different possible ways

Then i created the CNN list. Also, using the loss function as hinge and the addition of regularizer made our final layer an SVM layer 



# CONCLUSION
Increasing epoch to 15, the test data give us a test accuracy of 81% and i was able to test the few of the images to check if the model could classified the object


Further, I made a single prediction of one image of a dog and a cat. Having created a library to classify an array result less than zero to classify as a cat then result greater than zero as a dog. 

The model work perfectly and was able to classify the image as a cat and dog.

