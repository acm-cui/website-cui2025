---
title: Attendance information
label: Attend
description: Information on attending CUI !!conference.year!!.

maintainer: programme
lastmod: page

menu:
  main:
    text: Attend
    title: Information for ACM CUI !!conference.year!! attendees
    weight: 3
    identifier: attend
---

<p>
    CUI {{ site.conference.year }} will be an in-person event held in {{ site.conference.location }}. More information on attending CUI can be found below:
</p>
<ul>
{% for item in site.menus.attend %}
    <li class="{% if item.sep_before %}pt-3{% endif %}">
        <a href="{{ item.url | absolute_url }}" title="{{ item.alt | escape | replace: "!!conference.year!!", site.conference.year  | replace: "!!conference.location!!", site.conference.location  | replace: "!!conference.dates!!", site.conference.dates }}">
            {{ item.title }}
        </a>
    </li>
{% endfor %}
</ul>