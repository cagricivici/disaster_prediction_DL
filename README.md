# Deep Learning Project with Titanic Dataset from Kaggle
It was focus on examining the effect of different batch sizes. The purpose of this repo is to visualise results in a page csv file.
 
Train.csv file is prepared for training model. This file contains 891 passengers with its personal information such as sex, cabin, age, fare, embarked, cabin class which is called 'feature'. Each feature could effect the results - survived or died. 

Test.csv file is prepared for testing model which is trained. This file contains 418 passengers. Actually Kaggle serves us to use raw dataset but we divide 2 part for train and test. Our division coefficient is set as 0,67. 

Our tensor: 7 - 3 - 1 ('activation function: softplus')(3 layers)  
Optimizer: Adam
Loss function: binary cross entropy
LR: 0,001



As result, my project is to present training models according to different batch size (2 and 2^n). In myresults.csv, each batch size has values which means who can survive or die.  





