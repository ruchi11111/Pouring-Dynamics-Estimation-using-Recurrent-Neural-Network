# Pouring-Dynamics-Estimation-using-Recurrent-Neural-Network

Designed a Recurrent Neural Network using TensorFlow and Keras to estimate the response to a sequence of a robot pouring water in a cup actions. 
The dataset consisted of 688 motion sequences that included features like velocity, angle of pouring, weight before pouring, height, etc., with their respective measurements. 
Achieved a loss of approximately 0.00037 on train data and 0.00039 on validation data. 

There are two files, train.py and test.py used for training and testing respectively. 
The test file takes in model checkpoint as well as scalar variable as a .sav file to test the dataset.
