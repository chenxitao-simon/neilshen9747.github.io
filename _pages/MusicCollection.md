---
layout: archive
title: "MusicCollection"
permalink: /MusicCollection/
author_profile: true
---



![](/images/Album/NFR.jpg){:height="20%" width="20%"} .caption[*Norman F____ Rockwell - Lana Del Rey*]  &nbsp; &nbsp;  ![](/images/Album/Melodrama.jpg){:height="20%" width="20%"} .caption[*Melodrama - Lorde*] &nbsp; &nbsp;   ![](/images/Album/21.jpg){:height="20%" width="20%"} .caption[*21 - Adele*]
<!-- <br />Norman Fxxxxx Rockwell &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Melodrama &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 21
<br />Lana Del Rey &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Lorde &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Adele  -->

<!-- | [![](/images/Album/NFR.jpg){:height="20%" width="20%"}] | [![](/images/Album/Melodrama.jpg){:height="20%" width="20%"}] | [![](/images/Album/21.jpg){:height="20%" width="20%"}] |
|:---:|:---:|:---:|
|Norman F___ Rockwell!| Melodrama | 21 |
|Lana Del Rey | Lorde | Adele | -->

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
