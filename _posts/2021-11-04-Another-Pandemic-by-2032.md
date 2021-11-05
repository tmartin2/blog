---
layout: post
title: "Rough Estimate: Another Deadly Pandemic by 2032"
date: 2021-11-05 14:28:44 -0000
---

__Note__: This is a question I was given on a test task after applying to a fellowship on AI policy (not the same occupational entity as in [Delaying Transformative AI](https://tmartin2.github.io/blog/2021/09/16/Delaying-Transformative-AI.html)). I spent roughly an hour writing my response. Here is the question: 

_What is the likelihood that at least one single new pandemic (not SARS-CoV-2 or variants) causes >=0.04% of world population to die within a one year period (as measured by the official reported death toll, not excess deaths) by 2032 Jan 1? Why do you give that answer? What factors are important?_

Here is my answer. As with my [AI regulation post](https://tmartin2.github.io/my-blog/2021/11/04/US-Europe-AI-regulation.html), I describe criticisms of my responses at the end, and detail some considerations that I missed in my initial response.

## My Response

(*) BR := Base Rate, ED := Estimated, MT := Meta, FST := For Sake of Time (time limit for this task)

___Main Considerations___
- BR: Occurrence of natural pandemics
- BR: Duration of natural pandemics
- BR: Lethality of natural pandemics
- BR: Transmissibility of natural pandemics
- BR: Vaccination rate for natural pandemics
- BR: Efficacy of vaccination for natural pandemics
- ED: Occurrence of human-engineered pandemics
- ED: Duration of human-engineered pandemics
- ED: Lethality of human-engineered pandemics
- ED: Transmissibility of human-engineered pandemics
- ED: Future vaccination rates + efficacy for any pandemic  
- MT: How all of the above values change over time

___Other Considerations___
- Activity (priming) of SARS-CoV-2 response infrastructure between 2022-2032
- Improved government responses to pandemics following SARS-CoV-2
- Improved population (mask wearing, social isolation) behavior to SARS-CoV-2 pandemic
- Global population fluctuations (what will 0.04% be in 2022, 2023, …, 2032?)
- Global population densities (how clustered people are)
- Global population migration patterns
- MT: The above characteristics but for the initial onset region, i.e. where the pandemic begins (death toll of pandemic likely has high sensitivity to initial conditions)

___Likelihood Estimate___

While I could parse out each consideration in detail, I opt to perform a more rudimentary analysis, given the time constraints.

NCBI “Pandemics Through History” (abbr. PTH) (1) gives 18 major pandemics since 541 AD, which means (2022-541) / 18 = ~82.3 avg. years per pandemic. However, 16 of those 18 pandemics have occurred since 1817, which means that the avg. years between pandemics (in more recent times) is actually closer to (2022-1817) / 16 = ~12.8 years, which FST is around 10 years. So, there is approximately a 50% chance that a natural pandemic occurs (if this seems too high, check the PTH list for pandemics in the the last 20 years) before 2032, under these assumptions.

OurWorldInData (2) estimates the human population at the start of 2022 to be ~7.79 billion and in 2032 to be ~8.69 billion. In 2022, 0.04%(7.79b) = ~3.12 million people, and in 2032, 0.04%(8.69b) = ~3.48 million people. FST, I’m going to take the midpoint and say 0.04% of the population before 2032 is ~3.30 million people.

So, what is the likelihood this pandemic actually results in >= ~3.30m people dying?

Lethality (% who contract contagion and die) and transmissibility (% chance two people in proximity transfer contagion) are two critical factors for this, but I do not currently know how to calculate these for natural pandemics, and also do not know where to look to find these.

For context, the Black Death (3) stands out in my mind as the most lethal pandemic (~100m deaths of the ~475m people alive at the time, so ~21.0% global pop. died), and WHO reports (Nov. 4) that there have ~250m SARS-CoV-2 cases, and ~5m deaths (of the ~7.79b people alive at the time, so ~0.064% global pop. died, and ~2% of those who contracted SARS-CoV-2 died). So, another SARS-CoV-2 equivalent pandemic would be enough to exceed 0.04% global pop. deaths, and another Black Death equivalent pandemic would definitely be enough.

Vaccines and government mandates have helped diminish the SARS-CoV-2 death toll, and given the current (including next 10 years) state of civilizational pandemic-preparedness, will likely be even more efficacious at curbing deaths in the future. My intuition is that the death toll of SARS-CoV-2 would have been reduced ~40-80% (so now ~0.0256%-0.032% of global pop. dead) if the same measures such as masks, social isolation, an effective vaccine, shutdowns, etc… that were implemented at the height of SARS-CoV-2 had existed prior to SARS-CoV-2 occurring, which will be the case for any near-future pandemic.  

So, a SARS-CoV-2 equivalent occurring in the future, given all that has happened, will likely not be enough to surpass 0.04% of global pop. deaths. What, then, is the likelihood that a future pandemic is just slightly more lethal than SARS-CoV-2? Again, this is tough to estimate, but to answer it we should look to where SARS-CoV-2 falls hierarchically in history of pandemics, i.e. we need to find the # pandemics worse than SARS-CoV-2, controlled for the protective structures instituted now and in the future.

FST (strong), eyeballing PTH, all recent pandemics (e.g., SARS-CoV, Influenza A/H1N1, MERS-CoV) save SARS-CoV-2 have resulted in < 0.04% global pop. dying, and older pandemics that resulted in >=0.04% of global pop. dying occurred in environments devoid of present civilizational protective measures. If these older pandemics had had the protective measures of present and future day implemented, I’d estimate that about half of them would have no longer resulted in >=0.04% of global pop. dying. Moreover, I’d estimate that the likelihood that the next pandemic is one of equal or greater magnitude to one of these older one’s to be 20%. As a final loose estimate, I’d say that p(‘new pandemic has death toll >=0.04% global pop. dead before Jan. 1’) = p(‘natural pandemic occurs’)p(‘natural pandemic results in >=0.04% global pop. dead’)p(‘civilizational protective measures reduce chance natural pandemic results in >=0.04% global pop. dead’) = 0.5 x 0.2 x 0.5 = 5%.

FST (very strong, out of time for this question), I would predict (subjectively; based on Precipice, Metaculus predictions, etc…) that there is <= 2% chance that a human-engineered pandemic kills >= 0.04% of the global population in the next 10 years, so I set the final likelihood estimate to <= 7%.

___Links___

(1) https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7874133/  (search ‘pandemic history’)
(2) https://ourworldindata.org/world-population-growth (search ‘global population growth’)
(3) https://en.wikipedia.org/wiki/Black_Death (search ‘Black Death’)
(4) https://ourworldindata.org/covid-vaccinations (search ‘covid global vaccinations’)
…not doing links anymore given time difficulties

## Criticisms and Additional Considerations
