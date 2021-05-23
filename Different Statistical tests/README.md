# Data-Science
Data science and statistics concept

ref: https://ncss-wpengine.netdna-ssl.com/wp-content/themes/ncss/pdf/Procedures/NCSS/Normality_Tests.pdf 

## Normality Tests
Normality test actually test to verify the data follows gaussian distribution, as we always assume that for parameteric testing data is normally distributed(mean=0, std=1). 
But, it is always good to verify in advance.
Normailty test is one of the main prequisite to any statistical testing especially for parameteric test.
There are 2 ways to do that either mathematically or grahically. However, graphically has advantage of providing a better understanding of the data. <br>
Distribution chart like __Frequency distribution, box-plot, stem-and-leaf plot, P-P (probability-probability ) plot, and Q-Q(Quantile -Quantile )__ plot are used for normality.
Different Normality test is as follows:
1. Kolmogorov-smirnov(K-S)test
2. Shapiro-Wilk test
3. Anderson-Darling test
4. Cramer-von Mises test
5. D'Agostino's K-squared test
6. Anscombe-Glynn kurtosis test
7. D'Agostino-Pearson omnibus test
8. Jarque-Bera test 


ref:- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3693611/

 ## Correlation Test

Verifying the relation between two samples. Correlation is a bivariate analysis that measures the strength of association between two variables and the direction of the relationship. In terms of the strength of relationship, the value of the correlation coefficient varies between +1 and -1. A value of ± 1 indicates a perfect degree of association between the two variables. As the correlation coefficient value goes towards 0, the relationship between the two variables will be weaker. The direction of the relationship is indicated by the sign of the coefficient; a + sign indicates a positive relationship and a – sign indicates a negative relationship. Usually, in statistics, we measure four types of correlations:

ref: https://www.statisticssolutions.com/free-resources/directory-of-statistical-analyses/correlation-pearson-kendall-spearman/

- Pearson’s Correlation Coefficient
- Spearman’s Rank Correlation
- Kendall’s Rank Correlation
- Chi-Squared Test

## Stationary Tests
Test to verify that time series data is stationary or not. A stationary series data has the property of constant mean, variance and covariance over time.
Example: relationship between wages and house prices,exchange rates, profits and dividends, and consumption and GDP.

Test to check stationary:

- ADF Test(Augmented Dickey Fuller)
- KPSS Test(Kwiatkowski-Phillips-Schmidt-Shin)


## Parametric Statistical Hypothesis Tests


__Parametric__ : Assume specific distribution(Mean) <br>
__Non Parametric__: Do not assume specific distribution(Median) (Also known as distribution free test)

Paramteric Tests:
- 1 sample Student t test
- 2 sample t-test
- One way ANOVA test

Advantage Parameteric test: 
- Provide trustworthy results with distribution are skewed and non gaussian.
- Have greator statistical power.

Advantage of Non- Paramteric test:
- None Parameteric access median which can be sometime usefull in some study areas.
- Valid when our samples size is small and data is not normally distributed. 
- Can analyze Ordinal data, ranked data, and outliers


## Non Paramtric Statistical Hypothesis Tests

- Wilcoxon signed rank test
- Mann- Whitney test
- Kruskal- Wallis 
- Friedman test


