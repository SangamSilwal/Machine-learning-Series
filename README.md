# Summary
## [ Outlier Detection | Z-Score Method ](https://github.com/SangamSilwal/Machine-learning-Series/blob/main/class_9_A.ipynb)
Here I learned about Z-Score Method for removing outlier in the dataset.There are 2 approach to remove outlier :-
1. Trimming: We just remove the row conatinaing the outlier
2. Clapping: We replaced the lower outlier by lower maximum data and upper outlier by upper maximum data
The formula for calculating lower and upper data is --> mean - 3SD \ mean + 3SD

## [Outlier Detection | IQR Method](https://github.com/SangamSilwal/Machine-learning-Series/blob/main/Day_9_B.ipynb)
Here I learned about IQR method to handle outliers in the dataset. Basically this IQR method is used when the dataset is skewed.
IQR or Inter Quartile Range is calculated as IQR = Q3 - Q1
After getting the IQR we can find the lower limit and upper limit as : 
- Upperlimit = 75Quantile + 1.5*IQR
- LowerLimit = 25Quantile - 1.5IQR
After find the Upperlimit and the lowerLimit we can simply use two approach 1> Trimming and 2> Clapping.
