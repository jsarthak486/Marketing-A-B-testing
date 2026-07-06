# 📊 A/B Testing Analysis – Marketing Campaign Optimization

> **Data Analyst Portfolio Project**
>
> A complete A/B Testing analysis to evaluate whether a new advertising strategy significantly improves user conversion rates using statistical hypothesis testing and data visualization.

---

## 📌 Project Overview

Businesses spend millions on advertising campaigns every year. But how do we know if a new marketing strategy actually performs better?

In this project, I analyzed a real-world A/B testing dataset to determine whether the **Test Group** outperformed the **Control Group** in terms of customer conversion.

The project combines **data cleaning, exploratory data analysis (EDA), statistical testing, visualization, and business insights** to support data-driven decision making.

---

## 🎯 Business Problem

The marketing team introduced a new advertising strategy and randomly assigned users into:

- **Control Group** – Existing advertisement
- **Test Group** – New advertisement

The objective is to answer:

- Does the new advertisement increase conversion?
- Is the improvement statistically significant?
- Should the company adopt the new campaign?

---

## 📂 Dataset Information

The dataset contains user-level marketing campaign data including:

- User ID
- Test Group (Control/Test)
- Converted (Yes/No)
- Total Ads Seen
- Most Active Day
- Most Active Hour

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📈 Project Workflow

### 1. Data Loading

- Imported dataset
- Examined structure
- Checked data types
- Verified missing values
- Removed duplicate records

---

### 2. Exploratory Data Analysis (EDA)

Performed visual and statistical analysis including:

- Conversion rate comparison
- Distribution of users
- Ads viewed analysis
- Conversion by weekday
- Conversion by hour
- Group-wise comparisons

Visualizations include:

- Count Plots
- Bar Charts
- Histograms
- Box Plots
- Heatmaps

---

### 3. Statistical Analysis

Applied hypothesis testing to validate business decisions.

#### Independent Samples t-test

Compared conversion rates between:

- Control Group
- Test Group

**Objective:**

Determine whether the observed difference occurred by chance.

---

#### ANOVA

Analyzed whether conversion rates differed across:

- Days of the Week

---

## 📊 Key Findings

✔ Compared conversion performance between control and test groups.

✔ Evaluated user behavior based on advertisement exposure.

✔ Identified peak conversion days.

✔ Determined whether observed differences were statistically significant.

✔ Converted statistical findings into actionable business insights.

---

## 📌 Business Insights

Based on the analysis:

- Statistical testing provides evidence for deciding whether the new campaign should replace the existing one.
- Data-driven experimentation reduces business risk before launching large-scale marketing campaigns.
- User engagement patterns can help optimize advertisement scheduling.

---

## 📁 Repository Structure

```
├── ABtesting.ipynb          # Complete analysis notebook
├── marketing_AB.csv         # Dataset
├── README.md                # Project documentation
```

---

## 🚀 Skills Demonstrated

### Data Analysis

- Data Cleaning
- Exploratory Data Analysis
- Feature Understanding
- Business Interpretation

### Statistics

- Hypothesis Testing
- Independent t-test
- ANOVA
- p-value Interpretation
- Statistical Significance

### Data Visualization

- Matplotlib
- Seaborn
- Insightful Charts
- Business Dashboards

### Python Libraries

- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn

---
### Conversion Rate by Test Group

![Conversion Rate](<img width="497" height="328" alt="image" src="https://github.com/user-attachments/assets/2f3cb07c-d0a1-4031-9fe7-b6bb4e776455" />
)
### conversion Rate by Most Ads Hour
![Conversion Rate](<img width="658" height="331" alt="image" src="https://github.com/user-attachments/assets/4c56104d-e80b-4d66-8812-e6b7c4e8d34c" />
)
## 💼 Why This Project Matters

This project demonstrates my ability to:

- Solve real business problems using data
- Perform end-to-end data analysis
- Apply statistical techniques correctly
- Communicate insights through visualization
- Translate analytical results into business recommendations

These are essential skills expected from a **Data Analyst** in industries such as Marketing, E-commerce, Product Analytics, and Business Intelligence.

---

## 📚 What I Learned

Through this project I strengthened my understanding of:

- A/B Testing methodology
- Experimental design
- Statistical hypothesis testing
- Data storytelling
- Business-focused analytics
- Python for real-world data analysis

---

## 👨‍💻 Author

**Sarthak Jain**

Aspiring **Data Analyst** passionate about transforming raw data into meaningful business insights through analytics, visualization, and statistical modeling.

---

## ⭐ If you found this project useful...

Please consider giving this repository a ⭐ on GitHub.

Thank you for visiting!
