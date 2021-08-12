# Bayes posterior analysis to simulate digital marketing click rate

See Juputer notebook for details. 

## Analysis Goal

We are running a digitial marketing campaign for a client. 
Our main metrics are number of clicks, number of impressions, money spent on impressions (cost).

After 11 days we would like to assess our metrics and decide whether it would pay off to spend additional money. 

### Baseline posteriors analysis

We will use the data observed after 11 days to get the posterior distribution for each metric. This will tell us, if we keep the campaign parameters unchanged, what to expect at the end of the campaign. 

### Posterior comparative analysis

We want to simulate 2 scenarios:
- scenario 1: Impressions increase by 10% with additional money spent, we simulate 5% increase in CTR
- scenario 2: Impressions increase by 10%, we simulate 10% increase in CTR

Then we do posterior distribution analysis between the base and the two scenarios.

### Conclusion

We want to recommend whether it is worth while for the client to increase spending on the current running campaign. 

- 5% CTR increase is on average 3.25 clicks greater than base with probability 93.15% at average cost of R9.18 per day, given that 10% increase in Impressions produces 5% increase in CTR

- 10% CTR increase is on average 4.17 clicks greater than base with probability 97.99% at average cost of R9.17 per day, given that 10% increase in Impressions produces 10% increase in CTR

- 10% CTR increase is on average 2.17 clicks greater than 5% increase with probability 69.98% at average cost of R9.17 per day, given that 10% increase in Impressions produces 5-10% increase in CTR
