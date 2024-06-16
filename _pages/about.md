---
permalink: /about/
title: "The Team"
layout: single
---

<div class="grid-container" style="display:grid;grid-template-columns: auto auto auto auto;">
{% for member in site.data.members %}
    <div class="bio">
        <img src="{{ site.baseurl }}/{{ member.photo }}">
        <div class="name"> {{ member.name }} </div>
        <p> {{ member.bio }} </p>
    </div>
{% endfor %}
</div>