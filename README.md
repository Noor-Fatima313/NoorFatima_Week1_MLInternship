# NoorFatima_Week1_MLInternship
# Titanic Data Exploration & Preprocessing

## Overview

This project was completed as part of the **CodGen Machine Learning Internship – Week 1**.

The main goal of this task was to learn the basic steps involved in preparing a dataset before building a Machine Learning model. These steps include loading the dataset, exploring its contents, handling missing values, encoding categorical data, creating visualizations, and writing observations based on the analysis.

The dataset used for this project is the **Titanic Survival Dataset** from Kaggle.

---

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## Dataset

**Dataset:** Titanic Survival Dataset

The dataset contains information about Titanic passengers such as:

- Passenger Class
- Name
- Gender
- Age
- Fare
- Embarked Port
- Survival Status

---

## Tasks Completed

### Task 1 – Load and Explore the Dataset

- Loaded the dataset using Pandas.
- Displayed the first five rows.
- Checked the dataset shape.
- Viewed column names and data types.
- Generated summary statistics.
- Identified missing values.

---

### Task 2 – Handle Missing Values

The missing values were handled as follows:

- Filled missing values in the **Age** column using the median.
- Filled missing values in the **Embarked** column using the mode.
- Removed the **Cabin** column because it contained too many missing values.

---

### Task 3 – Encode Categorical Data

Used **Label Encoding** to convert categorical columns such as **Sex** and **Embarked** into numerical values so they could be used for further analysis.

---

### Task 4 – Data Visualization

Created the following visualizations:

- Histogram of Age
- Histogram of Fare
- Bar chart of Passenger Class
- Correlation Heatmap

These plots helped in understanding the distribution of the data and the relationships between different features.

---

### Task 5 – Observations

Some important observations from the dataset include:

- Female passengers had a higher survival rate than male passengers.
- First-class passengers were more likely to survive.
- Higher ticket fares were generally associated with better survival.
- Age had a weaker relationship with survival compared to gender and passenger class.
- The Cabin column contained many missing values and was removed during preprocessing.

---

## What I Learned

Through this project, I learned how to:

- Load datasets using Pandas.
- Explore and understand data.
- Handle missing values properly.
- Encode categorical variables.
- Create useful visualizations.
- Interpret data and draw meaningful conclusions.

This project provided a good introduction to the data preprocessing stage of a Machine Learning workflow.

---

## Author

**Machine Learning Internship – Week 1**

CodGen Virtual Internship Program
