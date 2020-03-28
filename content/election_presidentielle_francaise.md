---
title: Élection Présidentielle Française 2017
author: Felix
type: page
date: 2017-04-29T17:03:11+00:00

---
# Basic Setup

I had used R in the past to collect tweets, but this technique has its limitations, when one wants to collect a lot of data and do so 24/7. In my opinion there is no way around Python in this case and in the best case a server is at hand as well. It is the first time I am using this combination, I did some research to find a setup that is fast, since I was expecting a lot of tweets around the election days. My setup is based on this great [twitter scraper repo][1]. In the first days I only had a few words to track specified, but adjusted my list based on a simple preliminary analysis of collected data.

In the following sub pages I present some basic analysis of collected tweets in the light of the presidential elections in France.

# Track terms

these are the terms for which Twitter&#8217;s API was looking in tweets to forward matches.

  * &#8220;presidentielle2017&#8221;, &#8220;presidentielles2017&#8221;, &#8220;presidentielle&#8221;, &#8220;presidentielles&#8221;, &#8220;#France2017&#8221;, &#8220;#Frenchelections&#8221;
  * &#8220;Fillon&#8221;, &#8220;Fillon2017&#8221;, &#8220;projetfillon&#8221;, &#8220;jevotefillon&#8221;, &#8220;fillongate&#8221;,&#8221;francoisfillon&#8221;
  * &#8220;Hamot&#8221;, &#8220;Hamot2017&#8221;,
  * &#8220;LePen&#8221;, &#8220;Le Pen&#8221;, &#8220;marielepen&#8221;, &#8220;marine2017&#8221;, &#8220;#mlp&#8221;,
  * &#8220;Macron&#8221;, &#8220;enmarche&#8221;, &#8220;macron2017&#8221;, &#8220;jevotemacron&#8221;, &#8220;emmanuelmacron&#8221;
  * &#8220;Melenchon&#8221;, &#8220;jlm2017&#8221;, &#8220;jlmelenchon&#8221;,
  * &#8220;Arthaud&#8221;,
  * &#8220;Poutou&#8221;,
  * &#8220;Asselineau&#8221;, &#8220;Asselineau2017&#8221;,
  * &#8220;Dupont-Aignan&#8221;, &#8220;DupontAignan&#8221;,
  * &#8220;Lassalle&#8221;,
  * &#8220;Cheminade&#8221;

In total my dataset contains 8,783,948 tweets.

# Analysis

  * [Number of tweets per day][2]

#

 [1]: https://github.com/dataquestio/twitter-scrape
 [2]: {{< ref "number_tweets_per_day.md" >}}