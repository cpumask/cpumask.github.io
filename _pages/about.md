---
permalink: /
title:
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! I am an assistant professor at the Luddy School of Informatics, Indiana University Bloomington. 
Before joining IUB, I obtained my Ph.D. degree from [UC Riverside](https://www.ucr.edu) 
under the supervision of [Prof. Zhiyun Qian](https://www.cs.ucr.edu/~zhiyunq/), 
and received my postdoc training at [Georgia Tech](https://www.gatech.edu), 
working with [Prof. Taesoo Kim](https://taesoo.kim).  

My research area is computer system and software security, I am especially interested in devising and applying 
sophisticated  program analysis techniques to solve practical yet challenging security problems, 
such as vulnerability discovery and analysis in complex software systems like OS Kernels. 
My past research applies different approaches (e.g., manual reverse engineering, automatic static and dynamic 
program analysis) to analyze different code layers (e.g., binary, IR, and source code), revealing multiple kernel security 
vulnerabilities and resulting in open-source security tools attracting interest from both academia and industry.  

<span style="color:red;">Prospective Students: </span>
I am actively looking for Ph.D. students who are passionate about computer security research. 
If you enjoy hacking, feel free to drop me an email with your CV and a brief self-introduction! 
Though not necessary, background in program analysis, reverse engineering, CTF, bug hunting, 
or source code level understanding of complex software (e.g., OS kernels, browsers, databases) 
would be advantageous.  

## Selected Publications  
{% for post in site.publications reversed %}
  {% if post.selected %}
    {% include pub-entry.html %}
  {% endif %}
{% endfor %}

## Selected Professional Service  
* Journal Reviewer
  * IEEE Transactions on Software Engineering (TSE) 2023
  * Security and Communication Networks (SCN) 2022
  * ACM Transactions on Privacy and Security (TOPS) 2021
* Conference TPC Member
  * IEEE Security and Privacy (Oakland) 2024
  * EAI SecureComm 2023
* Sub-Reviewer
  * IEEE Security and Privacy (Oakland) 2018 - 2022
  * USENIX Security 2020, 2022 - 2023
  * ACM Conference on Computer and Communications Security (CCS) 2016 - 2019, 2023
  * Network & Distributed System Security (NDSS) 2019 - 2021
  * ACM Symposium on Operating Systems Principles (SOSP) 2021
  * ACM Internet Measurement Conference (IMC) 2017 - 2018
  * ACM AsiaCCS 2016, 2018