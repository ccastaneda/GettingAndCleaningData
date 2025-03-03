# GettingAndCleaningData

<P>
This repo is for the final project in this course. Following are the instructions to process, clean the data given to generate one more data product: tidy.txt

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

You should create one R script called run_analysis.R that does the following:
<OL>
<LI> Merges the training and the test sets to create one data set.
<LI>Extracts only the measurements on the mean and standard deviation for each measurement.
<LI>Uses descriptive activity names to name the activities in the data set
<LI>Appropriately labels the data set with descriptive variable names.
<LI>From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each
activity and each subject.
</OL>
<p>The process goes as follows: 

<OL>
<LI> Download the data. 
<LI> unzip the datafile. 
<LI> Read files:
<UL>
<LI>activity_labels.txt a file with two columns V1 (id 1-6); V2(txt WALKING ..) describing the activities measured in the original data. 
<LI>features.txt a file with two columns V1 (id 1-561); V2 (txt fBodyBodyGyroJerkMag-meanFreq()...) presenting the variables 
measured, their name and numerical value. 
</UL>
<LI> While required to extract the values for the mean and std, the variable names were also modified to add clarity 
to the descriptive activity names in the data set from "tBodyAcc-std()-Z" to "tBodyAccSTDZ" . 
<LI> Read the datasets train and test and appropriately label the data set with descriptive variable names. 
<LI> Merge the data 
<LI> Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
</OL>
