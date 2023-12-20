# Time Series Forecasting Project

## Introduction

Hello and welcome to my Time Series Forecasting Project! This is a personal project focused on understanding and applying time series models for forecasting. Specifically, the project targets time and demand forecasting in the context of oil prices and demand, utilizing data from the OPEC repository.

## Project Overview

The main aim of this project is to compare traditional time series forecasting models with the latest neural networks, determining their efficacy in different scenarios, especially in non-seasonal data contexts. A significant part of this project involved creating a dataset from scratch, meticulously selecting and processing data from over 50 datasets in the OPEC repository, which included various factors affecting oil price and demand.

## Challenges and Methodology

One of the primary challenges was the creation and handling of the dataset. The data spans from 1983 to 2022 and includes key metrics like GDP, population, exports, oil trade, spot prices, etc. A comprehensive Exploratory Data Analysis (EDA) was conducted to understand the data and identify relevant features. This project tested five different models: a traditional machine learning model (SVR), a BILSTM, a CNN, and two traditional time series forecasting models - ARIMA and Holt-Winters.

## Key Findings

- **Model Performance**: The Holt-Winters linear model outperformed others, including ARIMA, neural networks, and general machine learning models. This was particularly notable since the dataset was non-seasonal, and these models adapted well to this kind of data.

- **Data Insights**: The analysis revealed fluctuations in spot prices, production, and demand, reflecting global economic and political events. Country-specific analyses also showcased diverse economic and resource management strategies.

## Future Scope

The project's future scope includes improving the Root Mean Squared Error (RMSE) of our models and possibly integrating additional features from other repositories. Continuous enhancement of the forecasting models and exploring new methodologies remain core objectives.

## Conclusion

This project was a deep dive into the world of time series forecasting, providing valuable insights into oil price and demand prediction. It serves as a starting point for countries and companies worldwide to utilize these findings for their pricing strategies and demand estimation.

## File Structure

```
/Time-Series-Forecasting-Project
├── Data                  # Contains the datasets used for the project
├── Final Report          # Comprehensive report detailing the project
└── Src                   # Source code for the project
```

## How to Use This Repository

1. **Data Source**: Access the OPEC dataset [here](https://asb.opec.org/data/ASB_Data.php).
2. **Models Tested**: Check out the various models implemented and their configurations.
3. **Results**: Explore the results and findings detailed in the analysis sections.
