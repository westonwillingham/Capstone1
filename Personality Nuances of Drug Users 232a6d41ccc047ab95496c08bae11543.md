# Personality Nuances of Drug Users

### 🧐  In an online survey, individuals reported comprehensive personality metrics and their drug consumption levels for a wide array of drugs. What can we glean from these numbers that may provide insight into how personality can influence drug patterns, and perhaps how drug patterns influence personality? Can we find personality trends in users of specific drugs?

---

### How was this data collected?

It came from an online survey, taken over an 18 month period, using a snowball sampling methodology, where participants share [the study](https://www.researchgate.net/publication/318204156_The_Five_Factor_Model_of_Personality_and_Evaluation_of_Drug_Consumption_Risk) with other friends after completion.  Most of the participants came from the USA and UK, and most were of white ethnicity. Upon first glance, it seems that this sample population does more drugs than normal population samples. Over half of the sample has done a psychedelic drug, which is much higher than the estimated [10% of Americans](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3917651/) who have taken a psychedelic drug before in their lives. 

> This sample is not reflective of all people in the world, but it does help show how personality can be correlated to drug use patterns.

## Who participated?

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled.png)

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%201.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%201.png)

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%202.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%202.png)

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%203.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%203.png)

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%204.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%204.png)

## Personality Metrics

They measured seven indicators of personality.  In psychology, the widely accepted Five Factor Model (FFM) gives a comprehensive understanding of human personality and behavior trends.   These metrics include Neuroticism (N), Extraversion (E), Openness to Experience (O), Agreeableness (A), and Conscientiousness (C).  Other metrics included a measure of impulsiveness, and sensation seeking.  

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%205.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%205.png)

Descriptions of each personality metric 

## Drug Usage Metrics

Subjects were asked how frequently (if at all) they had taken a barrage of substances. The 18 drugs are the following:  alcohol, amphetamines, amyl nitrite, benzodiazepine, cannabis, chocolate, cocaine, caffeine, crack, ecstasy, heroin, ketamine, legal highs, LSD, methadone, magic mushrooms, nicotine and volatile substance abuse. It also included a fake drug, "Semeron" as a control to find dishonest and exaggerated consumption reports.  

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%206.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%206.png)

The graphs below show the distribution of when the users last used these drugs.  CL stands for "Consumption Level", and CL0 means they have never taken the drug, and CL6 means they had taken the drug within the day.  

---

## Drug Usage of the Sample

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%207.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%207.png)

## Initial Inquiries

- How many people in the sample have done each drug?
- How often do people do these drugs?
- How is psychedelic drug use correlated to personality metrics?
- Are there personality metrics that might correlate with susceptibility to addiction?

## Looking for Potential Correlations

For a variety of drugs, I looked to see if there were any correlations from plots.  I created series of plots that looked like this...

After plotting the distributions of personality scores for each drug consumption level, my attention was drawn to a few correlations in particular.  

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%208.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%208.png)

This plot shows the distributions of openness scores for individuals reporting different consumption levels. These "violin plots" are helpful in looking to see if the distributions are similar.   

> I generated 144 plots (8 factors * 18 drugs) and visually inspected them all. While most didn't show interesting patterns, there were a few that did.

# Chasing Correlations

### Are Psychedelics Correlated to Openness to Experience?

Psychedelic drugs have been found to correlate to (and perhaps cause) high measures of openness to experience.  People high in this measure have abstract thought patterns, value intellectual matters, are less moralistic, and more curious.     

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%209.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%209.png)

This graph, and the graph of Openness vs Mushrooms in the previous section showed me that there was probably a strong correlation between psychedelic use and openness to experience.  

### Could it be a coincidence? Let's hypothesis test this!

A hypothesis test is a statistical test that measures how likely it would be that the given difference between populations is just a matter of random variation. Its a measure of "what are the odds they aren't truly any different?". 

For this hypothesis test, I compared people who had taken a psychedelic drug at least once in their lives to  those who had not.  

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2010.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2010.png)

People in the sample who had taken mushrooms or acid, or both. 

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2011.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2011.png)

Plots showing that those who have tripped (orange area) have a higher mean openness score than those who have not.   

With the sample population split at nearly 50%, a two sample hypothesis test is performed on the openness scores of those who have tripped and those who have not.  

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2012.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2012.png)

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

# Do Psychedelics Curb Addiction to Hard Drugs?

[Recent research](https://www.scientificamerican.com/article/johns-hopkins-scientists-give-psychedelics-the-serious-treatment/) being done by NYU, Johns Hopkins, and Imperial College of London have shown strong potential in psychedelic therapy to break addictive habits, [including substance abuse problems.](https://www.cambridge.org/core/journals/the-british-journal-of-psychiatry/article/abs/controlled-study-of-lsd-treatment-in-alcoholism-and-neurosis/7DE568DA0939083E5598E69D64901A12)  As such, I tested it out with this dataset. 

### Does psychedelic use reduce your likelihood of drinking in the past day?

Alcohol, the deadliest drug in the United States, kills 88,000 people every year.   All other drug deaths amount to just 30,000.  I inquired, if you have tripped before in your life, are you more likely or less likely to drink tonight? 

I calculated the **conditional probability** that you drank alcohol in the past day, given that you have done psychedelics before. Contrary to my assumption, psychedelic users were 3% more likely to have drank. 

What if you were a conscientious psychedelic user? I found that if you were more consientious than average **and** you had tripped before, you still had a 6% higher chance of drinking alcohol that day.  

### What about meth?

Again, psychedelic use did not correlate to less meth consumption.  Given that you have taken psychedelics, you were 20% more likely to have consumed meth in the past week.  

### Coke?

Given that you have tripped in the past month, your odds of doing cocaine in the past week were 40% higher than those who had not tripped in the past month.  

> But does this mean anything?

It's hard to define any causal relationship between these because the data lacks a time series component.  It doesn't show one's relationship with a drug over time, it just shows a static representation of when they last consumed the drug. Doing psychedelic drugs is correlated to the use of other drugs. It would make sense that someone who has given up conventional notions of drug consumption would be curious to take others, or at least that the type of person who does drugs has done both. None of my data shows that psychedelics help people drink less, but my data is inconclusive.  

## What more correlations could exist?

Overwhelmed by the vast amount of potential correlations between drugs and personality metrics (144 to be exact), I visually plotted all of them and visually inspected these for trends. I did not find the level of statistical significance for these correlations. 

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2013.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2013.png)

### Given these potential correlations, what sticks out?

- Alcohol consumption was the only drug with a positive correlation to the amount of school somebody did
- Most drugs had a positive usage correlation to neuroticism, especially meth and heroin.
- Openness scores were similarly positively correlated, but it appeared that the highest correlations resided in drugs such as LSD, mushrooms, ecstasy, and cannabis.
- Agreeableness scores were negatively correlated with the use of most drugs, with the exceptions of extremely popular drugs like alcohol, caffeine, and nicotine.
- Conscientiousness scores were negatively correlated with nearly all drug usage.
- Extroversion had few correlations.  Frequent alcohol and ecstasy users were more extroverted than others, and mushrooms barely had a positive trend.  Meth and heroin were correlated with introversion, unlike any other drug.
- Sensation seeking was positively correlated to every drug except for caffeine, chocolate, and crack.  Crack didn't have many data points so it's hard to determine.
- Impulsiveness also strongly correlated to most drug usage, with the exception of a few popular drugs. Amphetamine usage was strongly correlated with impulsiveness, presumably due to ADHD medication prescriptions.

> Caveat: All of these trends were visually discerned from graphs and have not withstood rigorous statistical tests to find confidence levels. These results are exploratory in nature to incite further investigation.

## But wait, that's an Excel table!

The colored visualization above is generated from manually looking for trends in the categorical data and writing these trends in a format where I could generate colored numbers in Excel. It's not beautiful. 

> The table lacks information about the magnitude of the correlation and any measure of statistical significance...

I tried to rectify this, but it was not pretty.  I linearized the data, turning discrete categories of how recently a participant took the drug into how frequently they take it, extrapolated out from their consumption level.  A statistician would call this maneuver "hand-wavey", but it slightly helped me find numeric correlation values to compare.  

![Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2014.png](Personality%20Nuances%20of%20Drug%20Users%20232a6d41ccc047ab95496c08bae11543/Untitled%2014.png)

I began to find correlations using this method, but I soon stopped myself because I distrusted how I linearized the data.  The people who had taken the drug that day had a usage rate of 365 uses per 365 days, and this skewed the data a lot unnecessarily.  I don't believe that using a drug one year ago should have 365 times less of a weight than using it today.  For that purpose, I gave up trying to correlate this data using a linear method.  

# Next Steps

Obviously, the aforementioned trends have not been proven statistically significant and only represent and initial exploration into how personality may be correlated with drug use.  Next steps would include making the discrete categorical data values continuous and finding a correlation matrix. This would better justify conclusions made about personality indices correlating with drug use.  

## Caveat of the Data

This data is biased! Most of the people who took this survey were heavy drug users, and this population does not reflect the rest of the world. Yet, it does do a great job of showing how drugs users personality metrics all might line up.  Yet, I would only say that all of this could show correlation for American and British ethnically white people, as they represent the majority of the sample. If other populations used these drugs with different intentions, their personality metrics might correspond differently to their drug use.  For example, many indigenous populations of the world use psychedelic drugs for spiritual purposes. With great respect for these drugs, the personality types of the people who take these drugs might greatly differ than an American university student loosely taking them at a music festival.  

## Conclusions

What can we pull from this data? Can we predict your drug use given your personality?

I believe that I have a better idea of the typcial personality profiles of those who engage in these substances.  I found that people who did lots of amphetamines were more impulsive than the rest of the population. I even realized that alcohol drinkers were typically more educated! Overall, if you were a frequent drug user, of any of these drugs, you were more likely... 

- Less educated, agreeable, and conscientious
- More neurotic, open, sensation-seeking and impulsive

## Why does any of this matter?

If you are making conscious decisions about what drugs to introduce into your life, wouldn't you like to know what tendencies are correlated with these substances? 

During my freshman year of college, I drank incredulous amounts of coffee every day.  I subsequently developed anxious and neurotic patterns which resulted in my GPA dropping and my mental health plummeting.  I had no clue that such anxiety would be correlated with my caffeine consumption.  Once I understood how caffeine affected my mental health, I was able to get a better grip on my life. 

> If we truly understood trends of how drugs impacted our mental landscape, we might have a better chance in finding inner peace, conventional success, and mental patterns we can take ownership of.

While a drug may not "cause" you to change your personality, understanding what that drug is correlated with may give you a sense of whether that drug should play a role in your life.  Could it be that merely those with "high-drug-use-correlated" personality metrics take these drugs in the first place? I will keep mindfully exploring the world and get back to you on that one.