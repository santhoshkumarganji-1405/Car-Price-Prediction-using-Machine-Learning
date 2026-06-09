# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict the price of a car based on various features such as engine size, horsepower, mileage, fuel type, car body, and other vehicle specifications. A Machine Learning Regression model is trained using historical car data to estimate car prices with high accuracy.

The project demonstrates the complete Machine Learning workflow including data preprocessing, feature engineering, model training, evaluation, visualization, and model deployment preparation. The final model achieved an **R² Score of 0.955**, indicating excellent predictive performance. 

---

## 🎯 Objective

* Analyze car-related features affecting vehicle prices.
* Perform data preprocessing and feature encoding.
* Build a Machine Learning regression model.
* Predict car prices accurately.
* Evaluate model performance using standard regression metrics.
* Visualize important factors influencing car prices.

---

## 📂 Dataset

**Dataset Name:** CarPrice_Assignment.csv

The dataset contains **205 car records** with **26 attributes**, including:

* Car Name
* Fuel Type
* Aspiration
* Door Number
* Car Body
* Drive Wheel
* Engine Location
* Wheelbase
* Car Length
* Car Width
* Car Height
* Curb Weight
* Engine Type
* Cylinder Number
* Engine Size
* Fuel System
* Bore Ratio
* Stroke
* Compression Ratio
* Horsepower
* Peak RPM
* City MPG
* Highway MPG
* Price (Target Variable)

The dataset contains **205 entries with no missing values**, making it suitable for machine learning analysis. 

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Joblib
* Google Colab

---

## 📋 Project Workflow

### 1. Data Collection

* Imported the Car Price dataset.
* Loaded data using Pandas.

### 2. Data Exploration

* Examined dataset structure.
* Checked data types and statistical summaries.
* Verified missing values.

### 3. Data Preprocessing

* Removed unnecessary columns.
* Encoded categorical variables using Label Encoding.
* Prepared features and target variables.

### 4. Model Training

* Split dataset into training and testing sets.
* Used an 80:20 train-test split.
* Trained a Random Forest Regressor model.

### 5. Model Evaluation

Evaluated the model using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### 6. Data Visualization

* Feature Importance Plot
* Actual vs Predicted Price Scatter Plot

### 7. Model Saving

* Saved trained model using Joblib.

---

## 🤖 Machine Learning Algorithm

### Random Forest Regressor

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

Benefits:

* High accuracy
* Handles nonlinear relationships
* Robust against overfitting
* Works well on structured datasets

---

## 📊 Model Performance

| Metric   | Value      |
| -------- | ---------- |
| MAE      | 1307.67    |
| MSE      | 3522224.16 |
| RMSE     | 1876.76    |
| R² Score | 0.9554     |

The model achieved an **R² Score of 95.54%**, showing excellent predictive capability on unseen data. 

---

## 📈 Visualizations

### Feature Importance Analysis

Shows which car attributes have the greatest influence on price prediction.

### Actual vs Predicted Prices

Compares real car prices with model predictions to evaluate performance visually.

---

## 📁 Project Structure

```text
CodeAlpha_Car_Price_Prediction
│
├── dataset
│   └── CarPrice_Assignment.csv
│
├── notebook
│   └── Car_Price_Prediction.ipynb
│
├── images
│   ├── feature_importance.png
│   └── actual_vs_predicted.png
│
├── model.pkl
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/CodeAlpha_Car_Price_Prediction.git
```

Move into the project directory:

```bash
cd CodeAlpha_Car_Price_Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the notebook:

```bash
jupyter notebook Car_Price_Prediction.ipynb
```

Or run it directly in Google Colab.

---

## 📦 Requirements

```text
pandas==2.3.0
numpy==2.3.1
matplotlib==3.10.3
scikit-learn==1.7.0
joblib==1.5.1
```

---

## 🚀 Future Improvements

* Hyperparameter tuning using GridSearchCV.
* Deploy model using Flask or Streamlit.
* Add advanced feature engineering.
* Compare multiple regression algorithms.
* Build a web interface for price prediction.

---

## 📚 Learning Outcomes

Through this project, I learned:

* Data preprocessing techniques
* Feature encoding methods
* Regression modeling
* Model evaluation metrics
* Data visualization
* Machine Learning workflow implementation
* Real-world price prediction applications

---

## 🙌 Acknowledgements

This project was completed as part of the **CodeAlpha Machine Learning Internship Program**.

**Author:** Santhosh Ganji
**Domain:** Machine Learning
**Internship:** CodeAlpha

⭐ If you found this project useful, consider giving it a star on GitHub!
