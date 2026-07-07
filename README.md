# Data Cleaning and Exploratory Data Analysis on Titanic Dataset

## About the Project

This project focuses on **Data Cleaning** and **Exploratory Data Analysis (EDA)** using the Titanic dataset. Before performing any analysis or building machine learning models, it is important to clean the dataset and understand its structure. This project explores the data through statistical summaries and visualizations to identify trends, relationships, and patterns among different passenger attributes.

The analysis provides insights into factors such as passenger age, gender, ticket fare, passenger class, and survival.

---

## Project Goal

The main objectives of this project are:

- Clean the dataset by handling missing values.
- Understand the structure of the dataset.
- Explore the distribution of numerical and categorical features.
- Identify relationships between different variables.
- Visualize important trends using graphs and charts.

---

## Dataset

**Dataset:** Titanic Dataset

The dataset contains demographic and travel information about passengers aboard the RMS Titanic.

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

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Data Preparation

Before performing the analysis, the following preprocessing steps were carried out:

- Loaded the dataset.
- Examined the dataset structure and missing values.
- Filled missing values in the **Age** column using the median.
- Filled missing values in the **Embarked** column using the mode.
- Removed the **Cabin** column due to a large number of missing values.
- Generated statistical summaries for numerical features.

---

## Analysis Performed

The following analyses were carried out:

- Age Distribution
- Gender Distribution
- Survival Distribution
- Survival by Gender
- Survival by Passenger Class
- Fare Distribution
- Age vs Survival
- Fare vs Survival
- Correlation Heatmap
- Pair Plot Analysis

---

## Visualizations

The project includes the following visualizations:

- Histogram of Passenger Age
- Gender Distribution Plot
- Survival Distribution Plot
- Survival by Gender
- Survival by Passenger Class
- Fare Distribution Histogram
- Age vs Survival Box Plot
- Fare vs Survival Box Plot
- Correlation Heatmap
- Pair Plot of Selected Features

---

## Folder Structure

```
SCT_DS_02/
│
├── Titanic-Dataset.csv
├── Data_cleaning_and_EDA.ipynb
├── README.md
└── output_images/
```

---

## Key Findings

Some important observations from the analysis include:

- Most passengers were between **20 and 40 years** of age.
- Male passengers were more numerous than female passengers.
- Female passengers had a noticeably higher survival rate.
- First-class passengers had better survival chances than passengers in lower classes.
- Higher ticket fares were generally associated with a greater probability of survival.
- Age showed only a weak relationship with survival compared to other features.

---

## Conclusion

This project demonstrates the complete process of cleaning a dataset and performing exploratory data analysis. The visualizations and statistical analysis provide valuable insights into passenger demographics, travel characteristics, and survival patterns. The project also highlights the importance of EDA as a crucial step before developing machine learning models.

---

## Author

**Vijay Prakash**

Dr. B. R. Ambedkar National Institute of Technology (NIT Jalandhar)  
Jalandhar, Punjab

---
