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
a.	source("run_analysis.R")
b.	run_analysis()
5. The system will automatically download the dataset to reproduce a new tidy dateset.
6. Once it is done, it will create a new file in the working directory, that is tidydata.txt


