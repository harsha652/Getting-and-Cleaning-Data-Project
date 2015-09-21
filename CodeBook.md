Step1 : Merge the training and test sets to create one data set

x_test_data - This variable has the data present in X_test file
y_test_data - This variable has the data present in y_test file
subject_test_data - This variable has the data present in subject_test file

x_train_data - This variable has the data present in X_train file
y_train_data - This variable has the data present in y_train file
subject_train_data - This variable has the data present in subject_train file

x_data - It is the row merge of x_test_data and x_train_data
y_data - It is the row merge of y_test_data and y_train_data
subject_data - It is the row merge of subject_test_data and subject_train_data

Step2 : Extract only the measurements on the mean and standard deviation for each measurement

features - This variable has the data present in features file
x_data - Has the columns related to mean and std

Step3: Use descriptive activity names to name the activities in the data set

activities - This variable has the data present in activity_labels file
y_data is updated with the activity names 

Step4: Appropriately label the data set with descriptive variable names
all_data - It has all the datasets

Step5: Create a second, independent tidy data set with the average of each variable, for each activity and each subject
averages_data - It is the data set which contains average of each variable, for each activity and each subject
