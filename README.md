# Exploratory Data Analysis (EDA) on Boston Housing Dataset

## 📊 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the **Boston Housing Dataset**, which contains information about various attributes that influence housing prices in Boston suburbs. The aim is to understand the relationships between features, identify patterns, detect outliers, and extract meaningful insights that can help in building better predictive models.

## 📂 Dataset Description
The Boston Housing Dataset consists of 506 instances with 13 numerical/categorical features including:

- **CRIM**: Per capita crime rate by town.
- **ZN**: Proportion of residential land zoned for lots over 25,000 sq.ft.
- **INDUS**: Proportion of non-retail business acres per town.
- **CHAS**: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
- **NOX**: Nitric oxides concentration (parts per 10 million).
- **RM**: Average number of rooms per dwelling.
- **AGE**: Proportion of owner-occupied units built prior to 1940.
- **DIS**: Weighted distances to employment centers.
- **RAD**: Index of accessibility to radial highways.
- **TAX**: Full-value property tax rate per $10,000.
- **PTRATIO**: Pupil-teacher ratio by town.
- **B**: Proportion of blacks by town.
- **LSTAT**: % lower status of the population.
- **MEDV**: Median value of owner-occupied homes in $1000s (target variable).

## 🔍 Objectives
- Understand the distribution and relationships between features.
- Handle missing values and outliers.
- Visualize feature interactions using plots (histograms, pairplots, heatmaps, etc.).
- Identify correlations and patterns that affect housing prices.
- Prepare the dataset for further modeling and machine learning tasks.

## 📈 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🚀 Key Insights
- Strong correlation between `RM` (rooms) and `MEDV` (price).
- High crime rate (`CRIM`) and lower property values.
- Accessibility index (`RAD`) influences housing prices.
- Pollution (`NOX`) and lower socio-economic status (`LSTAT`) are negatively correlated with house values.

## 📂 Folder Structure
├── notebooks/
│ └── boston_housing_eda.ipynb
├── data/
│ └── boston_housing.csv
├── README.md
└── requirements.txt


## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/boston-housing-eda.git

