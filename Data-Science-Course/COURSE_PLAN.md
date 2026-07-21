# Data Science Course Plan

## Course Purpose

This course develops practical competence in preparing, exploring, analyzing, visualizing, and interpreting structured data with Python. It is designed for undergraduate learners, professional trainees, and independent learners preparing for machine-learning study.

The course emphasizes reproducible analysis, evidence-based interpretation, transparent assumptions, and responsible communication of results.

## Intended Audience

Learners should have:

- basic Python programming knowledge;
- familiarity with variables, functions, loops, and data structures;
- no prior formal data-science experience.

## Course Learning Outcomes

After completing the course, learners should be able to:

1. load and inspect structured datasets;
2. identify missing, duplicated, inconsistent, and invalid values;
3. apply and document appropriate data-cleaning decisions;
4. summarize numerical and categorical variables;
5. perform exploratory data analysis;
6. create clear statistical visualizations;
7. group, aggregate, and reshape data;
8. interpret correlation and association measures;
9. distinguish association from causation;
10. perform introductory statistical inference and hypothesis testing;
11. recognize potential outliers and data-quality limitations;
12. communicate findings with supporting evidence;
13. complete an end-to-end data-analysis case study.

## Public Repository Scope

The public repository contains:

- instructional notebooks;
- small teaching datasets;
- guided exercises;
- mini challenges;
- course documentation;
- references and further-reading recommendations.

Formal quizzes, answer keys, grading rubrics, and complete exercise solutions are intentionally excluded from the public repository.

## Recommended Course Sequence

| Unit | Notebook | Status | Main focus |
|---:|---|---|---|
| 1 | `Data_Cleaning_and_Missing_Values.ipynb` | Available | Inspection, missing values, duplicates, invalid values, type conversion, and validation |
| 2 | `Exploratory_Data_Analysis.ipynb` | Available | Distributions, summaries, relationships, grouping, outliers, and evidence-based findings |
| 3 | `Data_Visualization_with_Matplotlib.ipynb` | Planned | Visual encodings, chart selection, layout, annotation, and misleading graphs |
| 4 | `Descriptive_Statistics.ipynb` | Planned | Central tendency, dispersion, quantiles, skewness, and interpretation |
| 5 | `Grouping_Aggregation_and_Pivot_Tables.ipynb` | Planned | GroupBy, aggregation, crosstabs, pivot tables, and reshaping |
| 6 | `Correlation_and_Association.ipynb` | Existing content to review | Pearson, Spearman, categorical association, limitations, and interpretation |
| 7 | `Statistical_Hypothesis_Testing.ipynb` | Planned | Sampling, confidence intervals, p-values, t-tests, chi-square tests, and effect size |
| 8 | `US_Presidential_Election_Analysis.ipynb` | Existing case study | Applied exploratory analysis and interpretation |
| 9 | `End_to_End_Data_Analysis_Case_Study.ipynb` | Planned | Complete workflow from raw data to defensible conclusions |

## Unit Details

### Unit 1 — Data Cleaning and Missing Values

Topics:

- initial dataset inspection;
- data types;
- missing-value summaries;
- exact and business-key duplicates;
- inconsistent categorical labels;
- numeric and datetime conversion;
- invalid-value rules;
- imputation strategies;
- outlier screening;
- validation assertions;
- cleaning logs.

### Unit 2 — Exploratory Data Analysis

Topics:

- analytical questions;
- descriptive summaries;
- numerical distributions;
- categorical frequency analysis;
- grouping and aggregation;
- pivot tables and crosstabs;
- scatter plots and correlations;
- categorical–numerical comparisons;
- potential outliers;
- compact data-quality reports;
- evidence-based conclusions.

### Unit 3 — Data Visualization with Matplotlib

Topics:

- visual encoding principles;
- line, bar, histogram, scatter, and box plots;
- appropriate chart selection;
- figure sizing and axes;
- labels, titles, legends, and annotations;
- multiple series;
- accessibility considerations;
- misleading scales and visual distortion;
- export for reports and presentations.

### Unit 4 — Descriptive Statistics

Topics:

- population and sample;
- mean, median, mode;
- range, variance, and standard deviation;
- quartiles, percentiles, and IQR;
- skewness and distribution shape;
- robust summaries;
- interpretation in practical contexts.

### Unit 5 — Grouping, Aggregation, and Reshaping

Topics:

- `groupby`;
- single and multiple aggregations;
- named aggregation;
- pivot tables;
- crosstabs;
- wide and long data;
- `melt`;
- multi-index summaries;
- grouped interpretation.

### Unit 6 — Correlation and Association

Topics:

- covariance;
- Pearson correlation;
- Spearman rank correlation;
- monotonic and nonlinear relationships;
- correlation matrices;
- confounding;
- spurious correlation;
- association for categorical variables;
- correlation versus causation.

### Unit 7 — Statistical Hypothesis Testing

Topics:

- populations and samples;
- sampling variability;
- confidence intervals;
- null and alternative hypotheses;
- p-values;
- Type I and Type II errors;
- independent and paired t-tests;
- chi-square tests;
- effect size;
- statistical versus practical significance;
- assumptions and limitations.

### Unit 8 — Applied Election Analysis

Topics:

- historical data inspection;
- category and time-based summaries;
- comparative visualization;
- interpretation within dataset limitations;
- avoiding unsupported political conclusions.

### Unit 9 — End-to-End Case Study

Workflow:

1. define analytical questions;
2. inspect and clean data;
3. document assumptions;
4. perform EDA;
5. select suitable visualizations;
6. compute grouped and statistical summaries;
7. investigate unusual observations;
8. produce findings and limitations;
9. export a concise analytical report.

## Teaching Method

Each notebook should contain:

- title and lesson context;
- learning objectives;
- prerequisites;
- estimated duration;
- required libraries;
- conceptual explanation;
- executable examples;
- interpretation after major outputs;
- common mistakes;
- best practices;
- guided exercises;
- a mini challenge;
- key conclusions;
- references;
- the recommended next lesson.

Not every notebook needs the same length. Notebook depth should match topic complexity and avoid unnecessary repetition.

## Assessment Approach

Public materials may contain guided exercises and mini challenges. Formal assessment materials should be maintained privately.

Recommended private assessment components include:

- short conceptual checks;
- practical coding tasks;
- interpretation questions;
- a final applied analysis;
- instructor rubrics;
- answer keys.

## Technical Environment

Core packages:

```bash
pip install numpy pandas matplotlib jupyterlab
```

Later statistical units may also require:

```bash
pip install scipy statsmodels
```

Notebook-specific dependencies should be documented at the beginning of each notebook.

## Quality Standards

Every published notebook should:

- run from top to bottom without manual repair;
- avoid hidden local file dependencies;
- use reproducible random seeds where applicable;
- explain the meaning of outputs;
- distinguish observation from inference;
- state assumptions and limitations;
- avoid unnecessary package dependencies;
- preserve raw data when demonstrating cleaning;
- use clear variable names and readable code;
- include no private student data, answer keys, or confidential assessment material.
