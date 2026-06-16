# Weather-Prediction
# Australian Weather Prediction using Machine Learning

## Overview

This project uses Machine Learning techniques to predict whether it will rain tomorrow based on historical weather data from Australia.

The model is trained on the Australian Weather Dataset and analyzes features such as temperature, humidity, rainfall, pressure, wind speed, and cloud cover to make predictions.

## Problem Statement

Weather prediction is important for agriculture, transportation, disaster management, and daily planning. This project aims to predict rainfall for the next day using historical meteorological data.

## Dataset

Dataset: Australian Weather Dataset

Features include:
- MinTemp
- MaxTemp
- Rainfall
- Evaporation
- Sunshine
- Wind Speed
- Humidity
- Pressure
- Cloud Cover
- Temperature

Target Variable:
- RainTomorrow (Yes/No)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Handling Missing Values
4. Feature Encoding
5. Feature Selection
6. Model Training
7. Model Evaluation
8. Prediction

## Models Tested

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost (if used)

## Results

| Metric | Value |
|----------|----------|
| Accuracy |83.78% |
| Precision | 83% |
| Recall | 84% |
| F1 Score | 82% |

## Project Structure

Australian-Weather-Prediction/
│
├── dataset/
├── notebooks/
├── models/
├── screenshots/
├── requirements.txt
├── weather_prediction.ipynb
└── README.md

## Installation

```bash
git clone https://github.com/yourusername/Australian-Weather-Prediction.git

cd Australian-Weather-Prediction

pip install -r requirements.txt
```

## Usage

```bash
python weather_prediction.py
```

## Future Improvements

- Deploy as a web application using Flask
- Add real-time weather API integration
- Improve prediction accuracy
- Compare deep learning approaches

## Author

Atharva Dandwate
B.Tech Student, VIT Bhopal
