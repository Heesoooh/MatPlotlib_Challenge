# MatPlotlib_Challenge

## Purpose of Project
In this homework assignment, you’ll apply what you've learned about Matplotlib and to a real-world situation and dataset.
This assignment is applying concepts that I learned in pandas units and matplotlib to tell better story with graph. 
### Pymaceuticals
In this challenge, you are tasked to use Matplotlib and Jupyter Notebook to create a report that includes the following data with a written description of at least three observable trends based on data. The followings need to be created:
1. Create Bar Charts and a Pie Charts
* Generate two bar plots. Both plots should be identical and show the total number of timepoints for all mice tested for each drug regimen throughout the course of the study:
    * Create the first bar plot by using Pandas's DataFrame.plot() method
    * Create the second bar plot by using Matplotlib's pyplot methods
* Generate two pie plots. Both plots should be identical and show the distribution of female or male mice in the study:
    * Create the first pie plot by using both Pandas's DataFrame.plot()
    * Create the second pie plot by using Matplotlib's pyplot methods

2. Calculate Quartiles, Find Outliers, and Create a Box Plot
* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculate the quartiles and IQR and determine if there are any potential outliers across all four treatment regimens. Follow these substeps:
    * Create a grouped DataFrame that shows the last (greatest) time point for each mouse. Merge this grouped DataFrame with the original cleaned DataFrame
    * Create a list that holds the treatment names, as well as a second, empty list to hold the tumor volume data
    * Loop through each drug in the treatment list, locating the rows in the merged DataFrame that correspond to each treatment. Append the resulting final tumor volumes for each drug to the empty list
    * Determine outliers by using the upper and lower bounds, and then print the results
* Using Matplotlib, generate a box plot of the final tumor volume for all four treatment regimens. Highlight any potential outliers in the plot by changing their color and style
3. Create a Line Plot and a Scatter Plot
* Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse
* Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen
4. Calculate Correlation and Regression
* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment
* Plot the linear regression model on top of the previous scatter plot

The purpose of this challenge is to graph, chart and plot all the datas for the result data to have better story telling and easier for others to understand and compare data. In addition, the purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens

## Analysis 
By analyzing the report, followings found:
1.We need to clean data for any duplicate mice. When we took out duplicate Mouse ID, the total number of mice was 248. According to Pie plot, we found out that there are 51.0% male and 49.0% female mice.

2.The mouse weight and average tumor volume have the very strong positive relationship accroding to corrleation and regression plot. The correlation between mouse weight and the average tumor volume is 0.84.

3.Compare to other drugs tested, Capomulin and Ramicane showed the higest result on reducing the tumor size. On summary table, both shows low mean, ,median, variance, standard deviation and SEM.
## Recommandation 
From this challenge and analysis, I can recommend that Capomulin and Ramicane worked best to reduce the tumor volume. Correlation and Regression session proved for the Capomulin, so it will be nice do correlation and regression on Ramicane to actually prove it.   