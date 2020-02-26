---
layout: archive
title: "Movie Collection"
permalink: /MovieCollection/
author_profile: true
---

![](/images/Movie/adedsh.JPG){:height="50%" width="50%"} &nbsp; &nbsp;  ![](/images/Movie/ayzc.JPG){:height="50%" width="50%"}
![](/images/Movie/cgzx.JPG){:height="50%" width="50%"} &nbsp; &nbsp;  ![](/images/Movie/dbs.JPG){:height="50%" width="50%"}
![](/images/Movie/dbs.JPG){:height="50%" width="50%"} &nbsp; &nbsp;  ![](/images/Movie/djtc.JPG){:height="50%" width="50%"}
![](/images/Movie/hbdmqst.JPG){:height="50%" width="50%"} &nbsp; &nbsp;  ![](/images/Movie/hygs.JPG){:height="50%" width="50%"}
![](/images/Movie/jsc.JPG){:height="50%" width="50%"} &nbsp; &nbsp;  ![](/images/Movie/mfzybesj.JPG){:height="50%" width="50%"}
![](/images/Movie/myfi.JPG){:height="50%" width="50%"} &nbsp; &nbsp;  ![](/images/Movie/rs.JPG){:height="50%" width="50%"}
![](/images/Movie/skggp.JPG){:height="50%" width="50%"} &nbsp; &nbsp;  ![](/images/Movie/sxastd.JPG){:height="50%" width="50%"}
![](/images/Movie/wrzx.JPG){:height="50%" width="50%"} &nbsp; &nbsp;  ![](/images/Movie/xc.JPG){:height="50%" width="50%"}
![](/images/Movie/xfr.JPG){:height="50%" width="50%"} &nbsp; &nbsp;  ![](/images/Movie/xtjz.JPG){:height="50%" width="50%"}


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
