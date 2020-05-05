

# **Variance**

Variance and standard deviation measure the dispersion of a
set of data points around its mean value.
There are different formulas for population and sample
variance & standard deviation. This is due to the fact that the
sample formulas are the unbiased estimators of the population
formulas  



![image-20200429163048155](C:\Users\gmalarski\AppData\Roaming\Typora\typora-user-images\image-20200429163048155.png)

**Which formula’s which?**
Sometimes it can be tricky deciding whether you should
divide by n for the variance, or whether you should divide by
n – 1. The golden rule to remember is that dividing by n gives
you the actual variance for the set of data that you
have.
If you have the data for the entire population, then dividing
by n gives you the actual variance of the population. You
need to use the formula for σ2 and divide by n.
If you have a sample of data from the population, then
chances are you’ll want to use this to estimate the variance of
the population. This means that you need to use the formula
for s2 and divide by n – 1  

Wariancja (w wielkim uproszczeniu, bez uwzględnienia obciążenia estymatora) jest to [odchylenie standardowe](https://www.naukowiec.org/wiedza/statystyka/odchylenie-standardowe_703.html) podniesione do kwadratu. Jednakże w procesie obliczeń to wariancja jest pierwsza. Najpierw obliczamy wariancję, a dopiero wtedy odchylenie  standardowe, wyciągając pierwiastek z wartości wariancji.

- informuje nas czy sa male czy duze roznice pmiedzy srednia a poszczegolnymi wynikami
- czy wyniki sa bardziej skoncentrowane wokol sredniej
- If the number in the sample is small, there’s likely to be a bigger difference between the sample and
  population variances than if the size of the sample is large.  



# **STANDARD DEVIATION**

We’ve seen that the standard deviation is a way of saying how far
typical values are from the mean. The smaller the standard deviation,
the closer values are to the mean. The smallest value the standard
deviation can take is 0.
Like the mean, the standard deviation has a special symbol, σ. This is
the Greek character lowercase Sigma. (We saw uppercase Sigma, Σ, in
Chapter 2 to represent summation.)
To find σ, start off by calculating the variance, and then
take the square root  

![image-20200429165347084](C:\Users\gmalarski\AppData\Roaming\Typora\typora-user-images\image-20200429165347084.png)

![image-20200429165437712](C:\Users\gmalarski\AppData\Roaming\Typora\typora-user-images\image-20200429165437712.png)



- The standard deviation is the square root of the variance, which means that the variance is the square of the standard deviation. To find the variance from the standard deviation, square the value of the standard deviation  
- The standard deviation is0 if all of the values are the same. In other words, if each value is a distance of 0 away from the mean, the standard deviation wil be 0
- The most common measure at variability (zmiennosc) for a singe data set

#  **Variance vs Stdev**

The SD is usually more useful to describe the variability of the data  while the variance is usually much more useful mathematically.  For  example, the sum of uncorrelated distributions (random variables) also  has a variance that is the sum of the variances of those distributions.  This wouldn't be true of the SD.  On the other hand, the SD has the  convenience of being expressed in units of the original variable.

#  What Is the Coefficient of Variation (CV)?  

The coefficient of variation (CV) is a statistical measure of the  dispersion of data points in a data series around the mean. The  coefficient of variation represents the ratio of the standard deviation  to the mean, and it is a useful statistic for comparing the degree of  variation from one data series to another, even if the means are  drastically different from one another.

The coefficient of variation shows the extent of [variability](https://www.investopedia.com/terms/v/variability.asp) of data in a sample in relation to the mean of the population. In  finance, the coefficient of variation allows investors to determine how  much volatility, or risk, is assumed in comparison to the amount of  return expected from investments. Ideally, the coefficient of variation  formula should result in a lower ratio of the [standard deviation](https://www.investopedia.com/terms/s/standarddeviation.asp) to mean return, meaning the better risk-return trade-off. Note that if  the expected return in the denominator is negative or zero, the  coefficient of variation could be misleading

The coefficient of variation is helpful when using the risk/reward ratio to select investments. For example, an investor who is risk-averse may  want to consider assets with a historically low degree of [volatility](https://www.investopedia.com/terms/v/volatility.asp)(zmiennosc, nieprzewidywalnosc) and a high degree of return, in relation to the overall market or its  industry. Conversely, risk-seeking investors may look to invest in  assets with a historically high degree of volatility.

![image-20200429171030951](C:\Users\gmalarski\AppData\Roaming\Typora\typora-user-images\image-20200429171030951.png)

