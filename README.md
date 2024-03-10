# Wine-Acid-Analysis
Python(Jupiter Notebook)

This Jupyter notebook is part of my  learning experience in the study of central tendency

I have work with a simple data set that contains details of wine quality

In this exercise, I have performed  the following tasks:

1 - Load and study the data

2 - View the distributions of the various features in the data set and calculate their central tendencies

3 - Create a new Pandas Series that contains the details of the representative factor for quality
 
** Load and study the data**
Load the data and study its features such as:

-fixed acidity
-volatile acidity
-citric acid etc.

There are **4898** rows and **12** columns in the data.Each row contains the details of the types of acids present in white-wine and the quality

The features in the data set are:

Different acids and their Quality
View the distributions of the various features in the data set and calculate their central tendencies
By looking at the distributions of the various features in the data set calculate appropriate measures of central tendency for these features

By observe that the histogram is normally distributed.
The maximum count of values for fixed acidity lies in between 6 to 8.

Let's see the measures of central tendency in working!
Mean
Median
Mode
-We can see that mean and median are clear representative of the data.
-Mean and median are very close to each other.
-We can choose either of the parameters say mean as the measure of central tendency.
-We observe that this histogram is not well distributed, it is skewed a little towards the right.

As we have seen skewness, therefore we can check the distribution using distplot function.
The mean, median and mode are all measures of the center of a set of data. The skewness of the data can be determined by how these quantities are related to one another.
-If Skewness (S) = 0, then the distribution is normally distributed.
-If Skewness (S) > 0, then the distribution is positively skewed.
-If Skewness (S) < 0, then the distribution is negatively skewed.

Then second plot shows the normal distribution.

The normal distribution is described by the mean and the standard deviation.

The normal distribution is often referred to as a 'bell curve' because of it's shape:

-The median and mean are equal
-It has only one mode
-It is symmetric, meaning it decreases the same amount on the left and the right of the centre

We can calculate skewness too using skew() function in python.
We can clearly see that the skewness value is greater than 1, hence it is positively skewed.
The mean and the median are close to each other and the difference between them is very small.
We can safely choose the mean as the measure of the central tendency here.
We saw the distributions of the various features in the data set using appropriate plots
We calculated central tendency measures like mean, median and mode for the various features
The mean and the median for all the above features were similar, so we can choose the mean in these cases
The mode of the "Quality" feature can be chosen as a representative value

The representative acid for the quality is as follows:
The mean value of the fixed acidity would be 6.854
The mean value of the volatile acidity would be 0.2782
The mean value of citric acid would be 0.3341
The quality would be 6

**Final Conclusions**
-From the given data, we can use simple visualisations to get a sense of how data are distributed.
-We can use various measures of central tendency such as mean, median and mode to represent a group of observations.
-The type of central tendency measure to use depends on the type and the distribution of the data


