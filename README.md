# Housing Price Prediction
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on ata higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.<br/><br/>
Please find the dataset [link](https://github.com/srikanth24y/House-Price-Prediction/blob/main/train.csv)<br/>
Please find the data definition [link](https://github.com/srikanth24y/House-Price-Prediction/blob/main/data_description.txt)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Ridge model optimal lambda λ = 3.5
- Lasso Model optimal lambda λ = 0.001
- Ridge Model Train R-Square: 0.94 and Test R-Square: 0.90
- Lasso Model Train R-Square: 0.94 and Test R-Square: 0.90
##### Both Ridge and Lasso perform almost equally, since lasso can help in feature elimination and model may be more robust hence we are going to consider Lasso.
##### Top 10 Significant features
<table>
    <thead>
        <tr style="background: #72A0C1; color: #fff; font-weight: 600;">
            <th>Features</th>	
            <th>Coefficient</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>OverallQual_10</td><td>1.300821</td></tr>
        <tr><td>OverallQual_9</td><td>1.006531</td></tr>
        <tr><td>Neighborhood_StoneBr</td><td>0.397361</td></tr>
        <tr><td>GrLivArea</td><td>0.363124</td></tr>
        <tr><td>Neighborhood_Crawfor</td><td>0.351231</td></tr>
        <tr><td>SaleType_New</td><td>0.324428</td></tr>
        <tr><td>OverallQual_8</td><td>0.316113</td></tr>
        <tr><td>OverallCond_9</td><td>0.252729</td></tr>
        <tr><td>Exterior1st_BrkFace</td><td>0.245535</td></tr>
        <tr><td>Functional_Typ</td><td>0.217962</td></tr>
    </tbody>
</table>
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.21.6
- matplotlib - version 3.2.2
- seaborn - version 0.11.2
- plotly - version 5.5.0
- statsmodels - version 0.10.2
- sklearn - version 1.0.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@srikanth24y] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
