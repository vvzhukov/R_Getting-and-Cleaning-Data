## Codebook for the Getting and Cleaning Data Project

Run_analysis script will read the 'Human Activity Recognition Using Smartphones Data Set' .

1. It merges both training and test sets (/train/X_train.txt and /test/X_test.txt).
2. It includes the subjects who performed the activities (/train/subject_train.txt and /test/subject_test.txt).
3. It does NOT include the Inertial Signals.
4. It properly labels all the data.
5. It subsets the data using only subjects and measurement that are mean values or standard deviation values.
6. It does NOT use in the data subset any of the 'angle' values, although they are calculated using mean values.
7. It creates a tidy data set with the average of each of the variables on the data subset for each activity and each subject.
8. It exports the final tidy data set to a 'tidyData.csv' .

In the final file you will have a row for the average of each measured variable of the subset and each column represents a SUBJECT.ACTIVITY.
