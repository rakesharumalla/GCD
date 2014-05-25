Running the script:
========================================================


1. Download the data set and extract. It should result in a UCI HAR Dataset folder that has all the files in the required structure.
2. The training and test data are available in folders named train and test respectively.
3. Copy run_analysis.R script to this directory
4. Run the script
5. The tidy dataset should get created in the UCI HAR Dataset folder

## How it works?

High Level explanation of how the script works is given below

1. Merges the training and test data sets
2. Extracts mean and standard deviation for each measurement
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates tidy data set with the average of each variable for each activity and each subject

