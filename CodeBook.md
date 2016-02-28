Code Book
Project Description
In this code book, it includes information about the source data, the transformations performed after collecting the data and some information about the variables of the resulting data sets.

Source Data
The source data for this project can be found in The UCI Machine Learning Repository.

Study Design
1.Download the test data and the trainaing data.
2.Merges the training and the test sets to create one data set.
3.Extracts only the measurements on the mean and standard deviation for each measurement.
4.Uses descriptive activity names to name the activities in the data set.
5.Creates another independent tidy data set with the average of each variable for each activity and each subject.
6.Prodcued "calculated_tidy_data_tex" as the second expected ouput.


Variables
subjectId: 1 to 30 each representing a participant in the study

•	tBodyAcc-mean()-X 
•	tBodyAcc-mean()-Y 
•	tBodyAcc-mean()-Z 
•	tBodyAcc-std()-X 
•	tBodyAcc-std()-Y 
•	tBodyAcc-std()-Z 
•	tGravityAcc-mean()-X 
•	tGravityAcc-mean()-Y 
•	tGravityAcc-mean()-Z 
•	tGravityAcc-std()-X 
•	tGravityAcc-std()-Y 
•	tGravityAcc-std()-Z 
•	tBodyAccJerk-mean()-X 
•	tBodyAccJerk-mean()-Y 
•	tBodyAccJerk-mean()-Z 
•	tBodyAccJerk-std()-X 
•	tBodyAccJerk-std()-Y 
•	tBodyAccJerk-std()-Z 
•	tBodyGyro-mean()-X 
•	tBodyGyro-mean()-Y 
•	tBodyGyro-mean()-Z 
•	tBodyGyro-std()-X 
•	tBodyGyro-std()-Y 
•	tBodyGyro-std()-Z 
•	tBodyGyroJerk-mean()-X 
•	tBodyGyroJerk-mean()-Y 
•	tBodyGyroJerk-mean()-Z 
•	tBodyGyroJerk-std()-X 
•	tBodyGyroJerk-std()-Y 
•	tBodyGyroJerk-std()-Z 
•	tBodyAccMag-mean() 
•	tBodyAccMag-std() 
•	tGravityAccMag-mean() 
•	tGravityAccMag-std()
•	tBodyAccJerkMag-mean() 
•	tBodyAccJerkMag-std() 
•	tBodyGyroMag-mean()
•	tBodyGyroMag-std() 
•	tBodyGyroJerkMag-mean() 
•	tBodyGyroJerkMag-std()
•	fBodyAcc-mean()-X 
•	fBodyAcc-mean()-Y 
•	fBodyAcc-mean()-Z 
•	fBodyAcc-std()-X 
•	fBodyAcc-std()-Y 
•	fBodyAcc-std()-Z 
•	fBodyAccJerk-mean()-X 
•	fBodyAccJerk-mean()-Y 
•	fBodyAccJerk-mean()-Z 
•	fBodyAccJerk-std()-X 
•	fBodyAccJerk-std()-Y 
•	fBodyAccJerk-std()-Z 
•	fBodyGyro-mean()-X 
•	fBodyGyro-mean()-Y 
•	fBodyGyro-mean()-Z 
•	fBodyGyro-std()-X 
•	fBodyGyro-std()-Y 
•	fBodyGyro-std()-Z 
•	fBodyAccMag-mean() 
•	fBodyAccMag-std() 
•	fBodyBodyAccJerkMag-mean() 
•	fBodyBodyAccJerkMag-std() 
•	fBodyBodyGyroMag-mean() 
•	fBodyBodyGyroMag-std() 
•	fBodyBodyGyroJerkMag-mean() 
•	fBodyBodyGyroJerkMag-std() 


Activity Name
The activity that the subject was doing at the time of the measurement.
Links the class labels with their activity name. (from: https://github.com/dholtz/GettingAndCleaningData/blob/master/project_data/activity_labels.txt)

•	WALKING 
•	WALKING_UPSTAIRS 
•	WALKING_DOWNSTAIRS 
•	SITTING 
•	STANDING 
•	LAYING 
