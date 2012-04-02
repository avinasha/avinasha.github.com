---
layout: page
title: Avinasha S!
---
{% include JB/setup %}

Time to get my personal site going...

    <!DOCTYPE html>
    <htm ...

**&lt;Campfire Pings&gt;**

Ahh.. Work.. New Bug in [SupportBee](http://supportbee.com)

That was a quick fix!! I love doing **TDD** in **Ruby on Rails** and **Backbone.js**

    ... l>
    <head ...

Wow.. SupportBee's blogpost is on front page of HackerNews. Time to write one more!!

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

Now where was I...

    <head>
      <title> Avi...

Ahh.. Finally the weather clears up.. Time to travel!! Oh I write about those and much more [here](http://blog.avinasha.com)  

Oh.. I need to complete this page...

Ahh. screw it.. Wanna get in touch??  
[Twitter](http://twitter.com/AviShastry) | [Mail](mailto:me@avinasha.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".



## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


