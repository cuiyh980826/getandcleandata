==================================================================
Program for Coursera Data Science "Getting and Cleaning Data"
==================================================================
Written by Cui Yuhong
cuiyh.bit@gmail.com
==================================================================

The purpose of this project is to demonstrate the ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. The raw data comes from here:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

The dataset useful for run_analysis.R includes the following files:
====================================================================

- 'README.txt'

- 'features_info.txt': Shows information about the variables used on the feature vector.

- 'features.txt': List of all features.

- 'activity_labels.txt': Links the class labels with their activity name.

- 'train/X_train.txt': Training set.

- 'train/y_train.txt': Training labels.

- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 

- 'test/X_test.txt': Test set.

- 'test/y_test.txt': Test labels.

- 'test/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 

Output:
=======
1. run_analysis.R: a programe file for analysis the raw datasets and create a tidy dataset
2. meanresult.txt: an output dataset with 180*68 matrix
3. meanfeature.txt: detail information about variables in the output dataset
4. readme.md: explain  how the program work

These files will be submitted to the github repo:

Function by run_analysis.R
===========================
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation
for each measurement. 
3. Uses descriptive activity names to name the activities in the data
set 
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy 
data set with the average of each variable for each activity and each
subject.

Notes: 
======
- raw datasets from test/x and train/x is 10299*561
- test/y and train/y is values for activity ranging from 1 to 6
- test/subject and train/subject is 30 observed people
- pay attention to integer to character when Step 3

License:
========
All information can be public freely used and distributed for academic and education purpose, no responsibility implied or explicit can be addressed to the authors or their institutions for its use or misuse. Any commercial use is prohibited.

Cui Yuhong. August 2015.
