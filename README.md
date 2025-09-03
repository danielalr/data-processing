# Data processing

## Introduccion
This project focuses on the comprehensive data cleaning and preprocessing stages for a customer churn prediction model. It goes beyond basic methods by incorporating a thorough exploratory data analysis (EDA) and visualizing the impact of each cleaning step to ensure the data is robust and ready for a machine learning model.

## Data Source
The dataset used is DatasetChurn5000.csv, which contains information on customer behavior and account details. The key features include Edad (Age), Uso_mensual_GB (Monthly GB Usage), and Soporte_contactado (Support Contacted), all of which contain missing values.

## Key Preprocessing Steps and Methods
This project demonstrates a complete data cleaning workflow, with a focus on documenting and visualizing each step's effect on the data. The following methods were applied:

1. Exploratory Data Analysis (EDA)
Before any cleaning, a descriptive analysis of the dataset was performed to understand the initial state of the data. This included:

    Checking for missing values across all columns.

    Visualizing the distribution of key numerical features (Edad, Uso_mensual_GB) using histograms and boxplots to identify potential skewness and the presence of outliers.

2. Handling Missing Values
Missing values were handled using the median imputation method. The median was chosen because it's a robust statistic that is less affected by extreme values than the mean. The project includes a visual comparison of the feature distributions before and after imputation to demonstrate the minimal impact on the data's integrity.

3. Outlier Detection and Removal
Outliers were identified and removed using the Z-score method, which is effective for features with a near-normal distribution. The cleaning process for outliers was also visually validated using boxplots to show the reduction of extreme data points.

## Conclusion
This project provides a well-documented and reproducible data cleaning pipeline. By combining exploratory analysis with visual validation of the cleaning steps, it ensures that the resulting dataset is not only free of missing values and outliers but also maintains its original statistical properties as much as possible. The final processed dataset is saved as a new CSV file, making it directly available for the next stages of modeling and analysis.
