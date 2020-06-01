Getting and Cleaning Data - Course Project
The R script, run_analysis.R, are explained as following:

Manually downloaded the dataset and kept it in working directory.
Unzipped the zipped folder and view the data to develop a rough understanding about the data.
Load the activity and feature info.
Load both the training and test datasets, keeping only those columns which reflect a mean or standard deviation.
Loads the activity and subject data for each dataset, and merges those columns with the dataset.
Merges the two datasets.
Converts the activity and subject columns into factors.
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
The end result is shown in the file tidy.txt.