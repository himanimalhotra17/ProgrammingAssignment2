**Getting and Cleaning Data Course Project**

*Initial data for research*
The script is invented to analyze the data from UCI HAR Dataset. It's supposed that archive is extracted to the working directory.

The following files from the initial dataset is used:

features.txt - includes the descriptions for features measured
train/X_train.txt - includes the measurements of the features in train set (one row - 1 measurement of 561 features)
test/X_test.txt - includes the measurements of the features in test set
train/subject_train.txt - subject for each measurement from the train set
test/subject_test.txt - subject for each measurement from the test set
train/y_train.txt - activity (from 1 to 6) for each measurement from the train set
test/y_test.txt - activity (from 1 to 6) for each measurement from the test set

This is the course project for the Getting and Cleaning Data Coursera course.

The included R script, run_analysis.R, conducts the following:


1.Download the dataset from web if it does not already exist in the working directory.

2.Read both the train and test datasets and merge them.

3.Load the data feature, extract columns named 'mean'(-mean) and 'standard'(-std). Also, modify column names to descriptive . 

4.The data is appropriately labelled.

5.Generates 'Tidy Dataset' i.e 'Final Data'.The result is shown in the file FinalData.txt.
