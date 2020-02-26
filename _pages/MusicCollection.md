---
layout: archive
title: "MusicCollection"
permalink: /MusicCollection/
author_profile: true
---


![](/images/Album/Norman20%F_____g20%Rockwell!.jpg)   ![](/images/Album/Melodrama.jpg)    ![](/images/Album/21.jpg)
*Norman Fxxxxxx Rockwell*                             *Melodrama*                         *21
*Lana Del Rey*                                        *Lorde*                             *Adele 


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
