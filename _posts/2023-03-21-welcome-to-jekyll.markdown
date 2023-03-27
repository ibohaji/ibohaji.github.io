---
layout: post
title: "Assignment 2"
date: 2023-03-21 09:50:58 +0100
categories: jekyll update
---

## Introduction

### Edit: 
Throughout the world, police departments are working vigorously to minimize time to reach the crime scenes. Now a days one of the law enforcement strategy is to  use machine learning and data analytics, and predict any potential crime before it actually happen; this is called (predictive policing)[ Predictive policing - Wikipedia]. Using this technique, the law enforcement agencies optimally deploy their resources in potentially  high crime areas which will reduce the time to react and overcome crimes. 
Another very useful application of predictive policing is analyze the relation between different crimes, i.e how one crime is dependent or linked to another crime or crimes.  Controlling the root cause can reduce a lot of other undesirable related events. 

According to recent [report]( https://drugabusestatistics.org/drug-related-crime-statistics/#:~:text=46%25%20of%20prisoners%20in%20federal,serving%20time%20for%20drug%20offenses.) 46% of prisoners in US federal prison are there for drug related crimes and it has been considered as the major cause behind number of other crimes.  In this mini project we want to analyze how Drugs and Narcotics is related to other crimes, what are the things that grows along it. We have first checked Drugs related crimes to all other major crimes by examining their correlation and R2 scores , which are measures of how one thing is closely related to another thing. In our analysis, we found that the top three crimes which are closely related to drugs are 'STOLEN PROPERTY', 'ASSAULT' and 'BURGLARY'. It also makes sense, since a general idea is that drug addicts are notorious to steal from others in order to get money to buy drugs.....  



<div style="text-align: justify">Criminal behaviour has been an ongoing research field to assist in crime prevention. One way to better understand criminal behaviour is investigating the correlation between different crimes. Analysing correlation between different crimes can provide insights for criminal behavior in specific areas. We can also gain information on the motivations and methods of criminals, and use this information to develop more effective strategies for preventing and responding to crime. Some potentially correlated crimes are drugs and robbery. If there is a strong correlation between drug use and robbery in a given area, solving drug problems in the area may effectively reduce robbery crimes in the area as well. We will be analysing a dataset retrieved from [DataSF] (https://datasf.org/opendata/), which consists of crime data in San Franscisco from 2003 to 2018. We will be investigating the following crime types: ['DRUG/NARCOTIC', 'STOLEN PROPERTY', 'ASSAULT', 'BURGLARY']. </div>

## Bar plots

<div style="text-align: justify">Firstly, we have plotted bar plots representing average number of crime occurences against hours of the week for the following 4 crimes, 'DRUG/NARCOTIC', 'STOLEN PROPERTY', 'ASSAULT' and 'BURGLARY'. Our goal is to investigate if 'STOLEN PROPERTY', 'ASSAULT' and 'BURGLARY' have a similar average hourly crime occurences pattern over the week as 'DRUG/NARCOTIC'. <img style="float: right; width: 500px; height: 400px; padding-left:20px; padding-top:20px" src="/assets/images/barplot.jpg"> If you refer to the first bar plot, 'DRUG/NARCOTIC' has the following distribution where the number of crime occurences rise and peaks during the afternoon of each day. The crime count then decreases throughout the night and increase again towards the afternoon of the next day. We have observed that 'STOLEN PROPERTY' has the most similar activity pattern as 'DRUG/NARCOTIC' and it peaks at about 100 on Wednesday late afternoon. 'ASSAULT' has a slightly different activity pattern where the crime count does not rise as significantly as 'DRUG/NARCOTIC' in the afternoon. Instead, the crime count only increases gradually. Another difference is that crime count for 'ASSAULT' is the highest at 90 on Friday night and Saturday night. 'BURGLARY' crime count pattern is the least similar to 'DRUG/NARCOTIC', where there are two spikes during noon and afternoon for each day of the week.</div>

## Map plot

<embed 
       type="text/html" 
       src="/assets/images/my_plot.html"
       width="1400"
       height="800"
       style="margin-left: -300px"
       >

<div style="text-align: justify"> The trend spiked our interest to further investigate if we can detect similarity in the geographical pattern as well. The dots in the above geoplot plot represents the occurence of the crime at the arrest time, the color and size of each dot represent the category of crime and the occurence at the same exact location at the time, respectivly. The crime activity is very prominent in the district of tenderloin, this is due to several factors among others the high poverty, unemployment and addiction rates. It's further evident that root of most of the crimes are drug related, and thus the district needs to combat the  drug pandemic that is plaguing Tenderloin.    </div>

## Various

<embed 
       type="text/html" 
       src="/assets/images/Bokeh.html"
       width="900"
       height="600"
       style="float: left"
       >

<div style="text-align: justify"> This is text beside the bokeh. Description of the plot can be written here. </div>

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
