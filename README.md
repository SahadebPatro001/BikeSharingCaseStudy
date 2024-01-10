# Project Name
> ### **Bike Sharing Assignment**


## Table of Contents
* [General Info](#general-information)
* [Implementation Strategy](#implementation-strategy)
* [Technologies Used](#technologies-used)
* [Conclusion](#conclusion)
* [Acknowledgements](#acknowledgements)


## General Information
### Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

### Business Objectives
- Task is to create a model predicting shared bike demand using the existing independent variables.
- The management will utilize this model to comprehend how demand varies across different features, allowing strategic adjustments to meet demand levels and fulfill customer expectations.
- Additionally, the model serves as a valuable tool for the management to grasp the dynamics of demand in a new market.


## Implementation Strategy
1. Understanding Data
2. EDA
3. Data Preparation
4. Building a Model for Prediction
5. Linear regression assumptions proof
6. Model Prediction on test data
7. Calculating R squared values
8. Conclusion


## Conclusion

**Train Dataset**
- Train r square value: 0.844
- Train Adjusted r square value: 0.841

**Test Dataset**
- 0.789 is our r square test value.
- 0.833 will be the value for Adjusted R-squared for the test set.

**Observation**
- The model performs well on the training data, explaining 84.4% of the variance.
- When adjusting for the number of predictors, the adjusted value is 84.1% for the training set.
- For the test data, the model still accounts for a substantial 78.9% of the variance.
- The adjusted value of 83.3% for the test set suggests that the model's performance is consistent.
- Overall, the model is considered good as it effectively captures the variance in both training and test data.


## Technologies Used
- Python
- Python Libraries:
    - NumPy
    - Pandas
- Data Visualization
    - Matplotlib
    - Seaborn
- Editor:
    - Jupyter Notebooks
- Approach:
    - Exploratory Data Analysis (EDA)
    - Machine learning concepts
    - Simple Linear Regression
    - Multiple Linear Regression
    - Buiding a model with Linear Regression


## Acknowledgements

- This project is done as a part of IIIT PGP Case Study.
- References:
    1. **Python**
    - [Start with Python](https://www.python.org/)
    2. **NumPy**
    - [NumPy official doc](https://numpy.org/doc/stable/)
    3. **Pandas**
    - [Pandas official doc](https://pandas.pydata.org/pandas-docs/stable/)
    4. **MatPlotlib**
    - [MatPlotlib official doc](https://matplotlib.org/stable/users/index.html)
    5. **Seaborn**
    - [Seaborn official doc](https://seaborn.pydata.org/)
    6. **EDA:**
    - [Wikipedia - Exploratory Data Analysis](https://en.wikipedia.org/wiki/Exploratory_data_analysis)


## Contributors:
1. Sahadeb Patro
