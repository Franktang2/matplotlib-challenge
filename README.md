# Matplotlib Challenge


## Background

Two csv files were used:

1) The first file included columns for mouse id, timepoint, tumor volume, and metastatic sites. 

2) The second file included metadata information about the mice that participated in this study, such as mouse id, drug regimen, sex, age, and weight.

The two files were merged into a data frame using mouse id. The combined data frame along with the pandas and matplotlib libraries were used to create graphs and draw conclusions.


## Jupyter Notebook

**Summary Statistics**

The summary statistics (in tabular format) consist of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

**Bar Plots**

The bar plots show the number of data points for each treatment regimen. One plot is built using the pandas library and the other is built using the matplotlib library. Besides that difference, they are exactly the same plot.

**Pie Plots**

The pie plots chart the distribution of female versus male mice in the study. One plot is built using the pandas library and the other is built using the matplotlib library. Besides that difference, they are exactly the same plot.

**Quartiles, Outliers, and Boxplots**

To generate the box plots, the final tumor volume of each mouse across four of the most promising treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin) was calculated. Then, the quartiles and IQR were calculated to help determine if there are any potential outliers across all four treatment regimens.

The box and whisker plot shows the final tumor volume for all four treatment regimens (on the same plot) and highlights potential outliers (represented as a blue dot on the plot).

**Line and Scatter Plots**

A line plot was generated to show the time point versus tumor volume for mouse s185. The mouse was treated with Capomulin.

A scatter plot was created to show average mouse weight versus the average tumor volume for the Capomulin treatment regimen.

Finally, the correlation coefficient and linear regression model between average mouse weight and average tumor volume for the Capomulin treatment were calculated. The linear regression model is plotted on top of the scatter plot.


## Technologies Used

-Python

-Pandas library

-Jupyter Notebook

-Matplotlib library
