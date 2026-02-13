-------------------------------------------------------------------------------------------------------------------------------------------------------------------                                                       ** Titanic Data Preprocessing Project **   
-------------------------------------------------------------------------------------------------------------------------------------------------------------------

                ******Task 1: Data Cleaning & Preprocessing*******

Project Summary:
In this project, I prepared the Titanic dataset for machine learning by cleaning and organizing the data. Since real-world data often contains missing values and unnecessary information, preprocessing is an essential step before model training.

Work Done:
Loaded and explored the dataset using Pandas
Checked and handled missing values
Removed unnecessary columns (PassengerId, Name, Ticket, Cabin)
Filled missing Age values with mean
Filled missing Embarked values with mode
Converted categorical data (Male → 0, Female → 1)
Applied one-hot encoding for Embarked
Performed feature scaling on Age and Fare using StandardScaler
Saved the cleaned dataset as titanic_cleaned.csv

Tools Used:
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

Learning Outcome:
This project improved my understanding of data cleaning, handling missing values, categorical encoding, and feature scaling in the machine learning workflow.

                    ******Task 2: Exploratory Data Analysis (EDA)******

Project Summary:
In this task, I explored the Titanic dataset to understand it better. The main aim was to find patterns, relationships, and useful insights from the data before applying any machine learning models.

Work Done:
First, I loaded the dataset using Pandas and checked how the data looks. I used functions like head(), info(), and describe() to understand the dataset.
Then, I checked for missing values and handled them where needed.
After that, I used different visualizations to understand the data:
Histograms to see how values are distributed
Boxplots to identify outliers
Count plots to analyze categorical data
I also created a correlation matrix to understand how different features are related to each other.
Finally, I observed patterns in the data, especially how different features affect survival.

Tools Used:
Python
Pandas
NumPy
Matplotlib
Seaborn

Learning Outcome:
Through this task, I learned how to explore and understand a dataset. I got experience in using visualizations to find patterns and relationships. This helped me understand how data analysis is important before building machine learning models.
