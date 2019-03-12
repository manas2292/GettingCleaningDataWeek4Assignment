# Source Data Information:
A full description is available at the site where the data was obtained: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

# File with R code "run_analysis.R" perform 5 following steps:

1. Merging the training and the test sets to create one data set.
Reading files
Reading trainings tables
Reading testing tables
Reading feature vector
Reading activity labels
1.2 Assigning column names
1.3 Merging all data in one set

2.Extracting only the measurements on the mean and standard deviation for each measurement
2.1 Reading column names
2.2 Create vector for defining ID, mean and standard deviation
2.3 Making nessesary subset from setAllInOne

3.Using descriptive activity names to name the activities in the data set

4.Appropriately labeling the data set with descriptive variable names

5.Creating a second, independent tidy data set with the average of each variable for each activity and each subject
5.1 Making second tidy data set
5.2 Writing second tidy data set in txt file
