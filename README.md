# Pharmaceutical Analysis

The following code includes information from a study of mice. There is data for 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

The following code will generate all of the tables and figures needed for the technical report of the study as well as a top-level summary of the study results.

Data from several files were combined and then cleaned to remove duplicates.

## Summary Statistics

-  Summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen were conducted first with groupby and then with the aggregate method. 

<img src="https://github.com/kflores56/matplotlib-challenge/blob/main/Pymaceuticals/Images/1.png" width="700"/>

## Bar and Pie Charts

- Two bar charts were created to show the total number of measurements taken for each treatment regimen throughout the course of the study using Panda's DataFrame.plot() for the first map and  Matplotlib's pyplot for the second. 

<img src="https://github.com/kflores56/matplotlib-challenge/blob/main/Pymaceuticals/Images/3.png" width="400"/>

- Two pie charts were created to show the distribution of female or male mice in the study using Pandas's DataFrame.plot() for the first map and Matplotlib's pyplot for the second.

<img src="https://github.com/kflores56/matplotlib-challenge/blob/main/Pymaceuticals/Images/4.png" width="200"/>

## Final Tumor Volume Analysis

- For this analysis, the final tumor volume was calculated for each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 

- The quartiles and interquartile range were then calculated across all four treatment regimens.

<img src="https://github.com/kflores56/matplotlib-challenge/blob/main/Pymaceuticals/Images/5.png" width="400"/>

- This information was visualized using Matplotlib to generate a box and whisker plot of the final tumor volume for each of the four treatment regimens.

<img src="https://github.com/kflores56/matplotlib-challenge/blob/main/Pymaceuticals/Images/6.png" width="400"/>

## Sample of Capomulin Data

- This analysis selected a sample mouse, i557, that was treated with Capomulin. Information about this mouse was used to generate a line plot of tumor volume over time.

<img src="https://github.com/kflores56/matplotlib-challenge/blob/main/Pymaceuticals/Images/7.png" width="400"/>

## Full Analysis of Capomulin

- The average tumor volume was calculated for mice that received the Capomulin treatment regimen. This was compared to the mice's weight using a scatter plot. 

<img src="https://github.com/kflores56/matplotlib-challenge/blob/main/Pymaceuticals/Images/8.png" width="400"/>

- The correlation coefficient was calculated for these two variables as well as the linear regression model. 

- The scatter plot and linear regression model were then visualized on the same graph. 


<img src="https://github.com/kflores56/matplotlib-challenge/blob/main/Pymaceuticals/Images/9.png"/>

## Final Insights

When looking across all of the aggregated data, calculations, and comparisons the following is noted: 
- When looking across all drug regimens Capomulin and Ramicane had the smallest tumor sizes when central tendencies were calculated.
- These two drug regimens also had the most overall measurements and the lowest standard deviations which means all data points were closely clustered around the mean.
- It is also interesting to note, that while the data for these two drug regimens were closely clustered they also contained outliers.
- Overall, we can note, the larger the size of the tumor the higher the weight of the mouse.
