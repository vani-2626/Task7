# Dataset Summary Report using Python & Pandas

This project demonstrates how to load, inspect, and summarize a CSV dataset using **Python and Pandas**. The notebook focuses on understanding the basic structure and characteristics of a student dataset before performing further data analysis.

## Dataset Overview

| Category             | Details                         |
| -------------------- | ------------------------------- |
| Dataset              | Student Dataset                 |
| Rows                 | 25                              |
| Columns              | 7                               |
| Programming Language | Python                          |
| Library              | Pandas                          |
| Platform             | Google Colab / Jupyter Notebook |

## Features

| Feature                 | Data Type | Description                   |
| ----------------------- | --------- | ----------------------------- |
| `Student_ID`            | int64     | Unique student identifier     |
| `Name`                  | object    | Student name                  |
| `Age`                   | int64     | Student age                   |
| `Course`                | object    | Student's course              |
| `Marks`                 | float64   | Student marks                 |
| `Attendance_Percentage` | float64   | Student attendance percentage |
| `City`                  | object    | Student's city                |

## What the Notebook Covers

The notebook demonstrates:

* Loading a CSV dataset into a Pandas DataFrame
* Viewing the first few rows using `head()`
* Viewing the last few rows using `tail()`
* Viewing random samples using `sample()`
* Checking the dataset shape using `shape`
* Inspecting column names using `columns`
* Inspecting the DataFrame index using `index`
* Checking data types using `dtypes`
* Getting dataset information using `info()`
* Generating descriptive statistics using `describe()`
* Identifying missing values using `isnull().sum()`
* Making basic observations about the dataset

## Missing Values

| Column                  | Missing Values |
| ----------------------- | -------------: |
| `Marks`                 |              1 |
| `Attendance_Percentage` |              1 |
| `City`                  |              1 |

The remaining columns do not contain missing values.

## Basic Observations

* The dataset contains **25 rows and 7 columns**.
* There are **4 numerical features**: `Student_ID`, `Age`, `Marks`, and `Attendance_Percentage`.
* There are **3 text/categorical features**: `Name`, `Course`, and `City`.
* Missing values are present in `Marks`, `Attendance_Percentage`, and `City`.
* The dataset provides basic student information that can be used for further data cleaning and analysis.

## Files

```text
Dataset-Summary-Report/
│
├── Dataset_Summary_Report.ipynb
├── Day7_Student_Dataset.csv
└── README.md
```

## How to Run in Google Colab

1. Download or clone this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Open `Dataset_Summary_Report.ipynb`.
4. Upload `Day7_Student_Dataset.csv` to the Colab session.
5. Make sure the CSV file is in the same working directory as the notebook.
6. Run the notebook cells from top to bottom.

The notebook loads the dataset using:

```python
import pandas as pd

file_path = "Day7_Student_Dataset.csv"
df = pd.read_csv(file_path)
```

## How to Run Locally

Install the required libraries:

```bash
pip install pandas numpy jupyter
```

Open the notebook:

```bash
jupyter notebook Dataset_Summary_Report.ipynb
```

Make sure `Day7_Student_Dataset.csv` is stored in the same folder as the notebook.

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Google Colab**
* **Jupyter Notebook**

## Conclusion

This project demonstrates the basic steps required to understand a dataset using Pandas. The analysis covers dataset structure, records, columns, data types, descriptive statistics, and missing values, providing a foundation for further data cleaning and exploratory data analysis.

