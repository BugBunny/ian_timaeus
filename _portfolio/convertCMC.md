---
title: "convertCMC - convert century-month codes to *Stata* dates"
excerpt: "*Stata* package<br/><img src='/images/500x300.png'>"
collection: portfolio
---

*Stata* package to convert century month codes (CMCs) into *Stata* dates.

CMCs (i.e. dates coded as months since the start of the year 1900), are widely used by the *Demographic and Health Surveys* program and others.

`convertCMC` can randomly impute an exact day of the month to each date. This avoids (at least in aggregate) the biases that can arise when doing arithmetic with CMCs. For example, a child that was born in January 2013, whose mother was interviewed in January 2018, may have been either 4 or 5 completed years old at that time depending on whether the mother was interviewed before or after the child's birthday.

`convertCMC` takes into account the length of each month and knows about leap years. 

[https://github.com/BugBunny/convertCMC](https://github.com/BugBunny/convertCMC "Open link in a new window")

(doi: [10.5281/zenodo.3557306](https://doi.org/10.5281/zenodo.3557306)) 
