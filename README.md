📘 Day 4 – Pandas Basics
🎯 Objective

To learn the basics of the Pandas library, load a CSV dataset, and explore the data by viewing rows, columns, and dataset information.

📖 Introduction

🐼 Pandas is one of the most popular Python libraries used for data analysis and data manipulation. It helps users organize, clean, analyze, and process data efficiently. Pandas provides two important data structures: Series (one-dimensional) and DataFrame (two-dimensional), making it easy to work with datasets stored in CSV, Excel, SQL, and other file formats.

🛠️ Software Requirements

💻 Python 3.x
📚 Pandas Library
📝 VS Code / Jupyter Notebook
📂 CSV Dataset (students.csv)

📥 Installing Pandas

Before using Pandas, install it using the following command:

➡️ pip install pandas

📂 Dataset Used

📄 The dataset used in this task is students.csv, which contains student information such as ID, Name, Age, Course, and Marks.

🚀 Program 1 – Import Pandas
📝 Aim

To import the Pandas library into Python.

📖 Explanation

The import pandas as pd statement imports the Pandas library and assigns it the alias pd. This alias makes it easier to use Pandas functions throughout the program.

📂 Program 2 – Load a CSV Dataset
📝 Aim

To load a CSV file into a Pandas DataFrame.

📖 Explanation

The read_csv() function reads the data stored in the CSV file and converts it into a DataFrame. A DataFrame is a table-like structure consisting of rows and columns, making data easy to analyze.

👀 Program 3 – View First Five Rows
📝 Aim

To display the first five rows of the dataset.

📖 Explanation

The head() function displays the first five records of the dataset by default. It helps users quickly understand how the data is organized.

🔍 Program 4 – View Last Five Rows
📝 Aim

To display the last five rows of the dataset.

📖 Explanation

The tail() function displays the last five records of the dataset. It is useful for checking the ending part of large datasets.

🏷️ Program 5 – View Column Names
📝 Aim

To display the names of all columns in the dataset.

📖 Explanation

The columns attribute returns the list of column names present in the DataFrame. This helps identify the available data fields.

ℹ️ Program 6 – View Dataset Information
📝 Aim

To display complete information about the dataset.

📖 Explanation

The info() function provides useful information such as:

📌 Number of rows
📌 Number of columns
📌 Data types
📌 Non-null values
📌 Memory usage

This information helps understand the structure of the dataset.

📏 Program 7 – Display Dataset Shape
📝 Aim

To find the number of rows and columns.

📖 Explanation

The shape attribute returns the dimensions of the dataset in the form (rows, columns). It helps determine the size of the DataFrame.

📊 Program 8 – Display Statistical Summary
📝 Aim

To view statistical information about the dataset.

📖 Explanation

The describe() function generates statistical details such as:

📈 Count
📊 Mean
📉 Standard Deviation
🔢 Minimum Value
🔢 Maximum Value
📌 Quartiles

This summary is useful for understanding numerical data.

📚 Concepts Learned

✅ Importing the Pandas library
✅ Reading CSV files
✅ Creating DataFrames
✅ Viewing rows using head() and tail()
✅ Displaying column names
✅ Viewing dataset information
✅ Checking dataset dimensions
✅ Generating statistical summaries

🌍 Applications of Pandas

📊 Data Analysis
🤖 Machine Learning
📈 Business Analytics
💰 Financial Analysis
🏥 Healthcare Data Analysis
🛒 Sales and Marketing Analytics
📚 Research and Education

⭐ Advantages of Pandas

🚀 Fast and efficient data processing
📂 Easy handling of structured data
🧹 Simplifies data cleaning and preprocessing
🔍 Powerful filtering and analysis features
📊 Supports integration with NumPy, Matplotlib, and Scikit-learn
💡 Easy to learn and widely used in Data Science

🎯 Skills Gained

✅ Imported the Pandas library successfully
✅ Loaded a CSV dataset into a DataFrame
✅ Viewed rows and columns of the dataset
✅ Explored dataset information
✅ Understood DataFrame structure
✅ Performed basic data exploration using Pandas

✅ Expected Outcome

🎉 Successfully learned the basics of the Pandas library and loaded a CSV dataset into a DataFrame. Performed basic operations such as viewing rows, columns, and dataset information, gaining a strong foundation in data analysis using Pandas.

📝 Conclusion

🎓 Day 4 provided a solid introduction to the Pandas library. By learning how to import Pandas, load CSV datasets, and explore data using various built-in functions, I developed essential skills required for data analysis. These concepts will serve as the foundation for advanced topics such as data cleaning, visualization, and machine learning. 🚀
