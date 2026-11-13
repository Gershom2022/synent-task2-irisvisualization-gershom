# Synent Task 2: Iris Data Visualization

**Author:** Gershom Mosora Nyamongo

**Program:** Synent Technologies - Data Science Internship (Task 2)

**Demo video:** https://youtu.be/HBe_aYndzTA

## Problem Statement
Visualize patterns in the Iris dataset to understand how the three flower species differ, using a bar chart, a histogram, a scatter plot and a comparison of features.

## Dataset
Iris dataset (Kaggle): 150 rows and 5 columns (sepal length, sepal width, petal length, petal width, species), with 50 flowers for each of three species: setosa, versicolor and virginica. There are no missing values.

## Approach
- Loaded and inspected the data and checked summary statistics
- Bar chart: average petal length by species
- Histogram: distribution of petal length
- Scatter plot: petal length against petal width, coloured by species
- Compared features with group averages, a correlation heatmap and a pair plot

## Results
- Setosa is clearly separate from the other two species, mainly because of its small petals.
- Petal length and petal width are the best features for telling species apart, and are strongly correlated (0.96).
- Versicolor and virginica overlap slightly.

## Tools
Python, pandas, matplotlib, seaborn, Jupyter Notebook
