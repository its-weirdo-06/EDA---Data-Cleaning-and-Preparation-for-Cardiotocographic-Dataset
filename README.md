# EDA---Data-Cleaning-and-Preparation-for-Cardiotocographic-Dataset

**Description:**

This repository contains Python code for data cleaning and preparation for the Cardiotocographic dataset. The dataset consists of various features related to fetal heart rate (FHR) and uterine contractions, among others.

**Steps Performed:**

**Loading the Dataset:**

Loaded the dataset into a DataFrame using Pandas.

Checked the structure and information of the dataset using df.info() and df.head().

**Handling Missing Values:**

Detected missing values in the dataset using df.isna().sum().

Decided to drop rows with missing values using df.dropna().

**Outlier Detection and Treatment:**


Detected outliers using the interquartile range (IQR) method.

Treated outliers by replacing extreme values with the lower and upper bounds calculated from the IQR.

**Summary Statistics:**

Generated descriptive statistics for each variable using df.describe().

**Data Visualization:**

Created histograms to visualize the distributions of numerical variables.

Constructed a correlation heatmap to explore relationships between pairs of variables.

Utilized violin plots to visualize the distribution of each variable.

**Exporting Cleaned Dataset:**

Saved the cleaned dataset as a CSV file using df.to_csv().

**File Structure:**

EDA_Assignment.ipynb: Jupyter Notebook containing the Python code for data cleaning and preparation.

Cardiotocographic_cleaned.csv: Cleaned dataset saved as a CSV file.

