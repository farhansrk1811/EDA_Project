# Exploratory Data Analysis of Roller-Coaster Characteristics

## Project Overview

This project explores a roller-coaster dataset using Python to identify patterns, trends, data-quality issues, and relationships between selected numerical variables.

The analysis uses statistical summaries and data visualizations to understand roller-coaster speeds, introduction years, heights, and inversions.

## Objectives

- Understand the structure and characteristics of the dataset.
- Calculate descriptive statistical summaries.
- Identify missing values and duplicate records.
- Visualize roller-coaster speed and introduction-year distributions.
- Examine correlations between selected numerical variables.
- Summarize the key findings and limitations of the analysis.

## Dataset Description

The dataset, `coaster_db.csv`, contains **1,087 records and 56 columns**.

Some of the variables used in the analysis include:

- `coaster_name`: Roller-coaster name
- `Speed`: Recorded speed information
- `Location`: Roller-coaster location
- `Status`: Operating or other recorded status
- `Manufacturer`: Manufacturer information
- `speed_mph`: Speed in miles per hour
- `height_value`: Numerical height value
- `Inversions`: Number of inversions
- `year_introduced`: Year introduced

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code
- Git and GitHub

## Methodology

### 1. Data Loading and Inspection

Loaded the CSV dataset into a Pandas DataFrame and inspected its dimensions, column names, data types, and sample records.

### 2. Statistical Analysis

Calculated descriptive statistics, including count, mean, median, standard deviation, minimum, maximum, and quartiles for relevant numerical variables.

### 3. Data Quality Assessment

Examined missing values, missing-value percentages, and duplicate records. The dataset contains incomplete fields that may affect the interpretation of certain results.

### 4. Data Visualization

Created the following visualizations:

- Histogram of roller-coaster speeds with a density curve
- Histogram of roller coasters by introduction year
- Correlation heatmap for selected numerical variables

### 5. Correlation Analysis

Examined Pearson correlations among speed, height, inversions, and introduction year to identify possible linear relationships.

## Key Findings

- The dataset contains 1,087 records and 56 columns.
- The average recorded roller-coaster speed is approximately **48.62 mph**, while the median is **49.70 mph**.
- Recorded speeds are concentrated around the middle speed ranges, with a right-skewed distribution.
- The introduction-year histogram contains more records in recent decades than in the earliest decades.
- No completely duplicated rows were detected.
- The dataset contains **29,435 missing cells**, indicating substantial data incompleteness.
- The selected numerical variables show weak positive correlations. The largest off-diagonal correlation in the calculated matrix is **0.25**, between speed and inversions.

## Conclusion

This project demonstrates how Exploratory Data Analysis can be used to understand a dataset through statistical summaries, visualizations, data-quality checks, and correlation analysis.

The results indicate that recorded roller-coaster speeds are concentrated around the middle ranges and that the selected numerical variables have relatively weak linear relationships. Missing data and potential extreme observations should be investigated further before drawing stronger conclusions.

## Limitations

- Many dataset fields contain missing values.
- Repeated coaster names do not necessarily indicate duplicate records.
- Extreme numerical values may require validation.
- Correlation does not establish causation.
- The observed introduction-year distribution represents the records in this dataset and may not reflect the total number of roller coasters built worldwide.

## How to Run the Project

1. Install Python and the required libraries.
2. Download or clone this repository.
3. Keep `coaster_db.csv` in the project directory.
4. Open `introduction-to-exploratory-data-analysis.ipynb` in VS Code or Jupyter Notebook.
5. Select a Python kernel and execute the notebook cells.

Install the main dependencies using:

```bash
python -m pip install pandas numpy matplotlib seaborn jupyter ipykernel
```

## Project Files

- `introduction-to-exploratory-data-analysis.ipynb`: Notebook containing the EDA code, statistical summaries, visualizations, and findings.
- `coaster_db.csv`: Dataset used for the analysis.
- `README.md`: Project documentation.

## Author

**Farhan Sirkhot**

GitHub Repository: https://github.com/farhansrk1811/EDA_Project