Wearable Computing 
========================================================

## What's done here
The purpose of this project is to show how to to collect, clean, and  work with a data set. Concretely, the `run_analysis.R` does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 


## How the different scripts fit together

- `run_analysis.R` Downloads and unzips the data from the above url and stores it in the `current directory for further analysis and contains the *full code and can be run to reproduce the results*
- `CodeBook.md` describes the variables, the data, and transformations performed to clean up the data
