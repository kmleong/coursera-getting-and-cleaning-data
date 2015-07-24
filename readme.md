Getting and Cleaning Data


About this Project:

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 


Synopsis of the data used:  

One of the most exciting areas in all of data science right now is wearable computing. Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from this project represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: 

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Here are the data for the project: 

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

 

How to run the run_analysis.R

1. Please ensure that you have install package plyr in R Studio. 


2. Create a folder and set it as working directory using setwd() function in R Studio


3. Put the run_analysis.R into that folder


4. In the R Studio, type the following command:
4a.	source("run_analysis.R")
4b.	run_analysis()


5. The script will automatically download the dataset to reproduce a new tidy dateset through following steps:

5a. 	Download and exact the dataset into the data folder

5b. 	Merges the training and the test sets to create one data set
i.	Read and merge the Activity files, subject files and features files
ii.	set names to variables
iii.	Merge columns to get the data frame Data for all data

5c. 	Extracts only the measurements on the mean and standard deviation for each measurement
i. 	Subset Name of Features by measurements on the mean and standard deviation
ii.	Subset the data frame Data by seleted names of Features

5d. 	Uses descriptive activity names to name the activities in the data set
i. 	Read descriptive activity names from "activity_labels.txt"
ii. 	Names of Features will labeled using descriptive variable names

5e.	Appropriately labels the data set with descriptive variable names

5f.	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject


6. Once it is done, it will create a new file in the working directory, that is tidydata.txt


