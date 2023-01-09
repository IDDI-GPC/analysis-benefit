# Introduction

The core idea of GPC is to allow patients and clinicians to elicit among the outcomes of the trial, an order of importance that is most relevant to them. The outcomes can be of any type (categorical, continuous, or time-to-event), and can include efficacy, toxicity, quality of life, or cost-related information.
Once the order of preferences has been established, the GPC procedure operates in the following way:

1. Pairs are formed for the trial data between all patients of the control arm and all patients of the experimental arm.

2. Each pair is compared on the first priority:

	a) If the outcome is more favorable for the patient in the experimental arm, the pair is declared a "win".

	b) If the outcome is more favorable for the patient in the control arm, the pair is declared a "loss".

	c) If no patient is favored because the outcomes are either equal, or not different enough for proclaiming a clinically relevant winner, the pair is declared a "tie".

3. Pairs that are ties on the first priority, are subsequently compared on the second priority in an attempt to classify them as wins, losses or ties again.

4. This recursive classification is operated until either all pairs are classified as wins or losses, or all outcomes have been investigated following the choice of priorities.

# References

* Buyse M. Generalized pairwise comparisons of prioritized outcomes in the two-sample problem. Stat Med. 2010 Dec 30;29(30):3245-57. [doi: 10.1002/sim.3923](http://doi.org/10.1002/sim.3923).
(PDF available <a href="../pdfs/2010_Buyse.pdf" target="_blank">here</a>.)
																								