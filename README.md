# Steel Industry Energy Consumption Optimization
### Project Overview
This repository contains the baseline machine learning analysis conducted during Week 2 of my AI/ML internship at ITSimplera Solutions. The objective of this project is to predict factory electricity usage (Usage\_kWh) based on operational metrics, contributing to energy optimization efforts.
### Key Achievements
Data Profiling & Cleaning: Performed a comprehensive analysis of a 35,040-row dataset, utilizing an Interquartile Range (IQR) framework to identify and mitigate extreme consumption outliers.
Feature Analysis: Identified Carbon Dioxide emissions (CO_2(tCO_2)) as the most significant predictor for energy consumption, with a relative importance score nearing 1.0.
Model Benchmarking: Implemented and compared two primary regression models:
Linear Regression: Established a baseline with an R^2 score of ~0.67 and an MAE of ~3.49 kWh.
Decision Tree Regressor: Outperformed the baseline with an R^2 score of 99% and an MAE of ~0.26 kWh.
Technologies Used
Python
Pandas & NumPy
Scikit-Learn
