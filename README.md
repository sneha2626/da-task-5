# da-task-5
Python-Basics-Reading-Data-Simple-Cleaning-Pandas-
Dataset Name: Students Performance Dataset

Dataset Description

The dataset contains demographic and academic performance information of students, including:

Gender

Race/Ethnicity

Parental education

Lunch type

Test preparation course

Math, Reading, and Writing scores

Tools & Technologies Used

Python

Pandas

Jupyter Notebook

Tasks Performed 1️ Dataset Loading

Loaded the dataset using pd.read_csv()

Verified successful loading using .head() and .info()

2️ Data Inspection

Examined dataset structure

Checked column names and data types

Identified presence of missing values

3️ Missing Value Analysis

Used .isnull().sum() to identify missing values

Applied conditional cleaning only where required

Avoided unnecessary imputation when data was already clean

4️ Handling Missing Values

Numeric columns: planned mean-based filling

Categorical columns: planned mode-based filling

Added safety checks to prevent runtime errors

Documented cases where no cleaning was required

5️ Duplicate Detection

Checked duplicate rows using .duplicated().sum()

Removed duplicates using .drop_duplicates()

Verified row count before and after removal

6️ Column Review

Reviewed all columns for relevance

Found all columns to be meaningful

No columns were dropped

7️ Feature Engineering

Created a new column average_score using subject scores

Created performance_level based on average score:

High

Medium

Low

8️ Export Cleaned Dataset

Exported cleaned data using .to_csv()

Saved output file as cleaned_data.csv
