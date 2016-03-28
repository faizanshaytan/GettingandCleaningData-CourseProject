# GettingandCleaningData-CourseProject
Getting and Cleaning Data: Week 4 | Course Project

You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Notes about How this Repo works together

1. After downloading the source data to your computer, you can unzip the zip file to get a "UCI HAR Dataset" directory with all of the necessary data to run this on your own.  As a sidenote, the run_analysis.R script in this Repo can download this and unzip the file on your computer for you.
2. Grab the script: ```run_analysis.R``` (https://raw.githubusercontent.com/faizanshaytan/GettingandCleaningData-CourseProject/master/run_analysis.R) and place it in the parent folder of the ```UCI HAR Dataset```.
3. After setting your working directory with setwd(), run ```source("run_analysis.R")```.
4. Make sure to load the libraries ```data.table``` and ```reshape2```
4. run_analysis.R will then generate two Tidy data sets.  One is titled: ```tidy-dataset.txt``` and the other is ```tidy-datasetAVG.txt```
