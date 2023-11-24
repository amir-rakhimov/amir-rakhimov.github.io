---
layout: default
title: About
permalink: /about
---

My name is Amir Rakhimov. I'm a PhD student at the National Institute of Genetics, Japan.
Originally, I'm from Kazakhstan. This website is a collection of my projects, papers, and other things.

![Image](/images/logo/my-logo.png)
 
# Contact me
[Email](mailto:amir.rakhimov.b@gmail.com)

# Education
<ol>
    {% for degree in site.data.education %}
    <li class="degree">{{ degree.name }}, {{ degree.institution }}</li>
    <ul>
        <li class="degree"> {{degree.dates}}</li>
        <li class="degree"> {{degree.major}}</li>
        <li class="degree"> {{degree.supervisors}}</li>
    </ul>
    <br>
    {% endfor %}
</ol>