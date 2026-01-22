# Principles of Data Analytics

## Overview

This repository contains a Jupyter Notebook of tasks completed as part of an assignment for the *Principles of Data Analytics* module, which is a component of the Higher Diploma in Science in Computing in Data Analytics at ATU. 

The analysis of the Iris dataset by R.A. Fisher serves to demonstrate the skills developed throughout the module.

---

## Problems and Tasks

### Task 1: Loading the Dataset
- Import the Iris dataset from the `sklearn.datasets` module.
- Explain, in your own words, what the `load_iris()` function returns.

### Task 2: Explore the Data Structure
- Print and explain the shape of the dataset.
- Print the first and last 5 rows of the data.
- Print the feature names and the target classes.

### Task 3: Summarize the Data
For each feature in the dataset, calculate and display:
- Mean
- Minimum
- Maximum
- Standard deviation
- Median

### Task 4: Visualize Features
- Plot histograms for each feature using `matplotlib`.
- Add appropriate titles and axis labels.

### Task 5: Scatter Plot
- Choose any two features from the dataset and create a scatter plot.
- Color-code the scatter plot points to represent the three different target classes.

### Task 6: Analyze Relationship
- Use `numpy.polyfit` to add a regression line to the scatter plot from Task 5.

### Task 7: Analyze Class Distributions
- Create boxplots of the petal lengths for each of the three classes.

### Task 8: Compute Correlations
- Calculate the correlation coefficients between the features.
- Display the results as a heatmap using `matplotlib`.

### Task 9: Fit a Simple Linear Regression
- For the two features chosen in Task 5:
  - Calculate the coefficient of determination (R² value).
  - Re-create the plot from Task 6 and annotate it with the R² value.

### Task 10: Pairplot
- Use Seaborn to create a pairplot of the dataset.
- Explain, in your own words, what the pairplot depicts.

---

## Setup and Installation

To run the notebook, you can set up the environment using the provided requirements files.

### Using `conda`:
Create a Conda environment with the necessary dependencies:
```bash
conda create --name <environment-name> --file requirements.txt
```

### Using `pip`:
Install the required packages directly in your current environment:
```bash
pip install -r requirements.txt
```

### Run in GitHub CodeSpaces:
Alternatively, you can run the notebook directly in GitHub CodeSpaces:
1. Sign up for a free GitHub account.
2. Navigate to the repository page in your browser.
3. Click the green **Code** button.
4. Select the **Codespaces** tab and click **Create New Codespace on main**.
5. Open `tasks.ipynb` from the left-side explorer (reload if it initially opens as plain code).
6. Click the play button near the top of the notebook to execute code cells.
7. Install all suggested extensions and select the appropriate Python environment as the interpreter.

---

## Technologies Used

The following technologies and tools were used in this project:
- **Python**: Core programming language.
- **Git**: Version control system.
- **GitHub**: Repository hosting and management.
- **Codespaces**: Virtual IDE for running Jupyter Notebooks in the cloud.
- **Jupyter Notebook**: Interactive environment for developing and sharing data analysis.
- **Matplotlib**: Visualization library for creating histograms, scatter plots, and heatmaps.
- **Seaborn**: Data visualization library, used for generating pairplots.

---

## Contact

For any issues or questions regarding this project, please feel free to contact **Céaman Collins**, the sole contributor. You can reach out via GitHub.
