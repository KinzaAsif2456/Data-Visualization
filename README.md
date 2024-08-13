# Data-Visualization
All  types of Data visualizations using matplotlib library and Seaborn

### Overview
This script demonstrates various data visualization techniques using a synthetic dataset created with NumPy and pandas. The visualizations include histograms, box plots, density plots, bar charts, pie charts, scatter plots, and heatmaps. It also introduces outliers to the dataset and shows how to use box plots to identify them.
The code is divided into two main sections: Univariate Analysis and Bivariate Analysis.

### Libraries Used
** - pandas:** For data manipulation and analysis.
** - numpy:**   For generating synthetic data.
** - matplotlib.pyplot:** For creating static, animated, and interactive visualizations in Python.
** - seaborn:** For making statistical plots with enhanced aesthetics.

### Dataset
A synthetic dataset is created with the following columns:
**- age:** Numerical data representing age (normally distributed with a mean of 35 and standard deviation of 10).
**- income:** Numerical data representing income (normally distributed with a mean of 50,000 and standard deviation of 15,000).
**- satisfaction:** Numerical data representing satisfaction level (uniformly distributed between 1 and 10).
**- gender:** Categorical data with two possible values ('Male', 'Female').
**- purchased:**  Categorical data with two possible values ('Yes', 'No').

### Code Structure
The code is organized into sections, each focusing on a specific aspect of data visualization. The sections are:
- Univariate Analysis
- Bivariate Analysis
- Outlier Detection
Each section contains comments explaining the purpose of the code and the visualization

### Univariate Analysis

Univariate analysis involves examining the distribution of a single variable. In this section, we explore different visualization techniques to understand the distribution of the 'age' variable.
**- Histogram:** A histogram is a graphical representation of the distribution of a variable. We create a histogram of the 'age' variable using Matplotlib's hist function.
**- Box Plot:** A box plot is a concise way to display the distribution of a variable. We create a box plot of the 'age' variable using Seaborn's boxplot function.
**- Density Plot:** A density plot is a smoothed version of the histogram. We create a density plot of the 'age' variable using Seaborn's kdeplot function.

### Bivariate Analysis

Bivariate analysis involves examining the relationship between two variables. In this section, we explore different visualization techniques to understand the relationships between the 'age', 'income', and 'satisfaction' variables.
**- Scatter Plot:** A scatter plot is a graphical representation of the relationship between two variables. We create a scatter plot of the 'age' and 'income' variables using Matplotlib's scatter function.
**- Box Plot for Categorical vs Numerical:** We create a box plot to visualize the distribution of 'income' by 'gender' using Seaborn's boxplot function.
**- Heatmap for Correlation:** A heatmap is a graphical representation of the correlation between multiple variables. We create a heatmap of the correlation matrix using Seaborn's heatmap function.

### Outlier Detection

Outliers are data points that are significantly different from the rest of the data. In this section, we introduce some outliers to the dataset and use box plots to detect them.
**-Box Plot for Outlier Detection:** We create box plots for the 'age' and 'income' variables to detect outliers using Seaborn's boxplot function.
