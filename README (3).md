# Data Analysis and Machine Learning Projects

A collection of Python notebooks covering data cleaning, exploratory data analysis, data visualization, pandas manipulation, and employee attrition analysis. All notebooks are beginner-friendly and built using standard data science libraries.

---

## Table of Contents

- [Repository Structure](#repository-structure)
- [Notebooks Overview](#notebooks-overview)
- [Installation](#installation)
- [Technologies Used](#technologies-used)

---

## Repository Structure

```
data-analysis-projects/
│
├── Copy_of_Employee_LeaveOrNot_Analysis.ipynb   # Employee attrition EDA
├── data_cleaning.ipynb                          # Data cleaning techniques
├── Data_visualization.ipynb                     # Data visualization methods
├── Pandas_data_manipulation_.ipynb              # Pandas data manipulation
└── README.md
```

---

## Notebooks Overview

### 1. Employee LeaveOrNot Analysis

Exploratory data analysis on an employee dataset to understand factors that influence whether employees leave the organization.

**Key topics covered:**
- Loading the employee dataset from Kaggle
- Inspecting column names, shape, and data types
- Analyzing the `Education` and `JoiningYear` columns — frequency counts, percentage distributions, and unique values
- Identifying missing values across all columns
- Visualizing the distribution of education levels using bar plots (Seaborn)

**Dataset:** Employee dataset sourced from Kaggle (`tawfikelmetwally/employee-dataset`)

---

### 2. Data Cleaning

A hands-on notebook for cleaning a real-world food survey dataset (`food_coded.csv`) using pandas.

**Key topics covered:**
- Detecting and handling missing values with `isnull()` and `fillna()`
- Identifying and counting duplicate records
- Separating numeric and object (categorical) columns using `select_dtypes()`
- Fixing mixed-type columns (`GPA`, `weight`) using `pd.to_numeric()` with error coercion
- Exploring unique values and value counts in categorical columns
- Label encoding categorical columns (e.g., mapping cuisine types to numeric values)

---

### 3. Data Visualization

A comprehensive introduction to data visualization in Python using Matplotlib and Seaborn, demonstrated on the Iris and Titanic datasets.

**Key topics covered:**
- Line plots on time-series data with cumulative sums
- Bar charts and horizontal bar charts for categorical data
- Histograms — stacked, unstacked, and horizontal orientations
- Visualizing distributions using the Iris dataset (`sepal_length`, `sepal_width`)
- Working with real datasets: Iris and Titanic (loaded via Seaborn)

---

### 4. Pandas Data Manipulation

A practical notebook for data wrangling and manipulation using the Titanic dataset (`Titanic-Dataset.csv`).

**Key topics covered:**
- Loading and inspecting data with `head()`, `tail()`, and `dtypes`
- Filtering rows using `loc` and `np.where()`
- Grouping data with `groupby()` and computing aggregate counts
- Selecting and slicing columns, including multi-column selection
- Sorting string columns and slicing with step intervals
- Adding new columns to a DataFrame
- Converting columns to categorical data types with `pd.Categorical()`

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/data-analysis-projects.git
   cd data-analysis-projects
   ```

2. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn kagglehub
   ```

3. Open the notebooks in Jupyter or Google Colab:
   ```bash
   jupyter notebook
   ```

   Or upload directly to [Google Colab](https://colab.research.google.com/).

4. Add the required datasets to your environment before running:
   - `food_coded.csv` — for `data_cleaning.ipynb`
   - `Titanic-Dataset.csv` — for `Pandas_data_manipulation_.ipynb`
   - Employee dataset — loaded automatically via `kagglehub` in the Employee analysis notebook

---

## Technologies Used

- **Python 3**
- **NumPy** — numerical operations and random data generation
- **pandas** — data loading, cleaning, and manipulation
- **Matplotlib** — plotting and visualization
- **Seaborn** — statistical data visualization and built-in datasets
- **KaggleHub** — programmatic dataset downloads from Kaggle

---

## License

This project is open-source and available under the [MIT License](LICENSE).
