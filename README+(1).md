## Advanced Regression Assignment
>A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

 
>The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Multiple linear regression is performed on the dataset.
- The project is done as part of coursework in the Machine Learning module.
- We are trying to find which variables are significant in predicting the price of a house, and how well those variables describe the price of a house
- The Surprise housing dataset is being used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- LotFrontage :  If the Linear feet of street connected to property area increases then the Price increase
    
- BsmtFullBath	: :  If the BsmtFullBath area is more the SalePrice is higher
    
- Overall Condition: If the Overall Condition is Excellent the SalePrice is higher
    
- MSZoning_RH : If the house is near residential area then the SalePrice is higher
    
- Overall quality: If the Overall quality is Excellent the SalePrice is higher
    
- Exterior1st_CBlock : If the house Exterior is CBlock then price is less
    
- Garage Area: If the Garage Area is more the SalePrice is higher
    
- CentralAir: If the CentralAir is Yes the SalePrice is higher

These variables tells about the linear relation with respect to the price by which the company can improve their sales. For instance they can concentrate in investing in properties which may have high SalePrice in future

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn
- numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

## Contact
Created by [@miltonnepoli] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
