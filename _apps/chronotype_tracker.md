---
title: Chronotype Tracker
owner: Sindyoke
order: 8
desc: Tool for hacking your productivity - track how you feel by entering your estimates by hour, get summarized data after a few weeks, and find your most productive hours. Especially useful for freelancers.
---

To get the most of your day, I found the advice to track for at least 3 weeks, for every waking hour. I wanted to see when I am most productive, energized and creative.

I tried with Google Sheets, but it didn't work for me because I skipped some hours - I needed a reminder. Also, I needed to open Google Sheets every hour.

I also tried finding such an app on Google Play, but not only that I couldn't find it, I found numerous blogposts saying there is no such app for Android and that it should be built. So I decided to build it myself, and offer it to others on Google Play.

Initially, you set your wake hours, categories you want to track (default categories are: energy, focus, motivation, creativity), and number of weeks (default: 3 weeks). Every hour, app shows you the notification to enter data. Click on it takes you to the exact screen. After a few weeks, you can look at the chart and see your most effective hours.

It is work in progress - reminder is working, UI is almost finished (although it despreately needs polishing :) ) so it's able to enter data, but database is not yet in place.

Next tasks:
- saving hourly data in Room database
- drawing charts: for every category - query from database, x-axis: hour, y-axis: average value from all entered days for that hour
- create intro screens - short tutorial for using the app