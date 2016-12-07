---
title: |
  Data transformations and\
  Non-Parameteric Methods
author: Paul M. Magwene
date:   07 December 2016
...


# What do you do if your data is not normally distributed?

## Is my data normally distributed?

![](./whitlock_13.1-1.jpg)


## Some non-normal distributions

![](./whitlock_13.1-2.jpg)


## Visual tools: normal quantile plot

![](./whitlock_13.1-3.jpg)


## Example data set: Comparing biomass between protected and unprotected marine sites

![](./whitlock_13.1-4.jpg)

## A formal test for normality: Shapiro-Wilk Test


# Data transformations

A number of mathematical transformations can sometimes help to make data more approximately normal

 1. Log transformation
 #. Arcsine transformation
 #. Square root transformation
 #. Square transformation
 #. Natural exponential transformation
 #. Reciprocal transformation


## Log transformation


$$X' = \ln[X]$$

Tends to work well when:

 - The data are all positive
 - The frequency distribution is right skewed
 - The data span several orders of magnitude
 - The measurements are ratios or products of variables
 - e.g. morphological measures such as body mass, length

## Log transformation, cont.

![](./whitlock_13.3-1l.jpg){height=1.5in}\ ![](./whitlock_13.3-1r.jpg){height=1.5in}


## Log transformation of biomass ratio data set

## Cautions

- $\bar{X'} \neq \ln[X]$
- Often will do analyses in log transformed data, and then back transform to original scale to report *geometric mean*  and CIs to facilitate interpretation


## Arcsine transformation

$$
X' = arcsin[\sqrt{X}]
$$

Used when data are proportions

## Square-root transformation

$$
X'  = \sqrt{X + 1/2}
$$

Used when the data are counts, such as number of eggs laid, number of bacterial colonies, number of mates acquired, etc.

## Other transformations

Square transformation, $X' = X^2$

 - left skewed data

Natural exponential function, $X' = e^{X}$

 - alternative for left skewed data

Reciprocal transformation, $X' = \frac{1}{X}$

 - right skewed, all data points have the same sign


# Non-parametric tests

## Sign test (alternative to one-sample t-test)

Non-parameteric alternative to one-sample t-test

## Mann-Whitney U-test (alternative to two-sample t-test)

Non-parameteric alternative to two-sample t-test

## Kruskal-Wallis test (alternative to ANOVA)

## Spearman's rank correlation 

## Assumptions of non-parametric tests

## Power of non-parametric tests
