---
layout: page
title: Sweet Strike Prices
permalink: /sweet-strike-prices/
---

**Disclaimer : Please consult with your attorney, accountant, and/or tax advisor for advice concerning your particular circumstances**


I ran a python code to analyse 20 years closing prices of Nifty 50 Index to formulate a fair idea of how much the index moved from one expiry to another.

I expect this to help us in determining sweet option strike prices which are expected to give us gains.

Check out the [this github page][github-nifty] for the complete results and the sweet strike price ranges.
What follows is an example of the analysis and how to use the data thereby generated

For instance, consider the following results of weekly change analysis (Thursday to Thursday)

* The change has been under **1** percent **29.52%** times
* The change has been under **2** percent **26.51%** times
* The change has been under **3** percent **17.27%** times
* The change has been under **4** percent **11.24%** times
* The change has been under **5** percent **5.82%** times

Taking this practically let's say the closing price of Nifty on a certain Thursday was 10000. And assume you did a bidirectional option sell at 5 percent difference, that is to say
you sold a put option at 9500 and call option at 10500, i.e **SELL 9500PE and SELL 10500PE** chances of your profits along a 20 year 
span is as high as **90.36%**. If you were to be a safer trader and took 6% variance your chance goes up to **94.58%**

Another data point I would like to say is the monthly change percentages.
* The change has been under **2** percent **23.68%** times
* The change has been under **4** percent **21.93%** times
* The change has been under **6** percent **20.18%** times
* The change has been under **8** percent **15.79%** times
* The change has been under **10** percent **8.33%** times
* The change has been under **12** percent **4.39%** times

Taking this practically let's say the closing price of Nifty on a certain Thursday was 10000. And assume you did a bidirectional option sell at 12 percent difference, that is to say
you sold a put option at 8800 and call option at 11200, i.e **SELL 8800PE and SELL 11200PE** chances of your profits along a 20 year 
span is as high as **94.3%**.

This doesn't mean you should sell at expiry and hold till the next expiry. The catch here lies in how well you come out of winning trades and losing trades respectively.
How well you manage the 5% times you fail and limit your losses will go on to determine how successful an option trade you are going to become.
Please note that I took only deep OTM options since I am not a full time trader. I believe this data can be put into more use by aggressive sellers who sell near 
the money.


[github-nifty]:   https://github.com/royce2892/bankthenifty/

