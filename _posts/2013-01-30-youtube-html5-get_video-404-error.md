---
layout: post
title: "Youtube HTML5 Player get_video 404 Error"
description: "Google owns Chrome and Youtube but doesn't know how to get the two to work together"
category: google
tags: [chrome,youtube,google,404,get_video]
---
{% include JB/setup %}
## About Tired of Chrome and Youtube Not Playing Well Together

It would be similar if say, the Navy and the Army fought each other or Ford started building aftermarket car radios that only worked in every car except Ford. You would think if a company owned two pieces of technology they would make damn sure that these two things would work well together, but I guess with Google this is just not the case.

So when I see a JavaScript error using the YouTube API in Chrome, I pretty much assume it's a Chrome issue any more, especially if that is the only place it is happening. Why?

##Unable to post message to http://www.youtube.com. Recipient has origin

This is a known Webkit bug, so it doesn't just effect Chrome but Safari also and a few lesser known browsers using the Webkit engine. It happens when you start a video using the API. Using the YouTube play button on the video is fine, but creating your own button and using the YouTube provided JavaScript to start the video will result in this error. So if you do that, just plan on seeing this error every time a video is played because there is no fix in this case.

##GET http://www.youtube.com/get_video?... 404 (Not Found)

This is a new one. Seems to happen only in good old Chrome using the HTML5 player API. Considering the bug from the last issue is caused by a callback firing before the video is ready, I am kind of assuming this is the same type of issue. Though I am not sure yet. I haven't found much on this error.

Everything in Google has to do with scraping and downloading YouTube videos when it comes to searching for this error. Here is the type of url that is erroring:

http://www.youtube.com/get_video?noflv=1&video_id=CwU6qFDkHvQ&cpn=ew4pC_u%2F&fmt=43&ptk=youtube_none&splay=1&start=14.35699965804815

That is not the complete url but notice the start parameter. It seems that would be the position in the video to start playing. The funny thing is, this error happens after trying to start the video at the beginning. Still hunting for the real answer to this error.