# Getting-and-Cleaning-Data-Project
Contains the run_analysis R file for the final project

The script works by reading a Sumsang data set "UCI HAR Dataset". This contains human activity recognition using smartphones.

The script:
1. Reads activity files
2. Reads subject files
3. Reads features files
4. combines data tables by rows
5. names the variables
6. Merges the training and the test sets to create one data set
7. Extracts only the measurements on the mean and standard deviation for each measurement
8. Uses descriptive activity names to name the activities in the data set
9. Appropriately labels the data set with descriptive variable names
10. creates a second, independent tidy data set with the average of each variable for each activity and each subject
