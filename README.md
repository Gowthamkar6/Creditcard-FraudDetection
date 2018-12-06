# Creditcard-FraudDetection

We are bulding network with dense fully connected layer.Dropout is for zero noise layers

PLotting the frequencies of fraud and non-fraud transactions in the data

Converting dataset into array

Splitting the data into train and test and observing their dimensions

Obtaining the fraud and non-fraud records in train

Now consider only the non-fraud records for training

Separating out the fraud records from the train 

Adding/concatinating the fraud records from train data to the test

Separating the independent and the class variable

Expanding the dimensions of y for later concatenation

Model bulding with dropout and dense layer with input, hidden and output layer with adam optimizer

Getting the errors from the non fraud data separately 

Getting the errors from the fraud data separately

Obtaining predictions for non fraud records

Obtaining preictions for fraud records

Identifying the error computation method by autoencoder(Mean Squared Error). The computation is as follows 

Computing errors on the non-fraud data

Computing errors on the fraud data

Computing the distribution of errors in both non-fraud and fraud data

Experimentation to fix a threshold for classification of a transaction into fraud or non-fraud



