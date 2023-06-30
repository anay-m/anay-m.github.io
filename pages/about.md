---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
 am a CS student at the University of Michigan who is passionate about technology, travel, sports, movies, dance, music, and more! I always want to try new things, whether that means using a new Python library or eating fried ice cream for the first time. Feel free to contact me at *anaym@umich.edu* if you ever want to chat or try something new together!

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>