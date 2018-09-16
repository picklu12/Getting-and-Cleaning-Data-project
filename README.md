# Getting and Cleaning Data - Project

This is the course project for the Getting and Cleaning Data .
The R script, `run_analysis.R`, does the following:

1. Download the dataset frfom the website if it does not already exist in the working directory
2. Read the file and Load the activity and feature information 
3. Loads both the training and test datasets, keeping only those columns which
   reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset and merges the two datasets
5. Converts the `activity` and `subject` columns into factors and creates a tidy dataset that consists of the average value of each
   variable for each subject and activity pair.

The out put result is shown in the file `tidy.txt`.