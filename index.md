---
layout: page
title: Last Pages
tagline: Supporting tagline
---
{% include JB/setup %}

{% for post in site.posts %}
# {{ post.date | date_to_string }} [{{ post.title }}]({{ BASE_PATH }}{{ post.url }})
{{post.content}}
{% endfor %}
