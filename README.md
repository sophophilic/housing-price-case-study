# Housing Price Case Study
##### Background:
* A US-based housing company named Surprise Housing has decided to enter the Australian market.
* The company is looking at prospective properties to buy to enter the market.

##### Company Info
* The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
* The company has collected a data set from the sale of houses in Australia.

##### High Level Requirements
* Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
* The company wants to know the following -
    1. Which variables are significant in predicting the price of a house, and
    2. How well those variables describe the price of a house
    3. Determine the optimal value of lambda for ridge and lasso regression

##### Business Goal (Objectives)
* Create a model for the price of houses with the available independent variables.

##### Why is this needed ?
* It will be used by the management to understand how exactly the prices vary with the variables.
    * The model will be a good way for management to understand the pricing dynamics of a new market.
* The Management can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns

## Table of Contents
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The variables significant in predicting the price of a house are -
1. RoofMatl_CompShg        |Roof Material is "Standard (Composite) Shingle"
2. RoofMatl_Tar&Grv     --> Roof Material is "Gravel & Tar"
3. GrLivArea            --> Above grade (ground) living area square feet
4. RoofMatl_WdShngl     --> Roof Material is "Wood Shingles"
5. RoofMatl_WdShake     --> Roof Material is "Wood Shakes"
6. MSZoning_RL          --> Residential Low Density
7. OverallQual          --> Overall material and finish of the house
8. RoofMatl_Membran     --> Roof Material is "Membrane"
9. RoofMatl_Metal       --> Roof Material is "Metal"
10. RoofMatl_Roll       --> Roof Material is "Roll"


- Optimal value of lambda for Ridge Regression = 4
- Optimal value of lambda for Lasso = 0.001

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - v3.9.0
- Seaborn - v0.12.2
- pandas - v2.0.1
- numpy - v1.24.3
- matplotlib - v3.7.1
- sklearn - v0.0.post5
- statsmodels - v0.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@sophophilic] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
