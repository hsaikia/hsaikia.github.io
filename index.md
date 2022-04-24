---
layout: default
title: Hello Multiverse
permalink: /
---

Welcome curious visitor, in this page you'll find links to my various projects and creative outlets.

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
    
### Food

- Vegan recipes from my home cooking pastimes on [Instagram](https://www.instagram.com/eat_and_let_live/).


### Music

- Some of my (bad) guitar recordings on [SoundCloud](https://soundcloud.com/milwac).

### Software and Programming

- I am a Software Developer working in Simulations for Autonomous Driving. Sources to my public projects, are hosted on my [Github](https://github.com/hsaikia).
- My publications are listed on [Google Scholar](https://scholar.google.com/citations?hl=en&user=B6UDagwAAAAJ).
- [Learn By Example](https://www.youtube.com/channel/UCrip_x8QZ7GLTykFWJgS5Ww) is my YouTube channel where I post videos on solving programming puzzles.

### Connect

- [LinkedIn](https://www.linkedin.com/in/himangshu-saikia-a4a4711b)
