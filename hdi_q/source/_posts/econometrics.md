---
title: 'Econometrics: Key Terms'
author: hdi_q
language: zh-CN
date: 2021-06-12 00:00:00
index_img: /img/econometrics/cover.jpg
banner_img: /img/captured/IMG_20191125_073315.jpg
excerpt: 'Econometrics: Key Terms'
categories: Econometrics
tags: [Econometrics]
mathjax: true
---

声明：该篇博客基于《计量经济学》整理，仅作工作室及其成员学习交流使用，禁止转载。图片源自网络，皆为非商业化用途，若存在侵权情况请联系作者要求删除。

## Chapter 1 Economic Questions and Data

**Randomized controlled experiment:**
An experiment that is randomized in the sense that the treatment is assigned randomly.

**Control group:**
The group that receives no treatment.

**Treatment group:**
The group that receives the treatment.

**Causal effect:**
The effect on an outcome of a given action or treatment as measured in an ideal randomized controlled experiment.

**Experimental data:**
Come from experiments designed to evaluate a treatment or policy or to investigate a casual effect.

**Observational data:**
Data contained by observing actual behaviour outside an experimental setting.

**Cross-sectional data:**
Data on different entities for a single time period.

**Observation number:**
The number of values that are contained in the dataset.

**Time series data:**
Data for a single entity collected at multiple time periods.

**Panel data / Longitudinal data:**
Data for multiple entities in which each entity is observed at two or more time periods.

## Chapter 2 Review of Probability

**Outcomes:**
The mutually exclusive potential results of a random process.

**Probability:**
The proportion of the time that the outcome occurs in the long run.

**Sample space:**
The set of all possible outcomes.

**Event:**
A subset of the sample space, that is, a set of one or more outcomes.

**Discrete random variable:**
Takes on only a discrete set of values.

**Continuous random variable:**
Takes on a continuum of possible values.

**Probability distribution:**
The list of all possible values of the variable and the probability that each value will occur.

**Cumulative probability distribution:**
The probability that the random variable is less than or equal to a particular value.

**Cumulative distribution function (c.d.f):**
A cumulative probability distribution is also referred to as a $c.d.f.$.

**Bernoulli random variable:**
A binary random variable.

**Bernoulli distribution:**
The probability distribution of a binary random variable.

**Probability density function (p.d.f.) / Density function / Density:**
A function whose value at any given sample in the sample space can be interpreted as providing a relative likelihood that the value of the random variable would equal that sample.

**Expected value:**
The long-run average value of the random variable over many repeated trials or occurrences.

**Expectation:**
The expected value of the random variable.

**Mean:**
The expected value of the random variable.

**Variance:**
The expected value of the square of the deviation of the random variable from its mean.

**Standard deviation:**
The square root of the variance.

**Moments of a distribution:**
The mean, variance, skewness, and kurtosis.

**Skewness:**
Measures the lack of symmetry of a distribution.

**Kurtosis:**
A measure of how much the variance of the random variable arises from extreme values.

**Outlier:**
An extreme value of the random variable.

**Leptokurtic:**
A distribution with kurtosis exceeding 3.

**$r^{th}$ moment:**
The expected value of $Y^r$.

**Joint probability distribution:**
The probability that the random variables simultaneously take on certain values.

**Marginal probability distribution:**
Distinguish the distribution of the marginal distribution from the joint distribution.

**Conditional distribution:**
The distribution of a random variable conditional on another random variable taking on a specific value.

**Conditional expectation / Conditional mean:**
The mean of the conditional distribution of $Y$ given $X$.

**Law of iterated expectations:**
The expectation of $Y$ is the expectation of the conditional expectation of $Y$ given $X$.

**Conditional variance:**
The variance of $Y$ conditional on $X$ is the variance of the conditional distribution of $Y$ given $X$.

**Independently distributed / Independent:**
The value of one of the variables provides no information about the other.
The conditional distribution of $Y$ given $X$ equals the marginal distribution of $Y$.

**Covariance:**
The expected value $E[(X-\mu_X)(Y-\mu_Y)]$.

**Correlation:**
The covariance between the random variables divided by their standard deviations.

**Uncorrelated:**
$$Corr (X, Y) =0$$

**Normal distribution:**
A type of continuous probability distribution for a real-valued random variable.

**Standard normal distribution:**
The normal distribution with the mean of 0 and the variance of 1.

**Standardize a variable:**
Subtract the mean, then divide the result by the standard deviation.

**Multivariate normal distribution:**
A generalization of the one-dimensional (univariate) normal distribution to higher dimensions.

**Bivariate normal distribution:**
The probability density function of two variables that are linear functions of the same independent normal random variables.

**Chi-squared distribution:**
The distribution of the sum of m squared independent standard normal random variables.

**Student t distribution / t distribution:**
The distribution of the ratio of a standard normal random variable, divided by the square root of an independently distributed chi-squared random variable with $m$ degrees of freedom divided by $m$.

**F distribution:**
The distribution of the ratio of a chi-squared random variable with degrees of freedom $m$, divided by $m$, to an independently distributed chi-squared random variable with degrees of freedom $n$, divided by $n$.

**Simple random sampling:**
*N* objects are selected at random from a population.

**Population:**

**Identically distributed:**
When $Y_i$ has the same marginal distribution for $i=1…n$.

**Independently and identically distributed (i.i.d.):**
When $Y_i$ are drawn from the same distribution and are independently distributed.

**Sample average / Sample mean:**

**Sampling distribution:**
The distribution of $\overline{Y}$ is called the sampling distribution of $\overline{Y}$.

**Exact (finite-sample) distribution:**
The sampling distribution that exactly describes the distribution of $\overline{Y}$ for any $n$.

**Asymptotic distribution:**
The large-sample approximation to the sampling distribution.

**Law of large numbers:**
Under general conditions, $\overline{Y}$ will be near $\mu_Y$ with very high probability when *n* is large.

**Convergence in probability / Consistency:**
The property that $\overline{Y}$ is near $\mu_Y$ with increasing probability as *n* increases.

**Central limit theorem:**
Under general conditions, the distribution of $\overline{Y}$ is well approximated by a normal distribution when *n* is large.

**Asymptotic normal distribution:**
The distribution of $\overline{Y}$ approaches the normal as *n* grows large, $\overline{Y}$ is said to have an asymptotic normal distribution.

## Chapter 3 Review of Statistics

**Estimator:**
A function of a sample of data to be drawn randomly from a population.

**Estimate:**
The numerical value of the estimator when it is actually computed using data from a specific sample.

**Bias, consistency, and efficiency:**
The bias of $\hat{\mu}_Y$ is $𝐸(\hat{\mu}_Y)$ − $\mu_Y$.

$\hat{\mu}_Y$ is an unbiased estimator of $\mu_Y$ if $𝐸(\hat{\mu}_Y) = \hat{\mu}_Y$.

$\hat{\mu}_Y$ is an consistent estimator of $\mu_Y$ if $\hat{\mu}_Y \stackrel{p}\longrightarrow \mu_Y$.

Let $\tilde\mu_Y$ be another estimator of $\mu_Y$ and suppose that both $\hat{\mu}_Y$ and $\tilde\mu_Y$ are unbiased . Then $\hat{\mu}_Y$ is said to be more efficient than $\tilde{\mu}_Y$ if $var(\hat{\mu}_Y) < var(\tilde{\mu}_Y)$.

**BLUE (Best Linear Unbiased Estimator):**
$\bar{Y}$ is the most efficient (best) estimator among all estimators that are unbiased and are linear functions of $Y_i$.

**Least squares estimator:**
The estimator $m$ that minimizes the sum of squared gaps $Y_i - min \sum^n_{i=1}(Y_i - m)^2$.

**Hypothesis tests:**

**Null hypothesis:**
The hypothesis to be tested.

**Alternative hypothesis:**
The hypothesis that holds if the null hypothesis does not hold.

**Two-sided alternative hypothesis:**

**p-value (significance probability):**
The probability of drawing a statistic at least as adverse to the null hypothesis as the one you actually computed in your sample, assuming the null hypothesis is correct.
The probability of drawing $\bar{Y}$ at least as far in the tails of its distribution under the null hypothesis as the sample average you actually computed.

**Sample variance:**

**Sample standard deviation:**
The square root of the sample variance.

**Degrees of freedom:**
The number of values in the final calculation of a statistic that are free to vary.

**Standard error of $\bar{Y}$:**
An estimator of the standard deviation of $\bar{Y}$.

**t-statistic (t-ratio):**
The standardized sample average $(\bar{Y} - \mu_{Y,0}) / SE(\bar{Y})$.

**Test statistic:**
A statistic used to perform a hypothesis test.

**Type I error:**
The null hypothesis is rejected when in fact it is true.

**Type II error:**
The null hypothesis is not rejected when in fact it is false.

**Significance level:**
The prespecified probability of a type I error.

**Critical value:**
The value of the statistic for which the test just rejects the null hypothesis at the given significance level.

**Rejection region:**
The set of values of the test statistic for which the test rejects the null hypothesis.

**Acceptance region:**
The values of the test statistic for which it does not reject the null hypothesis.

**Size of a test:**
The probability that the test actually incorrectly rejects the null hypothesis when it is true.

**Power of a test:**
The probability that the test correctly rejects the null hypothesis when the alternative is true.

**One-sided alternative hypothesis:**

**Confidence set:**
A set of values that contains the true population mean with a certain prespecified probability.

**Confidence level:**
The prespecified probability that population mean is contained in this set.

**Confidence interval:**
The confidence set for population mean turns out to be all the possible values of the mean between a lower and an upper limit, so that the confidence set is an interval.

**Coverage probability:**
The probability computed over all possible random samples, that it contains the true population mean.

**Test for the difference between two means:**

**Causal effect / Treatment effect:**
The expected effect on the outcome of interest of the treatment as measured in an ideal randomized controlled experiment.
The difference of two conditional expectations.

**Scatterplot:**
A plot of n observations on $X_i$ and $Y_i$.

**Sample covariance:**
The estimator of the population covariance.

**Sample correlation coefficient (sample correlation):**
The ratio of the sample covariance to the sample standard deviations.

## Chapter 4 Linear Regression with One Regressor

**Linear regression model with a single regressor:**
$$Y_i = \beta_0 + \beta_1X_i + u_i$$

**Dependent variable:**
$$Y$$

**Independent variable / Regressor:**
$$X$$

**Population regression line / Population regression function:**
$$\beta_0 + \beta_1X_i$$

**Population intercept:**
$$\beta_0$$

**Population slope:**
$$\beta_1$$

**Population coefficients:**
The intercept and the slope.

**Parameters:**
The intercept and the slope.

**Error term:**
$$u_i$$

**Ordinary least squares (OLS) estimators:**
$$\sum_{i=1}^n(Y_i - b_0 - b_1X_i)^2 \\ \beta_0, \beta_1$$

**OLS regression line / Sample regression line / Sample regression function:**
The straight line constructed using the OLS estimators: $\hat{\beta}_0 + \hat{\beta}_1X$.

**Predicted value:**
Given based on the OLS regression line.

**Residual:**
The difference between $Y_i$ and its predicted value: $\hat{u}_i = Y_i - \hat{Y}_i$.

**Regression $R^2$:**
The fraction of the sample variance of $Y_i$ explained by $X_i$.

**Explained sum of squares (ESS):**
The sum of squared deviations of the predicted values of $Y_i$ , $\hat{Y}_i$ from their average.

**Total sum of squares (TSS):**
The sum of squared deviations of $Y_i$ from its average: $ESS = \sum_{i=1}^n(\hat{Y}_i - \bar{Y})^2$ uses the fact that the sample average OLS predicted value equals $\bar{Y}$.

**Sum of squared residuals (SSR):**
The sum of the squared OLS residuals.

**Standard error of the regression (SER):**
An estimator of the standard deviation of the regression error $u_i$.

**Least squares assumptions:**

1. The conditional distribution of $u_i$ given $X_i$ has a mean of zero.
2. $(X_i, Y_i), i=1…n$, are independently and identically distributed.
3. Large outliers are unlikely.

## Chapter 5 Regression with a Single Regressor: Hypothesis Tests and Confidence Intervals

**Null hypothesis:**

**Two-sided alternative hypothesis:**

**Standard error of $\hat{\beta}_1$:**
An estimator of $\sigma_{\hat{\beta}_1}$, the standard deviation of the sampling distribution of $\hat{\beta}_1$.

**t-statistic:**
$$t = \frac{ \hat\beta_1 - \beta_{1,0} }{ SE (\hat\beta_1) }$$

**p-value:**
The probability of observing a value of $\hat{\beta}_1$ at least as different from $\beta_{1,0}$ as the estimate actually computed ($\hat{\beta}_1^{act}$), assuming that the null hypothesis is correct.

**Confidence interval for $\beta_1$:**
The set of values that cannot be rejected using a two-sided hypothesis test with a significance level.
An interval that has a probability of containing the true value of $\beta_1$.

**Confidence level:**
The interval contains the true value in 95% of all samples.

**Indicator variable / Dummy variable:**
A binary variable.

**Coefficient multiplying $D_i$ / Coefficient on $D_i$:**
$$Y_i = \beta_0 + \beta_1D_i + u_i. \beta_1$$

**Heteroskedasticity and homoskedasticity:**
The error term $u_i$ is homoskedastic if the variance of the conditional distribution of $u_i$ given $X_i$ is constant for $i=1…n$ and in particular does not depend on $X_i$. Otherwise, the error term is heteroskedastic.

**Homoskedasticity-only standard errors:**
$$SE(\hat\beta_1) = \sqrt{\tilde{\sigma}_{\hat{\beta}_1}^2}$$

**Heteroskedasticity-robust standard error:**
The standard errors lead to statistical inferences that are valid whether or not the errors are heteroskedastic.

**Gauss-Markov theorem:**
Under a set of conditions known as the Gauss-Markov conditions, the OLS estimator $\hat\beta_1$ has the smallest conditional variance, given $X_i$, of all linear conditionally unbiased estimators of $\beta_1$, that is, the OLS estimator is **BLUE**.

**Best linear unbiased estimator (BLUE):**
If the three least squares assumptions hold and if the error is homoskedastic, then the OLS estimator has the smallest variance, conditional on $X_i$ among all estimators in the class of linear conditionally unbiased estimators.

**Weighted least squares (WLS):**
Weights the ith observation by the inverse of the square root of conditional variance of $u_i$ given $X_i$.

**Homoskedastic normal regression assumptions:**
The five assumptions—the three least squares assumptions, that the errors are homoskedastic, and that the errors are normally distributed.

**Gauss-Markov conditions:**
States that $u_i$ has mean zero, that $u_i$ has a constant variance, and that the errors are uncorrelated for different observations.

## Chapter 6 Linear Regression with Multiple Regressors

**Omitted variable bias:**
If the regressor is correlated with a variable that has been omitted from the analysis and that determines, in part, the dependent variable.

**Multiple regression model:**
Include additional variables as regressors.

**Population regression line / Population regression function:**
$$E(Y_i | X_{1i} = x_1, X_{2i} = x_2) = \beta_0 + \beta_1 x_1 + \beta_2 x_2$$

**Intercept:**
$$\beta_0$$

**Slope coefficient of $X_{1i}$ / Coefficient on $X_{1i}$:**
$$\beta_1$$

**Slope coefficient of $X_{2i}$ / Coefficient on $X_{2i}$:**
$$\beta_2$$

**Holding $X_2$ constant / Controlling for $X_2$:**
$\beta_1$ is the effect on Y of a unit change in $X_1$, holding $X_2$ constant.

**Partial effect:**
Another phrase used to describe $\beta_1$.

**Population multiple regression model:**
$$Y_i = \beta_0 + \beta_1 X_{1i} + \beta_2 X_{2i} + u_i, i = 1, ..., n.$$

**Constant regressor:**
$$Y_i = \beta_0 X_{0i} + \beta_1 X_{1i} + \beta_2 X_{2i} + u_i, where X_{0i} = 1, i = 1, ..., n. \\ X_{0i}$$

**Constant term:**
$$\beta_0$$

**Homoskedastic:**
If the variance of the conditional distribution of $u_i$ given $X_{1i}, ..., X_{ki}, var(u_i | X_{1i}, ..., X_{ki})$, is constant for $i = 1, ..., n$ and thus does not depend on the values of $X_{1i}, ..., X_{ki}$.

**Heteroskedastic:**
If the variance of the conditional distribution of $u_i$ given $X_{1i}, ..., X_{ki}, var(u_i | X_{1i}, ..., X_{ki})$, is not constant for $i = 1, ..., n$ and thus depend on the values of $X_{1i}, ..., X_{ki}$.

**Ordinary least squares (OLS) estimators of $\beta_k$:**
The estimators of the coefficients $\beta_0, \beta_1, ..., \beta_k$ that minimize the sum of squared mistakes in $\sum^n_{i=1}(Y_i - b_0 - b_1 X_{1i} - ... - b_k X_{ki})^2$.

**OLS regression line:**
The straight line constructed using the OLS estimators: $\hat\beta_0 + \hat\beta_1 X_1 + ... + \hat\beta_k X_k$.

**Predicted value:**
$$\hat{Y}_i = \hat\beta_0 + \hat\beta_1 X_1 + ... + \hat\beta_k X_k$$

**OLS residual:**
$$\hat{u}_i = Y_i - \hat{Y}_i$$

**$R^2$:**
The fraction of the sample variance of $Y_i$ explained by (or predicted by) the regressors.

**Adjusted $R^2$ ($\bar{R}^2$):**
A modified version of the R2 that does not necessarily increase when a new regressor is added.

$$\bar{R}^2 = 1 - \frac{n - 1}{n - k - 1} \frac{SSR}{TSS} = 1 - \frac{s^2_{\hat{u}}}{s^2_Y}$$

**Perfect multicollinearity:**
If one of the regressors is a perfect linear function of the other regressors.
**Dummy variable trap:**
If all binary variables are included as regressors, then the regression will fail because of perfect multicollinearity.
**Imperfect multicollinearity:**
Two or more of the regressors are highly correlated in the sense that there is a linear function of the regressors that is highly correlated with another regressor.

## Chapter 7 Hypothesis Tests and Confidence Intervals in Multiple Regression

**Restrictions:**

**Joint hypothesis:**
A hypothesis that imposes two or more restrictions on the regression coefficients.

**F-statistic:**
Is used to test joint hypothesis about regression coefficients.

**Restricted regression:**
The null hypothesis is forced to be true.

**Unrestricted regression:**
The alternative hypothesis is allowed to be true.

**Homoskedasticity-only F-statistic:**
$$F = \frac{(SSR_{restricted} - SSR_{unrestricted}) / q}{SSR_{unrestricted} / (n - k_{unrestricted} - 1)}$$

$$F = \frac{(SSR_{unrestricted} - SSR_{restricted}) / q}{(1-R^2_{unrestricted}) / (n - k_{unrestricted} - 1)}$$

**95% confidence set:**
A set that contains the true population values of these in 95% of randomly drawn samples.

**Control variable:**
A regressor included to hold constant factors that, if neglected, could lead the estimated causal effect of interest to suffer from omitted variable bias.

**Conditional mean independence:**
The conditional expectation of $u_i$ given $X_{1i}$ and $X_{2i}$ does not depend on $X_{1i}$, although if can depend on $X_{2i}$. That is $E(u_i | X_{1i}, X_{2i}) = E(u_i | X_{2i})$.

**Base specification:**
The regression using this base set of regressors.

**Alternative specifications:**
Alternative set of regressors.

**Bonferroni test:**
Accept if $|t_1| \leqslant c$ and if $|t_2| \leqslant c$; otherwise, reject.

## Chapter 8 Nonlinear Regression Functions

**Quadratic regression model:**
$$Y_i = \beta_0 + \beta_1 X_1 + \beta_2 X^2_i + u_i$$

**Nonlinear regression function:**

**Polynomial regression model:**
$$Y_i = \beta_0 + \beta_1 X_1 + \beta_2 X^2_i + ... + \beta_r X^r_i + u_i$$

**Cubic regression model:**
$$Y_i = \beta_0 + \beta_1 X_1 + \beta_2 X^2_i + \beta_3 X^3_i + u_i$$

**Elasticity:**
The percentage of decrease in demand resulting from a 1% increase in price is called the price **elasticity**.

**Exponential function:**
$$x = e^x$$

**Natural logarithm:**
$$x = \ln(e^x)$$

**Linear-log model:**
$Y$ is not in logarithms, but $X$ is.

**Log-linear model:**
$Y$ is in logarithms, but $X$ is not.

**Log-log model:**
Both $Y$ and $X$ are specified in logarithms.

**Interaction term / Interacted regressor:**
$$Y_i = \beta_0 + \beta_1 D_{1i} + \beta_2 D_{2i} + \beta_3 (D_{1i} \times D_{2i}) + u_i.\\
D_{1i} \times D_{2i}$$

**Interaction regression model:**
The population regression model in $$Y_i = \beta_0 + \beta_1 D_{1i} + \beta_2 D_{2i} + \beta_3 (D_{1i} \times D_{2i}) + u_i$$.

**Nonlinear least squares:**
$$Y_i = f(X_{1i}, ..., X_{ki}, b_1, ..., b_m) + u_i \\ \sum^n_{i=1}[Y_i - f(X_{1i}, ..., X_{ki}, b_1, ..., b_m)]^2$$

**Nonlinear least squares estimators:**
$$b_0, b_1, ..., b_m$$

## Chapter 9 Assessing Studies Based on Multiple Regression

**Population studied:**
The population of entities from which the sample was drawn.

**Internal validity:**
If the statistical inferences about the causal effects are valid for the population being studied.

**External validity:**
If the inferences and conclusions can be generalized from the population and setting studied to other populations and settings.

**Population of interest:**
The population of entities to which the causal inferences from the study are to be applied.

**Functional form misspecification:**
If the true population regression function is nonlinear but the estimated regression is linear.

**Errors-in-variables bias:**
Its source is an error in the measurement of the independent variable.

**Classical measurement error model:**
Suppose that $w_i$ is uncorrelated with $X_i$ and with the regression error $u_i$.

$$\tilde{X}_i = X_i + w_i, corr(w_i, X_i) = 0 \ and \ corr(w_i, u_i) = 0$$

**Sample selection bias:**
If the data are missing because of a selection process that is related to the value of the dependent variable, beyond depending on the regressors, then this selection process can introduce correlation between the error term and the regressors.

**Simultaneous causality:**
Causality runs backward as well as forward.
An OLS regression picks up both effects, so the OLS estimator is biased and inconsistent.

**Simultaneous equations bias / Simultaneous causality bias:**
Arises in a regression of $Y$ on $X$ when, in addition to the causal link of interest from $X$ to $Y$, there is a causal link from $Y$ to $X$. this reverse causality makes $X$ correlated with the error term in the population regression of interest.

## Chapter 10 Regression with Panel Data

***Panel data:**
Data for $n$ different entities observed at $T$ different time periods.

**Balanced panel:**
The variables are observed for each entity and each time period.

**Unbalanced panel:**
A panel that has some missing data for at least one time period for at least one entity.

**Fixed effects regression model:**
$Y_{it} = \beta_1 X_{it} + \alpha_i + u_{it}$, in which $\alpha_1, ..., \alpha_n$ are treated as unknown intercepts to be estimated, one for each.

**Entity fixed effects:**
The terms $\alpha_1, ..., \alpha_n$.

**Time fixed effects regression model:**
With a single $X$ regressor: $Y_{it} = \beta_1 X_{it} + \lambda_t + u_{it}$

**Time fixed effects:**
The terms $\lambda_1, ..., \lambda_T$

**Entity and time fixed effects regression model:**
$Y_{it} = \beta_1 X_{it} + \alpha_i + \lambda_t + u_{it}$, where $\alpha_i$ is the entity fixed effect and $\lambda_t$ is the time fixed effect.

**Autocorrelated / Serially correlated:**
If $X_{it} is correlated over time for a given entity.$

**Heteroskedasticity- and autocorrelation-consistent (HAC) standard errors:**
Standard errors that are valid if $u_{it}$ is potentially heteroskedastic and potentially correlated over time within an entity.

**Clustered standard errors:**
Allow for heteroskedasticity and for arbitrary autocorrelation within an entity but treat the errors as uncorrelated across entities.

## Chapter 11 Regression with a Binary Dependent Variable

**Limited dependent variable:**
A dependent variable with a limited range.

**Linear probability model:**
The dependent variable is binary rather than continuous.

**Probit:**
$Pr(Y = 1 | X_1, X_2, ..., X_k) = \Phi(\beta_0 + \beta_1 X_1 + \beta_2 X_2 + ... + \beta_k X_k), = \frac{1}{1 + e^{-(\beta_0 + \beta_1 X_1 + \beta_2 X_2 + ... + \beta_k X_k)}}$

**Likelihood function:**
The joint probability distribution of the data treated as a function of the unknown coefficients.

**Maximum likelihood estimator (MLE):**
Of the unknown coefficient consists of the values of the coefficients that maximize the likelihood function.

**Fraction correctly predicted:**
Rule: If $Y_i = 1$ and the predicted probability exceeds 50% or if $Y_i = 0$ and the predicted probability is less than 50%, then $Y_i$ is said to be correctly predicted.

**Pseudo-$R^2$:**
Measures the fit of the model using the likelihood function.

## Chapter 12 Instrumental Variables Regression

**Instrumental variables (IV) regression:**
A general way to obtain a consistent estimator of the unknown coefficients of the population regression function when the regressor is correlated with the error term.

**Instrumental variables (Instrument):**
Additional variables used to glean the information about the movements in regressor that are uncorrelated with the error term.

**Endogenous variable:**
Variables correlated with the error term.

**Exogenous variable:**
Variables uncorrelated with the error term.

**Instrument relevance condition:**
$$corr(Z_i, X_i) \neq 0$$

**Instrument exogeneity condition:**
$$corr(Z_i, u_i) = 0$$

**Two stage least squares:**
The coefficient $\beta_1$ can be estimated using an IV estimator.

**Included exogenous variables:**
Additional regressors. Label W.

**Exactly identified:**
If the number of instruments (m) equals the number of endogenous regressors (k).

**Overidentified:**
If the number of instruments exceeds the number of endogenous regressors.

**Underidentified:**
If the number of instruments less than the number of endogenous regressors.

**Reduced form:**
$X_i = \pi_0 + \pi_1 Z_{1i} + ... + \pi_m Z_{mi} + \pi_{m+r} W_{ri} + v_i$, where $\pi_0, \pi_1, ..., \pi_{m+r}$ are unknown regression coefficients and $v_i$ is an error term.

**First-stage regression:**
Regress $X_{1i}$ on the instrumental variables $(Z_{1i}, ..., Z_{mi})$ and the included exogenous variables $(W_{1i}, ..., W_{ri})$ using OLS, including an intercept.

**Second-stage regression:**
Regress $Y_i$ on the predicted values of the endogenous variables $(\hat{X}_{1i}, ..., \hat{X}_{ki})$ and the included exogenous variables $(W_{1i}, ..., W_{ri})$ using OLS, including an intercept.

**Weak instruments:**
Instruments that explain little of the variation in $X$.

**First-stage F-statistic:**
Provides a measure of the information content contained in the instruments: the more information content, the larger is the expected value of the F-statistic.

**Test of overidentifying restrictions:**
Let $\hat{u}^{TSLS}_i$ be the residuals from TSLS estimation of $Y_i = \beta_0 + \beta_1 X_{1i} + ... + \beta_k X_{ki} + \beta_{k+1} W_{1i} + ... + \beta_{k+r} W_{ri} + u_i$. Use OLS to estimate the regression coefficient in $\hat{u}_i^{TSLS} = \delta_0 + \delta_1 Z_{1i} + ... + \delta_m Z_{mi} + \delta_{m+1} W_{1i} + ... + \delta_{m+r} W_{ri} + e_i$, where the $e_i$ is the regression error term. Let $F$ denote the homoskedasticity-only F-statistic testing the hypothesis that $\delta_1 = ... = \delta_m = 0$. The overidentifying restrictions test statistic is $J = mF$. Under the null hypothesis that all the instruments are exogenous, if $e_i$ is homoskedastic, in large samples $J$ is distributed $\chi_{m-k}^2$, where $m-k$ is the “degree of overidentification,” that is, the number of instruments minus the number of endogenous regressors.

## Chapter 13 Experiments and Quasi-Experiments

**Program evaluation:**
The field of study that concerns estimating the effect of a program, policy, or some other intervention or “treatment”.

**Potential outcome:**
The outcome for an individual under a potential treatment.

**Average causal effect / Average treatment effect:**
The mean of the individual causal effects in the population under study.

**Differences estimator:**
The difference in the sample averages for the treatment and the control groups, which can be computed by regressing the outcome variable $Y$ on a binary treatment indicator $X$:
$$Y_i = \beta_0 + \beta_1 X_{1i} + u_i, i = 1, ..., n.$$

**Differences estimator with additional regressors:**
Including some control variables $W$ in the regression.
$$Y_i = \beta_0 + \beta_1 X_{1i} + \beta_2 X_{2i} + ... + \beta_{1+r} W_{ri} + u_i, i = 1, ..., n.$$

**Randomization based on covariates:**
Randomization in which the probability of assignment to the treatment group depends on one or more observable variables $W$.

**Test for random receipt of treatment:**
Entails testing the hypothesis that the coefficients on $W_{1i}, ..., W_{ri}$ are zero in a regression of $X_i$ on $W_{1i}, ..., W_{ri}$.

**Partial compliance:**
The failure of individuals to follow completely the randomized treatment protocol.

**Instrumental variables estimation of the treatment effect:**
Entails the estimation of $Y_i = \beta_0 + \beta_1 X_{1i} + u_i, i = 1, ..., n.$ or $Y_i = \beta_0 + \beta_1 X_{1i} + \beta_2 X_{2i} + ... + \beta_{1+r} W_{ri} + u_i, i = 1, ..., n.$ if there are control variables—using the initial random assignment ($Z_i$) as an instrument for the treatment actually received ($X_i$).

**Attrition:**
Subjects dropping out of the study after being randomly assigned to the treatment or the control group.

**Hawthorne effect:**
In experiments with human subjects, merely because the subjects are in an experiment can change their behaviour.

**Quasi-experiment / Natural experiment:**
Randomness is introduced by variations in individual circumstances that make it appear as if the treatment is randomly assigned.

**Differences-in-differences estimator with additional regressors:**
The average change in $Y$ for those in the treatment group, minus the average change in $Y$ for those control group.
$$\Delta Y_i = \beta_0 + \beta_1 X_{1i} + \beta_2 X_{2i} + ... + \beta_{1+r} W_{ri} + u_i, i = 1, ..., n.$$
The OLS estimator of $\beta_1$ in the equation.

**Repeated cross-sectional data:**
A collection of cross-sectional data sets, where each cross-sectional data set corresponds to a different time period.

**Regression discontinuity designs:**
Studies that exploit a discontinuity in the probability of receiving treatment at a threshold value.
Sharp regression discontinuity and Fuzzy regression discontinuity.

**Local average treatment effect (LATE):**
The weighted average causal effect that is estimated by TSLS.

_**THE END**_
