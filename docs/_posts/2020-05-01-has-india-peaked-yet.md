---
layout: post
title: Has India Peaked Yet?
date:   2020-05-01 11:30:08 +0530
---
Recently, Data Driven Innovation lab (DDI) at Singapore University of Technology and Design (SUTD) came out with an [implementation][sutd-paper]{:target="_blank"} of the popular SIR model and tried to predict the Covid-19 peak dates for various countries including India. They predicted that India would peak on 20th April and 97% of the expected cases would have been identified by May 25th. We were curious to verify these dates and built a methodology to validate these predictions. Our method has a limitation that it can confirm the peak only 3 days after the actual peak date. After running our calculations, we find that the predictions are incorrect for most of the countries in the rising half of the epidemic, where new highs are still  being reported. The details of our analysis are presented [here][paper]{:target="_blank"} and our calculations and code is available on this [notebook][notebook]{:target="_blank"}.

It is still not confirmed that India has peaked 10 days after the predicted peak date and the actual date does not appear to be any time soon as per our calculations So it is highly unlikely that 97% of expected cases would end by the forecast date for countries such as India, Pakistan, Saudi Arabia, UAE.. Further we predict that the daily new cases will never become zero as predicted by this paper but will leave behind an asymptote.

[sutd-paper]: https://ddi.sutd.edu.sg/when-will-covid-19-end/
[notebook]: https://github.com/VICS-CORE/stats/blob/master/02_Total_daily_slope.ipynb
[paper]: 