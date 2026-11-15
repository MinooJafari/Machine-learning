# CO2 Emissions Prediction 🚗

## 📌 Project Overview
This project uses **Simple Linear Regression** to predict vehicle CO2 emissions based on fuel consumption data.

The goal is to explore the relationship between fuel consumption and CO2 emissions and build a machine learning model that can estimate CO2 emissions for different vehicles.

## 📊 Dataset
The dataset (`co2.csv`) contains 500 vehicle records with the following features:

| Feature | Description |
|---|---|
| engine | Engine size |
| cylandr | Number of cylinders |
| fuelcomb | Combined fuel consumption |
| out1 | CO2 emissions (Target Variable) |

## 🛠️ Technologies & Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## ⚙️ Project Workflow

### 1. Data Exploration
- Loaded the dataset using Pandas.
- Used `df.describe()` to analyze statistical information.
- Explored the distribution of CO2 emissions.

### 2. Data Visualization
- Used Seaborn to create a count plot.
- Created a correlation heatmap to examine relationships between variables.
- Visualized the relationship between fuel consumption and CO2 emissions.

### 3. Feature Selection
Selected `fuelcomb` (combined fuel consumption) as the independent variable.

Selected `out1` (CO2 emissions) as the target variable.

The `engine` and `cylandr` features were excluded from the model.

### 4. Model Training
- Used an 80/20 train-test split.
- Implemented Simple Linear Regression using Scikit-learn.
- Trained the model using the training dataset.

### 5. Prediction & Visualization
- Predicted CO2 emissions for the test dataset.
- Compared actual values with predicted values.
- Visualized the regression line and test data points.

### 6. Real-World Prediction
Used the trained model to estimate CO2 emissions for a Peugeot 206 with a combined fuel consumption of 6.4 L/100 km.

## 🤖 Machine Learning Model

**Algorithm:** Simple Linear Regression

**Independent Variable:** Fuel Consumption (`fuelcomb`)

**Dependent Variable:** CO2 Emissions (`out1`)

**Training Data:** 80%

**Testing Data:** 20%

## 🎯 Key Learning Outcomes
- Understanding Simple Linear Regression.
- Exploring and analyzing datasets with Pandas.
- Visualizing correlations using Seaborn.
- Splitting datasets into training and testing sets.
- Training machine learning models with Scikit-learn.
- Making predictions using a trained regression model.

## 📁 Project Structure

```text
CO2-Emissions-Prediction/
│
├── co2.csv
├── CO2_Emissions_Prediction.ipynb
└── README.md
```
