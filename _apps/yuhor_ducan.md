---
title: Yuhor Dućan
owner: Delta Holding
link: /_apps/:name
order: 1
desc: App for YuhorDucan stores. YuhorDucan are brand stores for meat factory Yuhor. App contains map & list of locations, news, promotions, recipes, loyalty programme, online orders. 
play: https://play.google.com/store/apps/details?id=rs.deltaholding.yuhorducan
---

As I grew as a developer, this app grew in parallel :) I'm proud of some solutions, although as every developer, I would totally rewrite it! :)

Being given only short textual specifications, I created the conceptual solution, initial design, UX and the entire Android application - front-end and Firebase back-end. But I have to thank my colleagues for answering many of my UX dilemmas, for testing and useful suggestions.

Application contains:
- contact information for every store: address, phone, open hours, location on Google Maps, Street View
- locate store closest to user's current location
- contact screen - links to contact info, social networks and form for feedback
- lists of promo actions, news, recipes, assortment
- loyalty program: user account linking Firebase login & Oracle DB, showing consumption, discounts, savings achieved
- online orders - registered and logged in users can get the prices and products for chosen shop and date, and send orders

App connects with 3 backends:
- it uses Firebase to read its content
- content is entered by content editors in PHP backend, which is also used to load pictures and save FCM tokens
- for online orders it connects to Oracle database through Mulesoft web services

It uses:
- Firebase Auth, Analytics, Database, Crashlytics, FCM (Notifications)
- Google APIs: maps, location
- Square: Retrofit, OkHttp3, Picasso
- mostly ConstraintLayout, and excellent library by Mindorks - PlaceholderView for expanded recycler view

It has 4 variants: dev, staging, debug, release, that are set in gradle and can co-exist together on the device.