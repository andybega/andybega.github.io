---
layout: single
title: Map of the age of state leaders
date: 2017-12-12 12:00
category: research
tags: [Archigos, REIGN, state leaders, thematic map]
excerpt: A thematic world map showing the age of current state leaders, with data from Archigos and REIGN. 
header: 
  teaser: /content/2017/map-leader-age.png
og_image: /content/2017/map-leader-age.png
---

The map below shows the age of the world's state leaders on 12 December 2017. 

[![Map of state leader ages]({{ site.url }}/content/2017/map-leader-age.png)]({{ site.url }}/content/2017/map-leader-age.png)

The mean age is around 62 years, ranging from 31.5 year old Sebastian Kurz in Austria---whose party won the last legislative elections and is in the process of forming a government---to 91.5 year old President Essebi in Tunisia. 

The data come from the [REIGN leader data](http://oefresearch.org/datasets/reign), which in part builds on and updates the [Archigos leader data](http://privatewww.essex.ac.uk/~ksg/archigos.html), a dataset of the leaders of the world's independent states from 1875 on. You can find a list of the leaders that are shown in the map [on github here](https://github.com/andybega/mireg-blogs/blob/master/leader-age-map/leader-data.csv).

Note that these data code the *de facto*, effective leader of a state, so the person listed there may not be the theoretical, *de jure* head of a state. For example, in parliamentary democracies the prime minister is coded as the state leader even though usually another person is the official, ceremonial head of state, while in semi-presidential regimes with both a president and prime-minister either might be designated the effective leader, and that designation might change in over time if the relative power of the two offices is altered. Similarly, in Russia Putin is coded as the uninterrupted leader since 2000, even for the period when Medvedev was president and Putin prime minister. The websites linked above both have code books that explain coding criteria in detail. 

The map was made in R using ggplot2, cowplot, and sf, with data via cshapes and rnaturalearth. The code is [on github](https://github.com/andybega/mireg-blogs/tree/master/leader-age-map).

## Are leaders in larger or less democratic countries older?

Estonia, where I live, has had a successsion of young prime ministers in their 30s, and the youngest leader on the map is in another small country, Austria. Maybe it is easier for young persons to rise to the top government position in a small, less populous country with less hierarchy. Similarly, if we think of Robert Mugabe's recent retirement, maybe regime type also plays a role in how old a state's leader is. 

First, here is leader age against country population, taken from the World Development Indicators:

[![Leader age versus population]({{ site.url }}/content/2017/leader-age-vs-country-pop.png)]({{ site.url }}/content/2017/leader-age-vs-country-pop.png)

There is pretty much no relationship at all. 

Next, leader age against an index of liberal democracy, from the Varieties of Democracy project (V-Dem): 

[![Leader age versus democracy-ness]({{ site.url }}/content/2017/leader-age-vs-democracy.png)]({{ site.url }}/content/2017/leader-age-vs-democracy.png)

There is a very slight pattern of younger leaders in more democratic regimes here, but it doesn't really explain much of the variation in age.  

Who are those really young leaders in really autocratic states? The list of current under 40 autocrats consists of Kim Jong-Un in North Korea at 34 (more or less, depending on who you ask), [Sheikh Al Thani](https://en.wikipedia.org/wiki/Tamim_bin_Hamad_Al_Thani) of Qatar at 37, and [Saleh Ali al-Sammad](https://en.wikipedia.org/wiki/Saleh_Ali_al-Sammad) of the Houthis in Yemen, at 38 (although you could argue who really is at the top in Yemen right now, if anyone). 
