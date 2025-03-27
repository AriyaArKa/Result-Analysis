# Student Performance Dataset - Data Analysis

## Overview
This project involves the analysis of a student performance dataset, examining various factors affecting student scores in mathematics, reading, and writing. The dataset contains demographic and academic information such as gender, parental education, lunch type, and test preparation status.

## Dataset Information
- **Total Columns:** 15
- **Total Rows:** ~10,000
- **Key Features:**
  - **Demographics:** Gender, Ethnic Group, Parent Marital Status
  - **Academic Background:** Parent Education Level, Test Preparation
  - **Scores:** Math, Reading, Writing Scores
  - **Other Variables:** Number of Siblings, Transport Means

## Installation & Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install numpy pandas matplotlib seaborn
```

## Data Cleaning & Processing
- Removed **unnamed index column**.
- Identified **missing values** in EthnicGroup, ParentEduc, TestPrep, ParentMaritalStatus, and TransportMeans columns.
- Checked summary statistics for score distributions and potential outliers.

## Key Findings
1. **Gender Distribution:** More female students than male students.
2. **Parental Education Influence:** Higher parental education correlates with better student performance.
3. **Score Distribution:** The average scores for Math, Reading, and Writing are ~66, 69, and 68, respectively.
4. **Outliers:** Some students scored 0, indicating possible data entry errors or missing exams.

## Next Steps
- Handle missing values (imputation or removal based on impact).
- Perform further statistical tests to determine correlations between factors.
- Develop predictive models to analyze score trends.

## Author
[Arka Nath]

## License
This project is for educational purposes only. Feel free to modify and improve upon it!

