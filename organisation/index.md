---
title: About us
label: Organizers
description: Information on the teams organising ACM CUI !!conference.year!!.

maintainer: socialmedia
lastmod: page

menu:
  main:
    text: Organizers
    title: The teams behind CUI !!conference.year!!
    weight: 6
    identifier: organisers
---

<p>
    The organization of the CUI {{ site.conference.year }} conference is pulled off by multiple incredibly dedicated teams, working together across multiple years, to ensure that everything runs smoothly on the day. The success of the conference is down to their continued effort and an incredible amount of goodwill. Information on each team is below:
</p>

<ul>
{% for item in site.menus.organisers %}
    <li class="{% if item.sep_before %}pt-3{% endif %}">
        <a class="" href="{{ item.url | absolute_url }}" title="{{ item.alt | escape | replace: "!!conference.year!!", site.conference.year | replace: "!!conference.location!!", site.conference.location | replace: "!!conference.dates!!", site.conference.dates }}">
            {{ item.title }}
        </a>
    </li>
{% endfor %}
</ul>
