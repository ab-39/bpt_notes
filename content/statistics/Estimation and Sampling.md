# Estimation and Sampling
#bpt/statistics
- - -
### Overall
Given that we can almost never test the entire population for a given condition or phenomenon, we have to make do with smaller samples. The question, then, is how well these samples reflect the larger population. In statistics, we approach this by trying to consider _how_ the sampling would play out if it were taken multiple times. Repeating the test multiple times will yield a distribution, from which we can draw inferences about the truth. 

We need to know a few definitions:
- $σ$ = standard deviation of the population
- $n$ = sample size 
- Standard error = the standard deviation _of the sampling distribution_ -> informs us about the precision of the estimate:
  - $=σ/\sqrt{n}$ 

This information culminates in [[the central limit theorem]], which tells us that the *distribution of means* from samples of size **n**, obtained from a population with mean **µ** and standard deviation **σ** will be approximately normal, with the same mean as the population (i.e. µ) and standard deviation equal to **σ/√n**. In other words, when we take a sample _of samples_, the true value of the mean will lie within two standard errors of the mean 95% of the time. 
- - -
