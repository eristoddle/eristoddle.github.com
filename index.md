---
layout: page
title: Stephan Miller
tagline: My Code Blog
---
{% include JB/setup %}

## Just Starting This Blog

And I am still customizing and setting it up. Until it is actually active you can see posts I have written [here](http://www.stephanmiller.com).
    
## Recent Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>