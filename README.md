# PDA_Project2020
Programming for Data Analytics Project 2020

For this project, I create a data set of simulated data relating to the phenomenon of football team performance. It contains 488 observations, with each observation representing one match. The four variables in the data set are Possession, Shots, BMI (Body Mass Index) and Result. *Result* is a categorial variable with three categories - Win, Lose and Draw. *Possession* and *Shots* are both non-zero, numerical variables while BMI is a continuous variable representing average team BMI. I based the simulation largely on a pre-existing data set containing data from the 2017/2018 Premier League season and which can be found in this repository. I draw the Result, Possession and Shots data from this data set while I add BMI because there is a lack of interesting continuous variables in the pre-existing data set. 

The jupyter notebook in this repository details the process I undertook to generate the final simulated data set. I examine the properties and relationships between each variable in the pre existing data set, while for the BMI variable, I research its characteristics and likely relationship with Possession, Shots and Result. Based on these variable properties, I generate simulated data using the `numpy.random` package. 

The jupyter notebook is divided into 3 sections:
* Phenomenon chosen
* Investigation of variables
* Simulation
