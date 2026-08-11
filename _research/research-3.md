---
layout: archive
title: "Social Epidemiology"
excerpt: "Investigating social determinents of health using a combination of public health and new media data sources.<br/><img src='/images/BD4HE_Banner_Top.png'>"
collection: research
---

# <span style="color:darkred">Research Faculty/Data Scientist · #BigData4HealthEquity</span> 

![Big Data for Health Equity](/images/BD4HE_Banner_Top.png)

Through my work with the Big Data for Health Equity team, I have gained considerable experience with large-scale data management and analytics using public health data from the CDC and NIH, as well as new media data sources.  I've integrated diverse data sources and used multilevel modeling approaches to examine intersectional health inequities. I'm also involved in research that is developing used novel machine learning approaches to derive public sentiment measures from social media data to use as social-contextual measures to investigate health disparities.




## <span style="color:darkred">Social Media Sentiment as a Contextual Health Exposure</span>

![Racial Sentiment](/images/Epidemiology_2024_Figure2.png)

<p style="margin-bottom:1.6em"><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Health Equity</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Public Health</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Machine Learning</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Natural Language Processing</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Open Science</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Social Media</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Vital Statistics</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">Python</span><span style="display:inline-block;font-size:0.78em;padding:2px 9px;margin:0 4px 5px 0;border-radius:99px;border:1px solid #c3c2b7;color:#52514e;text-decoration:none;white-space:nowrap">R</span></p>

Survey measures of population attitudes are expensive, infrequent, and coarse in geography. That makes them awkward as an exposure variable in health research, where you often want to know what the social environment looked like in a particular place at a particular time.

Our group developed an alternative: derive area-level, time-resolved sentiment measures from social media at scale. The pipeline collects topic-referencing posts, applies machine learning sentiment classification, and aggregates to geographic and temporal units that can be joined to health data. We published the method with **full technical guidance and code** so other groups could replicate it rather than rebuild it — the point was to make the approach usable, not to hold it.

1. Nguyen, T. T., **Merchant, J. S.**, Makres, K., Dennard, E., Criss, S., & Nguyen, Q. C. (2026). SOCIAL MEDIA AND MENTAL HEALTH. From Posts to Patterns: Using Social Media to Investigate Drivers of Population Health, 146.
1. Nguyen, T. T., **Merchant, J. S.**, Yue, X., Mane, H., Wei, H., Huang, D., ... & Nguyen, Q. C. (2024). A Decade of Tweets: Visualizing Racial Sentiments Towards Minoritized Groups in the United States Between 2011 and 2021. *Epidemiology*, *35*(1), 51-59.
1. Nguyen, T. T., Yue, X., Mane, H., Seelman, K., ... **Merchant, J. S.**, ... & Nguyen, Q. C. (2025). Decoding digital discourse through multimodal text and image machine learning models to classify sentiment and detect hate speech in race-and lesbian, Gay, bisexual, transgender, queer, intersex, and asexual community–related posts on social media: Quantitative study. Journal of Medical Internet Research, 27, e72822.


**What it was used for:**


### <span style="color:darkred">Race Disparities in Maternal Health and Birth Outcomes</span>

**Birth outcomes.** As lead analyst, I linked area-level racial sentiment to ten years of National Vital Statistics System natality records. Racially minoritized mothers living in areas with higher measured racial animosity showed elevated rates of preterm birth and low birth weight, after adjustment for individual risk factors and census-tract covariates. We uncovered increased incidence of pre-term birth, low-birth weight, and maternal hypertension among racially minoritized mothers living in areas with higher racial animosity across ten years of National Vital Statistics System Natality (NVSS-N) data. I also was involved in qualitative content analysis of focus groups of racially diverse mothers about their experiences with maternal health care.

1. Drew, L. B., **Merchant, J.**, Thoma, M. E., Mane, H., Yue, X., & Nguyen, T. T. (2026). The association between state-level negative racial sentiment and maternal hypertension in the US from 2016 to 2021: An observational study using Twitter data. PLoS One, 21(4), e0346564.
1. Nguyen, T. T., Criss, S., Kim, M., De La Cruz, M. M., Thai, N., **Merchant, J. S.**, ... & Nguyen, Q. C. (2023). Racism during pregnancy and birthing: experiences from Asian and Pacific Islander, Black, Latina, and Middle Eastern women. *Journal of Racial and Ethnic Health Disparities*, 10(6), 3007-3017.
1. Nguyen, T. T., **Merchant, J. S.**, Criss, S., Makres, K., Gowda, K. N., Mane, H., ... & Allen, A. M. (2023). Examining Twitter-Derived Negative Racial Sentiment as Indicators of Cultural Racism: Observational Associations With Preterm Birth and Low Birth Weight Among a Multiracial Sample of Mothers, 2011-2021. *Journal of Medical Internet Research*, 25, e44990.
1. Nguyen, T. T., Criss, S., Kim, M., De La Cruz, M. M., Thai, N., **Merchant, J. S.**, ... & Nguyen, Q. C. (2022). Racism during pregnancy and birthing: experiences from Asian and Pacific Islander, Black, Latina, and Middle Eastern women. *Journal of Racial and Ethnic Health Disparities*, 1-11.


**Hate crimes.** A related analysis tracked Twitter sentiment against reported anti-Asian
hate crimes in New York City across 2019–2022, spanning the pandemic.

**Health messaging.** Further work examined exposure to partisan news content and hate
speech in relation to racial and ethnic health disparities, and changes in online Jewish
discourse around real-world events.
