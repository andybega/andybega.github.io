---
layout: single
title: Quick lookup for country codes
date: 2014-01-29 02:48:21.000000000 +02:00
categories:
- post
tags:
- ccode
- gwcode
---

2017-11-01: 

In the meantime I've written a minimal R package with the COW and GW state lists and a rudimentary search helper function at [https://github.com/andybega/states](https://github.com/andybega/states).

***

After more than half a decade at this, it has finally dawned upon me that instead of downloading the [Correlates of War](http://www.correlatesofwar.org/) state system membership table, or the [Gleditsch and Ward refinement](http://privatewww.essex.ac.uk/~ksg/statelist.html) of it, every time I wonder what country "338" is, it might be easier to upload them to Google:

[COW codes and state system membership](https://docs.google.com/spreadsheet/ccc?key=0Aoh3Wxrwx3o6dDZXRHFMSnNaSHphb1RCaks5Qlppd1E&usp=sharing)

[G&W codes and state system membership](https://docs.google.com/spreadsheet/ccc?key=0Aoh3Wxrwx3o6dERVT0lUYXNSTnVrSG5vRzg4YzBDSFE&usp=sharing)

And, for the sake of self-promoting completeness, code to [produce panel data]({{ site.baseurl }}{% post_url 2013-12-11-code-for-blank-state-panel-data %}) reflecting COW or G&W state system membership, and old Stata code to [change country names to COW codes]({{ site.baseurl }}{% post_url 2013-09-05-stata-do-files-for-country-code-conversions %}).
