According to the instructions, the Cumulative Retest Project submission task will be completed in 2 days. The workflow of the project involves Human Resource Management and is conducted using Jupiter Notebook (VS Code).

I merged all the CSV files to create a DataFrame, and then imported the necessary libraries into our Python environment. For data manipulation and analysis, I'm utilizing the Pandas library.
import pandas as pd

Loaded the dataset
Next, I loaded the given dataset into a Pandas DataFrame, replacing "dataset.csv" with the filepath of the dataset (IHR).
df = pd.read_csv('IHR.csv’)
To gain insight into the dataset's structure and information, I viewed the first few rows of the dataset (IHR).
By viewing the first few rows, I can get a sense of the dataset’s structure and the information it contains.
print(df.head())
Summary statistics provide valuable insights into the distribution, central tendency, and variability of our data.
print(df.describe())
Checking for missing values in the dataset (IHR) is crucial as they can affect the accuracy and reliability of our analysis.
print(df.isnull().sum())
Understanding the data types of each column is essential for data manipulation and analysis. Let’s examine the data types of each column.
print(df.dtypes)
"Data cleaning was performed using a lambda function to remove unwanted characters from the given dataset (IHR). 
After completing the data cleaning process, the cleaned data was saved to a file named 'IHR.csv'.
Then, feature engineering was performed using get_dummies(). Additionally, line plots, scatter plots, and box plots were executed using Matplotlib and Seaborn. 
Following this, the sklearn library was utilized for model building and model testing. 
I imported a dataset of titles and descriptions from the dataset (IHR). 
Using seven columns, I tokenized them using NLTK and Python.


