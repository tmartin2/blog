---
layout: post
title: "Rough Estimate: Delaying Transformative AI"
date: 2021-09-16 14:28:44 -0000
---

__Note__: This is a question I was given on a test task for a remote internship position that focused on AI alignment. I got an interview for the position, but never heard back from the team, so I do not think I was accepted. I spent roughly two hours composing my response. Here is the question:

_What is the expected value (or disvalue) from transformative artificial intelligence counterfactually being delayed by one year? Assume that all other projects are not delayed._

- Interpret “value” to be from your own ethical perspective.
- Briefly explain your biggest sources of uncertainty and what you’d spend more time on if you had more time.

Here is my answer. At the end, I describe criticisms of my responses, and detail some considerations that I missed in my initial response.

## My Response

__Main Considerations__

- How should _value_ be defined?
- How should _transformative AI_ be defined?
- When (in what global-technological ecosystem) might transformative AI be created?
- How much impact might transformative AI have on the value metric in the year following the "when" date?
- How much does the exact "when" date contribute to how impactful transformative AI might be?
- How might delaying the onset of transformative AI by one year affect the value metric (1) outside of the effects that transformative AI would have had during that year, and (2) through modulating the expected impact that transformative AI will have on the value metric, starting in the following year?

__Value__

I believe that much of scientific and technological progress tends towards improving human well-being, and towards automating the fulfillment of human needs, such as shelter, food production, water security, freedom from bodily affliction or deficiency, etc..., which are all important for human well-being. With this in mind, I believe that the value or disvalue conferred by delaying transformative artificial intelligence by one year should be measured in terms of human well-being.

How is human well-being measured?

There is no real consensus among researchers about how well-being should be measured, and, for the most part, there are a host of different indices, such as the [Composite Global Well-Being Index](https://sci-hubtw.hkvisa.net/10.1007/s11205-015-1112-5), the [Organization for Economic Co-operation and Development (OECD) Better Life Index](https://www.oecdbetterlifeindex.org/), or the [Human Development Index (HDI)](http://hdr.undp.org/en/content/human-development-index-hdi). Of these three indices, the last one is the most well established, and has historical data available.

From the UN:

> _The Human Development Index (HDI) is a summary measure of average achievement in key dimensions of human development: a long and healthy life, being knowledgeable and have a decent standard of living._

_Assuming_ that the UN's HDI data is measured properly, and _assuming_ that there weren't any significant errors in the 2020 data reports, which is the most recent year available for the HDI measures, I select the HDI as an approximate measure of human well-being. The UN sorts HDI by country; given the time constraints of this problem, I select the 3 most populous nations's HDIs as a proxy for global HDI in 2020, which I am using as an approximation for global human well-being in 2020.

[WorldOMeter](https://www.worldometers.info/world-population/population-by-country/) reports that, in the year 2020, the China had ~1.4 billion people (HDI index = 0.761), India had ~1.3 billion people (HDI index = 0.645), and the USA had ~0.331 billion people (HDI index = 0.926). _Assuming_ that the world population was ~8.0 billion people in 2020, and that the ~(8.0 -   1.3   -   1.4   -   0.331) = ~5.0 billion people not living in one of the three most populous countries also have an average HDI of around (0.761 + 0.645 + 0.926) / 3 = 0.776, we can say that:

_The global HDI, which we assume to roughly measure human well-being, was approximately 0.776 in the year 2020._

__Transformative AI__

I first considered defining transformative AI in both a "shallow" and "strong" sense. For example, _shallow_ transformative AI might complete tasks as complex as creating an app for a particular problem (maybe some more advanced version of OpenAI's GPT could do this), but not across problems (no general intelligence); _strong_ transformative AI, on the other hand, could be akin or equivalent to AGI, and would significantly outperform humans on tasks involving general intelligence.

Nonetheless, I have opted to select [OpenPhilanthropy](https://www.openphilanthropy.org/blog/some-background-our-views-regarding-advanced-artificial-intelligence#Sec1)'s definition of transformative AI:

> _Roughly and conceptually, transformative AI is AI that precipitates a transition comparable to (or more significant than) the agricultural or industrial revolution._

So, using the well-being value metric, we can ask:

 _How much will global HDI change during the transformative AI "revolution"?_

Determining what a shift "comparable" to the industrial or agricultural revolutions would mean for today's (or the future's) global HDI  is difficult, as it requires knowing how much the global HDI shifted during the industrial and agricultural revolutions, and how similar  a transformative AI "revolution" will be to these revolutions.

Without verifying the data sources or accuracy, [OurWorldInData](https://ourworldindata.org/human-development-index) reports that the HDI for the UK in 1870 (earliest year available) was ~0.21, and according to Wikipedia, the industrial revolution for the UK ceased around ~1850. The lowest HDIs in the same year were ~0.02. From these numbers, it seems that an industrial revolution confers a rapid increase of ~0.20 points on the HDI.

Given my lack of time and data, I am going to ignore the significance of the transition engendered by the agricultural revolution, and work solely off of the HDI estimate for the industrial revolution.

The baseline rate, i.e. the rate outside of an industrial revolution, of HDI increase ___appears___ to be linear in many countries. In 2015, [OurWorldInData](https://ourworldindata.org/human-development-index) reports that the UK has an HDI of ~0.76, which is quite similar to our estimated average global HDI for 2020. The UK's baseline rate of global HDI increase is ~(0.76 - 0.21) / ~(2015 - 1870) = ~0.0038 points per year, and I use this as the global baseline rate of HDI increase.

On the Metaculus question [When will the first AGI system be devised, tested, and publically known of?](https://www.metaculus.com/questions/3479/when-will-the-first-artificial-general-intelligence-system-be-devised-tested-and-publicly-known-of/), 226 forecasters predict (as of September 9th, 2021) that the median (lower 25% = 2032, upper 75% = 2064) year that the first AGI will be developed and demonstrated might be 2044. _Assuming_ that this Metaculus prediction is reasonably accurate, I select 2044 as the hypothetical onset year for transformative AI, which I _assume_ to be comparable to AGI or superintelligence (the risk posed by transformative AI is then also assumed to be comparable).

So, the global HDI in 2044 might be around ~0.776 + (~0.0038 * (~2044   - 2020)) = __0.8672__.

The maximum HDI value a country can have, at the moment, is 1.0. _Assuming_ that transformative AI ___is reasonably aligned with human values___, the magnitude of HDI increase might significantly
exceed that of the ~0.20 estimated increase for an industrial revolution. This would push the global HDI to 1.0 by 2045, but I don't think that the HDI should stop there, and in this document, I operate as if the HDI can exceed 1.0. In the year following the onset of transformative AI, I don't think it'd be too unreasonable to expect a minimum HDI increase of ~0.40, double that of the industrial revolution; this would put the global HDI by 2045 at ~(0.8672 + 0.40) = ~1.267.

However, there is also cause to believe that transformative AI ___might be unaligned with human values___. Moreover, transformative AI could ___pose a non-trivial risk for human extinction___. I think setting the HDI to 0.0 makes sense in an extinction scenario. I am extremely uncertain about how much existential risk transformative AI poses, and am also uncertain about how to factor in the cost of losing all future human lives. Furthermore, I am uncertain about how much existential risk transformative AI poses _in the first year_ after it is created.

So, there is the "good scenario", where the HDI rapidly increases by ~0.40 or more, and the "extinction scenario", where the HDI goes to zero. There could also be another scenario where the HDI decreases by ~0.40 or more, but does not go all the way to zero: I call this the "bad scenario". I _assume_ p("extinction scenario") = 0.05, p("good scenario") = 0.45, and p("bad scenario") = 0.50. An expected change in the HDI might then be 0.05(~  -0  .8672) + 0.45(~0.40)   -   0.50(~0.40) = ~  -0  .0634, which would bring the expected global HDI in 2045 to ~(0.8672 + 0.0038   -   0.0634) = ~0.8076. Of course, the "bad scenario" HDI value ranges ~0.40 to 0.999..., and the "good scenario" HDI value might be much greater that ~0.40, so the expected global HDI in 2045 might actually be very different from ~0.8076.

If the onset of transformative AI didn't occur in 2044, the global HDI at the start of 2045 might be around ~(0.8672 + 0.0038) = ~0.871. Also, progress is made each year in research on AI-safety and AI-alignment. I _assume_ that the risk of the "bad scenario" or the "extinction scenario" occurring decreases by 1% for each year of additional research. Delaying the onset of transformative AI by one year would then mean that, in 2045, the expected change in the HDI might be 0.04(~  -0  .8672) + 0.47(~0.40)   -   0.49(~0.40) = ~  -0  .0427 instead of ~  -0  .0634.

<!-- Just as I am uncertain about how to factor in future HDI changes in t -->

__Estimate and Final Comments__

_The expected value from transformative artificial intelligence counterfactually being delayed by one year could be approximately (0.0634   -   0.0427) = ~0.0207 fewer points lost on the Human Development Index, in the year directly following the onset of transformative artificial intelligence. I expect that, should transformative AI be especially good or especially bad, the HDI changes over the long-term could be tremendous, and that the magnitude of these long-term values with a one year delay will be comparable to those in a scenario without a delay._

This is a very important question, and quite a difficult one to forecast. Nonetheless, I had fun completing this task.

My largest "assumptions" concern (1) how well HDI approximates well-being; (2) how global well-being / HDI can be measured; (3) how a transition comparable or more significant than the industrial or agricultural revolutions influences well-being; (4) how impactful transformative AI will be depending on the "when" date; (5) __how to weigh in the future loses or gains when calculating expected well-being value after transformative AI__; (6) how risky transformative AI will be for humanity; (7) how effective AI-safety research is at reducing the risks posed by transformative AI.

## Criticisms and Additional Considerations
