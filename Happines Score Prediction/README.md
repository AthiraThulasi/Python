# HAPPINESS SCORE PREDICTION

## INTRODUCTION

Happiness is very important part of an individual's life because it can improve ones lives in many ways and contribute to a more positive and thriving society. How happy are people today? What are the factors that contribute to the happiness of individuals in a country? How satisfied are people in different societies? And how do our living conditions affect all of this?Let's see whether we can find answer to some of the questions.

This Project aims to find the factors that contribute to happiness score and predict happiness score of individuals in different countries using Linear Regression. The project uses data from the World Happiness Report which includes various predictors such as GDP, social support, Family, perception of corruption, freedom to make life choices and Trust in govt corruption. The Project utilizes Happiness data set from 2018 to 2021 which includes the Happiness Scores of different countries across the globe.

## DATA SET SOURCE

Happiness Score data set uses data from the Gallup World Poll which happens every year. The Gallup World Poll consists of more than 100 global questions as well as region-specific items.

https://worldhappiness.report/ed/2018
https://worldhappiness.report/ed/2019/
https://worldhappiness.report/ed/2020/
https://worldhappiness.report/ed/2021/

## DATA SET

Happiness Score data set includes different factors that contribute to the happiness score of an individual.

Total Number of Observations: 614

Number of Predictors/Features : 6

Response Variable : Happiness Score

## Features are as follows:

GDP per Capita
Family
Health Life Expectancy
Freedom
Generosity
Trust Government Corruption
Happiness Score
OBJECTIVE

**Objective is to perform different analysis to understand about the dataset, clean the data set and build a model to make predictions on happiness score**

(1) Missing values - Is there missing values in data set?

Yes, Happiness score dataset contains missing values. Mean imputation is done to to handle missing values in the data set by replacing missing values with the mean of the non-missing values of the same feature.

(2) Outliers - Any outliers present? How to remove those?

BOXPLOT is used to identify outliers.Find z-scores for each data point. Any rows with z-scores above a certain threshold are removed.The resulting DataFrame contains only the non-outlier rows.

(3) Is any scaling required for the features in dataset?

The dataset was found to have features within a similar range and therefore scaling is not necessary.Scaling is important when features have vastly different ranges, but this was not the case in the current dataset.

(4) Is the data set require any record linkage to link matching entities?

Since the dataset contains only numerical values, there are no text or categorical values that need to be matched or linked to identify the same entities across different records.

(5) Relevance of using Jaccard Metric to compare the similarity of column names between data sets?

The Jaccard metric is used to measure the similarity between two sets of data. Since the column namesrepresenting same features have different names across data sets, jaccard metric is used for comparison to determine how similar or dissimilar the columns are between the two datasets.

(6) Prediction - Predicting happiness score using Linear Regression model with all features

(7) Tried a different model with less feature variables

(8) Determined the coefficients of model to see which all factors have highest contribution to happiness score

(9) Find the Adj Rsquare and MSE to compare model perfomance

(10) Tried MLP and KNN regression for score prediction.
