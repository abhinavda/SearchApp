# SearchApp
Retrives Amazon results and sorts them by number of reviews 

<img width="1280" alt="searchapp homepage" src="https://user-images.githubusercontent.com/27103067/34322688-2557ac98-e7f4-11e7-887b-d004e1ee9380.png">

# Intent:
Twitter exposes an API to consume live stream of tweets in realtime. Tweets and their location can be used to give useful recommendations to both clients and consumers(tweeple).

# Requirements:
1. Python 2.7
2. Django
3. HTML/CSS

Spark streaming is perfect for getting data from twitter in realtime. It is very efficient and fast in performing operations. This is due it's in-memory computing.
We can perform analysis with live data or it can be stored in a database to later perform complex breakdown of data.
Elasticsearch is a perfect fit for this scenario. It is fast, built to scale horizontally, accepts any kind of data. Logstash, an open source, data processing pipeline is used to ingest data, perform intended filtrations before sending that data to Elasticsearch. Data is stored in Elasticsearch in the form of JSON documents. Kibana, part of Elasticsearch stack, can be used to create indexes, visualize data in number of ways. Kibana also comes with tile map service which is used in this application to observe the tweets location.

# Results:
A short demonstration can be seen in the video, it shows origin of tweets in realtime.
https://github.com/abhinavda/Tweetslocator/blob/master/Tweets%20location.mp4

# Use cases:
This application can be used to give recommendations.
1. Tweets and their location can be used together. We can identify interests of the consumers, use it to recommend clients in setting up restaurant or a shop, etc in a particular area.
2. Suggestions can be given to consumers regarding nearby restaurants, events, etc.
