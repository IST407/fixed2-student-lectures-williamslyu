## Predicting Property Values: A Comprehensive Analysis and predictions of Real Estate Trends in Queens, New York City

## Introduction
The objective of this project is to predict property values in Queens, New York City, using machine learning models. By analyzing various features such as property characteristics, neighborhood data, and historical trends, we aim to provide accurate and actionable predictions for real estate prices. This study will explore the application of advanced regression techniques to capture complex relationships in real estate data, which are often influenced by multiple variables such as location, amenities, and economic indicators.
Our approach leverages the power of machine learning to improve upon traditional methods of real estate valuation, offering a more dynamic and adaptable model. This project is innovative because it incorporates diverse data sources, including both structured and unstructured data, to create a comprehensive analysis. We believe that by applying machine learning algorithms such as decision trees, random forests, or neural networks, we can significantly enhance prediction accuracy, which will be valuable to real estate professionals, investors, and policymakers.
The potential impact of this project is significant. By improving the accuracy of property value predictions, stakeholders can make more informed decisions regarding investments, pricing strategies, and urban development planning. If successful, this project could serve as a model for similar predictive analyses in other regions.


## Literature Review

## StakeHolders
This project addresses the needs of several key stakeholders, each with unique priorities.
Real Estate Agents, Home Buyers,  Investors, Urban Planners

## Data and Methods
This section will introduce your data and specify your modeling approach.
Data:
https://www.nyc.gov/site/finance/property/property-rolling-sales-data.page


There are 23,288 rows, 21 columns. The data features each property’s address information (street address, zip code, block number, lot number). It also includes the sale price of each property and the neighborhood. We anticipate needing one dataset as the city provided a large amount of data for us to work with. We know this data is reliable as the city records accurate property sale data in order to ensure proper tax assessments and maintain up-to-date public records. 
## Methods
Data Preprocessing:
Data Preprocessing and Transformations
Given the nature of real estate data, several preprocessing steps are essential to ensure that our models perform effectively:

Handling Missing Data

Encoding Categorical Variables

Feature Scaling

Feature Engineering

Handling Date Features


Modeling Techniques:
The following models will be applied to the preprocessed data:

Linear Regression:

Decision Trees:

Random Forest Regressor:

Neural Networks:

## Evaluation Metrics
Consistent with stakeholder needs, our evaluation will focus on metrics that reflect how well our models can predict property values and support decision-making. The following metrics will be used:

Mean Absolute Error (MAE): 

Root Mean Squared Error (RMSE)

R-squared (R²)

