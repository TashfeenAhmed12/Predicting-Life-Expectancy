# Predicting-Life-Expectancy
Predictive Model to predict Life Expectancy for a Country based on various health and social-economic factors

# Objective
The goal is to develop a predictive model using the Life Expectancy dataset from the World Health Organization (WHO) to estimate life expectancy based on various health factors and socio-economic indicators. This solution will assist healthcare organizations and policymakers in identifying key areas for improvement in public health. According to [National Library of Medicine](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5387671/#:~:text=3-,Projections%20of%20future%20mortality%20and%20life%20expectancy%20are%20needed%20to,comparison%20of%20a%20few%20models.), projections of future mortality and life expectancy are needed to plan for health and social services and pensions

**Usage**: The solution will be used to analyze trends, identify significant health determinants, and guide policy decisions aimed at improving life expectancy in different countries.

**Current Solutions**: Presently, life expectancy projections are based on statistical analysis and epidemiological models, which may not always incorporate a wide range of socio-economic factors.

**Problem Framing**: This is a supervised learning problem, where the model will be trained with historical data to predict life expectancy. 

**Performance Measurement**: The model's performance can be measured using Mean Squared Error (MSE) or Root Mean Squared Error (RMSE) to quantify the prediction accuracy for life expectancy.

The success of this model aligns with the broader goal of improving public health outcomes by providing insights into factors influencing life expectancy, thereby aiding effective policy-making.

# Data Acquistion
**Data Requirements**: The required data includes a dataset containing information on health indicators, socio-economic factors, and life expectancy for various countries.

**Data Source**: The data was sourced from Kaggle, specifically from the dataset titled "Life Expectancy (WHO)." Kaggle is a reputable platform for sharing and accessing datasets.

https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who

Latitude and longitude dataset was sourced from Kaggle

https://www.kaggle.com/datasets/paultimothymooney/latitude-and-longitude-for-every-country-and-state

**Data Size**: The dataset was examined to determine its size, which includes the number of rows and columns. It was found to be of manageable size for analysis.

# Attribute Information
**Country**:Country Name

**Year**: Year

**Status**: Developed or Developing Status

**Life Expectancy**: Life Expectancy in age

**Adult Mortality**: Adult Mortality Rates of both sexes (probability of dying between 15 and 60 years per 1000 population)

**Infant Deaths**: Number of Infant Deaths per 1000 population

**Alcohol**: Alcohol, recorded per capita (15+) consumption (in litres of pure alcohol)

**Percentage Expenditure**: Expenditure on health as a percentage of Gross Domestic Product per capita(%)

**Hepatitis B**: Hepatitis B (HepB) immunization coverage among 1-year-olds (%)

**Measles**: Measles - number of reported cases per 1000 population

# Results and Insights
Some key questions answered:

* Does various predicting factors which has been chosen initially really affect the Life expectancy? What are the predicting variables actually affecting the life expectancy?

* How does Infant and Adult mortality rates affect life expectancy?

* Does Life Expectancy has positive or negative correlation with eating habits, lifestyle, exercise, smoking, drinking alcohol etc.
  
* What is the impact of schooling on the lifespan of humans?

* Does Life Expectancy have positive or negative relationship with drinking alcohol?

* Do densely populated countries tend to have lower life expectancy?

* Do developed countries have higher average life expectancy then developing?
