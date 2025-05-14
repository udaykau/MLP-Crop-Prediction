# Crop Export Value Prediction using Multi-Layer Perceptron (MLP)

This project leverages data science and machine learning techniques to predict crop export values for different countries using a Multi-Layer Perceptron (MLP) neural network. The workflow includes data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and future prediction.

## Table of Contents

- [Overview](#overview)
- [Data Sources](#data-sources)
- [Features](#features)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)
- [License](#license)

## Overview

The goal of this project is to build a predictive model for crop export values based on a variety of economic, agricultural, and environmental indicators. The model is trained on historical data and can be used to forecast future export values for a given country and year.

## Data Sources

The project uses multiple datasets from FAOSTAT, including:

- Consumer Prices Indicators
- Crops Production Indicators
- Food Balances Indicators
- Food Trade Indicators
- Land Temperature Change
- Pesticides Use
- Emissions
- Exchange Rate
- Land Use
- Food Security Indicators

All datasets are expected to be in CSV format and located in the project directory.

## Features

Key features used for prediction include:

- Year
- Total crop products value
- Export Quantity value
- Import Value
- Rodenticides usage
- Dietary energy
- Food production variability
- Food supply variability
- Land area value
- Exchange rate value

## Project Structure

- `MLPCropPrediction.ipynb` — Main Jupyter notebook containing all code for data loading, preprocessing, analysis, modeling, and prediction.
- `data/` — Directory for all input CSV files (not included in this repository).
- `predictions_output.csv` — Output file containing true and predicted export values.
- `data.csv` — Preprocessed and merged dataset used for modeling.

## How to Run

1. **Install Dependencies**  
   Ensure you have Python 3.8+ and the required libraries:
   ```sh
   pip install pandas numpy matplotlib seaborn tensorflow scikit-learn
