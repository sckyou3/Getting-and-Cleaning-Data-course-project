# Getting-and-Cleaning-Data-course-project
It is a project for Getting and Cleaning Data Course by Johns Hopkins University on Coursera

The data used in this project was collected from the accelerometer and gyroscope of Samsung Galaxy S smartphone.

This repository contains the following files:


-<README.md>, which provides an overview of this project and data


-<tidy_data.txt>, which contains the data set


-run_analysis.R, the R script used to create the data set


The R script run_analysis.R can be used to create the data set. 
This script has following steps
*Download source data and unzip it
*Read Data
*Mergest the training and the test sets to create one data set
*Extracts only the measurements on the mean and standard deviation for each measurement
*Uses descriptive activity names to name the activities in the data set
*Appropriately labels the data set with descriptive variable names
*From the data set in step4, creates a second, independent tidy data set with the average of each variable for each activity and each subject

The tidy_data.txt in this repository was created by  running the run_analysis.R script using R version 3.5.2 on Windows 10 pro 64-bit edtion.

The script requires the dplyr package
