## Types of Sampling
While web and other online experiments have an easy time collecting data, 
collecting data from traditional methods involving real populations is a much more difficult proposition. 
If you need to perform a survey of a population, 
it could be unreasonable in both time and money costs to try and collect thoughts from every single person in the population. 
This is where sampling comes in. 
The goal of sampling is to only take a subset of the population, 
using the responses from that subset to make an inference about the whole population. 
Here, we'll cover two basic probabilistic techniques that are commonly used.

The simplest of these approaches is **simple random sampling**. 
In a simple random sample, each individual in the population has an equal chance of being selected. 
We just randomly make draws from the population until we have the sample size desired; 
your sample size depends on the level of uncertainty you are willing to have about the collected data. 
Since everyone has an equal chance of being drawn, 
we can expect the feature distribution of selected units to be similar to the distribution of the population as a whole. 
In addition, a simple random sample is easy to set up.

However, it is possible that certain groups are underrepresented in a simple random sample, 
especially those that make up a low proportion of the population. 
If there are certain rarer subgroups of interest, 
it can be worth adding one additional step and performing **stratified random sampling**. 
In a stratified random sample, we need to first divide the entire population into disjoint groups, or strata. 
That is, each individual must be a part of one group, and only one group. 
For example, you could divide people by gender (male, female, other), or age (e.g. 18-25, 26-35, etc.).

Then, from each group, you take a simple random sample. 
In a proportional sample, the sample size is proportional to how large the group is in the full population. 
For example, if you require 1000 data points, and stratified individuals of proportion {0.5, 0.3, 0.2}, 
then you would take 500 people from the first group, 300 from the second, and 200 from the third. 
This guarantees a certain level of knowledge from each subset, and theoretically a more representative overall inference on the population.

An alternative approach is to take a nonproportional sample from each group. 
For example, we could simply sample 500 people from each group. 
Computing the overall statistics in this case requires weighting each group separately, 
but this extra effort offers a higher understanding of each subgroup in a deeper investigation.
