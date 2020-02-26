---
layout: archive
title: "MusicCollection"
permalink: /MusicCollection/
author_profile: true
---

<img align="left" src=".images/NFR.jpg" width="20%" height="20%" alt="Made with Angular" title="Angular" hspace="20" />
<img align="left" src=".images/Melodrama.jpg" width="20%" height="20%" alt="Made with Bootstrap" title="Bootstrap" hspace="20"/>
<img align="left" src=".images/21.jpg" width="20%" height="20%" alt="Developed using Browsersync" title="Browsersync" hspace="20"/>

<!-- ![](/images/Album/NFR.jpg){:height="20%" width="20%"}   ![](/images/Album/Melodrama.jpg){:height="20%" width="20%"}    ![](/images/Album/21.jpg){:height="20%" width="20%"} -->


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
