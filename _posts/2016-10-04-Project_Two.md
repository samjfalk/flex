---
layout: post
title: "Billboard Top 100"
date: 2016-10-05
excerpt: "Exploratory Data Analysis"
tags: [EDA, GA]
comments: false
---

Thanks for tuning in to today's radio story about Billboard Top 100 data! Let's review some of the specifics of the report. 

In the analysis we noticed that many songs dropped off after their 20th week on the charts. Our experts at the radio station said this could be because longer songs tend not to last very long on the charts. We found this very interesting, so we wanted to test it. 

<img src="http://i63.tinypic.com/xkx0cz.png" width="800">

But before jumping in, genre was visualized to see if there sound be anything else we could be looking into. The graph below shows that there were far more Rock songs on the list than any other, but that is no surprise considering our station loves rock and all of you out there love it too.

<img src="http://i66.tinypic.com/rumiat.png" width="800">

The data supplied by Billboard only tracks songs that have peaked, not all music that has made it to the the top 100, so it is difficult to make extensive assumptions around the genre data. Moving forward the analysis steered clear of evaluating by genre. 

We decided to revisit our first conundrum, does the length of the song effect the length of time it lasts on the Billboard Top 100? After extensive analysis using a t-test and a shuffle test on both long (above median time on charts) and short (below median time on charts). We concluded that we fail to reject the null and song length (whether it is long or short), does not effect the time a track stays on the charts. 

A visualization of the data shows that there is a relative normal distribution of song length to weeks on billboard. Also, comparing Long (in magenta) to Short(in green) doesn't show any significant differences. 

<img src="http://i65.tinypic.com/23ksrba.png" width="800">

Some assumptions were made in the analysis of this data:
-Assume that Rock n Roll is the same as Rock 

-Assume that all artists are properly labeled with the proper genre


Review of Hypotheses:
-Null Hypothesis: Regardless of length of song, a song will apply to the normal distribution of weeks on Billboard

-Alternate Hypothesis: The shorter the song the longer it lasts on Billboard

Find Jupyter Notebook for this project <a href="https://github.com/samjfalk/GA-DSI/blob/master/Projects/Project_2_sam_falk.ipynb">here</a>