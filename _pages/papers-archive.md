---
layout: single
title: Projects & papers
sitemap: true
permalink: /projects/
author_profile: false
excerpt: A list of projects and papers I have worked on.
tags: []
---

<!--
## Projects

Below is a list of projects I have or am working on, and below that lists of R packages and papers I have published or written. 

### HFC - 2017 on

https://www.hybridforecasting.com

R, Python Flask

### Mercury - 2016 to 2017

https://www.iarpa.gov/index.php/research-programs/mercury
https://www.iarpa.gov/index.php/research-programs/hfc

R, Python, web-scraping, docker

### PITF - 2012? to 2015

Independently, I helped produce coup forecasts for 2017. 

### C-IED

Modeling and predicting the occurrence of IED events in Afghanistan at a high resolution of ~1km^2 grid cell-day units. Eventually expanded to modeling mines in Colombia, with estimates of the probability that province is mine free or not mine free. 

R, PostGIS

### ICEWS event data

MySQL

-->



## R packages

[*spduration*](https://andybeger.com/spduration): implementation of Weibull and Log-logistic split-population duration models. These models are designed for instances when you want to model the duration to some event but the population of cases consists of a mixture that includes some proportion of cases that will not experience the event at all, e.g. at what age teenagers start smoking, criminal recidivism among former prisoners, and cancer relapse. 

[*states*](https://andybeger.com/states): make country-year/month/day panel data that is consistent with the COW or Gleditsch & Ward lists of independent states. I use these bare-bones panels as templates to which other data have to conform when merging IR datasets. 

## Articles, technical reports

Peer-reviewed academic articles and one technical report:

- [Splitting It Up: The spduration Split-Population Duration Regression Package for Time-varying Covariates](https://journal.r-project.org/archive/2017/RJ-2017-056/index.html)
<br> 2017, *The R Journal* 
<br> This is included as a vignette in the spduration R package. 

- [Lessons from near real-time forecasting of irregular leadership changes](http://journals.sagepub.com/doi/full/10.1177/0022343316680858)
<br> 2017, *Journal of Peace Research*
([appendix]({{ site.url }}/content/papers/Ward_Beger_2017_ForecastingLessons_JPR_Appendix.pdf), [replication](https://github.com/andybega/jpr-forecasting-lessons))

- [Irregular Leadership Changes in 2014: Forecasts using ensemble, split-population duration models](http://www.sciencedirect.com/science/article/pii/S0169207015000485), 
<br> 2016, *International Journal of Forecasting* 
([pdf]({{ site.url }}/content/papers/ijf-ilc2014.pdf), [replication](https://github.com/andybega/ijf-ilc2014))

- [Ensemble Forecasting of Irregular Leadership Changes](http://rap.sagepub.com/content/1/3/2053168014557511),
<br> 2014, *Research &amp; Politics* ([pdf]({{ site.url }}/content/papers/rap-ensembe-forecasting.pdf), [replication](https://github.com/andybega/rap-ensemble-forecasting))

- [Irregular Leadership Changes in 2014: Forecasts using ensemble, split-population duration models](http://arxiv.org/abs/1409.7105),
<br> 2014, *arXiv* ([pdf](http://arxiv.org/pdf/1409.7105v1.pdf))
<br> This is a 59 page technical report written for the Political Instability Task Force.

## Manuscripts

Unpublished papers (and that I am not working on publishing):

- [Precision-recall curves](http://ssrn.com/abstract=2765419)
<br> 2016, *on SSRN* ([pdf]({{ site.url }}/content/papers/Beger_2016_PrecisionRecallCurves.pdf))
<br> For rare outcomes (\**cough*\*, a lot of IR), ROC curves and the area under them are not a great measure of model fit. Look at (the area under) precision-recall curves as well. 

- **Using front lines to predict deaths in the Bosnian civil war**
<br> 2012, ([pdf]({{ site.url }}/content/papers/Beger_2012_Bosnia.pdf))
<br> To be useful for forecasting and prediction, a statistical model needs to be feasible given the data it requires. This paper examines the relationship between front lines and other, time-invariant variables, and killings during the Bosnian civil war from 1992 to 1995. It uses a Bayesian spatial count model to estimate and compare model fit to other, more established conflict models. One of the dissertation papers.

- [Explaining and predicting interstate war deaths](http://ssrn.com/abstract=2765421)
<br> 2012, *on SSRN* ([pdf]({{ site.url}}/content/papers/Beger_2012_WarFatalities.pdf))
<br> This paper is about predicting interstate war battle deaths. Data on 89 interstate wars between 1815 and 1991 is used to estimate a truncated regression model that provides the basis for out-of sample forecasts for two other wars. Also a dissertation paper. 

- **Predicting the intensity and location of violence in war**
<br> 2012, ([pdf]({{ site.url }}/content/papers/Beger_A_2012_Dissertation.pdf))
<br> My three-papers-wrapped-together Ph.D. dissertation. 

- **Simulating the Effects of Selection Bias in the Minorities at Risk Project.**
<br> 2008, ([pdf]({{ site.url }}/content/papers/Beger_2008_MARSelectionBias.pdf))
<br> How much of a problem is it that the Minority at Risk project collects information only for ethnic groups that are "at risk", i.e. selection on the dependent variable?
