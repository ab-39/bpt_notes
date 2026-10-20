# Approach to Diagnostic Tests
#bpt/statistics
- - -
### Overview
Fundamentally, we want a diagnostic test to do two things:
- _Be positive_ if they _have_ the disease = sensitivity = true positive rate 
- _Be negative_ if the _do not have_ the disease = specificity = 1 — false positive rate 

This gives us our first two parameters for interpreting diagnostic tests. There are a few key points to consider with these two constructs:
- They reference the _truth_ (actual disease state) as the standard against which they are calculated
- In terms of Bayesian inference, these give a probability of a test outcome _conditional on_ disease state 
- They are _unaffected_ by disease prevalence -> these are properties of the _test_ 

> [!NOTE] Definitions:
> 1. Sensitivity = the proportion of people _with the disease_ who return a positive result for it on a given test 
> 2. Specificity = the proportion of people _free from the disease_ who return a negative result on a given test 

When we actually run a test on a patient, however, we want to know two things:
- What the likelihood is that a positive result truly represents having the disease = positive predictive value
- What the likelihood is that a negative result truly represents _not_ having the disease = negative predictive value

This gives us our next two parameters for interpreting diagnostic tests. Again, consider:
- These reference _the test result_ as the standard against which they are calculated
- In terms of Bayesian inference, these give a probability of a disease state _conditional_ on test outcome  
- These _are_ affected by disease prevalence -> these are properties of the test _in a specific population context_ 

> [!NOTE] Definitions
> 1. Positive predictive value = the proportion of people _with a positive test result_ who actually have the disease
> 2. Negative predictive value = the proportion of people _with a negative test result_ who actually do not have the disease 

#### The Likelihood Ratio
The likelihood ratio allows us to synthesise the information given by the prevalence (prior odds of a disease), sensitivity, and specificity, to arrive at a post-test estimate (posterior odds). The positive likelihood ratio is defined as:
$LR+ = (True Positive Fraction) / (False Positive Fraction) =  (Sensitivity) / (1 - Specificity)$ 

The product of the prior odds and the positive likelihood ratio gives the post-test likelihood. At its simplest, this is an application of [[Bayes’s Rule]]. Similarly, the negative liklihood ratio uses the same information, formatted slightly differently, to draw similar conclusions for a negative test:
 $LR- = (True Negative Fraction) / (False Negative Fraction) =  (Specificity) / (1 - Sensitivity)$

#### Continuous Diagnostic Tests
While the above takes a binary categorical approach to tests, the reality is that most diagnostic tests have their values drawn from large populations which are used to define normal (usually the 95% confidence intervals) and abnormal. These are then _used_ to create categories. Changing the thresholds for these definitions _change our test parameters_:
- Increasing the threshold for a positive test:
  - Specificity increases
  - Sensitivity decreases
- Decreasing the threshold for a positive test:
  - Specificity decreases
  - Sensitivity increases 

#### Receiver Operating Characteristic Curves 
These allow us to incorporate the data from sensitivity and specificity _at a range_ of cutoff levels to gain a higher-level overview of how the test works. Plotting the sensitivity vs (1 — specificity) yields:
![](Approach%20to%20Diagnostic%20Tests/image.png)
Simplified, an ROC curve that has values clustered in the top-left quadrant of the graph is able to combine sensitivity and specificity. This information can be summarised using the area under the curve - the higher the AUC, the better the test. 
- - -
