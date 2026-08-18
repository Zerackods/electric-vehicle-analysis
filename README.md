# Electric Vehicle Analysis

## Overview

Analysis of electric vehicle population data using Python.

## Objective

Identify the most common electric vehicle type and evaluate whether
the vehicle type can be predicted using available characteristics.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Analysis

- Data cleaning
- Exploratory data analysis
- Data visualization
- Feature analysis
- Predictive modeling

## Results

An analysis of 112,328 electric vehicles registered in Washington State revealed that BEVs dominate the market with a 76.4% share compared to 23.6% for PHEVs;
Tesla accounts for 46.2% of the total, Seattle leads in adoption, and 2022 saw the highest number of registrations, confirming a trend of sustained growth since 2020. 
A KNN model (K=3) predicted the vehicle type with 99.93% accuracy and an F1-score of 99.91%—validated against a baseline classifier of 76.43%
demonstrating that "electric_range" is the most discriminating variable, given the minimal physical overlap between the two types.

## Conclusion

Tesla’s 46.2% market concentration signals a genuine opportunity for other brands in the long-range BEV segment, where demand exists but product variety is limited. 
The top 10 cities—led by Seattle—should be prioritized for fast-charging infrastructure investment, as they already possess a critical mass of users.

