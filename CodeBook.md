## Code Book 
### Peer Assessments /Getting and Cleaning Data Course Project
==================================================================
Human Activity Recognition Using Smartphones Dataset
Version 1.0 - Extract / Transform / Analyse
==================================================================
##  variables
activity : subject activity during training : 6 possible values :
* WALKING
* WALKING UPSTAIRS
* WALKING DOWNSTAIRS 
* SITTING
* STANDING
* LAYING
Subject : Identifier of the subject from 1 to 30
mean : mean of mean value for a given subject & activites
## data
This set containt results of 30 subjects with 6 sorts of activities
## transformations
activity (former an integer) was transform with factor() function
data was order by activity & subjects
mean represent the mean of the mean for a given activity and subject
