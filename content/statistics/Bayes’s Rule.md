# Bayes’s Rule
#bpt/statistics
- - -
### A Quick and Dirty Approach
To calculate the posterior odds of an event, we need to multiply the prior odds by the likelihood ratio. 
> Recall that the positive likelihood ratio is the rate of test positive individual in the truly positive cohort to the ratio of test positive individuals in the truly negative cohort, i.e. $Sensitivity / (1 - Specificity)$

A worked example:
*A new D-dimer assay has a sensitivity for deep venous thrombosis (DVT) of 95% and a specificity of 50%. It is proposed to use it to screen a group of passengers after long distance travel. Previous data have suggested this group has a pre-test probability of DVT of 1%.
What is the best estimate of the post-test odd of DVT in an individual with a positive D-dimer result?*

1. Prior odds = pre-test probability: in this case, the population prevalence of DVT is 1%, and so we have a prior odds of having a DVT of 1:99
2. Likelihood ratio: in this case 95% of individuals with a DVT will test positive, while 50% of those who do not have a DVT will test negative (i.e. 50% of those who do not have a DVT will test positive), which can be represented as a ratio as 95:50 = 19:10
3. Posterior odds = prior odds * LR+ = (1:99) * (19:10) = (19:990) = 19/1009, which for simplicity’s sake we can approximate to 2%

This suggests that the post-test probability of having a DVT in a patient in this cohort who tests positive is 2%.
- - -
