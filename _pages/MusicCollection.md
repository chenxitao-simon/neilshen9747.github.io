---
layout: archive
title: "MusicCollection"
permalink: /MusicCollection/
author_profile: true
---


![](/images/Album/Norman20%F_____g20%Rockwell!.jpg){:height="33%" width="33%"}   ![](/images/Album/Melodrama.jpg){:height="33%" width="33%"}    ![](/images/Album/21.jpg){:height="33%" width="33%"}


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
