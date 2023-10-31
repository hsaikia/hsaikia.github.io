---
layout: default
title: Hello Multiverse
permalink: /
---

Welcome curious visitor, in this page you'll find links to my various projects and creative outlets.

## About

- I am a Software Developer working in the Autonomous Driving domain. 
- [Learn By Example](https://www.youtube.com/channel/UCrip_x8QZ7GLTykFWJgS5Ww) is my YouTube channel where I post educational content on various CS topics.
- Sources to my public projects, are hosted on my [Github](https://github.com/hsaikia).
- My publications are listed on [Google Scholar](https://scholar.google.com/citations?hl=en&user=B6UDagwAAAAJ).
- I like strategy board games like Chess and Agricola, and often spend a lot of time thinking about algorithms for optimal decision making in games.
- I organize hikes every now and then in and around Munich in the [Hiking Buddies Munich](https://www.hiking-buddies.com/routes/user/5581/) community.
- Vegan recipes from my home cooking pastimes on [Instagram](https://www.instagram.com/eat_and_let_live/).
- Some of my (bad) guitar recordings on [SoundCloud](https://soundcloud.com/milwac).

## Connect

[LinkedIn](https://www.linkedin.com/in/himangshu-saikia-a4a4711b)

## Articles and Blog posts

<div>
	  {% for tag in site.tags %}
      <h3>{{ tag[0] }}</h3>
      <ul>
        {% for post in tag[1] %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
      </ul>
      {% endfor %}
</div>
    
