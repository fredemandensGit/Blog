---
title: "Click here to begin reading"
weight: 1
author: "Jens Christian Bang Gribsvad, Frederik Hartmann"
---
## Why should we want more people to bike?

We all know that exercising is good for your body, and this also matter when it comes to biking. As noted by <span style="color:orange"> [Victoria State Government](https://www.statista.com/statistics/191204/participants-in-bicycling-in-the-us-since-2006/) </span>, biking can help protect you from serious diseases such as *stroke, heart attack, some cancers, depression, diabetes, obesity and arthritis*.

![Capital Bikeshare bikes in Washington DC]({{< baseurl >}}/happybike.png)

But even with the spectacular health benefits of biking, we only see that *one percent of all trips that Americans take—to work, to the store, on vacation—are by bike, compared with 87 percent by car or truck.*  Furthermore, by biking, we also help battle the climate change, one trip at a time. *Transportation is the largest source of green house emissions, and cars and light trucks account for 58 percent of transportation emissions.* These data were compiled by Ilana Strauss on [National Geographic](https://www.nationalgeographic.com/environment/article/is-the-us-becoming-more-bike-friendly). Our goal is therefore to help both the earth but also the individual by making it more attractive to bike! In this project we will examine the patterns of bike sharing in Washington DC by investigating a dataset from the bike-sharing company [Capital Bikeshare](https://capitalbikeshare.com/) along with a dataset containing weather data. The data is recorded in a 2 year period from 2011 to 2012. We have chosen to work with these 2 datasets to enable an investigation of temporal patterns in weather data and number of rented bikes along with an analysis of geo data of the bike stations in the city.

By investigating and learning about bike patterns we can, from the perspective of a bikesharing company, aim to make bike sharing more convenient for the customers. In particular, we must ensure there is always a sufficient supply of bikes to be rented and enough bike-stations around the city. So let's investigate how we can help both the people and the earth, one rental bike at a time.

## Capital Bikeshare Dataset

As mentioned we work with the [Capital Bikeshare](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset) dataset from Washington DC.

![Capital Bikeshare bikes in Washington DC]({{< baseurl >}}/CBS_DC.png)

This dataset consists of hourly data points in the 2 year period from 2011-2012. This data holds information about the specific trips, i.e., duration of the trip, start and stop stations (addresses) and even more.
We pair this data set with a weather data sat from the same period, in order to be able to investigate how weather might influence the number of bike-trips. The weather data consists of various weather-attributes such as temperature, feeling temperature, humidity, windspeeds and even more cool features. Initially we will investigate the what the data at hand looks like in the data exploration post.

## Data exploration

Upon investigating the data, we see multiple things that is expected. We do however also see some unexpected things. We invite the reader to interact with the following figures. First we investigate temporal patterns

{{< include-html "temporal_plots.html" >}}

One could also expect the daily bicycle patterns to be completely different when considering an average weekday or day at the weekend.
{{< include-html "Avg_hrly_count.html" >}}

Next we investigate weather patterns

{{< include-html "Weather_plots.html" >}}

Upon investigation, we see that indeed more people are biking, when the temperature is higher, with a peak in the 20-30 degree interval. This is also expected, since most people enjoy biking in good weather. Further we see, that obviously the weather situation impacts the number of bikers.

And here we see a heat map of the summerdays

<iframe src="/Heatmap_summerdays.html"
	sandbox="allow-same-origin allow-scripts"
	width="100%"
	height="500"
	scrolling="no"
	seamless="seamless"
	frameborder="0">
</iframe>

## Discussing the findings

So what can we discuss

## What can we conclude?


So what can we conclude?
