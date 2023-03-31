# data_analysis_neuro

## Short description
Analysis of an OpenNeuro dataset in Python.

## What is this project about?
Within the scope of this project, I analyzed the following open source dataset:

Zareba, M.R., Fafrowicz, M., Marek, T., Beldzik, E., Oginska, H., & Domagalik, A. (2022). Structural (t1) images of 136 young healthy adults; study of effects of chronotype, sleep quality and daytime sleepiness on brain structure. OpenNeuro. [Dataset] doi:10.18112/openneuro.ds003826.v3.0.0

The dataset contains 136 participants and 10 variables. The data were collected to explore circadian rythmicity and more precisely, to research structural brain correlates of human chronotypes.

## What did the analyses entail?
- Read the dataset
- Explore the dataset and get a general overview, including a descriptive summary, data types, distributions
- Check for outliers and missing values
- Conduct descriptive analyses: descriptive statistics of dataset and subsets
- Conduct inferential analyses
- Compute correlations between all interval scaled variables
- Compute t-Test between EC and LC groups regarding LEFG
- Calculate regression model with LEFG as dependent variable and CHQAM as predictor

## How will the respective steps be implemented?
- Read the data, data wrangling with the pandas module and explore the dataset a bit with some built-in functions
- Data visualization with matplotlib, seaborn
- Data analyses and statistics with numpy, statsmodels and pingouin
