# Global-Emissions-Analysis-A-Focus-on-BRICS-Countries-1949-2022-
Analyzed greenhouse gas emissions across BRICS nations (1949–2022) using Python and Tableau; built regression and time-series models explaining over 95% of CO₂ variability and supporting data-driven sustainability insights.

## Overview

This project presents a comprehensive analysis of greenhouse gas emissions across BRICS nations (Brazil, Russia, India, China, South Africa) from 1949 to 2022.
Using Python, Tableau, and machine learning models, it identifies emission trends, pollutant correlations, and future forecasts to support sustainable policy decisions.

## Objectives

Analyze historical emission trends across BRICS countries.

Identify the major contributors to CO₂ and other greenhouse gases.

Forecast future emission levels using time-series models.

Recommend actionable policies for sustainability and renewable energy adoption.

## Methodology

Data Collection – Historical emissions data from EDGAR, World Bank, and SIPRI (1949–2022).

Exploratory Data Analysis (EDA) – Identified top pollutants, emission growth patterns, and country-level drivers.

## Modeling & Forecasting

Multiple Linear Regression – Predicted CO₂ levels based on other gases.

ARIMA – Forecasted emission trends up to 2030.

Random Forest Regression – Feature importance and pollutant impact modeling.

Visualization – Developed interactive dashboards in Tableau/Power BI.

## Key Findings

CO₂ emissions in China and India continue to rise sharply due to industrialization.

SO₂ and Organic Carbon (OC) are the strongest predictors of CO₂ emissions.

Random Forest Regression achieved R² = 0.992, explaining 99.2% of CO₂ variability.

ARIMA forecasts indicate continued growth through 2030, with India showing the steepest curve.

## Results Summary

| Model                     | Technique         | Accuracy / R² | Key Insights                                |
|----------------------------|------------------|----------------|---------------------------------------------|
| Multiple Linear Regression | Statistical      | 0.93           | Weight of industrial pollutants significant |
| Random Forest Regression   | Machine Learning | 0.95           | SO₂ & OC most influential on CO₂            |
| ARIMA                      | Time Series      | —              | Predicts 10–15% rise by 2030                |
