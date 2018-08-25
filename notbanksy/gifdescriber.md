---
layout: page
title: Gif Describer
permalink: /gifdescriber/
---

# {{page.title}} Archive

I describe gifs I see. You can like them on [facebook](https://www.facebook.com/gifdescriber/).
<div class="home">
   <ul class="post-list">
    {% for gifdesc in site.gifdescriptions %}
        <li><a href="{{ meme.url }}">{{ gifdesc.title }}</a><span>{{gifdesc.content}}</span></li>
    {% endfor %}
  </ul>
</div>