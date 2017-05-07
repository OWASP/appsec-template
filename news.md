---
title: News
---

# {{page.title}}

<ul class="news">
{% for article in site.data.news %}
<li><a href="{{article.url}}">{{article.title}}</a>
{{article.ingress}}
</li>
{% endfor %}
</ul>
