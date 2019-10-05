---
title: Check Tokens
owner: Sindyoke
order: 2
desc: App that pings Google API to get info about all FCM tokens in your database.
---

I realized that it's not easy to get info about FCM tokens, for example analytics for number of users subscribed to topics. Google does not have that kind of API that would return cumulative result, so we need to send GET requests one by one for every token, which is of course cumbersome and should be automatized.

I decided to create an app that will send requests for all the tokens in the database.

List of tokens can be loaded from local file or url. For every token, app sends the request to get token info, and saves it to local database (I use Room to load it in local sqlite). App then returns total number of tokens, and number of active tokens. If we want all the details, we can copy the database file and open it for example in SQLite Viewer, and then export it to excell. We can then get number of tokens subscribed to any particular topic.

The main challenge was to queue and send thousands of GET requests without crashing. For that I used a trick I saw in one of Google's codelabs: I use pool of Executors, and for network executors I create as many as device has cores. Works perfectly, and downloads more than 1000 in several seconds.