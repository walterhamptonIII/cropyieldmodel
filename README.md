# U.S. Corn Belt Corn Yield Prediction

A machine learning framework developed as a Master's thesis research project at Jean Monnet University, focused on forecasting agricultural corn yields across U.S. Corn Belt counties using historical climate metrics and environmental data.

## Overview

Accurate crop yield forecasting is critical for global food security, supply chain logistics, and agricultural market analysis. This repository contains the complete end-to-end data pipeline and machine learning experimentation framework used to predict annual corn yields at the county level. By integrating multi-source climate metrics with historical agronomic data, the models capture non-linear weather-yield relationships across key agricultural regions in the United States.

## Key Features

* **County-Level Granularity:** Analyzes agricultural data and climate features mapped specifically to U.S. Corn Belt counties.
* **Climate-Driven Modeling:** Incorporates seasonal temperature anomalies, precipitation totals, and localized meteorological indices.
* **Robust ML Pipeline:** Implements data ingestion, automated feature engineering, model training, and performance evaluation workflows.
* **Master's Thesis Research:** Developed as part of the Master's in Machine Learning and Data Mining (MLDM) program requirements, culminating in an August 2026 thesis defense.

## Tech Stack

* **Language:** Python
* **Data Processing & ML:** Pandas, Scikit-Learn, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Version Control:** Git

## Project Structure

```text
├── data/               # Raw and processed multi-county agricultural datasets
├── notebooks/          # Exploratory data analysis and feature engineering experiments
├── report/            # Evaluation metrics, performance plots, and saved model artifacts
└── README.md
