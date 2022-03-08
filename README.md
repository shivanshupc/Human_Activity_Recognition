# Human_Activity_Recognition
Applied ML/DL to recognise the Human Activity. </br>

This project is to build a model that predicts the human activities such as Walking, Walking_Upstairs, Walking_Downstairs, Sitting, Standing or Laying.
This dataset is collected from 30 persons(referred as subjects in this dataset), performing different activities with a smartphone to their waists. The data is recorded with the help of sensors (accelerometer and Gyroscope) in that smartphone. This experiment was video recorded to label the data manually.

Data </br>
All the data is present in 'UCI_HAR_dataset/' folder in present working directory. </br>
Feature names are present in 'UCI_HAR_dataset/features.txt' </br>
Train Data </br>
'UCI_HAR_dataset/train/X_train.txt'
'UCI_HAR_dataset/train/subject_train.txt'
'UCI_HAR_dataset/train/y_train.txt' </br>
Test Data </br>
'UCI_HAR_dataset/test/X_test.txt'
'UCI_HAR_dataset/test/subject_test.txt'
'UCI_HAR_dataset/test/y_test.txt' </br>
Quick overview of the dataset : </br>
Accelerometer and Gyroscope readings are taken from 30 volunteers(referred as subjects) while performing the following 6 Activities.

Walking </br>
WalkingUpstairs </br>
WalkingDownstairs </br>
Standing </br>
Sitting </br>
Lying. </br>
Readings are divided into a window of 2.56 seconds with 50% overlapping. </br>

Accelerometer readings are divided into gravity acceleration and body acceleration readings, which has x,y and z components each. </br>

Gyroscope readings are the measure of angular velocities which has x,y and z components. </br>

Jerk signals are calculated for BodyAcceleration readings. </br>

Fourier Transforms are made on the above time readings to obtain frequency readings. </br>
 
Now, on all the base signal readings., mean, max, mad, sma, arcoefficient, engerybands,entropy etc., are calculated for each window. </br>

We get a feature vector of 561 features and these features are given in the dataset. </br>

Each window of readings is a datapoint of 561 features. </br>
