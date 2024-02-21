# Project Name
> Advance Linear Regression Assignment: 
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
This assignment helps the company to identify below, 
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
  A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and    flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

- What is the business probem that your project is trying to solve?
This model will be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- What is the dataset that is being used?
train.csv provided as part of the problem statement

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
•Training MSE: Ridge regression has a lower training MSE (0.0152) compared to Lasso regression (0.0171), indicating that Ridge regression fits the training data slightly better.
•Test MSE: Lasso regression has a lower test MSE (0.0229) compared to Ridge regression (0.1133), indicating that Lasso regression performs better on unseen data. This suggests that Lasso regression might be better at generalizing to new data.
•Overfitting: Ridge regression seems to be overfitting more than Lasso regression, as evidenced by the significant increase in test MSE compared to training MSE. Lasso's test MSE is closer to its training MSE, indicating better generalization.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- SkLearn
- StatsModel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@GargIshani] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->