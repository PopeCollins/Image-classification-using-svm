# Image-classification-using-svm
Image classification

After import tensorflow library, I initate a command to use 70% of GPU for the classificaion 
Then imprted ImageDataGenerator for data augumentation. I did the augumentation of train data set is to add noise (systemaically or randomly alter the image) to increase the size of the data to make it robust enough to cover any aspect or possible ways the data could be generated. This will as well help our model to be trained enough to produce an outcome that incoporate different data from different possible ways


Then i created the CNN list. Also, using the loss function as hinge and the addition of regularizer made our final layer an SVM layer 

# CONCLUSION
Increaing epoch to 15, give us a test accuracy of 81% 


Further, I made a single prediction of one image of a dogs. Having created a library to classify an array result less than zero to classify as a cat then result greater than zero as a dog. 

