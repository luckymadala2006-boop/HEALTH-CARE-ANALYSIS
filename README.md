# Healthcare Analytics for Doctor Visits

## Project Overview

**Healthcare Analytics for Doctor Visits** is a data analysis project that explores patient healthcare data to identify patterns and relationships associated with the number of doctor visits.

The project uses Python-based data analysis and visualization techniques to examine factors such as **age, gender, income, illness, health condition, reduced activity, and chronic conditions**.

---

## Problem Statement

Healthcare datasets contain valuable information about patients and their healthcare utilization. Analyzing this data can help identify patterns in doctor visits and understand how different patient characteristics are associated with healthcare usage.

This project analyzes healthcare data to discover meaningful patterns related to the number of doctor visits.

---

## Objectives

* Understand and analyze the healthcare dataset.
* Perform data cleaning and preprocessing.
* Explore patient demographic and health-related factors.
* Analyze the distribution of doctor visits.
* Study relationships between healthcare factors and doctor visits.
* Create meaningful data visualizations.
* Generate insights from the analyzed data.

---

## Dataset

The dataset used in this project is:

**P2 - Healthcare Analytics for Doctor Visits**

### Dataset Details

* **Records:** 5,190
* **Columns:** 13
* **Missing Values:** 0
* **Duplicate Rows:** 0

### Important Variables

* `visits` – Number of doctor visits
* `gender` – Patient gender
* `age` – Patient age
* `income` – Patient income
* `illness` – Number of reported illnesses
* `reduced` – Reduced activity
* `health` – Health-related measure
* `private` – Private healthcare indicator
* `freepoor` – Free/poor healthcare indicator
* `freerepat` – Free/repat healthcare indicator
* `nchronic` – Chronic condition indicator
* `lchronic` – Long-term chronic condition indicator

The `Unnamed: 0` column is treated as an index/ID column and is excluded from the analysis.

---

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Google Colab**

---

## Data Analysis Process

The project follows these steps:

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Correlation Analysis
   ↓
Insights & Findings
```

---

## Data Cleaning

The following checks and preprocessing steps were performed:

* Checked dataset dimensions.
* Examined column names and data types.
* Checked for missing values.
* Checked for duplicate records.
* Removed the unnecessary index column.
* Generated descriptive statistics.
* Examined unique values of variables.

---

## Exploratory Data Analysis

The following analyses were performed:

### 1. Doctor Visits Distribution

The distribution of the number of doctor visits was analyzed to understand healthcare utilization patterns.

### 2. Gender Analysis

Doctor visits were compared across male and female patients.

### 3. Age Analysis

The age distribution of patients and its relationship with doctor visits were explored.

### 4. Illness Analysis

The relationship between the number of reported illnesses and doctor visits was analyzed.

### 5. Reduced Activity Analysis

The relationship between reduced activity and doctor visits was examined.

### 6. Health Analysis

Health-related values were compared with doctor visits.

### 7. Income Analysis

The relationship between income and doctor visits was analyzed.

### 8. Chronic Condition Analysis

Doctor visits were analyzed based on chronic-condition indicators.

### 9. Correlation Analysis

A correlation matrix and heatmap were created to identify relationships among numerical variables.

---

## Key Findings

* The dataset contains **5,190 patient records**.
* There are **no missing values or duplicate records** in the analyzed dataset.
* A large proportion of records have zero doctor visits.
* Female patients have a higher average recorded doctor-visit count than male patients.
* Average doctor visits generally increase with the number of reported illnesses.
* Reduced activity shows a positive relationship with doctor visits.
* Illness and health-related variables also show positive relationships with doctor visits.
* Chronic-condition indicators show differences in recorded doctor-visit frequency.
* The `visits` variable has a highly concentrated distribution around zero.

---

## Visualizations

The project includes visualizations such as:

* Doctor Visits Distribution
* Patient Distribution by Gender
* Average Doctor Visits by Gender
* Age Distribution
* Age vs Doctor Visits
* Illness Distribution
* Illness vs Average Doctor Visits
* Reduced Activity vs Doctor Visits
* Health vs Doctor Visits
* Income vs Doctor Visits
* Chronic Conditions Analysis
* Correlation Heatmap

---

## End Users

This analysis can be useful for:

* Hospitals and healthcare organizations
* Doctors and healthcare professionals
* Healthcare data analysts
* Healthcare researchers
* Healthcare administrators

---

## How to Run the Project

### 1. Open Google Colab

Create a new notebook in Google Colab.

### 2. Upload the Dataset

Upload:

```text
P2-Healthcare Analytics for Doctor Visits.csv
```

### 3. Install/Import Required Libraries

The project uses:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

### 4. Load the Dataset

```python
df = pd.read_csv("P2-Healthcare Analytics for Doctor Visits.csv")
```

### 5. Run the Analysis

Execute the notebook cells sequentially to perform data cleaning, exploratory analysis, visualization, and correlation analysis.

---

## Project Structure

```text
Healthcare-Analytics-Doctor-Visits/
│
├── P2-Healthcare Analytics for Doctor Visits.csv
├── Healthcare_Analytics_Doctor_Visits.ipynb
└── README.md
```

---

## Conclusion

This project demonstrates how healthcare data can be analyzed using Python to identify patterns in doctor visits. Through data cleaning, exploratory data analysis, visualization, and correlation analysis, the project provides insights into the relationship between patient characteristics, health factors, and healthcare utilization.

---

## Author

**Madala Rama Lakshmi**

B.Tech – Artificial Intelligence and Machine Learning

---

## Tools

Developed using **Python and Google Colab**.
