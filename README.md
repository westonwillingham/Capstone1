# Personality Nuances of Drug Users

### 🧐  In an online survey, individuals reported comprehensive personality metrics and their drug consumption levels for a wide array of drugs. What can we glean from these numbers that may provide insight into how personality can influence drug patterns, and perhaps how drug patterns influence personality? Can we find personality trends in users of specific drugs?

---

### How was this data collected?

It came from an online survey, taken over an 18 month period, using a snowball sampling methodology, where participants share [the study](https://www.researchgate.net/publication/318204156_The_Five_Factor_Model_of_Personality_and_Evaluation_of_Drug_Consumption_Risk) with other friends after completion.  Most of the participants came from the USA and UK, and most were of white ethnicity. Upon first glance, it seems that this sample population does more drugs than normal population samples. Over half of the sample has done a psychedelic drug, which is much higher than the estimated [10% of Americans](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3917651/) who have taken a psychedelic drug before in their lives. 

> This sample is not reflective of all people in the world, but it does help show how personality can be correlated to drug use patterns.

## Who participated?

![Images/Untitled.png]
(Images/Untitled.png)

![Images/Untitled%201.png]
(Images/Untitled%201.png)

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%202.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%202.png)

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%203.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%203.png)

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%204.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%204.png)

## Personality Metrics

They measured seven indicators of personality.  In psychology, the widely accepted Five Factor Model (FFM) gives a comprehensive understanding of human personality and behavior trends.   These metrics include Neuroticism (N), Extraversion (E), Openness to Experience (O), Agreeableness (A), and Conscientiousness (C).  Other metrics included a measure of impulsiveness, and sensation seeking.  

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%205.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%205.png)

Descriptions of each personality metric 

## Drug Usage Metrics

Subjects were asked how frequently (if at all) they had taken a barrage of substances. The 18 drugs are the following:  alcohol, amphetamines, amyl nitrite, benzodiazepine, cannabis, chocolate, cocaine, caffeine, crack, ecstasy, heroin, ketamine, legal highs, LSD, methadone, magic mushrooms, nicotine and volatile substance abuse. It also included a fake drug, "Semeron" as a control to find dishonest and exaggerated consumption reports.  

---

## Drug Usage of the Sample

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%206.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%206.png)

## Initial Inquiries

- How many people in the sample have done each drug?
- How often do people do these drugs?
- How is psychedelic drug use correlated to personality metrics?
- Are there personality metrics that might correlate with susceptibility to addiction?

## Looking for Potential Correlations

For a variety of drugs, I looked to see if there were any correlations from plots.  I created series of plots that looked like this...

After plotting the distributions of personality scores for each drug consumption level, my attention was drawn to a few correlations in particular.  

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%207.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%207.png)

This plot shows the distributions of openness scores for individuals reporting different consumption levels. These "violin plots" are helpful in looking to see if the distributions are similar.   

> I generated 144 plots (8 factors * 18 drugs) and visually inspected them all. While most didn't show interesting patterns, there were a few that did.

# Chasing Correlations

### Are Psychedelics Correlated to Openness to Experience?

Psychedelic drugs have been found to correlate to (and perhaps cause) high measures of openness to experience.  People high in this measure have abstract thought patterns, value intellectual matters, are less moralistic, and more curious.     

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%208.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%208.png)

This graph, and the graph of Openness vs Mushrooms in the previous section showed me that there was probably a strong correlation between psychedelic use and openness to experience.  

### Could it be a coincidence? Let's hypothesis test this!

A hypothesis test is a statistical test that measures how likely it would be that the given difference between populations is just a matter of random variation. Its a measure of "what are the odds they aren't truly any different?". 

For this hypothesis test, I compared people who had taken a psychedelic drug at least once in their lives to  those who had not.  

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%209.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%209.png)

People in the sample who had taken mushrooms or acid, or both. 

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2010.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2010.png)

Plots showing that those who have tripped (orange area) have a higher mean openness score than those who have not.   

With the sample population split at nearly 50%, a two sample hypothesis test is performed on the openness scores of those who have tripped and those who have not.  

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2011.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2011.png)

This is the distribution of the difference in mean openness scores, assuming no difference in population mean.  The vertical line on the far right represents how much of an outlier it would be that the two populations had the same openness score.  

The hypothesis test rejects the null hypothesis with a p-value of nearly zero, 1.9e-59 to be precise...

> Therefore, I am positive that there is a non-negligible difference in openness score means between the two samples

This concludes that it would be virtually impossible for the difference in openness scores to be just random variation, implying definite correlation between openness and psychedelic use.  

## Further correlations with psychedelics?

I did more hypothesis testing to find that with near certainty, psychedelic use is correlated with personality in the following ways... 

- Psychedelic users had higher degrees of **openness to experience, impulsiveness, sensation seeking, neuroticism** (all p-values < 0.005)
- They had lower measures of **agreeableness** and **conscientiousness**
- Psychedelic users also were slightly **more introverted**, but only with a p-value of 0.226

### Why?

- These are correlations, and causation can only be speculated from afar.
- Researchers have found that psychedelics change people's **openness to experience**
- 
- Other metrics may explain why psychedelic users are prone to trip in the first place, with lower degrees of **agreeableness** contributing to their willingness to follow conventional rules.

## If you have tripped once, does that mean anything? What about people who have tripped in the past month?

The same tests were performed for people who had tripped within the past month.  Here is what I found. 

- Frequent psychedelic users still had more **openness to experience, impulsiveness, and sensation seeking.** They were still less **conscientious,** and less **agreeable. Same results.**
- Yet, for those who had tripped within the past month, there was no discernible correlation of **neuroticism** nor **extroversion.**
- It seems that people who have tripped once are more neurotic than those who hadn't, but those who had tripped in the past month were no more neurotic than others.

### What about those who had tripped in the past week?

- These people had even higher measures of openness to experience, impulsiveness, sensation seeking and were less conscientious.

---

---

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2012.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2012.png)

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2013.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2013.png)

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2014.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2014.png)

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2015.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2015.png)

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2016.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2016.png)

The graphs below show the distribution of when the users last used these drugs.  CL stands for "Consumption Level", and CL0 means they have never taken the drug, and CL6 means they had taken the drug within the day.  

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2017.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2017.png)
