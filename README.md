# Project Name
> US-based housing company analysis to enter the Australian market 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. 
The company uses data analytics to purchase houses at a price below their actual values and 
flip them on at a higher price. For the same purpose, the company has collected a data set from 
the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. 
You are required to build a regression model using regularisation in order to predict the actual 
value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- As per below matric Ridge and Lasso have better R2-squared value
- Lasso shows below minimum MSE on Train and Test dataset, 
	Hence Lasso is suggested as bette model.

Metric	Linear Regression	Ridge Regression	Lasso Regression
0	R2 Score (Train)	8.228888e-01	8.004744e-01	8.043567e-01
1	R2 Score (Test)	7.876792e-01	8.000501e-01	8.026647e-01
2	RSS (Train)	1.130093e+12	1.273113e+12	1.248341e+12
3	RSS (Test)	5.984713e+11	5.636012e+11	5.562315e+11
4	MSE (Train)	3.326934e+04	3.531186e+04	3.496663e+04
5	MSE (Test)	3.696448e+04	3.587145e+04	3.563615e+04

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas library - version 1.4.2
- Numpy library - version 1.21.5
- scikit-learn - version 1.0.2
- matplotlib - version 3.5.1
- Seaborn - version 0.11.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project is done for study purose.
Thanks for dataset !! :-)

## Contact
Created by [@RatneshFlash] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->