---
layout: page
title: Stephan Miller
tagline: My Code Blog
---
{% include JB/setup %}

## I Used to Keep Most of this in Wikidpad

So most of these posts are lists, notes and the like that I don't want to forget.

I am leaving one of the default posts here on the blog just so that I have some notes on how to use Jekyll which is what powers this blog. Plus a [link](http://jekyllbootstrap.com/usage/jekyll-quick-start.html) here, so I remember how to post to this thing.

I am using the Twitter Bootstrap theme with the Superhero template from [Bootswatch](http://bootswatch.com/).
    
## Recent Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

##CoderWall
<section class="coderwall" data-coderwall-username="eristoddle" data-coderwall-orientation="horizontal"></section>