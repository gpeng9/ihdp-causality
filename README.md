# ihdp-causality

The purpose of this project is to apply a treatment effect estimator to a dataset provided from the Infant Health and Development Program (IHDP). The estimator will help determine the causal effect of intensive high-quality childcare from a trained provider (the treatment) on the cognitive test scores of premature infants (the outcome).

The code simply fits a logistic regression model on the data and uses it to predict the treatment (x) from the outcomes (z) and estimate the treatment effect quantitatively. The estimates will show whether there is beneficial causal effect on the outcome. The formula used is
