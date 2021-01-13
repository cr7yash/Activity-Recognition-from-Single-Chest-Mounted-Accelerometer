# Activity-Recognition-from-Single-Chest-Mounted-Accelerometer

The Activity Recognition from Single Chest-Mounted Accelerometer dataset mainly comprises of uncalibrated accelerometer data mounted on 15 respondents(users). The experiment analyses 7 activities performed by each respondent wearing the accceloremeter. The activities in the dataset are identified by numbers and following is the information of the numbers assigned to each of the activity:

1. Working at computer is identified as 1
2. Standing up, Walking and going updown stairs is identified as 2
3. Standing is identified as 3
4. Walking is identified as 4
5. Going upDown stairs is identified as 5
6. Walking and talking with someone is identified as 6
7. Talking While Standing is identified as 7

## Preparing the data

In order to prepare the data I have read all the 15 data files at once. Moreover, while appending each file I have added one column representing the respondent number.

## Data Exploration
The data exploration will help in understanding the dataset which is much neededto derive insights from the dataset. We see that after performing different explorations for different columns, each exploration showcases a new insight about the data.
It also helps in understanding the nature of the respondents and profile the subjects of their behaviour.

## Identifying the activities
For this, I have taken into account the x,y,z acceleration trends with respect to the activities performed by the respondents. This helps in understanding and infering the type of activity they are performing at a given time period.

## Data Modelling

Decision tree classifier:
 Decision Tree With Kfold Cross Validation:
 
KNN (KNearst Neighbor) Classifier:
  KNN with KFold Cross Validation
