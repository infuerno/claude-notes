---
layout: default
---
# Claude Notes
 
Random notes made with the help of Claude.
 
## Notes
 
<ul class="notes">
{%- for post in site.posts %}
  <li><time>{{ post.date | date: "%-d %b %Y" }}</time> <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{%- endfor %}
</ul>