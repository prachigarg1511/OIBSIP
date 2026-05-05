<h1 align="center">🧠 Oasis Infobyte Data Science Internship</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Internship-Oasis%20Infobyte-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Data%20Science-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Language-Python-yellow?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Tasks%20Completed-5%2F5-brightgreen?style=for-the-badge" />
</p>

<p align="center">
  This repository contains all the tasks completed during my <strong>Data Science Internship</strong> at <a href="https://oasisinfobyte.com/">Oasis Infobyte</a>.
  Each project demonstrates the application of machine learning, data analysis, and Python programming to solve real-world problems.
</p>

---

## 👩‍💻 Intern Details

| Field         | Details              |
|---------------|----------------------|
| **Name**      | Prachi Garg          |
| **Role**      | Data Science Intern  |
| **Organization** | Oasis Infobyte    |
| **Duration**  | May 2026             |

---

## 📁 Repository Structure

```
OIBSIP/
│
├── Task-1/                     # Iris Flower Classification
│   └── iris_classification.ipynb
│
├── Task-2/                     # Unemployment Analysis
│   └── unemployment_analysis.ipynb
│
├── Task-3/                     # Car Price Prediction
│   └── Car_Price_Prediction.ipynb
│
├── Task-4/                     # Email Spam Detection
│   └── Email_Spam_Detection.ipynb
│
├── Task-5/                     # Sales Prediction
│   └── Sales_Prediction.ipynb
│
├── TASK-1 DATASET/
├── TASK-2 DATASET/
├── TASK-3 DATASET/
├── TASK-4 DATASET/
├── TASK-5 DATASET/
│
└── README.md
```

---

## 📌 Task Descriptions

---

### ✅ Task 1: Iris Flower Classification

> **Objective**: Train a machine learning model to classify Iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — based on their sepal and petal measurements.

| Attribute          | Details                              |
|--------------------|--------------------------------------|
| **Dataset**        | Iris.csv (150 records, 4 features)   |
| **Algorithm**      | Decision Tree / Random Forest Classifier |
| **Key Features**   | Sepal Length, Sepal Width, Petal Length, Petal Width |
| **Result**         | High accuracy multi-class classification |

**Key Steps:**
- Exploratory Data Analysis with pairplots and heatmaps
- Label encoding of target variable
- Model training and evaluation using accuracy score and confusion matrix
- Visualized decision boundaries

---

### ✅ Task 2: Unemployment Analysis with Python

> **Objective**: Analyze the unemployment rate in India, with a focus on the sharp surge caused by the COVID-19 pandemic lockdowns.

| Attribute          | Details                                    |
|--------------------|--------------------------------------------|
| **Dataset**        | Unemployment in India.csv (~740 records)    |
| **Type**           | Exploratory Data Analysis (EDA)            |
| **Key Libraries**  | Pandas, Matplotlib, Seaborn, Plotly        |
| **Result**         | Identified severe unemployment spike during Apr–May 2020 |

**Key Steps:**
- Data cleaning and handling of missing values
- State-wise and region-wise unemployment trend analysis
- Animated and interactive visualizations using Plotly
- Correlation analysis between employment rate and labour participation

---

### ✅ Task 3: Car Price Prediction

> **Objective**: Predict the selling price of used cars based on brand, year, mileage, fuel type, transmission, and ownership history.

| Attribute          | Details                                  |
|--------------------|------------------------------------------|
| **Dataset**        | car data.csv (302 records, 9 features)   |
| **Algorithm**      | Random Forest Regressor                  |
| **Key Features**   | Car Age, Present Price, KMs Driven, Fuel Type, Transmission |
| **Result**         | **R² Score: 0.96** — Excellent predictive accuracy |

**Key Steps:**
- Feature engineering: derived `Car_Age` from `Year`
- One-hot encoding of categorical features
- Random Forest model training with 100 estimators
- Evaluation using MAE, MSE, R² Score
- Feature importance visualization

---

### ✅ Task 4: Email Spam Detection

> **Objective**: Build a text classifier to automatically detect and filter spam messages from legitimate ones (ham).

| Attribute          | Details                                    |
|--------------------|--------------------------------------------|
| **Dataset**        | spam.csv (~5,572 messages)                 |
| **Algorithm**      | Multinomial Naive Bayes + TF-IDF           |
| **Key Libraries**  | Scikit-learn, NLTK, Seaborn                |
| **Result**         | **Accuracy: 97%** on unseen test data      |

**Key Steps:**
- Data cleaning: removed duplicate entries, handled latin-1 encoding
- Label encoding: ham → 0, spam → 1
- TF-IDF Vectorization with English stop words removal
- Multinomial Naive Bayes classification
- Confusion matrix and classification report
- Custom prediction function to test new messages

---

### ✅ Task 5: Sales Prediction Using Python

> **Objective**: Predict future product sales based on advertising expenditures across TV, Radio, and Newspaper channels.

| Attribute          | Details                                   |
|--------------------|-------------------------------------------|
| **Dataset**        | Advertising.csv (200 records, 4 features) |
| **Algorithm**      | Linear Regression                         |
| **Key Features**   | TV, Radio, Newspaper advertising budgets  |
| **Result**         | **R² Score: 0.90** — Strong model fit     |

**Key Steps:**
- Data cleaning: removed index column, checked for nulls
- Correlation heatmap analysis (TV showed strongest correlation: ~0.78)
- Pairplot visualization for feature-target relationships
- Linear Regression model training and evaluation
- Actual vs. Predicted sales plot with regression line
- Business insight: **TV advertising is the primary sales driver**

---

## 🛠️ Tech Stack

| Tool / Library  | Purpose                          |
|-----------------|----------------------------------|
| `Python 3.x`    | Core programming language        |
| `Pandas`        | Data manipulation and analysis   |
| `NumPy`         | Numerical computations           |
| `Matplotlib`    | Data visualization               |
| `Seaborn`       | Statistical plotting             |
| `Scikit-learn`  | Machine learning models          |
| `Jupyter`       | Interactive notebook environment |

---

## 📊 Results Summary

| Task | Problem Type     | Algorithm            | Best Metric         |
|------|------------------|----------------------|---------------------|
| 1    | Classification   | Random Forest        | High Accuracy       |
| 2    | EDA              | Statistical Analysis | Insight-driven      |
| 3    | Regression       | Random Forest        | R² = **0.96**       |
| 4    | Classification   | Naive Bayes + TF-IDF | Accuracy = **97%**  |
| 5    | Regression       | Linear Regression    | R² = **0.90**       |

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/prachigarg1511/OIBSIP.git
   cd OIBSIP
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. Open any `Task-X/*.ipynb` notebook and run all cells.

---

## 🙏 Acknowledgements

A huge thank you to **Oasis Infobyte** for providing this opportunity to work on practical, industry-relevant machine learning projects. This internship has significantly strengthened my skills in data preprocessing, model building, and analytical thinking.

---

<p align="center">⭐ If you found this helpful, consider giving a star to the repo!</p>
