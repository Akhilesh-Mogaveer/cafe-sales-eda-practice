# Café Sales — Data Cleaning & EDA Practice

## What This Is
A self-practice project to learn:
- Data cleaning techniques in Pandas
- Handling missing values, wrong datatypes, dirty strings
- EDA using Matplotlib and Seaborn

## Dataset
Dirty café sales dataset with 10,000 rows containing:
- NULL values, ERROR strings, UNKNOWN placeholders
- Mixed datatypes in numeric columns
- Inconsistent categorical values

## What I Practiced
### Cleaning
- Detected and replaced ERROR/UNKNOWN with NaN
- pd.to_numeric(errors='coerce') for mixed columns
- Mean imputation for numerical columns
- Mode imputation for categorical columns
- Datetime conversion
- IQR-based outlier detection (found 259 outliers)

### Visualization
- Bar, Histogram, Pie, Box, Violin
- Scatter, Bubble chart, Regression plot
- Heatmap, Pairplot, Line chart
- Both Matplotlib and Seaborn

## What I Learned
- Real datasets are always messy
- Cleaning takes more time than analysis
- Different plots serve different purposes
 
