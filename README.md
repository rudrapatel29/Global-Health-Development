# **Global Health Expenditure Analysis (WHO)**

## **Overview**
This project analyzes the Global Health Expenditure Database from the World Health Organization (WHO) to uncover trends, patterns, and disparities in health spending across countries and regions. The analysis involves data cleaning, exploration, visualization, and statistical analysis to provide insights into global health expenditure and its implications on healthcare systems.

## **Project Goals**
- **Popularity Analysis**: Investigate how health expenditure varies across countries and regions, and identify regions with the highest and lowest expenditure.
- **Regional Analysis**: Determine health expenditure patterns across different regions and income groups.
- **Spending Trends**: Examine changes in health expenditure over time and its impact on healthcare accessibility.

## **Data Wrangling and Manipulation**
The following techniques were used to clean and manipulate the dataset:

- **Handling Missing Values**: Identified and removed rows with missing values in critical columns.
- **DateTime Conversion**: Converted any relevant date columns to datetime format for time-based analysis.
- **Indexing**: Set appropriate columns as indexes for easier data handling.
- **Feature Extraction**: Extracted year and region information to analyze trends over time and across regions.

## **Analysis Highlights**

### **Data Cleaning**
- Identified and removed rows with missing or inconsistent data.

### **Popularity Analysis**
- Analyzed health expenditure as a percentage of GDP by country and region.
- Visualized trends in expenditure over time and across different income groups.

### **Regional Analysis**
- Compared Domestic General Government Health Expenditure (GGHE-D) across regions such as Europe, Africa, and the Western Pacific.
- Analyzed disparities in Out-of-Pocket Expenditure (OOPS) among different income groups.

### **Spending Trends**
- Investigated changes in health expenditure over the years and its impact on healthcare accessibility.

## **Visualization and Tools**

### **Libraries Used**
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib**: For plotting and visualization.
- **seaborn**: For advanced visualizations.

### **Visualization Techniques**
- **Bar plots**: To show regional health expenditure and average spending.
- **Line plots**: To visualize trends in health expenditure over time.
- **Scatter plots and heatmaps**: To explore relationships between different health expenditure metrics.

### **PowerBI Dashboard**
The PowerBI dashboard includes the following visualizations:

1. **Current Health Expenditure as % of GDP by Region**: Highlights regions with the highest and lowest health expenditures relative to GDP.
2. **Current Health Expenditure per Capita**: Shows countries with the highest and lowest per capita health spending.
3. **Private vs. Government Health Expenditure Over the Years**: Demonstrates the evolution of government and private sector contributions to healthcare.
4. **External Health Expenditure Trends**: Displays reliance on external contributions in low-income regions.
5. **Average Out-of-Pocket Expenditure by Region**: Shows the burden of out-of-pocket costs in various countries.

You can explore the dashboard for deeper insights into global health expenditure [here](#).

## **Technologies Used**
- **Python Libraries**: pandas, numpy, seaborn, matplotlib.
- **Power BI**: For creating interactive visualizations and dashboards.
- **Data Cleaning & Preprocessing**: Removing inconsistencies, handling missing data, and preparing the dataset for analysis.
- **Advanced Analytics**: Correlation and causation analysis to explore relationships between different health expenditure metrics.

## **Conclusion**
The analysis reveals significant disparities in global health expenditure, with wealthier countries generally investing more in healthcare relative to GDP. Lower-income regions often depend on external contributions, highlighting the need for tailored health funding strategies.

## **Repository Contents**
- **Data**: The dataset used for analysis (with necessary anonymization and data cleaning steps).
- **Notebooks**: Jupyter notebooks containing the data analysis and visualization code.
- **Codebook**: An Excel sheet containing description of columns in the dataset.
- **Dashboard**: A PDF of Visualizations made using PowerBI.

---
