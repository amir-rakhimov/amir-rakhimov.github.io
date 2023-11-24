---
layout: default
title: About
permalink: /about
---

# Amir Rakhimov
I am a PhD student from Kazakhstan at the National Institute of Genetics, Japan. I am in the Biological networks laboratory under supervision of Masanori Arita. We collaborate with .

My research focuses on naked mole-rat's and their longevity. I analys gut microbiome data.


![Image](/images/logo/my-logo.png)
 
# Contact me
[Email](mailto:amir.rakhimov.b@gmail.com)

# Education
<ol>
    {% for degree in site.data.education %}
    <li class="degree"><b>{{ degree.name }}</b>, {{ degree.institution }}</li>
    <ul>
        <li class="degree"> {{degree.dates}}</li>
        <li class="degree"> Major: {{degree.major}}</li>
        <li class="degree"> Thesis title: <i>"{{degree.thesis}}"</i></li>
        <li class="degree"> Supervisors: {{degree.supervisors}}</li>
        <li class="degree"> Final grade: {{degree.final_grade}}</li>
    </ul>
    <br>
    {% endfor %}
</ol>