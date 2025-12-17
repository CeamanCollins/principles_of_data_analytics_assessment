# Princicples of Data Analytics

This is a [jupyter notebook](tasks.ipynb) of tasks completed for an assignment for the Principles of Data Analytics module as part of the Higher Diploma in Science in Computing in Data Analytics.

This analysis of the iris dataset by R.A. Fisher serves to demonstrate learning points over the course of the module.

## Problems

### Task 1: Loading The Dataset
> Import the Iris data set from the sklearn.datasets module.
> Explain, in your own words, what the load_iris() function returns.

### Task 2: Explore the Data Structure
> Print and explain the shape of the data set.
> Print the first and last 5 rows of the data.
> Print the feature names and the target classes.

### Task 3: Summarise the Data
> For each feature in the dataset, calculate and display:
> * mean
> * minimum
> * maximum
> * standard deviation
> * median

### Task 4: Visualize Features
> Plot histograms for each feature using matplotlib.
> Add appropriate titles and axis labels.

### Task 5: Scatter Plot
> Choose any two features from the data set and create a scatter plot of them.
> Color-code the three different classes of the scatter plot points.

### Task 6: Analyze Relationship
> Use numpy.polyfit to add a regression line to the scatter plot from Task 5.

### Task 7: Analyze Class Distributions
> Create box-plots of the petal lengths for each of the three classes.

### Task 8: Compute Correlations
> Calculate the correlation coefficients between the features.
> Display the results as a heatmap using matplotlib.

### Task 9: Fit a Simple Linear Regression
> For your two features in Task 5, calculate the coefficient of determination $R^2$.
> Re-create the plot from Task 6 and annotate it with the $R^2$ value.

### Task 10
> Use seaborn to create a pairplot of the data set.
> Explain, in your own words, what the pairplot depicts.

## Setup

If you choose to run this in your own local environment, there is a requirements file that contains the necessary packages needed to execute all cells in the notebook. This can be imported as an environment using conda:

> $ conda create --name <env> --file requirements_conda.txt

And using pip you can import to your current working environment using:

> $ pip install -r requirements_pip.txt

Alternatively you can browse the notebook directly in GitHub or use GitHub codespaces to run the code contained in the notebook:

1. Sign up for a free GitHub account.
2. Go to the repository page in your browser.
3. Click the green Code button.
4. Click the Codespaces tab.
5. Click Create New Codespace on main.
6. Click tasks.ipynb in the left browser. You may need to click off and back on if the page is loaded as code instead of as a notebook.
7. Click the play button next to the first code box and install the suggested extensions.
8. Select the installed python environment as the python interpreter.

## Technologies

- Python
- Git
- Github
- Codespaces
- Jupyter

## Contact

If you are having trouble with any part of this project please contact [Céaman Collins](mailto:ceaman.collins@gmail.com?subject=[GitHub]%20PoDA%20Tasks) the sole contributor to this project. 
