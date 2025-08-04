# task-1-netflix-cleaning
Data cleaning and preprocessing of Netflix Movies and TV Shows dataset using Python.
# Task 1: Netflix Data Cleaning & Preprocessing

This project is part of an AI & ML internship task focused on cleaning and preparing raw data for analysis and modeling. The dataset used here is the **Netflix Movies and TV Shows** dataset.

## 📂 Dataset
- Source: [Netflix Titles – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Contains information about movies and TV shows on Netflix, including:
  - Title, Director, Cast
  - Country, Date Added, Duration
  - Genre, Rating, and Description

## 📌 Objective
To clean and preprocess the dataset to make it ready for machine learning models by:
- Handling missing values
- Converting categorical features
- Creating new time-based features
- Detecting and visualizing outliers
- Exporting the cleaned dataset

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🧹 Key Preprocessing Steps
- Filled missing values in `director`, `cast`, `country` using appropriate strategies.
- Converted `date_added` to datetime format and extracted `year_added` and `month_added`.
- Encoded `type` (Movie / TV Show) using label encoding.
- Cleaned `duration` and visualized outliers for movies using boxplots.
- Exported the cleaned dataset as `cleaned_netflix_data.csv`.

## 📊 Visualizations
- Boxplot of movie durations to detect outliers.

## ✅ Final Output
- Cleaned dataset file: `cleaned_netflix_data.csv`
- Jupyter/Colab notebook: `netflix_data_cleaning.ipynb`

## 🔗 Submission
This task is submitted as part of the internship.  
Feel free to explore, clone, or reuse the notebook for learning.

