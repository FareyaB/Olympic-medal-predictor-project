## Olympic Winner Prediction

This repository contains a project that predicts which country or athlete is most likely to win medals in future Olympic Games based on historical data, team strengths, and other key factors. The project utilizes advanced machine learning techniques and data analysis to build predictive models for Olympic outcomes.

## Features:
*Historical Data Analysis*: Aggregates and analyzes past Olympic Games results to identify trends.
*Predictive Modeling*: Uses machine learning algorithms to forecast medal winners.
*Data Visualization*: Provides interactive visualizations for medal trends, country performance, and athlete analysis.
*Factors Considered*: Includes variables such as team rankings, athlete performance, training data, and other relevant predictors.
*Flexible Input*: Allows custom input of future games data to improve predictions for upcoming Olympic events.

## Goals:
To provide sports analysts, fans, and researchers with tools to make data-driven predictions about Olympic outcomes and better understand the factors behind winning performances.

## Project Steps

1. Form a hypothesis.
2. Find and explore the data.
3. (If necessary) Reshape the data to predict your target.
4. Clean the data for ML.
5. Pick an error metric.
6. Split your data.
7. Train a model.


## File overview:

* `machine_learning.ipynb` - the main project code
* `data_prep.ipynb` - the code to generate the team-level dataset from an athlete-level dataset


## Installation

To follow this project, please install the following locally:

* Python 3.8+
* Python packages
    * pandas
    * numpy
    * scikit-learn
    * seaborn


## Data

I am using data from the Olympics, which was originally on [Kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results).

* [teams.csv](https://drive.google.com/uc?export=download&id=1L3YAlts8tijccIndVPB-mOsRpEpVawk7) - the team-level data that we use in this project.
* [athlete_events.csv](https://drive.google.com/uc?export=download&id=1Ah4wOyNFMGREq8Yw_Jbv7u2CeI_6tpn5) - this is the original athlete-level data