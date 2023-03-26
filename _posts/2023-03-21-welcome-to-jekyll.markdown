---
layout: post
title: "Assignment 2"
date: 2023-03-21 09:50:58 +0100
categories: jekyll update
---

## Introduction

Criminal behaviour has been an ongoing research field to assist in crime prevention. One way to better understand criminal behaviour is investigating the correlation between different crimes. Analysing correlation between different crimes can provide insights for criminal behavior in specific areas. We can also gain information on the motivations and methods of criminals, and use this information to develop more effective strategies for preventing and responding to crime. Some potentially correlated crimes are drugs and robbery. If there is a strong correlation between drug use and robbery in a given area, solving drug problems in the area may effectively reduce robbery crimes in the area as well. We will be analysing a dataset retrieved from DataSF (https://datasf.org/opendata/), which consists of crime data in San Franscisco from 2003 to 2018. We will be investigating the following crime types: ['DRUG/NARCOTIC', 'STOLEN PROPERTY', 'ASSAULT', 'BURGLARY'].

## Bar plots

Firstly, we have plotted bar plots representing average number of crime occurences against hours of the week for the following 4 crimes, 'DRUG/NARCOTIC', 'STOLEN PROPERTY', 'ASSAULT' and 'BURGLARY'. Our goal is to investigate if 'STOLEN PROPERTY', 'ASSAULT' and 'BURGLARY' have a similar average hourly crime occurences pattern over the week as 'DRUG/NARCOTIC'. <img style="float: right; width: 500px; height: 400px; padding-left:20px; padding-top:20px" src="/assets/images/barplot.jpg"> If you refer to the first bar plot, 'DRUG/NARCOTIC' has the following distribution where the number of crime occurences rise and peaks during the afternoon of each day. The crime count then decreases throughout the night and increase again towards the afternoon of the next day. We have observed that 'STOLEN PROPERTY' has the most similar crime count pattern as 'DRUG/NARCOTIC' and it peaks at about 100 on Wednesday late afternoon. 'ASSAULT' has a slightly different crime count pattern where the crime count does not rise as significantly as 'DRUG/NARCOTIC' in the afternoon. Instead, the crime count only increases gradually. Another difference is that crime count for 'ASSAULT' is the highest at 90 on Friday night and Saturday night. 'BURGLARY' crime count pattern is the least similar to 'DRUG/NARCOTIC', where there are two spikes during noon and afternoon for each day of the week.

## Map plot

<embed 
       type="text/html" 
       src="/assets/images/map.html"
       width="1400"
       height="800"
       style="margin-left: -300px"
       >

This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot. This is a bunch of text descriping map plot.

## Bokeh plot

<embed 
       type="text/html" 
       src="/assets/images/Focuscrime.html"
       width="600"
       height="600"
       style="float: left"
       >
This is text beside the bokeh. Description of the plot can be written here

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
