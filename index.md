---
layout: default.liquid
title: Openscape community
---
This is Openscape, a community revival and continuation of Soundscape. You can find the community [on discord](https://discord.gg/j7mMbxyf) and [Git Hub](https://github.com/openscape-community).  


{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}
