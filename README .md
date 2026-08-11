# Dataset Summary Report — Pandas

This project contains a Google Colab/Jupyter Notebook that performs a basic summary and structural exploration of a student dataset using **Python and Pandas**.

## Files

- `Dataset_Summary_Report.ipynb` — Complete analysis notebook.
- `Day7_Student_Dataset.csv` — CSV dataset used by the notebook.

## What the Notebook Covers

The notebook demonstrates:

- Loading a CSV file into a Pandas DataFrame
- Viewing the first few rows with `head()`
- Viewing the last few rows with `tail()`
- Viewing random records with `sample()`
- Checking dataset shape using `shape`
- Inspecting column names using `columns`
- Inspecting the DataFrame index using `index`
- Checking column data types using `dtypes`
- Inspecting overall structure with `info()`
- Generating descriptive statistics with `describe()`
- Checking missing values with `isnull().sum()`
- Recording basic observations about the dataset

## Dataset Summary

The supplied dataset contains:

- **25 rows**
- **7 columns**
- Features: `Student_ID`, `Name`, `Age`, `Course`, `Marks`, `Attendance_Percentage`, `City`

### Data Types

| Column | Data Type |
|---|---|
| Student_ID | int64 |
| Name | object |
| Age | int64 |
| Course | object |
| Marks | float64 |
| Attendance_Percentage | float64 |
| City | object |

### Missing Values

The dataset contains:

- `Marks`: 1 missing value
- `Attendance_Percentage`: 1 missing value
- `City`: 1 missing value

All other columns have no missing values.

## How to Run in Google Colab

### Option 1 — Upload the Repository Files

1. Download or clone this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Open `Dataset_Summary_Report.ipynb`.
4. Make sure `Day7_Student_Dataset.csv` is available in the same Colab working directory.
5. Run the notebook cells from top to bottom.

The notebook expects the dataset at:

```text
Day7_Student_Dataset.csv
```

### Option 2 — Open the Notebook from GitHub

1. Open Google Colab.
2. Select **File → Open notebook**.
3. Choose the **GitHub** tab.
4. Enter the GitHub repository URL.
5. Open `Dataset_Summary_Report.ipynb`.
6. Upload `Day7_Student_Dataset.csv` to the Colab session if it is not already available.
7. Run all cells.

## How to Run Locally

Make sure Python and Pandas are installed.

```bash
pip install pandas numpy jupyter
```

Then open the notebook:

```bash
jupyter notebook Dataset_Summary_Report.ipynb
```

Keep the CSV file in the same folder as the notebook.

## Expected Output

After running the notebook, you will see:

- First and last records
- Random sample records
- Dataset dimensions
- Column names and index information
- Data types and non-null counts
- Descriptive statistics
- Missing-value counts
- A concise summary of the dataset

## Technologies Used

- Python
- Pandas
- NumPy
- Google Colab / Jupyter Notebook

## Project Structure

```text
Task7/
│
├── Dataset_Summary_Report.ipynb
├── Day7_Student_Dataset.csv
└── README.md
```
