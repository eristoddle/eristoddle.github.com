---
layout: post
title: "Lithe, A Blog Using the Lithium PHP Framework"
description: "I thought I create a lightweight blogging application using the Lithium Framework #li3 and MongoDB."
category: lithium
tags: [lithium, li3, mongodb, php, blog, lithe]
---
{% include JB/setup %}
## Tired of Huge CMSs that I Have To Relearn Every Few Months
I love the ease of use with Wordpress. Most sites I can find plugins to do just about everything, which involves more data spread out across more tables with more joins to bring them all together.

I started hating MySql when I dealt with Magento. Found NoSql and for the stuff I do, it works better and I don't filter my ideas into a database structure before I can do things. And using Lithium I forget about the database most of the time.

##PHP is just the default and it works

I have used a NodeJS server to experiment with a few things. I have use a few Python based servers. And I will have to get a VPS or cloud server at least to put you on one. There is just too much to remember correctly to get it right and the general web developer won't really know what you are talking about.

I am running the test of this blog on an Nginx server and using MongoDB so I guess I am being a little hypocritical about using technologies that are not readily available form every hosting provider, but this blog will run just fine with Apache and MySql. You just have to switch the database provider by commenting a few lines and uncommenting a few others. I will put a post up on that eventually.

[Lithe](https://github.com/eristoddle/lithe)
