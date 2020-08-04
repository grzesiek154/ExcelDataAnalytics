# Variability

- Dispersion
- Spread in Data 
- How Spread Out is Data
- Are the data points clustered around the Mean?
- Does the Mean Fairly Represent the Data Points

## Range

- Max - Min
- Simple to calculate. Sensitive to extreme values

## Interquartile Range

- Quartile 3 - Quartile 1
- The range for the middle 50% of the data. It overcomes the sensitivity to extreme values

## Deviation

- How far one datum is from the mean. "How far above or below the mean is the particular value?"
- "Deviation about the mean"
- For any data set, the sum of the deviations is always zero!!!! This is why mathematically, we either square (Variance or Standard Deviation) or take the absolute value (Mean Absolute Value)

## Variance

- A Numerical Measure that says how much variability there is in the data points
- Variance uses all the data points, not just some like Range and Interquartile Range
- Variance has squared units, which makes interpreting it difficult. Standard Deviation undoes the squared units and is thus easier to interpret and is more commonly used
- Use VAR.P function for population data and VAR.S for sample data.

## Standard Deviation = SD

- Standard Deviation uses all the data points, not just some like Range and Interquartile Range
- Standard Deviation does not have squared units (like Variance) and is thus easier to interpret; the standard deviation has the same units as the data!!
- Population SD = "little sigma" = s ; Sample SD = s
- The sample standard deviation is a point estimator of the population standard deviation

### Interpretation of Standard Deviation:

- A Numerical Measure that says how much variability there is in the data points
- Standard Deviation Is Like An Average Of The Deviations
- Standard Deviation tells us how fairly the mean represents its data points
- Standard Deviation tells us how clustered the data points are around the mean
- For financial assets standard deviation is a measure of risk or fluctuation in asset value

## Coefficient of Variation

- Coefficient of Variation converts the SD to SD per unit of Mean
- Formula = SD/Mean
- For every one unit of mean, what is the SD?
- What percentage is SD in relation to the Mean?
- Use Coefficient Of Variation to compare:

1) Data in different units.

2) Data in the same units, but the means are far apart.

# Distribution, Relative Location, Outliers

## Shape of Distribution

### Histograms

- Histograms show the shape of the distribution visually.
- A few short column heights to the left means skew negative of left
- A few tall column heights to the right means skew positive or right
- Bell shape or Symmetrical Shape indicates no skew

### Skew

- Skew measures the shape of the distribution
- Use SKEW function

#### Left or Negative Skew

- A few small values pull the Mean down away from Median
- Mean usually less than Median

#### Right or Positive Skew

- A few big values pull the Mean up away from Median
- Mean usually greater than Median
- Bell Shape or Symmetrical Shape - No Skew
- Mean and Median equal

## Relative Location

### z Score = Standardized Value

- Z score measures the relative location of a particular x in the data set (as compared to the mean), in units of standard deviation.

- Z Score tells you "How Many Standard Deviations The Particular Value Is Away From The Mean". 1? -1? 1.5? 0?

  zi <  0, value below mean
  zi >  0, value above mean
  zi = 0, value is equal to mean

- z = (Particular Value - Mean)/StandardDeviation = zi = (xi-Xbar)/s

- Observations in 2 different data sets that have the same z-score are said to have the same relative location or the same number of standard deviations away from the mean.

- Use STANDARDIZE function

## Proportion of data values that lie between +/- a given number of standard deviations

### Chebyshev's Theorem

- Allows us to make a statement about the proportion of data values that must be within a specified number of standard deviations of the mean.
- Rule:
  At least (1 - 1/z^2) of the values in any data set will be within z standard deviations of the mean, where z is
   any value greater than 1.
- Real power of this Theorem:
  Applies to any data set regardless of the shape of the distribution of the data!
- At least 0.75, or 75.00%, of the data values must be within z = 2 standard deviations of the mean
- At least 0.89, or 89.00%, of the data values must be within z = 3 standard deviations of the mean
- At least 0.94, or 94.00%, of the data values must be within z = 4 standard deviations of the mean

### Empirical Rule

- When data has a Symmetric Distribution or Normal Distribution or Bell Shaped Distribution, the Empirical Rule Can be sued to determine the percentage of data values that must be within a specified number of standard deviations of the mean
- Approximately 68% of the data values will be within 1 Standard Deviation of the Mean
- Approximately 95% of the data values will be within 2 Standard Deviations of the Mean
- Approximately 99% of the data values (almost all the data) will be within 3 Standard Deviations of Mean

## Detecting Outliers

### Outlier

- An outlier is an unusually small or unusually large value in a data set.

### '+/- 3 Z Scores Outlier Rule

- A data value with a z-score less than -3 or greater than +3 might be considered an outlier.
-   It might be:
  1) an incorrectly recorded data value
  2) a data value that was incorrectly included in the data set
  3) a correctly recorded data value that belongs in the data set
- ABS is absolute Value function in Excel (Distance away from zero)

### '5 Number Summary

5 Number Summary Provides information like:

- Minimum Value 
- Maximum Value
- Median
- Range, Max -Min
- Quartiles
- Interquartile Range = Quart3 - Quart1 = range for middle 50%
- Basis for building Box Plot

### 'Box Plots and Outliers Rule of 1.5

Use 5 Number Summary and create hand draw chart Box Plot:

1. Horizontal Axis lists range of numbers from smallest to biggest
2. Box or rectangle is drawn with box ends at Quartile 1 and Quartile 2
3. Vertical line drawn at Quartile 2 (Median)
4. Vertical lines for Lower and Upper Limits that indicate that anything past is an Outlier.
   Lower Limit = Quartile 1 - 1.5*Interquartile Range, or 0.
   Upper Limit = Quartile 3 + 1.5*Interquartile Range
   **Although for this class we will use 1.5, other multiples can be used (see note on "5 Number & Box Blot" Worksheet
5.  "Whiskers", lines, are drawn from Q1 to Min and Q3 to Max
6.  Outliers can be drawn as an "X", "dot" or "small box"

![image-20200801132802065](C:\Users\grzeg\AppData\Roaming\Typora\typora-user-images\image-20200801132802065.png)





# Measures of Association or Linear Relationship Between 2 Variables

## Covariance

- Covariance measures the strength of the linear relationship between 2 variables. Positive values indicate a positive relationship; negative, a negative relationship
- Sample Covariance = sxy = (∑(xi - Xbar)*(yi - Ybar))/(n-1)
- Use COVARIANCE.S function
- Population Covariance = sxy = (∑(xi - µx)*(yi - µy))/N
- Use COVARIANCE.P function

### Understanding how Covariance works:

- Plot a Mean Line for X and a Mean Line for Y to divide chart into 4 quadrants
- When preponderance(przewaga liczebna, przewaga, wyższość) of the "X-Deviations Times Y-Deviations" are positive (X-Y markers are quadrant 1 and 3), the line will show a positive liner association or relationship: "As X Increases, Y Increase"
- When preponderance(przewaga liczebna, przewaga, wyższość)  of the "X-Deviations Times Y-Deviations" are negative (X-Y markers are quadrant 2 and 4), the line will show a negative liner association or relationship: "As X Increases, Y decrease"
- When preponderance(przewaga liczebna, przewaga, wyższość)  of the "X-Deviations Times Y-Deviations" are neither positive or negative (X-Y markers in all quadrants), the line will show no liner association or relationship
- Covariance measures the strength of the linear relationship between 2 variables, but has a problem with units.
  Because the value of covariance depends on units, we may get larger or smaller covariances simply because we change the units from inches to feet or feet to inches.
  To overcome this problem with units, we can divide the covariance by the product of the standard deviation to the x and y values, sx * sy , to get a relative measure of strength of association or relationship between 2 variables or a measure of strength per unit of standard deviation, sx * sy . This measure is called Correlation Coefficient

## Correlation Coefficient = Pearson Product Moment Correlation Coefficient

- Correlation Coefficient measure the strength and direction of linear association or relationship.
- Values range from -1, perfect negative linear relationship (all X-Y markers on  regression line) to +1, perfect positive linear relationship  (all X-Y markers on  regression line) 
- Values close to +1 show strong positive linear association/relationship
  Values close to -1 show strong negative linear association/relationship
  The closer to zero the weaker the relationship
  The closer the X-Y markers are to the regression line, the stronger the relationship
  The more the X-Y markers deviate from the regression line, the weaker the relationship
- Note: Because the Correlation Coefficient measure the strength and direction of a LINEAR relationship, not nonlinear relationships. If you get a correlation measure near zero, it may be true that there is a very weak linear relationship, but that does not say that there is not some other sort of non-linear relationship.
- Sample Correlation Coefficient = rxy = sxy /(sx * sy)
- Use PEARSON or CORREL functions
- Population Correlation Coefficient rxy = sxy /(sx * sy) , r is pronounced "Row"
- Use PEARSON or CORREL functions
- Sample Correlation Coefficient, rxy , is a point estimator of the Population Correlation Coefficient, rxy
- Correlation is not causation. (przyczynowosc)