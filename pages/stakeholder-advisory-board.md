---
layout: single-column-wide
title: Stakeholder Advisory Board
enable-banner: true
enable-header: true
permalink: "/about/stakeholder-advisory-board/"
page-sections:
- _page-sections/stakeholder-adv.board.md
image: assets/img/wolfgang-hasselmann-o9djtuw2_jq-unsplash.jpg

---
{% assign groups = site.stakeholder-groups | sort: "page-order" %}
{% for group in groups %}

<div class="medium-padding-top">
    <h2>{{group.title}}</h2>
    <p>{{ group.description}}</p>

    {% assign people_array = group.associated-people %}
    {% include associated-people.html custom_array=true array=people_array display-card=true display-raw=false name=true image=true professional-title=true email=true link-to-bio-page=true link-to-personal-website=true linkedin=true twitter=true facebook=true instagram=true %}
    {% unless forloop.last %}<hr>{% endunless %}
</div>
{% endfor %}