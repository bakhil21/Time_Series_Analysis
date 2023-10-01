# Terrain-Identification-from-Time-Series-Data-using-CNN-LSTM
A Convolutional Neural Network - Long short Term Memory based classifier to identify terrain a person is walking on using Time-Series IMU data.

In order to prepare the training set, we first read the CSVs from all the sessions for all the subjects. We then preprocess the data by running the following sections of the script - 
1. Reading the dataset
2. Preparing the data
3.Stacking up the data from all the sessions and subjects.
4. Dealing with imbalance in the data.
Running these 4 sections would give us the training data in its required shape and form. One thing to note is that we remove the extra time steps from training data manually to keep the number of time steps in training data and labels equal.

Test data is prepared the same way.To create the test data, we read the and preprosess them by running the following section of the code-
1. Preparing the test data
2. Processing the test data
We run these sections after replacing the required variables in them.

We can run the model by executing the CNN-LSTM section of the code.
