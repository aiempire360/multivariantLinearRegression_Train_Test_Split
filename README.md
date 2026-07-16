# 📊 Multiple Linear Regression with Train-Test Split

This project demonstrates how to build and evaluate a **Multiple Linear Regression** model using **Scikit-learn** with the **Train-Test Split** technique. The model predicts **Sales** based on advertising expenditures across different media channels.

---

## 📌 Project Overview

In this project, we:

- Load advertising data from an Excel file.
- Select multiple input features.
- Split the dataset into training and testing sets.
- Train a Multiple Linear Regression model.
- Predict sales on the test dataset.
- Evaluate the model using the R² Score.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn

---

## 📂 Project Structure

```
Multiple-Linear-Regression-Train-Test-Split/
│── multivariantLinearRegression_Train_Test_Split.py
│── AdvertisingSpendvsSales.xlsx
│── README.md
```

---

## 📊 Dataset Features

| Feature | Description |
|---------|-------------|
| TV | Advertising budget spent on TV |
| radio | Advertising budget spent on Radio |
| newspaper | Advertising budget spent on Newspaper |
| sales | Total sales (Target Variable) |

---

## 🤖 Machine Learning Algorithm

**Algorithm Used:**

- Multiple Linear Regression

---

## 🎯 Objective

Predict product sales based on advertising spending across different marketing channels.

---

## 🔄 Workflow

1. Import required libraries
2. Load dataset
3. Select input and target variables
4. Split dataset into training and testing sets
5. Train the Linear Regression model
6. Make predictions
7. Evaluate model performance using R² Score

---

## ✂️ Train-Test Split

The dataset is divided into:

- **80% Training Data**
- **20% Testing Data**

```python
from sklearn.model_selection import train_test_split

x_train, x_test, y_train, y_test = train_test_split(
    x,
    y,
    test_size=0.2
)
```

---

## 🚀 Model Training

```python
from sklearn.linear_model import LinearRegression

lr = LinearRegression()
lr.fit(x_train, y_train)
```

---

## 🔮 Prediction

```python
lr.predict(x_test)
```

---

## 📈 Model Evaluation

The model is evaluated using the **R² Score**.

```python
lr.score(x_test, y_test)
```

A higher R² Score indicates better prediction performance.

---

## 📚 Libraries Used

```python
import numpy as np
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
```

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/multiple-linear-regression-train-test-split.git
```

### 2. Install Required Libraries

```bash
pip install numpy pandas scikit-learn openpyxl
```

### 3. Run the Project

```bash
python multivariantLinearRegression_Train_Test_Split.py
```

---

## 🎓 Learning Outcomes

By completing this project, you will learn:

- Multiple Linear Regression
- Feature Selection
- Train-Test Split
- Model Training
- Model Prediction
- Model Evaluation using R² Score
- Real-world Machine Learning Workflow

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**SofiaKamal**

Learning Python, Data Science, and Machine Learning.

⭐ If you found this project helpful, don't forget to star this repository!
