# 🏙️ NYC Airbnb Price Analysis

## Project Overview

This project analyzes how different listing characteristics influence Airbnb prices in New York City. We focus on three key explanatory variables:
- **Room Type** (categorical: Entire home/apt, Private room, Shared room)
- **Number of Reviews** (continuous)
- **Availability (days per year)** (continuous)

Our research aims to provide insights for Airbnb hosts looking to optimize their pricing strategies, and for travelers seeking affordable yet comfortable accommodations.

## Research Question

> **How do different listing characteristics (room type, number of reviews, and availability) influence Airbnb prices in New York City?**

## Dataset

- **Source**: [New York City Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- **Relevant Variables**:
  - **Response Variable (Y)**:
    - `Price` (US dollars)
  - **Explanatory Variables (X)**:
    - `Room Type` (Entire home/apt, Private room, Shared room)
    - `Number of Reviews` (total number of reviews)
    - `Availability` (days available per year)
- **Other Variables (unused)**:
  - Listing ID, Name, Host ID, Host Name, Neighborhood Group, Neighborhood, Latitude, Longitude, Minimum Nights, Last Review, Reviews per Month, Calculated Host Listings Count

## Features

- **Exploratory Data Analysis (EDA)**: Gain insights into the distribution of room types, reviews, and availability.
- **Statistical Analysis**: Analyze the influence of key variables on Airbnb prices using regression models.
- **Visualization**: Visualize relationships between variables using charts and graphs.
- **Data Cleaning**: Handle missing data, outliers, and data preprocessing for better analysis.
- **Predictive Modeling**: Create models to predict Airbnb pricing based on selected features.

## Project Structure

```bash
📁 NYC-Airbnb-Price-Analysis/
│
├── README.md          # Project overview (this file)
├── data/              # Raw and cleaned dataset
├── notebooks/         # Jupyter notebooks for EDA and analysis
├── results/           # Figures, tables, and outputs
├── src/               # Source code for statistical models
└── report/            # Final written report and appendix
