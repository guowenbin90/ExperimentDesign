## Checking Bias
Biases in experiments are systematic effects that interfere with the interpretation of experimental results, 
mostly in terms of internal validity. 
Just as humans can have a lot of different biases, 
there are numerous ways in which an experiment can become unbalanced.

### Sampling Bias
Many experimental biases fall under the sampling bias umbrella. Sampling biases are those that cause our observations to not be representative of the population. For example, if assignment to experimental groups is done in an arbitrary fashion (as opposed to random assignment or matched groups), we risk our outcomes being based less on the experimental manipulation and more on the composition of the underlying groups.

Studies that use surveys to collect data often have to deal with the self-selection bias. The types of people that respond to a survey might be qualitatively very different from those that do not. A straight average of responses would not necessarily reflect the feelings of the full population; weighting responses based on the differences between the observed responses and properties of the target population may be needed to come to reasonable conclusions.

One type of sampling bias related to missing data is the survivor bias. Survivor bias is one where losses or dropout of observed units is not accounted for in an analysis. A key example of this was in British World War II operations research, where engineers avoided using survivor bias when they considered where to add armor to their planes. Rather than add armor to the spots where returning planes had bullet holes, armor was added to the spots where the planes didn't have bullet holes. That's because the planes that took shots to those places probably crashed, due to those locations being more vital for maintaining flight, so they didn't "survive" and weren't available for observation.

### Novelty Bias
A novelty effect is one that causes observers to change their behavior simply because they're seeing something new. We might not be able to gauge the true effect of a manipulation until after the novelty wears off and population metrics return to a level that actually reflects the changes made. This will be important for cases where we want to track changes over time, such as trying to get users to re-visit a webpage or use an app more frequently. Novelty is probably not a concern (or perhaps what we hope for) when it comes to manipulations that are expected to only have a one-shot effect.

### Order Biases
There are a couple of biases to be aware of when running a within-subjects experiment. Recall that in a within-subjects design, each participant performs a task or makes a rating in multiple experimental conditions, rather than just one. The order in which conditions are completed could have an effect on participant responses. A primacy effect is one that affects early conditions, perhaps biasing them to be recalled better or to serve as anchor values for later conditions. A recency effect is one that affects later conditions, perhaps causing bias due to being fresher in memory or task fatigue.

An easy way of getting around order biases is to simply randomize the order of conditions. If we have three conditions, then each of the six ways of completing the task (ABC, ACB, BAC, BCA, CAB, CBA) should be equally likely. While there still might end up being order effects like carry-over effects, where a particular condition continues to have an effect on future conditions, this will be much easier to detect than if every participant completed the task in the exact same order of conditions.

### Experimenter Bias
One bias to watch out for, especially in face-to-face experiments, is the experimenter bias. This is where the presence or knowledge of the experimenter can affect participants' behaviors or performance. If an experimenter knows what condition a participant is in, they might subtly nudge the participant towards their expected result with their interactions with the participant. In addition, participants may act differently in the presence of an experimenter, to try and act in the 'right' way – regardless of if a subject actually knows what the experimenter is looking for or not.

This is where design steps like blinding are important. In blinding, the administrator of a procedure or the participant do not know the condition being used, to avoid that subconscious bias from having an effect. In particular, the double-blind design hides condition information from both the administrator and participant in order to have a strong rein on experimenter-based biases.
