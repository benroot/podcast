---
title: Ben's Week in Medical School Podcast
---

# Ben's Week in Medical School Podcast #
<img src="https://raw.githubusercontent.com/benroot/twims/gh-pages/images/cover1400.jpg" alt="Logo with Stethoscope" height=260px>

A podcast about my journey through medical school, and a sampling of interesting topics about the human body, health, and medicine. 

[Listen on Stitcher](https://www.stitcher.com/podcast/bens-week-in-medical-school)

[Listen on Apple Podcasts](https://podcasts.apple.com/us/podcast/bens-week-in-medical-school/id1535996032)

[RSS Feed (for manual adding to your podcast app)](https://www.bencr.me/twims/podcast.xml "Direct RSS Link")

## Episodes
{% for post in site.posts %}
<a href="{{ site.url }}{{ post.url }}">Episode {{ post.episode_number}} - {{ post.title }}</a>
<audio src="https:{{post.file}}" type="audio/mpeg" controls>I'm sorry. You're browser doesn't support HTML5 <code>audio</code></audio>
{% endfor %}
