# Getting-and-cleaning-data-proj
Getting and Cleaning Data Project - Asignment

Ccourse project for the Getting and Cleaning Data course. The R script, `run_analysis.R`, does the following:

Download the dataset if it does not already exist in the working directory
Load the activity and feature info
Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
Loads the activity and subject data for each dataset, and merges those columns with the dataset
Merges the two datasets

Converts the 
* `activity` 
* `subject` 
columns into factors

Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
Final result is shown in the file `tidyData.txt`
