---
layout: default
title: Sindyoke's Android portfolio
---

<h2>{{page.title}}</h2>

This is the list of some Android projects I worked on. Some are for the company I work for, and the others are my private projects. I was the only developer on all, except BMW and Honda, where I inherited the code and published a few updates.

{% assign myapps = site.apps | sort: 'order' %}
{% for app in myapps %}
	{% assign appname = app.url | replace_first: '/apps/', '' | replace: '.md', '' %}
  <h3><a href="{{ '/_apps/' | append: appname }}">{{ app.title }} - {{ app.owner }}</a></h3>
  <p>{{ app.desc | markdownify }}</p>
{% endfor %}