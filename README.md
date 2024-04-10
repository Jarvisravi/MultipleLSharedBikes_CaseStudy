# Project Name
> SharedBikes CaseStudy


## Table of Contents
* Problem Statement
* Data Description
* Data Understanding
* Data Cleaning & Pre-processing
* Visualizing Numeric Variables & Categorical Variables
* Data Preparation
* Creating Dummy Variables
* Splitting the Data into Training and Testing Sets
* Building model (RFE)
* Checking VIF to detect multicollinearity 
* Residual Analysis of the train data
* Making Predictions Using the Final Model

<!-- You can include any other section that is pertinent to your problem -->

## General Information
BoomBikes, a leading bike-sharing provider in the United States, has experienced significant revenue declines amidst the ongoing COVID-19 pandemic. Negotiating the challenging market conditions, the company is strategizing to regain momentum once the lockdown restrictions are lifted, and economic activities rebound.

With a keen focus on reviving revenue streams, BoomBikes aims to develop a comprehensive business strategy. This involves:

1. Assessing post-quarantine demand for shared bikes nationwide by crafting a linear model.
2. Identifying key variables influencing revenue generation, particularly those pivotal in predicting shared bike demand.
3. Evaluating the model's accuracy in depicting the fluctuations in bike demand based on identified variables.

This proactive approach is geared towards positioning BoomBikes to swiftly respond to increased demand post-pandemic, thereby distinguishing itself in the market and maximizing profitability.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- From R-Sqaured and adj R-Sqaured value of both train and test dataset we could conclude that the above variables can well explain almost 81% of bike demand.
- Coeffiencients of the variables explain the factors effecting the bike demand

Based on final model top three features contributing significantly towards explaining the demand are:

 - Temperature (0.4933)
 - weathersit : Light Snow, Light Rain + Mist & Cloudy (-0.2857)
 - year (0.2341)

Hence, it can be clearly concluded that the variables `temperature` , `season`/ `weather situation` and `month`  are significant in predicting the demand for shared bikes.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
* NumPy
* Pandas
* Seaborn
* Matplotlib
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [Jarvisravi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
