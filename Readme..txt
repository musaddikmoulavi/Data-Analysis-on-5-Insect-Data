README
Overview
This project performs statistical analysis and exploratory data analysis on a dataset containing species richness and dominant land class. The analysis aims to explore the relationships between species diversity and land class, identify trends and patterns, and investigate potential reasons for variations in biodiversity indexes over time.

Key Objectives
Clarify the links between the diversity of species and land class.
Identify trends and patterns in the data.
Investigate possible reasons for variations in biodiversity indexes over time.
Methodology
Species Listing and Allocation:

The script starts by generating lists of all species.
It then allocates data for five selected taxonomic groups: Butterflies, Carabids, Hoverflies, Ladybirds, Grasshoppers, and Crickets. These groups are collectively referred to as BD5.
Descriptive Statistics:

For each taxonomic group in BD5, the script computes the following statistics:
Minimum
Maximum
First Quartile (Q1)
Second Quartile (Q2)
Mean
Median
Winsorized Mean
Correlation Matrix:

The script creates a correlation matrix for all pairs of variables within BD5 and presents it in a tabular format.
Visualization:

A boxplot is generated for the 'Hoverflies' variable to visualize its distribution.
Hypothesis Testing:

The script performs two hypothesis tests:
T-Test
KS-Test (Kolmogorov-Smirnov Test)
It generates p-values as outputs to assess statistical significance.
Contingency Test:

A contingency test is performed between BD5_up and BD11_up.
The test calculates:
Odds Ratio
Sensitivity
Specificity
Youden’s Index
Regression Analysis:

The script executes both linear regression and multiple linear regression to model the relationships between species diversity and land class.
Key Functions
Species Listing and Allocation: Generates species lists and allocates data for BD5.
Descriptive Statistics Calculation: Computes various statistical measures for each taxonomic group.
Correlation Matrix: Creates and displays a correlation matrix.
Visualization: Generates boxplots for data visualization.
Hypothesis Testing: Conducts T-Test and KS-Test to analyze statistical significance.
Contingency Testing: Performs contingency tests and calculates relevant metrics.
Regression Analysis: Executes linear and multiple linear regression models.
Conclusion
This analysis provides insights into the biodiversity patterns and their relationship with land class. By understanding these relationships, the project aims to contribute to the field of ecological research and inform conservation efforts.
