# Examining Tumor Growth, Drug Regimen Study Using Python, Pandas, Matplotlib

![Laboratory](Images/Laboratory.jpg)

## Object

I am using Python Matplotlib on a (fictional) data analysis project to find potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In the "study," 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance one drug called Capomulin to the other treatment regimens. The object here is to generate all of the tables and figures needed for the technical report of the study, as well as provide a summary of the results. 

## Charts (Pandas, Matplotlib)

In order to illustrate the findings of the the research study, I created a: 
* Summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
* Bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of mice per time point for each treatment regimen throughout the course of the study.
* Pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.
* Box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
* Line plot of time point versus tumor volume for a single mouse treated with Capomulin.
* Scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
* Linear regression model on top of the previous scatter plot.
