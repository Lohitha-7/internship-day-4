📘 Day 4 – Pandas Basics Documentation
📅 Internship Day 4: Pandas Basics
🎯 Objective

The objective of this task is to learn the basics of the Pandas library in Python. Pandas is used for loading, analyzing, and manipulating structured data such as CSV files.


📚 What is Pandas?

Pandas is an open-source Python library used for:

📂 Reading CSV and Excel files
📊 Data analysis
📝 Data cleaning
🔍 Viewing and filtering data
📈 Preparing datasets for machine learning


🛠️ Tools Used
🐍 Python 3.x
📓 Jupyter Notebook / VS Code
📦 Pandas Library
📥 Step 1: Import Pandas
import pandas as pd
📥 Step 2: Load a CSV Dataset

Example dataset: students.csv

import pandas as pd

data = pd.read_csv("students.csv")
print(data)
👀 Step 3: View First 5 Rows
print(data.head())
👀 Step 4: View Last 5 Rows
print(data.tail())
📏 Step 5: View Number of Rows and Columns
print(data.shape)

Example Output

(10, 4)

This means:

10 Rows
4 Columns
📋 Step 6: View Column Names
print(data.columns)

Example Output

Index(['ID', 'Name', 'Age', 'Marks'], dtype='object')
ℹ️ Step 7: View Dataset Information
print(data.info())

Example Output

<class 'pandas.core.frame.DataFrame'>
RangeIndex: 10 entries
Data columns (total 4 columns):
ID
Name
Age
Marks
📊 Step 8: View Statistical Summary
print(data.describe())
🔍 Step 9: Check Missing Values
print(data.isnull().sum())
📂 Sample Dataset (students.csv)
ID,Name,Age,Marks
1,Alice,20,85
2,Bob,21,90
3,Charlie,19,78
4,David,22,88
5,Eva,20,91
6,Frank,21,75
7,Grace,20,89
8,Harry,22,82
9,Ivy,19,95
10,Jack,21,80
📸 Expected Output
   ID     Name  Age  Marks
0   1    Alice   20     85
1   2      Bob   21     90
2   3  Charlie   19     78
3   4    David   22     88
4   5      Eva   20     91

(10, 4)

Index(['ID', 'Name', 'Age', 'Marks'], dtype='object')

<class 'pandas.core.frame.DataFrame'>
RangeIndex: 10 entries, 0 to 9
Data columns (total 4 columns)
🎯 Learning Outcomes

After completing this task, I was able to:

✅ Import the Pandas library.
✅ Load a CSV dataset successfully.
✅ Display the first and last rows of the dataset.
✅ View the number of rows and columns.
✅ Display column names.
✅ Understand dataset information using info().
✅ Generate summary statistics using describe().
✅ Check for missing values.
✅ Conclusion

This task helped me understand the fundamentals of the Pandas library. I learned how to load a CSV file, inspect the dataset, view rows and columns, and obtain important information about the data. These skills form the foundation for data analysis and preprocessing in Python.

Expected Outcome Achieved: ✅ Dataset successfully loaded and explored using Pandas.


Step 2: Load a CSV Dataset

Example dataset: students.csv

import pandas as pd

data = pd.read_csv("students.csv")
print(data)
