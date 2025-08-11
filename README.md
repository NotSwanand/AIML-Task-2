# 📊 Titanic Dataset – Exploratory Data Analysis (EDA)

## 📌 Objective
Perform EDA on the Titanic dataset to understand patterns, distributions, correlations, and detect anomalies using visualizations and descriptive statistics.

---

## 📁 Dataset
- **Source**: [Kaggle – Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 🛠 Tools Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib

---

## ✅ Steps Performed

### 1. Summary Statistics
- Used `.info()` and `.describe()` to inspect data types, missing values, and summary stats.
- Calculated mean, median, std, skewness for numerical features.

### 2. Univariate Analysis
- **Histograms** for numerical columns to understand distributions.
- **Boxplots** to detect outliers and spread of values.

### 3. Bivariate Analysis
- **Correlation Matrix** plotted using `seaborn.heatmap()` to identify relationships.
- **Pairplot** between key features like `Age`, `Fare`, `SibSp`, and survival.

### 4. Insights & Patterns
- Detected skewness in `Fare` and `Age`.
- Found outliers in `Fare` via boxplot.
- Observed that survival correlates with lower `SibSp` and `Parch` values.
- `Fare` and `Pclass` show moderate correlation with `Survived`.

---

## 📊 Visualizations Included
- Histograms of all numeric columns
- Boxplots of `Age`, `Fare`, `SibSp`, `Parch`
- Correlation heatmap
- Pairplot with `Survived` hue

---

## 📂 Files Included
- `Task2.ipynb` – Jupyter Notebook with all EDA steps and visualizations
- `README.md` – Documentation of the task

---

