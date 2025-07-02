Black Friday Purchase Prediction & Analysis
This Jupyter notebook explores and analyzes the Black Friday dataset, a popular dataset for retail analytics and machine learning. The goal is to understand customer purchase behavior and build predictive models using Python data science tools.
Features
Data Loading & Exploration:
Loads and inspects the Black Friday training and test datasets.
Data Cleaning:
Handles missing values and prepares the data for analysis.
Exploratory Data Analysis (EDA):
Visualizes key features and relationships using pandas, seaborn, and matplotlib.
Feature Engineering:
Combines and transforms features for better model performance.
Predictive Modeling:
(If included in later cells) Trains machine learning models to predict purchase amounts.
Dataset
Source: Black Friday Data
Files Used:
train.csv
test.csv
Requirements
Python 3.6+
Jupyter Notebook
pandas
numpy
matplotlib
seaborn
Install requirements with:
Apply to Black_Friday...
Usage
Place train.csv and test.csv in the same directory as the notebook.
Open the notebook:
Apply to Black_Friday...
Run the cells step by step to explore the data and follow the analysis.
Project Structure
Data Loading: Reads the CSV files into pandas DataFrames.
Data Merging: Combines train and test sets for unified analysis.
EDA: Visualizes distributions and relationships in the data.
Modeling: (If present) Builds and evaluates predictive models.
Notes
The notebook uses the deprecated DataFrame.append() method; consider replacing with pd.concat() for future compatibility.
Some columns have significant missing values (e.g., Product_Category_2, Product_Category_3).
