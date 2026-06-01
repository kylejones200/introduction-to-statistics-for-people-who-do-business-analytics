---
author: "Kyle Jones"
date_published: "April 20, 2024"
date_exported_from_medium: "November 10, 2025"
canonical_link: "https://medium.com/@kyle-t-jones/introduction-to-statistics-for-people-who-do-business-analytics-26878760a14a"
---

# Introduction to Statistics for people who do Business Analytics Before there was Analytics there was Statistics. For a long time,
statistics has been seen as a boring and hard topic but it doesn't have...

### Introduction to Statistics for people who do Business Analytics
#### Before there was Analytics there was Statistics. For a long time, statistics has been seen as a boring and hard topic but it doesn't have to be. It can be quite exciting!
My goal is to share some of the basics of statistics to help explain some of the things we do in business analytics. Often in analytics we use these techniques even if we don't know exactly how the values are calculated.

By understanding how to build these values from scratch, we will have a better understanding of what the data is (and is not) saying.

#### What is statistics?
Statistics is the science of collecting, organizing, analyzing, and interpreting data in order to make decisions.

Statistics is all around us. We hear statistics on the news and we use statistics to make business decisions.

In general, you can use statistics in 5 ways. Statitics can:

1.  [Describe data. This helps us characterizing populations and samples. We do this with tools like descriptive statistics, statistical intervals, correlation coefficients, graphics, and maps.]
2.  [Compare or Test data against other values or a pre-set threshold value. We use this to detect differences between statistical populations or reference values using simple hypothesis tests, and analysis of variance and covariance. For example, do all of these packages weigh at least 1 lbs?]
3.  [Identify or Classify groups with in the data. We often want to know when things go together. We can do this using descriptive statistics; statistical intervals and tests, graphics, and multivariate techniques such as cluster analysis.]
4.  [Predict values for things we haven't yet observed. Especailly in busiess we want to predict values for an output given diffenernt combinations of input values. We can do this using regression and neural networks, forecasting using time-series modeling techniques, and interpolating spatial data.\
    1. Explain --- Explaining latent aspects of phenomena using regression, cluster analysis, discriminant analysis, factor analysis, and other data mining techniques.]

How do we do this? This table shows some statistical methods that can be used to accomplish different goals.

<figcaption>Goals, Tools, and Applications for different stats techniques. Source: Author.</figcaption>

#### Why do we need statistics?
The world is full of uncertainty. Variability arises from two primary sources: variability in the natural process (inherent variability) and variability due to our imperfect measurement devices (measurement variability).

#### Summary Statistics
Once we have data set (sample), we want to determine basic summary statistics. We can look at quantitative summaries of data to get a sense of the range of values in the data. I like plotting data so I can look for patterns. We can also calculate common summary statistics: mean, median, mode, quartiles, max, min.

#### Descriptive Statistics
Descriptive statistics is a collection of techniques for organizing, summarizing, and presenting a sample of data in a convenient, informative way.

If you follow sports, you know have seen these stats in action. Like:

- Completed passes, yards gained by passing, rushing touchdowns
- Turnovers, rebounds, free-throws made
- Batting average, on-base percentage, runs produced

In Business/Economics, we have similar stats but we usually call them KPIs (key performance indicators:

- Average time customers spend on hold in a call center
- Proportion of prospects at a car dealership who end up purchasing
- Variability in stock returns for the Dow Jones for the past year
- Average amount of debt students carry after graduation
- Average market value of homes in a neighborhood
- Proportion of members of a focus group who think favorably about a new product

Here is an example from a dateset on food.

<h1 id="an-error-occurred." class="message">An error occurred.</h1>

Unable to execute JavaScript.

#### Variance and Standard Deviation
Knowing a single value of a stat is useful but it limited. We also need to know the spread of the data. For example, if someone gets a 90% on a test that is good right? Well, if everyone else got a 100% then it is not so good. If everyone else got a 60% then it is great!

Standard Deviation is like variance but better. \
- However, variance is a squared term \
- Difficult to understand --- squared ages? Squared income? (Difficult
substantive meaning) \
- Standard deviation: Square root of variance \
--- Another measure of spread \ --- Reverts back to original scale

Samples are data sampled from an underlying population. We use summary statistics to get a sense of the data. Common examples of summary statistics are mean, median, variance, and standard deviation.

#### Measures of Central Tendency
Sample mean: The sample mean (also called the arithmetic mean or sample average), is found by adding up all observations and dividing by the total number of observations.

We usually use the variable "x" when we talk about the sample mean but we don't have to use just that letter. We can use any letter we want to indicate a variable (X, Y, W, V, etc). Whatever we call the variable, a letter with a bar over it indicates the sample mean.

Here is an example in Excel using data about followers and engagement on social media.

<h1 id="an-error-occurred." class="message">An error occurred.</h1>

Unable to execute JavaScript.

#### Some key terms
- Mean: The Average --- The mean of a data set is the sum of the data entries divided by the number of entries.
- Median: The Middle --- The median of a data set is the value that lies in the middle of the data when the data set is ordered from least to greatest. How do you find it? Order the data entries. Find the middle data entry. Interpret the results in the context of the data.
- Mode: The Most --- The mode of the data set is the data entry that occurs with the greatest frequency. A data set can have one mode, more than one mode, or no mode. How do you find it? 1. Write the data in order. 2. Identify the entry, or entries, that occur with the greatest frequency. 3. Interpret the results in the context of the data.
- Range: Smallest-Largest values
- Outlier: A data entry that is far removed from the other entries in the data set.
- Descriptive Statistics: The branch of statistics that involves the organization, summarization, and display of data. Example: "For unmarried men, approximately 70% were alive at age 65" and "For married men, 90% were alive at 65."

*Inferential Statistics* is the branch of statistics that is about using a sample to draw conclusions about a population. A basic tool in the study of inferential statistics is probability. Inferential statistics is a collection of techniques designed to use sample data to make generally-applicable statements about the natural process or population from which the data arose. Example: Possible Inference: Being married is associated with a longer life for men.

Probability: We typically aren't interested in just the sample that we have (although the sample is still interesting).

\- Example: An insurance company sends out a survey to 100 policy holders asking them to rate their satisfaction with the service. \ --- Managers aren't just interested in only those 100 people. They want to be able to say something about the process (or population of customers) that is behind those customer satisfaction ratings\ --- That is, they want to infer (make a conclusion about) the process, so they can (perhaps) make adjustments to their website, coverage, customer service, etc.\ --- Probability helps us make the leap from a sample to population (or process) in an objective, mathematically justified way

Measures of Central Tendency

Estimators and Estimates: a mathematical function of the sample that tell us how to calculate an estimate of a parameter form a sample. Smaller the variance, most efficient the estimator. Hence, we require to find what are the "good" estimators.

Few vital criterial for goodness of an estimator are based on these properties:

Estimator, Parameter, and Excel Command

Probability Distributions

Probability theory forms the basis of all statistical inference. It allows us to "make the leap" from the sample we have to the population or process that we are trying to study. In order for us to be able to talk about statistics in an efficient way, we must agree upon some definitions. In this section, we will review some concepts that you should be familiar with from earlier classes.

A random variable is a numerical or categorical characteristic of a population or process whose range of possible values is known or assumed but for which the values are subject to random (or "chance") variation.

Any letter of the alphabet can be used to indicate a random variable. The most common choices are X, Z, and Y. The name of the random variable is written in capital letters, while a specific value that the random variable takes on is written in lowercase.

Here are some additional important definitions.

A probability can be thought of as a chance of something happening. The range of a valid probability for an event is 0 (no chance of the event occurring) to 1 (guaranteed for the event to occur). Probabilities are only positive.

A discrete random variable is a random variable whose entire set of values and associated probabilities can be completely listed or at least counted.

A continuous random variable is a random variable whose entire set of values cannot be listed because the possible values extend, in theory, to an infinite number of decimal places.

Once we have defined a random variable, we need some way to assign the probabilities to its values. In general, how we do this depends on whether the random variable is discrete or continuous. There is some highly technical mathematics involved in that we are going to skip right over in favor of the following definition:

A probability distribution is a specification of the possible values of a random variable and their associated probabilities, made either by listing the possible values and their probabilities or by providing a function that gives probabilities for a collection of possible values of the random variable.

Central limit theorem\ In the central limit theorem:

\* No matter the distribution\* the more samples, closer to normal\ \* the bigger the samples, the closer to normal

Measures of dispersion

Population variance: The mean of the squares of the deviations.\ Population standard deviation: The square root of the population variance.

1\. Find the mean and each deviation.\
2. Square each deviation.\
3. Find the sum of the squares.\
4. Divide by the number of data entries.\
5. Take the square root of the population variance.

Empirical Rule(Or 68--95--99.7 Rule)

For data with a (symmetric) bell-shaped distribution, the standard deviation has the following characteristics.

1\. About 68% of the data lie within one standard deviation of the mean.\
2. About 95% of the data lie within two standard deviations of the
mean.\
3. About 99.7% of the data lie within three standard deviations of the
mean.

Quartiles of a Data Set

What are quartiles?

The three quartiles, Q_1 ,Q_2 ,and Q_3 , approximately divide an ordered data set into four equal parts. About one quarter of the data fall on or below the first quartile Q_1.About one half of the data fall on or below the second quartile Q_2.About three quarters of the data fall on or below the third quartile Q_3.

Interquartile Range (IQR)

The interquartile range (IQR) of a data set is a measure of variation that gives the range of the middle 50% of the data. It is the difference between the third and first quartiles.

Box-and-Whisker Plot

1.  [Find the five-number summary of the data set. (minimum entry, first quartile, median, third quartile, maximum entry)]
2.  [Construct a horizontal scale that spans the range of the data.]
3.  [Plot the five numbers above the horizontal scale.]
4.  [Draw a box above the horizontal scale from\ Q_1 to Q_3 and draw a vertical line in the box at\ Q_2.]
5.  [Draw whiskers from the box to the minimum and maximum entries.]

#### Skewed Distributions

#### Standard normal distribution
It is a normal distribution with a mean of 0 and a standard deviation of 1.

Every normal distribution can be standardized using the following formula:

<figcaption>Standard normal distribution formula</figcaption>

#### Discrete Probability Distributions
A discrete probability distribution is a listing or specification of the possible values of a random variable and their associated probabilities.

- An upper-case letter (like X) will represent the name of the random variable,
- Its lower-case counterpart (like x) will represent the value of the random variable.
- The probability that the random variable X will equal x is P(X = x)

### Related Stories
- [[Getting to know Pandas for data analytics with Python](https://medium.com/@kylejones_47003/getting-to-know-pandas-for-data-analytics-with-python-7386da28dd33)]
- [[Basic Data Analysis using Pandas Library in Python](https://medium.com/@kylejones_47003/basic-data-analysis-using-pandas-library-61ed815b834a)]
- [[Confidence Intervals for Business Analytics](https://medium.com/@kylejones_47003/confidence-intervals-c3a1605bfb55)]
