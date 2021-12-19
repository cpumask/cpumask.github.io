---
permalink: /
title:
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! My name is Hang Zhang, I am a postdoc researcher in [SSLab](https://gts3.org) at [GaTech](https://www.gatech.edu), 
working with [Prof. Taesoo Kim](https://taesoo.kim).
I obtained my Ph.D degree from [UC Riverside](https://www.ucr.edu), under the supervision of 
[Prof. Zhiyun Qian](https://www.cs.ucr.edu/~zhiyunq/).  

My research area is Computer System Security, with a focus on vulnerability discovery and analysis in complex software
systems like OS Kernels. I am especially interested in bringing sophiscated program analysis techniques to the system security
research.
My past research apply different approaches (e.g., manual reverse engineering, automatic static and dynamic
program analysis) to analyze different code layers (e.g., binary, IR, and source code), revealing multiple kernel security 
vulnerabilities and resulting in open-source security tools.  

## Selected Publications  
{% for post in site.publications reversed %}
  {% if post.selected %}
    {% include pub-entry.html %}
  {% endif %}
{% endfor %}
