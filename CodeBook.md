#There are three core variables:

1. Main
2. Test 
3. Train

*Main : activity_labels Inertial Signals Inertial Signals 

*Test: features subject_test subject_train 

*Train: features.info X_test X_train

#4 basic level data sets will be defined and created:

*test data set
*train data set
*features data set
*activity labels data set

###Below steps are performed in the run_analysis.R script


Reading training tables - xtrain / ytrain, subject train

Reading the testing tables

Read the features data

Read activity labels data

Create Sanity and Column Values to the Train Data

Create Sanity and column values to the test data

Create sanity check for the activity labels value

At this stage the data sets have been created with the right coloumn names.

Now Merge the train and test data

Create the main data table merging both table tables

Use the grepl function to get the data and create a data set associated with the requirements.

Get the average of each variable for each activity using the aggregate function

The last step is to write the ouput to a text file 

