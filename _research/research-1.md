---
layout: archive
title: "Advanced Analytics"
excerpt: "I use advance multilevel statistical modeling in my research.<br/><img src='/images/YouthMentalHealth.svg'>"
collection: research
---

# <span style="color:darkred">Mental health disparities among US high school students at the intersection of race, gender, and sexual orientation.</span> 

![YouthMentalHealth](/images/YouthMentalHealth.png)


I was the lead investigator implementing multilevel modeling approaches to examine intersectional health inequities using I-MAIHDA (intersectional multilevel analysis of individual heterogeneity and discriminatory accuracy).


<p style="margin-bottom:1.6em"><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Mental Health</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Health Equity</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Public Health</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Multilevel Modeling</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Survey Data</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">R</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Shiny</span></p>

Studying one identity dimension at a time averages away the groups most affected. But
splitting a survey 40 ways produces cells too small for conventional stratified analysis
to say anything reliable about.

**Intersectional Multilevel Analysis of Individual Heterogeneity and Discriminatory
Accuracy (I-MAIHDA)** resolves the tension. By treating intersectional strata as random
effects rather than fixed ones, it borrows strength across strata: estimates for small
cells shrink toward the grand mean in proportion to their imprecision, so you get stable
estimates for all 40 combinations instead of noisy ones for a few and nothing for the
rest. It also partitions how much of the variation is additive versus genuinely
interactive — which turns "does intersectionality matter here?" from a theoretical
argument into a measurable quantity.

I applied this to suicidal ideation among U.S. high school students in the CDC's Youth
Risk Behavior Survey, across **40 combinations of race, gender, and sexual orientation**,
comparing waves before and after 2020. The results showed a considerably more nuanced
pattern than single-axis analyses had suggested, and identified which groups absorbed
the most of the 2020 disruption.

Related work extended the framework to examine how **state-level policy environments**
shape youth mental health outcomes across intersecting identities.

### Making it usable

Methods papers get cited; tools get used. I built and deployed an
**[interactive Shiny application](https://junaidmerchant.shinyapps.io/YRBSS_MAIHDA/)**
so researchers, policymakers, journalists, and advocacy organizations can explore the
intersectional estimates directly — no statistical training and no model fitting
required.

[Intersectional Youth Mental Health Interactive (preview):](https://junaidmerchant.shinyapps.io/YRBSS_MAIHDA/)

### Publication

Merchant, J. S., Nguyen, T. T., Makres, K., & Evans, C. R. (2025). Intersectional
inequities in suicide ideation by race, sexual orientation, and gender among US high
school students in the pre- and post-2020 waves of the YRBSS: an application of random
effects intersectional MAIHDA. *American Journal of Epidemiology, 194*(9), 2540–2552.
[doi:10.1093/aje/kwaf114](https://doi.org/10.1093/aje/kwaf114)

*Published in a special issue on methods in social epidemiology.*


# <span style="color:darkred">Intersectional Differences in Cognitive Aging Trajectories.</span> 

Currently working on expanding the I-MAIHDA approach to examine longitudinal cognitive aging data in the Health and Retirement study data. So far, we're finding differences in the onset of dimentia between the ages of 70-75 at the intersection of race, gender, and education.  

![CognitiveAgingTrajectories](/images/CognitiveAgingTrajectories.png)

