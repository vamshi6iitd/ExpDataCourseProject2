# Exploratory Data Analysis Course Project 2
Contains submission files of Course Project 2 of Exploratory Data Analysis course in Coursera

My code run_analysis contains 6 parts mainly, each as follows:

Part 1: #Reading Training Values & Renaming the labels descriptively

This part of the code reads Training Set Data one file after the other. It can be clearly seen from the code. We also rename all the col labels of data to descriptive labels.

Part 2: #Reading Test Values & Renaming the labels descriptively

This part of the code reads Training Set Data one file after the other. It can be clearly seen from the code. We also rename all the col labels of data to descriptive labels.

Part 3: #Creating TrainDataFrame

In this part, we create training data frame by combining all the training data that we read in part 1

Part 3: #Creating TestDataFrame

In this part, we create test data frame by combining all the test data that we read in part 2

Part 4: #MergingDataframes

In this part, we merge both data frames that we have created in part 3 & 4 namely, training data frame and test data frame

Part 5: #Cleaning Data

In this part, as we have obtained our main data frame, we first melt the dataframe considering only Activity & subject ID labels as ID and all the rest as measure.vars. Once we melt the data in such a way, we dcast it to get the mean of each observation characterized by (Activity, SubjectID). This finaltidy data set can be seen as tidyfinal

#CODEBOOK

Activity- y_train values depicting Acitivity ID performed by the subject

subID- subject_train values depicting the ID of the subject

feature1:561- 561 X_train/test values of the experiment

baccX1:128- 128 body_acc_x_train/test values of the experiment

baccY1:128- 128 body_acc_y_train/test values of the experiment

baccZ1:128- 128 body_acc_z_train/test values of the experiment

bgyroX1:128- 128 body_gyro_x_train/test values of the experiment

bgyroY1:128- 128 body_gyro_y_train/test values of the experiment

bgyroZ1:128- 128 body_gyro_z_train/test values of the experiment

taccX1:128- 128 total_acc_x_train/test values of the experiment

taccY1:128- 128 total_acc_y_train/test values of the experiment

taccZ1:128- 128 total_acc_z_train/test values of the experiment

##A common variable names for both train & test data have been created so that they merge by those specific cols when joined.


