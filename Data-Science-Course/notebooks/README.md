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
- perform exploratory data analysis;
- group and aggregate records;
- create and interpret pivot tables;
- calculate and interpret correlation coefficients;
- distinguish correlation from causation;
- create statistical and comparative visualizations;
- identify potential outliers;
- analyze historical election results;
- communicate findings clearly and acknowledge analytical limitations.

## Notebook Topics

| Notebook | Main topic |
|---|---|
| `Data_Cleaning_and_Missing_Values.ipynb` | Dataset inspection, duplicates, missing values, inconsistent categories, type conversion, invalid values, outlier screening, validation, and documentation |
| `Exploratory_Data_Analysis.ipynb` | Descriptive statistics, distributions, categorical summaries, grouping, pivot tables, correlation, outlier analysis, data-quality reporting, and interpretation |
| `Correlation.ipynb` | Pearson correlation, statistical interpretation, and multivariable visualization |
| `US_Presidential_Election_Analysis.ipynb` | Exploratory analysis of historical United States presidential-election results |

## Suggested Study Sequence

1. `Data_Cleaning_and_Missing_Values.ipynb`
2. `Exploratory_Data_Analysis.ipynb`
3. `Correlation.ipynb`
4. `US_Presidential_Election_Analysis.ipynb`

## Environment

The core notebooks require:

```bash
pip install numpy pandas matplotlib
```

Additional notebook-specific requirements should be checked inside each notebook.

## Course Principles

The course emphasizes that:

- raw data should be preserved;
- cleaning and analysis should be reproducible;
- missing-value treatment should be justified;
- visualizations should answer analytical questions;
- potential outliers should be investigated rather than automatically deleted;
- correlation should not be interpreted as causation;
- findings should be supported by measurable evidence;
- analytical limitations should be reported clearly.
