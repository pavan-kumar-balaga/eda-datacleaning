# Titanic Dataset — EDA & Data Cleaning

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** and **Data Cleaning** on the Titanic dataset using Python.

The goal is to identify and handle missing values, duplicates, incorrect data types, and outliers, followed by visualization and analysis of important patterns.

## 🛠️ Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📊 Dataset

* **Rows:** 891
* **Columns:** 12
* **Dataset:** Titanic Passenger Dataset

The dataset contains information such as passenger class, age, gender, fare, and survival status.

## 🧹 Data Cleaning

The following steps were performed:

* Checked dataset shape, data types, and summary statistics.
* Identified and handled missing values.
* Removed duplicate records.
* Converted relevant columns to appropriate data types.
* Detected outliers using the **IQR method**.
* Handled extreme Fare values.
* Created a `Cabin_Known` feature to preserve cabin availability information.

## 📈 EDA

The analysis included:

* Survival distribution
* Survival by gender
* Survival by passenger class
* Age and Fare distributions
* Boxplots for outlier detection
* Correlation analysis
* Correlation heatmap

## 💡 Key Insights

* Female passengers had a higher survival rate than male passengers.
* First-class passengers had better survival outcomes.
* Fare and passenger class showed an association with survival.
* Missing values and outliers required appropriate preprocessing before analysis.

## 📂 Project Structure

```text
Titanic-EDA/
├── README.md
├── .gitignore
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_Titanic_Dataset.csv
├── notebooks/
│   └── eda_and_cleaning.ipynb
└── docs/
    └── summary_report.pdf
```

## ▶️ How to Run

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Then open the notebook:

```bash
jupyter notebook
```

Run `notebooks/eda_and_cleaning.ipynb` to reproduce the analysis.

## ✅ Conclusion

The Titanic dataset was successfully cleaned and explored. The analysis identified important patterns in passenger survival and produced a cleaned dataset suitable for further analysis or machine-learning tasks.


