---
layout: default.liquid
title: Openscape community
---
This is Openscape, a sustainable, open source community revival and continuation of Soundscape. You can find the community [on discord](https://discord.gg/j7mMbxyf) and the code, wiki and issue trackers on [Git Hub](https://github.com/openscape-community).  

# Project status
We are currently in early testflight beta, building a community, seeking feedbac, ideas and setting up our own hosted infrastructure for the app's back-end services.  
If you are interested in the project, want to contribute or get notified of news, join our community! We can't do it alone - we need your support! Spread the word, help us translate the app as we make changes and make it available in new languages and places and more.
{% for post in collections.posts.pages %}
### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}
