---
layout: post
title:  "Covid Fatality Estimate in China"
date:   2023-01-09
categories: Analysis
---

As of 9 January 2023, China has reported 10,649,521 confirmed cases of COVID-19 with 33,144 deaths according to [WHO](https://covid19.who.int/region/wpro/country/cn). 

![China Covid WHO report](/assets/china-covid-who.png)

These numbers were published after China had lifted the COVID-zero policy on 7 Dec 2022. In retrospect, it’d be interesting to see what would happen should the COVID-zero policy be lifted at a different timeline. This analysis estimates death toll scenarios by assuming that policy change occurred between February 2021 and December 2022 in weekly intervals.

For each assumed COVID-zero end date, the figure below shows the estimated total number of deaths till 2 December. Each estimate is based on the projection from [UK death rate in each age group during the same period](https://www.ons.gov.uk/peoplepopulationandcommunity/healthandsocialcare/conditionsanddiseases/articles/coronaviruscovid19latestinsights/deaths#deaths-by-age).

![Death Estimate](/assets/deaths-estimate.png)

From the estimate, it shows that one year delay of policy change reduces the death toll by over half a million, while 6 months delay reduces it by nearly 200,000.

The breakdown of death toll per age group over time is presented below. Age groups `65 to 74` and `75 to 84` suffer the highest death toll, though both age groups combined account for 13% overall population.

![Alt Text](/assets/scenarios.gif)

Note: the estimates in this analysis did not factor in 
- The impact of early waves of COVID-19 deaths pre-February 2021 in the UK, which may increase the death estimates
- The difference in medical conditions in both countries