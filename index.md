---
layout: default
---

## A Jekyll template for publishing single-page websites and articles that are incredibly readable and fully responsive

{% for post in site.posts %}
### {{ post.title }}
{{ post.author }}
{{ post.teaser }}
{% endfor %}