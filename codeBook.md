Using the dataset from the zipped file UCI HAR dataset the run_analysis script can do the following:

1.Merges the training and the test sets to create one data set:
First read the required data from the UIC folder and assigned colunm names using various methods like read.table, colnames, c bind, rbind etc.

2.Extracts only the measurements on the mean and standard deviation for each measurement: 
Created a logical vector with TRUE values for ID, mean and Stdev columns and FALSE for other columns.

3.Uses descriptive activity names to name the activities in the data set:
Dataset and activity type combined using merge to get descriptive activity names.

4.Appropriately labels the data set with descriptive variable names: 
gsub function for paatern replacement to clean up the data labels.

5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject:
Produced a data set with the average of each variable for each activity.
