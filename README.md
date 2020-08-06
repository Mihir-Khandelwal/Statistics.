# Statistics.
## Discriptive Statistics.
- Mode: It is the number which occurs most frequently in the data series. It is robust and not affected by the couple of new values.
![](https://www.mathsisfun.com/data/images/mode.svg)
--------
- Mean: It is the average of the numbers in the data series. It is not robust.

![](https://www.mathsisfun.com/data/images/mean.svg)

--------
- Median: The absolute central value of the data series is called median.

![](https://www.mathsisfun.com/data/images/median.svg)

-----
- Outliers: Any value will fall really outside the range of the data is termed as a outlier.
  - Reasons for Outliers in the data.
1. Typos.
2. Measurement error.
3. Intentional error.
4. Legit outliers.
- Mean gets affected by Outliers while Mode not.
### Spread of Data.
- Spread of Data describes how similar or varied are the set of observations.

-----
1. Range: The difference between the smallest and largest values is called range. The bigger the range the more spread out is the data. It is not very robust metric to calculate spread of data. It takes the entire data into consideration.

![](https://www.mathsisfun.com/data/images/range.svg)

------
2. Inter Quartile Range(IQR): It is the difference between the third quartile and the first quartile. It is not affected by just a few outliers in the data. It takes 50% of the data into consideration.

![](https://sphweb.bumc.bu.edu/otlt/mph-modules/bs/bs704_summarizingdata/Interquartile-Odd.png)

------
3. Variance: It is the average squared deviations from the mean. The formula is given below.

![](https://www.surveygizmo.com/wp-content/uploads/2019/04/variance-formula-surveygizmo-blog.png)

-----
4. Standard Deviation: It is the square root of variance.

![](https://www.basic-mathematics.com/images/Standard-deviation-formula.jpg)

------
- Frequency Table: A table representing frequency or a count of a category.
------
- Probability: Number of changes a particular event will occur.
------
### Bernoulli Trials.
- An experiment which has exactly two outcomes. Probability distribution of the number of successes in 'n' Bernoulli Trials is called as Binomial Distriburtion.

![](https://www.wallstreetmojo.com/wp-content/uploads/2019/03/Binomial-Distribution-Formula1.jpg)

- p = probability of winning.
- 1-p = q = probability of loosing.
- n = number of times an event occur.
- k = number of times of winning.
      
------      
### Continuous Random Variable.
- They can take any value in a given range. Probability distribution of a continuous random variable is known as Probability Density Function.
- Example: Life of a fly, i.e. 4-6 days.

![](https://sites.nicholas.duke.edu/statsreview/files/2013/06/pdf.jpg)

------
### Central Limit Theorem.
- If we take means of random samples from a distribution and we plot the means, the graph approaches to a normal distribution when we have taken sufficiently large number of such samples. The theorem aslo states, that the mean of means will be approximately equal to the mean of the sample means.

![](https://image.slidesharecdn.com/samplingdistributionsstatpptbecdoms-120223031954-phpapp01/95/sampling-distributions-stat-ppt-bec-doms-21-728.jpg?cb=1329968038)

------
### Normal Distribution.
1. Area under the probability density function gives the probability fro the random variable to be in that range.
2. There is the large probability for the means to be around the actual mean of the data, than to be farther away.
3. Normal Distribution for higher standard deviations are flatter as compared to those for lover standard deviations.
- To convert Normal Distribution to a standard normal curve, replace frequencies with probabilities, so that the area under the curve is 1.
      
![](https://qph.fs.quoracdn.net/main-qimg-3e8079c89f2b8355c6be752b79feaa54.webp)

------
### Empirical Rule.
The Empirical Rule states that almost all data lies within 3 standard deviations of the mean for a normal distribution.
1. Under this rule, 68% of the data falls within one standard deviation.
2. 95% of the data lies within two standard deviations.
3. 99.7% of the data is within three standard deviations.
4. Totral area under the standard normal curve is 1.

![](https://qph.fs.quoracdn.net/main-qimg-a86744ea6f27735b381e097bed60e048.webp)

------
### Z Score.
The distance in terms of numbers of standard deviation, the observed value is away from the mean, is the standard score or the Z score.
- If 'Z' value is positive it means it is right of the mean, and if 'Z' value is negative it is to the left of the mean.

![](https://www.simplypsychology.org/Z-score-formula.jpg?ezimgfmt=rs:382x312/rscb19/ng:webp/ngcb19)

------
## Inferential Statistics. 
- A single measure of some attribute of a sample is called as Statistics.
- The statistic of the entire population in context is called as Population Statistics.
- The statistic of a group taken from a population is called as Sample Statistics.
------
### Estimation.
There are two types of Estimation.
- Point Estimation: Picking up a random sample from the data and calculating it's mean is called Point Estimation.
- Interval Estimation: Mean of the data is lying between lower bound(BD) and upper bound(UB), with 95% of confidence level is called Interval Estimation.

![](https://miro.medium.com/max/712/1*QYZX8IUnuehc_wrVD5iJcA.png)

------
### Confidence Level.
- It is the Interval[LB,UB] with k% of confidence level. It can be calculated by formula,

![](https://www.cqeacademy.com/wp-content/uploads/2017/12/Confidence-Interval-for-Population-Mean-Explainer.jpg)

------
### Margin of Error.
- It can be defined as how far could the given statistics lie from the calculated sample mean in either direction, which is positive or negative. 
- Confidence Intervals can be built with different degrees of confidence suitable to a user's needs like 70%, 90%.

![](https://cdn.educba.com/academy/wp-content/uploads/2019/04/Margin-of-Error-Formula1-1.jpg)

------
### Hypothesis.
A Hypothesis is nothing but a proposed explaination for a phenomenon.
1. Null Hypothesis: It can be that the sample statistics to be equal to the population statistics or that the intervention doesn't bring any difference to the sample.
2. Alternate Hypothesis: It basically negates the Null Hypothesis or says that the intervention brings a significant difference to the sample, or that the sample is significantly different from the population.

![](https://ihelptostudy.com/wp-content/uploads/writing-null-hypothesis-and-alternative-hypothesis_1.jpg)

------
### Directional Hypothesis.
For it, the null hypothesis is tested in only one direction. In this case, one tail test is used.

![](https://image.slidesharecdn.com/researchhypothesis-141103111454-conversion-gate02/95/research-hypothesisppt-18-638.jpg?cb=1415013421)

------
### Non- Directional Hypothesis.
For it, the null hypothesis is tested in only one direction. In this case, two tail test is used.

![](https://image.slidesharecdn.com/researchhypothesis-141103111454-conversion-gate02/95/research-hypothesisppt-19-638.jpg?cb=1415013421)

------
### Errors.
A hypothesis is not factual. It is highly dependent on the researcher.
1. Type 1 Error: Rejecting the null hypothesis when it's actually true (False Positive).
2. Type 2 Error: Failing to reject the null hypothesis when it's actually false (False Nagative).

![](https://163602-560839-raikfcquaxqncofqfm.stackpathdns.com/wp-content/uploads/2020/07/Graphical-representation-of-type-1-and-type-2-errors.jpg)

------
### Degree of Freedom.
- If we need to pick values in a sample with sample size 10, and mean of 100, we can choose 9 values freely, but the 10th one will be forced by the sample mean, so in this case, the degree of freedom will be 9.

![](https://cdn.educba.com/academy/wp-content/uploads/2019/12/Degree-of-Freedom-Formula.jpg)

------
### T-Tests.
#### Steps to perform T-Tests.
1. Define null and alternate hypothesis.
2. Compute T statistic.
3. Get T critical from the T-table.
4. Compare the computed T statistic and T critical value.

- It is very similar to Z scores. Here we use sample standard deviation to estimate population  standard deviation. T-tests have wider tails. It is mainly classified as below.
1. 1 Tailed Test: It refer to the case where the null hypothesis is defined, such that we need to check for the critical values only in a single direction.
2. 2 Tailed Test: It refer to the case where the null hypothesis is defined, such that we need to check for the critical values on both the sides of the mean.

![](https://keydifferences.com/wp-content/uploads/2017/01/one-tailed-vs-two-tailed-test-thumbnail.jpg)

------
### One sample T-test.
- It is used when we have a very small sample.

![](https://sites.nicholas.duke.edu/statsreview/files/2013/09/ttest2.jpg)

- If the T statistic value and critical T value are significantly different, we can say that there is significant difference between the two values.

------
### Two sample T-test.
- Here, difference is the difference in their means and the standard error would be the combine standard error of the two samples, and degree of freedom = n1+n2-2.

![](https://www.biologyforlife.com/uploads/2/2/3/9/22392738/949234_orig.jpg)

------
### Paired T tests.
- It is used to check the effect of the intervention on a sample.
- Here we check, if there is a significant difference in the same sample before and after the intervention or in two different conditions.
- Null Hypothesis would be the difference two sample means is 0.
- Alternate Hypothesis will be, thereis a significant difference between the two sample means.

![](https://www.leansigmacorporation.com/wp/wp-content/uploads/2015/12/Paired-t-Test-MTB_00.png)

### Chi-Squared tests.
- Chi Squared test is used to estimate how closely an observed distribution matches an expected distribution. It is referred to as a “goodness-of-fit” test.

![](https://www.thoughtco.com/thmb/ns7d4DC1AqVGme2p1-WYqC26r_s=/768x0/filters:no_upscale():max_bytes(150000):strip_icc()/latex_ac74fec08532861eb5f8b87226ebf396-5c59a6fcc9e77c00016b4195.jpg)

- Chi squared statistic will be smaller when observed value are closer to the expected value and vice-versa.
- Chi square test is unidirectional test.
- In chi square test degree of freedom is always one, as we can choose only one value freely.
- If calculated chi square statistic is smaller than chi square critical value, we fail to reject the null hypothesis, and there is no significant difference between the observed and expected values.

------
### Correlation.
It is used to determine the relationship between two variables. It's coefficient is denoted by 'r'.
- The correlation coefficient values ranges from -1 to +1, and 0 means no correlation.
