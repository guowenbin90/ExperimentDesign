## Types of Study
There are many ways in which data can be collected in order to test or understand the relationship between two variables of interest. 
These methods can be put into three main bins, based on the amount of control that you hold over the variables in play:

If you have a lot of control over features, then you have an experiment.
If you have no control over the features, then you have an observational study.
If you have some control, then you have a quasi-experiment.
While the experiment is the main focus of this course, 
it's also useful to know about the other types of study so that you can use them in effective ways, 
especially if an experiment cannot be run.

## Experiments
In the social and medical sciences, an experiment is defined by comparing outcomes between two or more groups, 
and ensuring equivalence between the compared groups except for the manipulation that we want to test. 
Our interest in an experiment is to see if a change in one feature has an effect in the value of a second feature, like seeing if changing the layout of a button on a website causes more visitors to click on it. Having multiple groups is necessary in order to compare the outcome for when we apply the manipulation to when we do not (e.g. old vs. new website layout), or to compare different levels of manipulation (e.g. drug dosages). We also need equivalence between groups so that we can be as sure as possible that the differences in the outcomes were only due to the difference in our manipulated feature.

Equivalence between groups is typically carried out through some kind of randomization procedure. 
A unit of analysis is the entity under study, like a page view or a user in a web experiment. 
If we randomly assign our units of analysis to each group, then on the whole, 
we should expect the feature distributions between groups to be about the same. 
This theoretically isolates the changes in the outcome to the changes in our manipulated feature. 
Of course, we can always dig deeper afterwards to see if certain other features worked in tandem with, or against, our manipulation.

## Observational Studies
In an experiment, we exert a lot of control on a system in order to narrow down the changes in our system from one source to one output. 
Observational studies, on the other hand, are defined by a lack of control. Observational studies are also known as naturalistic or correlational studies. 
In an observational study, no control is exerted on the variables of interest, perhaps due to ethical concerns or a lack of power to enact the manipulation. 
This often comes up in medical studies. For example, if we want to look at the effects of smoking on health,
the potential risks make it unethical to force people into smoking behaviors. Instead, we need to rely on existing data or groups to make our determinations.

We typically cannot infer causality in an observational study due to our lack of control over the variables. 
Any relationship observed between variables may be due to unobserved features, or the direction of causality might be uncertain. 
(We'll discuss this more later in the lesson.) 
But simply because an observational study does not imply causation does not mean that it is not useful. 
An interesting relationship might be the spark needed to perform additional studies or to collect more data. 
These studies can help strengthen the understanding of the relationship we're interested in by ruling out more and more alternative hypotheses.

## Quasi-Experiments
In between the observational study and the experiment is the quasi-experiment. 
This is where some, but not all, of the control requirements of a true experiment are met. 
For example, rolling out a new website interface to all users to see how much time they spend on it might be considered a quasi-experiment. 
While the manipulation is controlled by the experimenter, there aren't multiple groups to compare. 
The experimenter can still use the behavior of the population pre-change and compare that to behaviors post-change, to make judgment on the effects of the change. 
However, there is the possibility that there are other effects outside of the manipulation that caused the observed changes in behavior. For the example earlier in this paragraph, it might be that users would have naturally gravitated to higher usage rates, regardless of the website interface.

As another example, we might have two different groups upon which to make a comparison of outcomes, 
but the original groups themselves might not be equivalent. 
A classic example of this is if a researcher wants to test some new supplemental materials for a high school course. 
If they select two different schools, one with the new materials and one without, 
we have a quasi-experiment since the differing qualities of students or teachers at those schools might have an effect on the outcomes. 
Ideally, we'd like to match the two schools before the test as closely as possible, 
but we can't call it a true experiment since the assignment of student to school can't be considered random.

While a quasi-experiment may not have the same strength of causality inference as a true experiment, 
the results can still provide a strong amount of evidence for the relationship being investigated. 
This is especially true if some kind of matching is performed to identify similar units or groups. 
Another benefit of quasi-experimental designs is that the relaxation of requirements makes the quasi-experiment more flexible and easier to set up.
