# Introduction

The script `run_analysis.R`performs the below steps described in the course project's definition.

* Download the file from website and unzip the dataset
* Then, read the  activity labels file and features file.
* Extract only the data on mean and standard deviation a
* merge the test and train  data set adatasets and add labels

* Finally, we generate a new dataset with all the average measures for each subject and activity type . The output file is called `tidy.txt`, and uploaded to this repository.

# Variables

* `activityLabels`, `features`, 'train`, `trainActivities` ,`trainSubjects`, 'test', `testActivities` and `testSubjects` contain the data from the downloaded files.
* 'train`, `trainActivities` ,`trainSubjects` merge  to do further analysis.
* 'test', `testActivities` and `testSubjects` merge to do further analysis
*  merge test data and train data and create `allData` , a big dataset.
* Finally, melt and decast and crete `allDta.mean` contains the relevant averages which will be later stored in a `tidy.txt` file. 

## Activity Labels

* `WALKING` (value `1`): subject was walking during the test
* `WALKING_UPSTAIRS` (value `2`): subject was walking up a staircase during the test
* `WALKING_DOWNSTAIRS` (value `3`): subject was walking down a staircase during the test
* `SITTING` (value `4`): subject was sitting during the test
* `STANDING` (value `5`): subject was standing during the test
* `LAYING` (value `6`): subject was laying down during the test