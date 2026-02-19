---
layout: home
list_title: Posts
---
<div class="home"> <ul class="post-list"> {% for post in site.posts %} <li> <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span> <h3> <a class="post-link" href="{{ post.url | relative_url }}"> {{ post.title | escape }} </a> </h3> <div class="post-content"> {{ post.content }} </div> <hr> </li> {% endfor %} </ul> </div>