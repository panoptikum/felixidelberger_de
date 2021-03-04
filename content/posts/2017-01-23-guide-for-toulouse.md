---
title: Guide for Toulouse
author: Felix
type: post
date: 2017-01-23T15:32:09+00:00
url: /guide-for-toulouse/
categories:
  - Data Science
  - R

tags:
  - shiny
  - R
  - leaflet
  - dashboard

---
In my first semester at the Toulouse School of Economics I took the course &#8220;Statistical Software for Data Scientists&#8221;. The professor gave us the assignment to apply the techniques for data collection, data cleansing and data visuzaliation on some data. I came up with the idea to create a basic guide for new people in Toulouse. The guide offers people the oppportunity to look for cinemas, parks and other places of their interest. The guide is also online [available][1].

The city of Toulouse runs a [platform][2] for open data where several data sets are available free to use. The data sets that have places as their observations also include the coordinates of these places. Some of them provide the data for this guide. I&#8217;ve mainly used the R packages shiny, leaflet and ggmap. Shiny is a great tool and I&#8217;m sure that I will have use in the future again. It takes some time to understand how I make my own functions responsive, but the invest of some time was definetely worth it.

The guide features the possibility that users enter their address and see how far (air line) they are away from each listed location. The guide is still quite rudimentary. Possible extensions would be that users can click the markers on the map and details such as the address and opening hours would be presented. With some more work this guide could actually be used by new arrivals to have a list of locations at hand which they can explore. Unfortunately, I don&#8217;t think that I will have this time.

 [1]: https://felixidelberger.shinyapps.io/Guide_Toulouse/
 [2]: https://data.toulouse-metropole.fr/page/home/