## Re: Validity, Bias, and Ethics
Before getting to the data and its analysis, 
let's review a few of the conceptual points that go into creation of an experiment: validity, bias, and ethics.

We probably don't have too much to worry about in terms of validity. 
For conceptual validity, the evaluation metrics are directly aligned with the experimental goals, 
no abstraction needed. Internal validity is maintained by performing an experiment with properly-handled randomization and controls. 
We don't really need to answer to external validity since we're drawing from the full site population and there's no other population we're looking to generalize to.

As for biases, we might think of novelty bias as being a potential issue. 
However, we don't expect users to come back to the homepage regularly. 
Downloading and license purchasing are actions we expect to only occur once per user, so there's no real 'return rate' to worry about. 
One possibility, however, is that if more people download the software under the new homepage, 
the expanded user base is qualitatively different from the people who came to the page under the original homepage. 
This might cause more homepage hits from people looking for the support pages on the site, 
causing the number of unique cookies under each condition to differ. 
If we do see something wrong or out of place in the invariant metric (number of cookies), 
then this might be an area to explore in further investigations.

Finally, for ethical issues, the changes to the homepage should be benign and present no risk to users. 
Our experiment objectives are also clearly stated. 
Considering the low risks of the experiment, informed consent is at worst a minor concern; 
a standard popup to let visitors know that cookies are used to track user experience on the site will likely suffice. 
The largest ethics principle we should be concerned about is data sensitivity. 
We shouldn't get any sensitive data out of the cookie assignment and collection, 
though some information will be collected from the user when they go to download the software.
No sensitive data is required for the metrics we've laid out, so what we should do is just aggregate daily visits, downloads, and purchase counts without looking at any individual outcomes.
