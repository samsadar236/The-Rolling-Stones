# Critical Mineral Trade Analysis and Forecasting for India

## Project Overview

This project studies India’s export and import trade patterns for three critical minerals: copper, lithium, and graphite. These minerals are essential for electrification, renewable energy systems, and electric vehicle manufacturing. The goal of the project is to understand India’s dependence on foreign suppliers, evaluate long-term trade risks, and forecast future import trends using machine learning techniques.

The project combines data cleaning, exploratory analysis, key trade indicators, and predictive modeling to move from historical analysis to forward-looking insights that are relevant for mineral security and strategic planning.

---

## Problem Context

India’s demand for critical minerals has been rising rapidly due to infrastructure expansion, energy transition goals, and EV adoption. At the same time, domestic production remains limited for several of these minerals. This creates exposure to global price volatility, supply concentration, and geopolitical disruptions.

This project aims to answer three core questions.
How dependent is India on imports for critical minerals?
How have trade balances and import patterns evolved over time?
What do future import trends suggest about long-term mineral security risks?

---

## Data Description

The analysis uses official EXIM trade data published by the Directorate General of Commercial Intelligence and Statistics. The dataset covers the period from 2017 to 2024, with forecasts extending up to the next two to three years.

Each record contains information on the fiscal year, mineral type, trade flow, trade value in rupees, quantity, partner country, and relevant HS codes. Import and export datasets were cleaned, normalized, and aggregated to enable consistent analysis across minerals and time periods.

---

## Methodology

### Data Cleaning and Preparation

Raw trade files were consolidated across HS codes and years. Missing values, inconsistencies, and formatting issues were corrected. Trade values and quantities were standardized and aggregated at the mineral and year level to create clean analytical datasets.

### Exploratory Data Analysis

Exploratory analysis was conducted to study trade balance trends, import and export growth patterns, import dependency ratios, and partner concentration. Visualizations were used to identify structural trends, volatility, and periods of rapid change.

### Key Indicators

Several indicators were computed to assess mineral security. These included trade balance, import dependency ratio, net import ratio, and indicators capturing import concentration and supply risk.

---

## Machine Learning Based Forecasting

To move beyond historical trends, time series forecasting models were developed to predict future import values. Both traditional time series approaches and advanced predictive models were used to capture trend, seasonality, and volatility.

Forecasts were generated for short-term horizons of up to one year and medium-term horizons of two to three years. Model performance was evaluated using standard metrics including MAE, RMSE, MAPE, and R² score. Confidence intervals were included to reflect uncertainty and highlight potential risk zones.

---

## Key Insights

Lithium shows extremely high import dependence with strong price sensitivity. Forecasts indicate continued volatility, making lithium the most strategically vulnerable mineral in the analysis.

Graphite imports remain persistently high and stable, reflecting structural dependence. While forecasts are more predictable than lithium, high supplier concentration increases supply-chain risk.

Copper displays steadily rising import demand driven by electrification and infrastructure growth. Forecasts suggest sustained import pressure despite partial domestic production capacity.

Across all three minerals, future projections indicate continued reliance on imports under current conditions.

---

## Strategic Implications

The results highlight the need for diversification of supply sources, investment in domestic processing, and proactive policy planning. Forecast uncertainty bands help identify minerals where future shocks could have the largest economic and strategic impact.

This project demonstrates how predictive analytics can support mineral security by shifting analysis from reactive assessment to anticipatory risk evaluation.

---

## Tools and Technologies

The project was implemented using Python with libraries such as pandas, numpy, matplotlib, and time series forecasting tools. All analysis and modeling were conducted using Google Colab.

---

## Repository Structure

The repository contains separate folders for raw and cleaned data, analysis notebooks, visualizations, and final outputs. The README provides a high-level overview, while notebooks document the full analytical workflow.

---

## Conclusion

This project provides a data-driven assessment of India’s critical mineral trade and future import risks. By combining descriptive analysis with machine learning based forecasting, it offers insights that are relevant for policy makers, researchers, and analysts working on mineral security and energy transition planning.
