README

This dataset is a tidy type data of Human Activity Recognition Using Smartphones Dataset Version 1.0 [1] This dataset is made for the assignment of week 4, Data Science Specialization course3

The dataset includes the following files

‘README.md’ that explains the analysis files is clear and understandable.
‘run_analysis.R’ is the code for merging, extracting and rearrangement of the original data to make a tidy data.
‘tidy.txt’ is the output of ‘run_analysis.R’
‘codebook.md’ indicate all the variables and summaries calculated, along with units, and any other relevant information.
'run_analysis.R' is consist of following 8 steps

**** Check before running ‘run_analysis.R’

Be sure your working directory. Fix the directories properly before running read.table.
'dplyr’ and ‘tidyr’ packages should be installed for my ‘run_analysis.R’.
Read the datasets of Human Activity Recognition Using Smartphones Dataset Version 1.0 (each file names is used to each vector names)
'features.txt': List of all features.
'activity_labels.txt': Links the class labels with their activity name.
'train/X_train.txt': Training set.
'train/y_train.txt': Training labels.
'train/subject_train.txt': Each row identifies the subject
'test/X_test.txt': Test set.
'test/y_test.txt': Test labels.
’Test/subject_train.txt': Each row identifies the subject
Headering to each variable of each datasets

Merges the training and the test sets to create one data set

Extracts only the measurements on the mean and standard deviation for each measurement.

Uses descriptive activity names(‘activity_labels.txt') to name the activities in the data set

Appropriately labels the data set with descriptive variable names(‘features.txt’).

From the data set in step 6, creates a second, independent tidy data set(’Tidy.txt’) with the average of each variable for each activity and each subject.

Test ‘Tidy.txt'

Reference

[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012
