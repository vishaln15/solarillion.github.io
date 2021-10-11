---
layout: splash
title: Home
permalink: /
header:
    overlay_image: /assets/images/SFBanner.png
excerpt: 
    'Research in Edge Machine Learning, Robust Learning and Deep Learning.<br><br>[<i class="fab fa-github"></i> @solarillion](https://github.com/solarillion){: .btn .btn--github}&nbsp;&nbsp;[Join Us!](https://rebrand.ly/sf_admissions){: .btn .btn--danger}'
---
<div style="text-align: justify">
Solarillion Foundation is a not-for-profit research, outreach and education organisation working with research institutions, government agencies and organizations to carry out research on policy, technology and related areas in Edge Machine Learning, Robust Learning, Deep Learning, Renewable Energy and Sustainable Engineering.
<br><br>
Established in 2012, Solarillion encourages and mentors highly motivated undergraduate and graduate students and young professionals interested in research in the emerging areas of Edge Machine Learning, Robust Learning and Deep Learning. These students will ideally continue to pursue higher education in established institutions and follow a career path in engineering research and innovation.
</div>

## Latest News
<ul class="fa-ul">
{% assign news = site.posts %}
{% for news_item in news limit:5 %}
    {% include news-item.html item=news_item %}
{% endfor %}
</ul>

For older news, visit the <a href="/news-archive">News Archive</a>.
