# Getting and Cleaning Data Course Project

## Project Description

R script called ```run_analysis.R``` that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps to work

1. Download the data source and have a ```UCI HAR Dataset``` folder.
2. Put ```run_analysis.R``` in the parent folder of ```UCI HAR Dataset```.
3. Install required packages and run ```run_analysis.R```, it will generate a new file ```tiny_data.txt``` in your working directory.

## Dependencies

```run_analysis.R``` file depends on ```reshape2``` and ```data.table``` R packages.