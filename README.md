# adult_demographics_analysis

**Introduction**
The "YouTube Channels Dataset" analysis delves into a comprehensive exploration of a dataset associated with YouTube channels. This dataset, available here, encapsulates essential information about diverse YouTube channels. Key features include rank, grade, channel name, video uploads, subscribers, and video views.

**Dataset Overview**
The dataset encompasses 48,842 rows and 15 columns, providing a substantial amount of information for analysis.

**Dataset Information**
A detailed examination of the dataset structure reveals essential insights. It comprises a variety of columns, including age, workclass, fnlwgt, education, marital status, occupation, relationship, race, gender, capital gain, capital loss, hours per week, native country, and income.

**Data Cleaning**

### Handling Missing Values

Addressing missing values is crucial for robust analysis. This dataset initially underwent a process to identify and visualize null values. Rows with missing values were subsequently dropped, ensuring data integrity.

### Duplicate Data Removal
Duplicate entries within the dataset were identified and removed to maintain the accuracy and reliability of the data.

### Column Adjustment
Certain columns, such as educational-num, capital-gain, and capital-loss, were deemed unnecessary for the analysis and were consequently dropped.

**Univariate Analysis**
### Age Distribution
The age distribution within the dataset was explored, revealing insights into the age demographics of the YouTube channels included.

### Workclass Distribution
A histogram visualizing the distribution of workclass shed light on the prevalence of different work categories among the channels.

### Educational Attainment
An examination of the dataset uncovered the number of individuals with Bachelors or Masters degrees, providing educational insights.

**Bivariate Analysis**
Encoding Income Values
Income values ('<=50K' and '>50K') were encoded into numerical representations (0 and 1) for effective analysis.

### Workclass vs. Salary
A comparative analysis of workclass and associated salary levels showcased which work categories tended to yield higher average salaries.

### Gender vs. Salary
Examining the relationship between gender and salary revealed insights into income disparities.

### Categorical Conversion
To enhance categorical analysis, the 'workclass' column was converted to a categorical datatype.
