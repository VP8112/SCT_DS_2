# Data Cleaning and Exploratory Data Analysis on Titanic Dataset

## 📌 Overview

This project demonstrates the process of **Data Cleaning** and **Exploratory Data Analysis (EDA)** using the Titanic dataset. The objective is to preprocess the dataset by handling missing values and then explore the relationships between different variables through statistical summaries and visualizations.

Various plots are used to understand passenger demographics, survival patterns, fare distribution, and correlations among numerical features. The project provides meaningful insights into the characteristics of Titanic passengers and the factors that influenced survival.

---

## 📊 Objective

- Perform data cleaning by handling missing values.
- Explore the structure and characteristics of the dataset.
- Analyze the distribution of numerical and categorical variables.
- Identify relationships between different features.
- Visualize patterns and trends using informative plots.

---

## 📁 Dataset

**Dataset:** Titanic Dataset

The dataset contains information about passengers aboard the RMS Titanic, including demographic details, ticket information, passenger class, fare, and survival status.

### Features Used

| Feature | Description |
|---------|-------------|
| Age | Age of the passenger |
| Sex | Gender of the passenger |
| Pclass | Passenger class |
| Fare | Ticket fare |
| Embarked | Port of embarkation |
| Survived | Survival status |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📈 Data Cleaning

The following preprocessing steps were performed:

- Checked dataset information.
- Identified missing values.
- Filled missing values in the **Age** column using the median.
- Filled missing values in the **Embarked** column using the mode.
- Removed the **Cabin** column due to a large number of missing values.

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

### 1. Age Distribution
Visualizes the distribution of passenger ages using a histogram.

### 2. Gender Distribution
Displays the number of male and female passengers.

### 3. Survival Distribution
Shows the number of passengers who survived and those who did not.

### 4. Survival by Gender
Compares survival rates between male and female passengers.

### 5. Survival by Passenger Class
Analyzes how passenger class affected survival.

### 6. Fare Distribution
Illustrates the distribution of ticket fares.

### 7. Age vs Survival
Uses a box plot to compare passenger age with survival status.

### 8. Fare vs Survival
Uses a box plot to analyze ticket fare based on survival.

### 9. Correlation Heatmap
Shows the correlation among numerical features.

### 10. Pair Plot
Displays pairwise relationships between selected numerical variables.

---

## 🚀 Project Workflow

1. Import required libraries.
2. Load the Titanic dataset.
3. Display dataset overview.
4. Check and handle missing values.
5. Perform data cleaning.
6. Generate descriptive statistics.
7. Create visualizations for data exploration.
8. Analyze relationships between variables.
9. Summarize key observations.

---

## 📂 Project Structure

```
PRODIGY_DS_02/
│
├── Titanic-Dataset.csv
├── Task02.ipynb
├── README.md
└── output.png
```

---

## 📸 Expected Output

The project generates:

- Dataset Overview
- Statistical Summary
- Missing Value Analysis
- Age Distribution Histogram
- Gender Distribution Plot
- Survival Distribution Plot
- Survival by Gender Plot
- Survival by Passenger Class Plot
- Fare Distribution Histogram
- Age vs Survival Box Plot
- Fare vs Survival Box Plot
- Correlation Heatmap
- Pair Plot
- Key Observations

---

## 📚 Learning Outcomes

Through this project, the following concepts were explored:

- Data Loading
- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Histogram Visualization
- Count Plot Visualization
- Box Plot Analysis
- Correlation Analysis
- Pairwise Relationship Analysis
- Data Interpretation

---

## 📌 Conclusion

This project demonstrates the complete workflow of data cleaning and exploratory data analysis using the Titanic dataset. By preprocessing the data and visualizing important relationships, meaningful insights were obtained regarding passenger demographics, fare distribution, passenger class, and survival patterns. The project highlights the importance of EDA as a fundamental step before building machine learning models.

---

## 👨‍💻 Author

**Vijay Prakash**

Dr. B. R. Ambedkar National Institute of Technology (NIT Jalandhar)  
Jalandhar, Punjab

---
