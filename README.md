# Matplotlib
## Overview
In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.  Data cleaned by deleting duplicate data.

## The code does the following: 
* Generates a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
* Generates a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of measurements taken for each treatment regimen throughout the course of the study.
* Generates a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.
* Calculates the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
* Generates a box and whisker plot of the final tumor volume for all four treatment regimens using Matplotlib and highlights any potential outliers in the plot by changing their color and style.
* Generates a line plot of tumor volume vs. time point for a selected mouse that was treated with Capomulin. 
* Generates a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
* Calculates the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. 