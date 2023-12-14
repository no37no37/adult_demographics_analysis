# Adult Demographics Analysis

**Introduction**

This analysis delves into a comprehensive exploration of a dataset associated with Adult Demographics and income. 

**Dataset Overview**

The dataset encompasses 48,842 rows and 15 columns, providing a substantial amount of information for analysis.

**Dataset Information**

A detailed examination of the dataset structure reveals essential insights. It comprises a variety of columns, including age, workclass, fnlwgt, education, marital status, occupation, relationship, race, gender, capital gain, capital loss, hours per week, native country, and income.

## Data Cleaning

### Handling Missing Values

Addressing missing values is crucial for robust analysis. This dataset initially underwent a process to identify and visualize null values. Rows with missing values were subsequently dropped, ensuring data integrity.

### Duplicate Data Removal
Duplicate entries within the dataset were identified and removed to maintain the accuracy and reliability of the data.

### Column Adjustment
Certain columns, such as educational-num, capital-gain, and capital-loss, were deemed unnecessary for the analysis and were consequently dropped.

## Univariate Analysis

### Age Distribution
![image](https://github.com/no37no37/adult_demographics_analysis/assets/132648428/b734e8fd-2132-4c3c-9f5d-7d359b743d36)

The age distribution within the dataset was explored, revealing insights into the age demographics of the YouTube channels included.

### Workclass Distribution
![image](https://github.com/no37no37/adult_demographics_analysis/assets/132648428/7b15333b-95c0-46a9-bdbe-98abb89a79c3)

A histogram visualizing the distribution of workclass shed light on the prevalence of different work categories among the channels.

### Educational Attainment
An examination of the dataset uncovered the number of individuals with Bachelors or Masters degrees, providing educational insights.

## Bivariate Analysis

### Encoding Income Values
![image](https://github.com/no37no37/adult_demographics_analysis/assets/132648428/d278e9f3-6fbb-4901-806b-e815940faeda)

Income values ('<=50K' and '>50K') were encoded into numerical representations (0 and 1) for effective analysis.

### Workclass vs. Salary
A comparative analysis of workclass and associated salary levels showcased which work categories tended to yield higher average salaries.

### Gender vs. Salary
Examining the relationship between gender and salary revealed insights into income disparities.

### Categorical Conversion
To enhance categorical analysis, the 'workclass' column was converted to a categorical datatype.
