# Code Book

## Overview
This CodeBook describes the variables, data, and transformations performed to clean up the dataset.

## Variables

- **subject**: ID of the subject (1-30)
- **activity**: Activity performed (Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying)
- **measurement variables**: Sensor signals (Accelerometer, Gyroscope) that have been transformed to show Mean and Standard Deviation.

## Data Processing

1. Merged the training and test sets.
2. Extracted measurements on the mean and standard deviation for each measurement.
3. Applied descriptive activity names.
4. Cleaned variable names to be more descriptive.
5. Created a tidy dataset with the average of each variable for each subject and activity.
