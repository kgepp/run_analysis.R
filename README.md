How the scipt works

    Merges the training and the test sets to create one data set
    Extracts only the measurements on the mean and standard deviation for each measurement
    Uses descriptive activity names to name the activities in the data set
    Appropriately labels the data set with descriptive activity names
    Creates a second, independent tidy data set with the average of each variable for each activity and each subject

How to run_analysis.R

    Requires dplyr, data.table, and tidyr libraries
    Load both test and train data
    Load the features and activity labels
    Extract the mean and standard deviation column names and data
    Process the data
    Merge the data sets
