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

Note that these data code the *de facto*, effective leader of a state, so the person listed there may not be the theoretical, *de jure* head of a state. For example in parliamentary democracies the prime minister is coded as the state leader, and in Russia Putin is coded as the leader since 2000, even for the period when Medvedev was president and Putin prime minister. The websites linked above both have codebooks that explain coding criteria in detail. 

The map was made in R using ggplot2, cowplot, and sf, with data via cshapes and rnaturalearth. The code is [on github](https://github.com/andybega/mireg-blogs/tree/master/leader-age-map).