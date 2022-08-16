# Advanced Regression Assignment
> This assignment builds a regression model using regularisation to predict the actual value of the prospective properties. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
 
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation to predict the actual value of the prospective properties and decide whether to invest in them or not.
 
#### Business Goal:
The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
 
Also, determine the optimal value of lambda for ridge and lasso regression.

#### Dataset
The Bike Sharing dataset is  day.csv and Data dictionary is readme.txt.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- In the Linear regression model, the coefficients are in higher order
- Optimal value for alpha found for the Ridge regularization model is 3
- In the Ridge regularization model with alpha 3, all the coefficients are close to zero.
- On doubling the alpha value for Ridge, the coefficients further trend towards zero.
- Optimal value for alpha found for the Lasso regularization model is 0.0001
- Number of parameters with alpha 0.0001 on Lasso is 60
- In the Lasso regularization model, many of the coefficients are zero. The remaining coefficients are trending towards zero.
- On doubling the alpha value for Lasso, the coefficients further trend towards zero.
- Number of parameters with alpha 0.0002 on Lasso is 42
- Out of LR, Ridge, and Lasso models, the Lass models give better test performance.
- Though the optimal value of alpha for the Lasso model is 0.0001, there is only a minor dip in performance on doubling alpha to 0.0002.
- It appears that the Lasso model with alpha 0.0002 is the best the model. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - version 1.3.4
- matplotlib - version 3.4.3
- seaborn - version 0.11.2
- sklearn - version 0.24.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@bijupv] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->