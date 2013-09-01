---
layout: default

---
#Recent Posts ...

{% for post in site.posts limit: 5 %}
####  {{ post.date | date_to_long_string }} - [{{ post.title }}]( {{ post.url}})
{{ post.excerpt }}

{%  endfor   %}
