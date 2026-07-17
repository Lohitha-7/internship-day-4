DAY 4 – PANDAS BASICS
Objective

To learn the basics of the Pandas library, load a CSV dataset, and view rows, columns, and dataset information.

Introduction

Pandas is a Python library used for data analysis and data manipulation. It provides powerful data structures like Series and DataFrame, making it easy to work with structured data such as CSV files, Excel files, and databases.

Software Requirements
Python 3.x
Pandas Library
VS Code / Jupyter Notebook
students.csv Dataset
Installing Pandas
pip install pandas
Dataset (students.csv)
Student_ID,Name,Age,Course,Marks
101,Rahul,20,Data Science,85
102,Priya,21,Computer Science,90
103,Amit,19,AI & ML,88
104,Sneha,22,Cyber Security,92
105,Kiran,20,Data Analytics,80
Program 1 – Import Pandas
Code
import pandas as pd

print("Pandas Imported Successfully")
Output
Pandas Imported Successfully
Explanation

This program imports the Pandas library using the alias pd.

Program 2 – Load CSV File
Code
import pandas as pd

data = pd.read_csv("students.csv")
print(data)
Output
   Student_ID   Name  Age             Course  Marks
0         101  Rahul   20       Data Science     85
1         102  Priya   21   Computer Science     90
2         103   Amit   19            AI & ML     88
3         104 Sneha   22    Cyber Security     92
4         105 Kiran   20    Data Analytics     80
Explanation

The read_csv() function reads the CSV file and stores it in a DataFrame.

Program 3 – View First Five Rows
Code
print(data.head())
Explanation

Displays the first five rows of the dataset.

Program 4 – View Last Five Rows
Code
print(data.tail())
Explanation

Displays the last five rows of the dataset.

Program 5 – View Column Names
Code
print(data.columns)
Explanation

Displays the names of all columns in the dataset.

Program 6 – View Dataset Information
Code
data.info()
Explanation

Shows the number of rows, columns, data types, and memory usage.

Program 7 – Dataset Shape
Code
print(data.shape)
Output
(5, 5)
Explanation

Shows the number of rows and columns.

Program 8 – Statistical Summary
Code
print(data.describe())
Explanation

Displays statistical information such as count, mean, minimum, maximum, and standard deviation.

Concepts Learned
Importing Pandas
Reading CSV files
Creating DataFrames
Viewing rows and columns
Checking dataset information
Dataset shape
Statistical summary
Advantages of Pandas
Easy to use
Fast data processing
Supports large datasets
Built-in analysis functions
Works well with NumPy
Expected Outcome

The dataset was successfully loaded using Pandas. Basic operations such as viewing rows, columns, and dataset information were performed successfully.

Conclusion

Day 4 helped me understand the basics of the Pandas library. I learned how to load CSV datasets, inspect data, and perform basic data exploration. These concepts provide a strong foundation for future data analysis tasks.
