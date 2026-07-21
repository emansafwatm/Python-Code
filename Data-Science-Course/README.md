# Data Science Course

This directory contains instructional notebooks introducing practical data analysis, data cleaning, statistical relationships, visualization, exploratory analysis, and interpretation using Python.

The materials are intended for classroom demonstrations, guided laboratory sessions, and independent practice.

## Learning Objectives

After completing these notebooks, students should be able to:

- load structured data using Pandas;
- inspect dataset dimensions, columns, data types, and quality;
- identify and treat missing, duplicated, inconsistent, and invalid values;
- convert variables to suitable data types;
- summarize numerical and categorical variables;
- group and aggregate records;
- calculate and interpret correlation coefficients;
- distinguish correlation from causation;
- create statistical and comparative visualizations;
- analyze historical election results;
- communicate findings clearly and acknowledge analytical limitations.

## Notebook Topics

| Notebook | Main topic |
|---|---|
| `Data_Cleaning_and_Missing_Values.ipynb` | Dataset inspection, duplicates, missing values, inconsistent categories, type conversion, invalid values, outlier screening, validation, and documentation |
| `Correlation.ipynb` | Pearson correlation, statistical interpretation, and multivariable visualization |
| `US_Presidential_Election_Analysis.ipynb` | Exploratory analysis of historical United States presidential-election results |

## Suggested Study Sequence

### 1. Data Cleaning and Missing Values

Begin with:

```text
notebooks/Data_Cleaning_and_Missing_Values.ipynb
```

This notebook establishes the data-quality workflow required before reliable statistical analysis or machine learning.

### 2. Correlation Analysis

Continue with:

```text
notebooks/Correlation.ipynb
```

This lesson introduces numerical relationships and emphasizes that correlation does not establish causation.

### 3. Applied Exploratory Analysis

Complete:

```text
notebooks/US_Presidential_Election_Analysis.ipynb
```

This notebook applies data manipulation, summarization, and visualization to a historical dataset.

## Environment

The core notebooks require:

```bash
pip install numpy pandas matplotlib
```

Additional notebook-specific requirements should be checked inside each notebook.

## Data-Quality Principles

The course emphasizes that:

- raw data should be preserved;
- cleaning decisions should be reproducible;
- missing-value treatment should be justified;
- potential outliers should be investigated rather than automatically deleted;
- validation checks should be performed after cleaning;
- analytical limitations should be reported clearly.
