# Renewable Energy Generation Forecasting Using Machine Learning

## Project Overview

This project predicts **solar power generation** using historical solar plant and weather sensor data. The system applies a **Random Forest Regression** machine learning model to forecast the amount of solar energy generated based on environmental factors such as temperature and irradiation.

The project demonstrates the use of **data analysis, machine learning, and forecasting techniques** for renewable energy management.

---

## Objectives

* Analyze historical solar power generation data.
* Identify factors affecting energy production.
* Build a machine learning model for forecasting solar power output.
* Evaluate prediction accuracy using performance metrics.
* Visualize actual and predicted power generation.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

---

## Dataset

**Dataset Source:** Kaggle

**Files Used:**

1. Plant_1_Generation_Data.csv
2. Plant_1_Weather_Sensor_Data.csv

The dataset contains:

* Solar power generation records
* Ambient temperature
* Module temperature
* Solar irradiation
* Date and time information

---

## Project Workflow

```text
Data Collection
       ↓
Data Preprocessing
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
Train-Test Split
       ↓
Random Forest Regression
       ↓
Prediction
       ↓
Model Evaluation
       ↓
Visualization
```

---

## Features Used

### Input Features

* Ambient Temperature
* Module Temperature
* Irradiation
* Hour
* Day
* Month

### Target Variable

* AC_POWER

---

## Machine Learning Model

### Random Forest Regressor

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

Benefits:

* High accuracy
* Handles large datasets efficiently
* Works well for regression problems
* Easy to interpret feature importance

---

## Evaluation Metrics

The model performance is measured using:

### Mean Absolute Error (MAE)

Measures average prediction error.

### Mean Squared Error (MSE)

Measures squared prediction error.

### Root Mean Squared Error (RMSE)

Shows error in the same unit as power generation.

### R² Score

Indicates how well the model explains the variance in data.

---

## Results

The model successfully predicts solar power generation based on weather conditions and time-related features.

Generated outputs include:

* Actual vs Predicted Power Graph
* Feature Importance Chart
* Prediction for New Data
* Saved Machine Learning Model

---

## Folder Structure

```text
Renewable-Energy-Forecasting/
│
├── Plant_1_Generation_Data.csv
├── Plant_1_Weather_Sensor_Data.csv
├── renewable_energy_forecasting.ipynb
├── solar_power_model.pkl
├── README.md
└── requirements.txt
```

---

## Installation

Install required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn joblib
```

---

## Running the Project

1. Download the dataset from Kaggle.
2. Upload the dataset files to Google Colab.
3. Open the notebook.
4. Run all cells.
5. View the generated predictions and graphs.

---

## Sample Output

```text
===== MODEL PERFORMANCE =====

MAE  : 145.32
MSE  : 51234.67
RMSE : 226.35
R2 Score : 0.94
```

(Note: Results may vary depending on the dataset and train-test split.)

---

## Future Enhancements

* Deep Learning using LSTM
* Real-time weather data integration
* Web dashboard using Flask
* Solar power forecasting API
* Deployment on cloud platforms

---

## Applications

* Smart Grid Management
* Renewable Energy Planning
* Solar Farm Monitoring
* Energy Demand Forecasting
* Sustainable Energy Solutions

---

## Conclusion

This project demonstrates how machine learning can be used to forecast solar power generation accurately. By analyzing historical generation and weather data, the system helps improve renewable energy management and supports sustainable power planning.
<img width="755" height="122" alt="Screenshot 2026-06-23 141300" src="https://github.com/user-attachments/assets/4a25948d-bbc2-4b7b-8e5d-7a2b1040467c" />
<img width="581" height="91" alt="Screenshot 2026-06-23 141311" src="https://github.com/user-attachments/assets/075678bd-d4a7-44a4-8910-2ff4dc50391a" />
<img width="732" height="128" alt="Screenshot 2026-06-23 141320" src="https://github.com/user-attachments/assets/447f61e8-8623-4489-a245-e7149877ad58" />
<img width="473" height="131" alt="Screenshot 2026-06-23 141328" src="https://github.com/user-attachments/assets/2e6a59cf-faa0-4283-8e72-50f4f1cc51ff" />
<img width="457" height="237" alt="Screenshot 2026-06-23 141334" src="https://github.com/user-attachments/assets/61efd504-8158-437d-99ab-c14b87ee7403" />
<img width="1273" height="698" alt="Screenshot 2026-06-23 141340" src="https://github.com/user-attachments/assets/5a50a182-618f-4f53-bb42-4de93a98f29b" />
<img width="1178" height="642" alt="Screenshot 2026-06-23 141350" src="https://github.com/user-attachments/assets/a29e9caa-bcf1-4feb-8862-b13deab0b06a" />
<img width="1123" height="760" alt="Screenshot 2026-06-23 141401" src="https://github.com/user-attachments/assets/5e8afc7e-1e43-4927-8505-22f06a6ebc55" />
<img width="457" height="127" alt="Screenshot 2026-06-23 141407" src="https://github.com/user-attachments/assets/d3390b82-e6f3-4b05-8a75-02eb8ced19c9" />
<img width="592" height="61" alt="Screenshot 2026-06-23 141412" src="https://github.com/user-attachments/assets/d136347e-6c51-455d-a155-00b127c4fb14" />
