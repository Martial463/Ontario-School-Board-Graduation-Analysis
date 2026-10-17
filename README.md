 Ontario School Board Graduation Outcome Analysis
 Project Overview
This project examines whether selected secondary-school progress indicators can
help distinguish Ontario school boards whose five-year graduation rates fall
below the provincial benchmark.
The analysis uses three main predictors:
- Grade 10 OSSLT results
- Grade 10 credit accumulation
- Grade 11 credit accumulation
The outcome is whether a school board's five-year graduation rate is below the
provincial benchmark of 89.5%.
Research Questions
1. How much do five-year graduation rates vary across Ontario school boards,
   and how many boards fall below the provincial benchmark?
2. What relationships exist between Grade 10 OSSLT results, Grade 10 credit
   accumulation, Grade 11 credit accumulation, and five-year graduation rates?
3. How effectively can these secondary-school progress indicators distinguish
   school boards below the provincial five-year graduation benchmark?
Dataset
Source: Ontario Ministry of Education, School Board Achievements and Progress.
The original dataset contains Ontario school-board-level achievement and progress
indicators. After data cleaning and removal of incomplete records, the analytical
dataset contains 70 school boards.
Methodology
The project follows these stages:
1. Data validation and cleaning
2. Missing-value and outlier assessment
3. Univariate and bivariate exploratory analysis
4. Feature preparation
5. Logistic regression and shallow decision-tree modelling
6. Stratified five-fold cross-validation
7. Evaluation using accuracy, precision, recall, F1-score and confusion matrices
8. Comparison with a majority-class baseline
Repository Structure
— original public dataset
— cleaned analytical dataset
— preparation, EDA and modelling notebooks
— generated EDA reports
— project diagrams and visualizations
Exploratory Data Analysis
- notebooks/02_exploratory_data_analysis.ipynb
- reports/EDA_Report.pdf
- reports/EDA_Report.html
Ethics and Privacy
The dataset contains public, aggregated school board level information and no
personally identifiable student information. Results are interpreted as
board level associations rather than individual level or causal effects.
