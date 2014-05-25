Getting-and-Cleaning-Data
=========================


Here are the data for the project: 

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

 You should create one R script called run_analysis.R that does the following. 
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement. 
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive activity names. 
Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
Good luck!

-------------------------------

Steps Taken:

Unzip the data : https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Save into a local Directory


Save run_analysis.R in a folder with the dataset

in RStudi set the working directory to the location of the dataset

and then: source("run_analysis.R")

The R script will read the dataset and write these files:

merged_clean_data.txt

data_set_with_the_averages.txt 


Use data <- read.table("data_set_with_the_averages.txt") to read "data_set_with_the_averages.txt ". It is 180x68 because there are 30 subjects and 6 activities.

