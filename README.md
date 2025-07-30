 Melanoma Survival Analysis Using R

## Project Overview

This project applies exploratory data analysis (EDA) techniques to a melanoma dataset to understand patient survival outcomes based on clinical features. Using R and `ggplot2`, I analyzed relationships between variables such as age, sex, tumor thickness, and ulceration, providing actionable insights that could guide further modeling or clinical research.

---

##  Objectives

- Explore and summarize the melanoma dataset using R  
- Identify features associated with patient survival  
- Use visualizations to compare patterns across subgroups (e.g., male vs female)  
- Support clinical intuition with data-driven insights

---

##  Dataset Summary

The dataset includes patient-level melanoma data with fields such as:

- Age at diagnosis  
- Sex  
- Tumor thickness  
- Presence of ulceration  
- Histological classification  
- Survival time and status

---

##  Tools & Technologies

- **R**
- `dplyr`
- `ggplot2`
- `summarytools`

---

##  Methodology

1. **Data Cleaning & Transformation**
   - Checked for missing values
   - Reformatted variables (e.g., categorical conversions)

2. **Univariate Analysis**
   - Summarized variables using frequency tables and statistical summaries

3. **Bivariate Analysis**
   - Compared survival status across subgroups (e.g., by gender, ulceration)
   - Explored distribution of tumor thickness across survivors and non-survivors

4. **Visualizations**
   - Histograms and boxplots for continuous variables
   - Bar plots for categorical comparisons
   - Grouped summary tables using `group_by` and `summarise`

---

##  Key Insights

- Non-survivors had higher median tumor thickness compared to survivors  
- Ulceration was more common among patients who did not survive  
- Age showed a slight upward trend among non-survivors  
- Male patients had a higher mortality rate in the dataset

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)  
- Data cleaning and transformation in R  
- Subgroup comparisons and clinical data interpretation  
- Visualization with `ggplot2`  
- Descriptive statistics and frequency analysis

---

##  Author

Created by **Bob** — NHS nurse and aspiring data scientist focused on healthcare impact through data.  
For feedback and collaboration: **samjehbobga@yahoo.com**

---

##  What I Learned

- How small clinical features (like ulceration or thickness) play significant roles in survival  
- The power of grouped summary analysis in R  
- How to tell a data-driven story that clinicians can relate to

---
