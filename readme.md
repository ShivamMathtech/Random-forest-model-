---
noteId: "77bb0f7066f311f1aabf1904536c3cd9"
tags: []
---

# 🚗 Used Car Price Prediction

## 📌 Project Overview

The **Used Car Price Prediction** project aims to predict the selling price of used cars based on various vehicle attributes. By leveraging Machine Learning techniques, this system provides accurate price estimates that can assist both buyers and sellers in making informed decisions.

The model is trained on real-world data collected from CarDekho, one of India's leading automobile marketplaces.

---

# 🎯 Problem Statement

The used car market is highly dynamic, with vehicle prices influenced by multiple factors such as brand, model, age, fuel type, transmission, ownership history, and mileage.

This project addresses the challenge of estimating the fair market value of a used car using Machine Learning.

### Objectives

- Predict the selling price of a used car based on input features.
- Assist sellers in determining a competitive market price.
- Help buyers evaluate whether a listed vehicle is fairly priced.
- Reduce uncertainty in used car transactions through data-driven insights.

---

# 📊 Dataset Information

### Source

The dataset was collected through web scraping from the CarDekho platform.

### Dataset Statistics

| Attribute       | Value                   |
| --------------- | ----------------------- |
| Total Rows      | 15,411                  |
| Total Columns   | 13                      |
| Dataset Type    | Structured Tabular Data |
| Domain          | Automotive              |
| Target Variable | Selling Price           |

---

# 📋 Features Description

The dataset contains information related to various characteristics of used vehicles.

Typical features include:

- Car Name
- Brand
- Vehicle Age
- Kilometers Driven
- Fuel Type
- Transmission Type
- Seller Type
- Ownership History
- Mileage
- Engine Capacity
- Maximum Power
- Seats
- Selling Price (Target Variable)

---

# 🏗️ Project Architecture

```text
Data Collection
        │
        ▼
Data Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Model Training
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Model Evaluation
        │
        ▼
Price Prediction
```

---

# 🔧 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Flask / FastAPI (Optional Deployment)
- Jupyter Notebook

---

---

# 🔍 Exploratory Data Analysis

Key analyses performed:

- Missing Value Analysis
- Outlier Detection
- Correlation Analysis
- Feature Distribution Analysis
- Price Trend Analysis
- Categorical Feature Analysis
- Vehicle Age vs Price Analysis

---

# 🤖 Machine Learning Pipeline

### Data Preprocessing

- Missing Value Handling
- Duplicate Removal
- Feature Encoding
- Feature Scaling
- Data Cleaning

### Feature Engineering

- Vehicle Age Calculation
- Brand Extraction
- Derived Feature Creation
- Feature Selection

### Model Training

Algorithms evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

---

# 📈 Model Evaluation Metrics

The model performance is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

```python
from sklearn.metrics import mean_absolute_error
from sklearn.metrics import mean_squared_error
from sklearn.metrics import r2_score
```

---

# 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/ShivamMathtech/Random-forest-model-.git
```

### Navigate to Project

```bash
cd Random-forest-model-
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Project

### Training

```bash
python src/train.py
```

### Prediction

```bash
python src/predict.py
```

### Launch Web Application

```bash
python app/app.py
```

---

# 💡 Use Cases

- Automobile Dealerships
- Online Vehicle Marketplaces
- Price Recommendation Systems
- Vehicle Valuation Platforms
- Automotive Analytics

---

# 🔮 Future Improvements

- Deep Learning Models
- Real-Time Data Integration
- Vehicle Image Analysis
- Advanced Feature Engineering
- Cloud Deployment
- Explainable AI (XAI)
- Model Monitoring Pipeline

---

# 📚 Learning Outcomes

Through this project, you will gain hands-on experience in:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Regression Modeling
- Hyperparameter Optimization
- Model Deployment
- End-to-End Machine Learning Pipelines

---

# 🤝 Contributing

Contributions are welcome.

If you would like to improve this project, feel free to fork the repository, create a feature branch, and submit a pull request.

---

# 📜 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub to support future development.

---

## Author

**Shivam Singh**

Building intelligent systems through Machine Learning, Mathematics, Artificial Intelligence, and Data Science.
