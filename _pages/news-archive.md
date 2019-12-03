---
layout: splash
permalink: /news-archive/
---
## News Archive
<ul class="fa-ul">
{% assign news = site.posts %}
{% for news_item in news %}
    {% include news-item.html item=news_item %}
{% endfor %}
</ul>
