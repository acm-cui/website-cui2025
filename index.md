---
title: Welcome to CUI!
description: The International ACM Conversational User Interfaces conference for !!conference.year!! will take place in !!conference.location!! from !!conference.dates!!.

permalink: /
maintainer: general
lastmod: page

menu:
  main:
    text: Home
    title: CUI !!conference.year!! homepage
    weight: 1
---

<br>

<div class="row">
    <!-- <div class="col-xl-12 col-lg-12 col-md-12 col-12"> -->
    <div class="col-xl-8 col-lg-7 col-12">
        <p>
            <strong>ACM CUI {{ site.conference.year }}</strong> will be held in <strong>{{ site.conference.location }}</strong>, from <strong>{{ site.conference.dates }}</strong>. 
        </p>

        <p>
            The theme of this year's conference is “Weaving Conversations Through Tradition and Innovation”. This theme is a nod to the location of the conference, a place steeped in traditions that cross centuries, from Indigenous to Mennonite, but also a place that is nowadays associated with innovation (most famously the birthplace of the Blackberry and the revolution it has brought to connecting people through mobile communications). This arch connecting traditions to innovations is paralleled by the story of our own conference – while we are a new and innovative conference, our roots reach several decades into the past (and to the early days of voice processing, natural language interaction, and dialogue systems). We aim to weave traditions with innovations, much like the Mennonite communities with whom we’re sharing the area weave the quilts they are renowned for.
        </p>
	 <h2></h2>
    		<h2>Tracks and Deadlines:</h2>
  		<ul>
    		<li class="pt-3">Papers - 13th February 2025</li>
       		<li>Provocations - <strike><em>10th April 2025</em></strike> <b> 17th April 2025 </b> </li>
	  	<li> Short Papers & Works-in-Progress - <strike><em>10th April 2025</em></strike> <b> 17th April 2025</b></li>
     		<li>Interactivity & Creativity - <strike><em>10th April 2025</em></strike> <b> 17th April 2025 </b> </li>
		<li>Workshops - <strike><em>4th February 2025</em></strike> <b>11th February 2025 </b></li>
   		<li>Tutorials - 3rd March 2025</li>
      		<li>Doctoral Consortium - <strike><em>10th April 2025</em></strike> <b> 15th May 2025 </b> </li>
       		</ul>
	<h2></h2>
		<h2>Relevant topics</h2>
	<p>Topics relevant to the conference include, but are not limited to:</p>
	<ul>
		<li>Voice user experience</li>
		<li>Speech Interfaces</li>
		<li>Text-based conversational interfaces</li>
		<li>Chatbots</li>
		<li>Speech synthesis</li>
		<li>Speech recognition</li>
		<li>Context-aware dialogue management</li>
		<li>Conversational search</li>
		<li>Methods for conversational user interface development and evaluation</li>
		<li>Multimodal interaction involving speech, text or other language based interfaces</li>
		<li>Natural language processing and understanding related to the above</li>
		<li>Ethical and privacy considerations related to the above</li>
		<li>Large Language Models (LLMs)</li>
    </ul>

	<h2></h2>
	
		<p>
			We are planning an in-person event for {{ site.conference.year }}. <br>We hope you can join us!
			<br><br>
   			<!--<a href="https://forms.gle/MnYTTtLcHzNP8L4s5"><strong>Volunteer now to join the organizing committee (OC)! </strong>  </a><br><br>-->
      			Edith Law, Jaisie Sin, and Jim Wallace
			ACM CUI {{ site.conference.year }} Organising Committee
		</p>

		<!--<hr class="mt-4">
		
		<p class="pt-2">
		<em class="small">All deadlines are at <a href="https://time.is/Anywhere_on_Earth" title="The current time in 'Anywhere on Earth'">23:59 Anywhere on Earth</a></em>
		</p>

		<ul class="list-unstyled">

			<li>
				<h3 class="mb-0"><a href="{{ "/submit/papers/" | relative_url }}" title="CUI {{ site.conference.year }} Papers track information">Papers</a></h3>
				{% for date in site.data.track_dates['papers'] -%}
				{% if date.homepage %}
				{{ date.label }}: <br class="d-md-none">{% if date.extended_date %}<strike><em>{{ date.date }}</em></strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br><br {% unless forloop.last %}class="d-md-none"{% endunless %}>
				{% endif %}
				{%- endfor -%}
			</li>

			<li class="pt-3">
				<h3 class="mb-0">Short Papers (<a href="{{ "/submit/provocations/" | relative_url }}" title="CUI {{ site.conference.year }} Provocations track information">Provocations</a>, <a href="{{ "/submit/posters/" | relative_url }}" title="CUI {{ site.conference.year }} Posters track information">Posters</a>, <a href="{{ "/submit/demos/" | relative_url }}" title="CUI {{ site.conference.year }} Demos track information">Demos</a>)</h3>
				{% for date in site.data.track_dates['short_papers'] -%}
				{% if date.homepage %}
				{{ date.label }}: <br class="d-md-none">{% if date.extended_date %}<strike><em>{{ date.date }}</em></strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br><br {% unless forloop.last %}class="d-md-none"{% endunless %}>
				{% endif %}
				{%- endfor -%}
			</li>

			<li class="pt-3">
				<h3 class="mb-0"><a href="{{ "/submit/workshops/" | relative_url }}" title="CUI {{ site.conference.year }} Workshop track information">Workshops</a></h3>
				{% for date in site.data.track_dates['workshops'] -%}
				{% if date.homepage %}
				{{ date.label }}: <br class="d-md-none">{% if date.extended_date %}<strike><em>{{ date.date }}</em></strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br><br {% unless forloop.last %}class="d-md-none"{% endunless %}>
				{% endif %}
				{%- endfor -%}
			</li>

			<li class="pt-3">
				<h3 class="mb-0">Doctoral Consortium</h3>
				{% for date in site.data.track_dates['doctoral_consortium'] -%}
				{% if date.homepage %}
				{{ date.label }}: <br class="d-md-none">{% if date.extended_date %}<strike><em>{{ date.date }}</em></strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br><br {% unless forloop.last %}class="d-md-none"{% endunless %}>
				{% endif %}
				{%- endfor -%}
			</li>
		</ul>
		-->
	</div>

	<div class="col-xl-4 col-lg-5 col-md-6 col-12 mt-md-0 mt-4 mb-md-0 mb-5 px-md-3 px-5 d-flex align-content-start justify-content-center flex-wrap">
		<a href="https://acm.org/" title="ACM CUI {{ site.conference.year }} is an ACM In-Cooperation conference" class="flex-grow-1">
			<img src="{{ "/assets/img/banner-logo-acm.png" | relative_url }}" alt="ACM In-Cooperation logo" title="ACM CUI {{ site.conference.year }} is an ACM In-Cooperation conference" class="d-dk-none homepage-banner">
			<img src="{{ "/assets/img/logo-acm-dk.png" | relative_url }}" alt="ACM In-Cooperation logo" title="ACM CUI {{ site.conference.year }} is an ACM In-Cooperation conference" class="d-lt-none homepage-banner">
		</a>
		<a href="https://sigchi.org/" title="ACM CUI {{ site.conference.year }} is an ACM In-Cooperation conference" class="flex-grow-1">
			<img src="{{ "/assets/img/banner-sigchi.png" | relative_url }}" alt="ACM SIGCHI logo" title="ACM CUI {{ site.conference.year }} is an ACM In-Cooperation conference" class="mt-md-3 mt-5 d-dk-none homepage-banner">
			<img src="{{ "/assets/img/banner-sigchi-dk.png" | relative_url }}" alt="ACM SIGCHI logo" title="ACM CUI {{ site.conference.year }} is an ACM In-Cooperation conference" class="mt-md-3 mt-5 d-lt-none homepage-banner">
		</a>
		<a href="https://cui.acm.org/community//" title="ACM CUI {{ site.conference.year }} is part of the ACM CUI Community" class="flex-grow-1 flex-shrink-1 mt-3">
			<img src="{{ "/assets/img/logo-cui.png" | relative_url }}" alt="The ACM CUI Community" title="ACM CUI {{ site.conference.year }} is part of the ACM CUI Community" class="mt-md-3 mt-5 d-dk-none homepage-sponsor">
			<img src="{{ "/assets/img/logo-cui-dk.png" | relative_url }}" alt="The ACM CUI Community" title="ACM CUI {{ site.conference.year }} is part of the ACM CUI Community" class="mt-md-3 mt-5 d-lt-none homepage-sponsor">
		</a>
	

		<!-- comment sponsors
		<h2 class="mt-5 text-center flex-grow-1">Sponsors</h2> -->
		<!--
		<div class="d-flex flex-row flex-items-basis-0">
			<a href="https://www.fnr.lu/" title="ACM CUI {{ site.conference.year }} is sponsored by Luxembourg National Research Fund" class="flex-grow-1 flex-shrink-1">
				<img src="{{ "/assets/img/sponsor-fnr-cmyk-small.png" | relative_url }}" alt="The Luxembourg National Research Fund" title="ACM CUI {{ site.conference.year }} is sponsored by the Luxembourg National Research Fund" class="mt-md-3 mt-5 d-dk-none homepage-sponsor">
				<img src="{{ "/assets/img/sponsor-fnr-white.png" | relative_url }}" alt="Luxembourg National Research Fund" title="ACM CUI {{ site.conference.year }} is sponsored by the Luxembourg National Research Fund" class="mt-md-3 mt-5 d-lt-none homepage-sponsor">
			</a>
		</div>
		-->
		<!-- <div class="d-flex flex-row flex-items-basis-0">
			<a href="https://www.luxai.com" title="ACM CUI {{ site.conference.year }} is sponsored by the LuxAI" class="flex-grow-1 flex-shrink-1">
				<img src="{{ "/assets/img/sponsors/sponsor-lux-light.png" | relative_url }}" alt="LuxAI" title="ACM CUI {{ site.conference.year }} is sponsored by LuxAI" class="mt-md-3 mt-5 d-dk-none homepage-sponsor">
				<img src="{{ "/assets/img/sponsors/sponsor-lux-dark.png" | relative_url }}" alt="LuxAI" title="ACM CUI {{ site.conference.year }} is sponsored by LuxAI" class="mt-md-3 mt-5 d-lt-none homepage-sponsor">
			</a>
		</div> -->
		
	<!--	<div class="d-flex flex-row flex-items-basis-0 mx-auto">
			<a href="https://www.list.lu" title="ACM CUI {{ site.conference.year }} is sponsored by Luxembourg Institute of Science and Technology" class="flex-grow-1 flex-shrink-1">
				<img src="{{ "/assets/img/sponsors/sponsor-list.png" | relative_url }}" alt="Luxembourg Institute of Science and Technology" title="ACM CUI {{ site.conference.year }} is sponsored by Luxembourg Institute of Science and Technology" class="mx-auto mt-md-3 mt-5 d-dk-none homepage-sponsor">
				<img src="{{ "/assets/img/sponsors/sponsor-list-dark.png" | relative_url }}" alt="Luxembourg Institute of Science and Technology" title="ACM CUI {{ site.conference.year }} is sponsored by Luxembourg Institute of Science and Technology" class="mx-auto mt-md-3 mt-5 d-lt-none homepage-sponsor">
			</a>
		</div> -->

	<!--	<div class="d-flex flex-row flex-items-basis-0">
			<a href="https://www.uni.lu" title="ACM CUI {{ site.conference.year }} is sponsored by the University of Luxembourg" class="flex-grow-1 flex-shrink-1">
				<img src="{{ "/assets/img/sponsors/sponsor_uni_lu.png" | relative_url }}" alt="University of Luxembourg" title="ACM CUI {{ site.conference.year }} is sponsored by the University of Luxembourg" class="mt-md-3 mt-5 d-dk-none center homepage-sponsor">
				<img src="{{ "/assets/img/sponsors/sponsor_uni_lu_dark.png" | relative_url }}" alt="University of Luxembourg" title="ACM CUI {{ site.conference.year }} is sponsored by the University of Luxembourg" class="mt-md-3 mt-5 d-lt-none homepage-sponsor">
			</a>
		</div> -->

		<!--
		<div class="d-flex flex-row flex-items-basis-0">
			<a href="https://www.uni.lu/snt-en/" title="ACM CUI {{ site.conference.year }} is sponsored by the Interdisciplinary Centre
Interdisciplinary Centre for Security, Reliability and Trust" class="flex-grow-1 flex-shrink-1">
				<img src="{{ "/assets/img/sponsor-uni-snt.png" | relative_url }}" alt="The Interdisciplinary Centre
Interdisciplinary Centre for Security, Reliability and Trust" title="ACM CUI {{ site.conference.year }} is sponsored by the Interdisciplinary Centre
Interdisciplinary Centre for Security, Reliability and Trust" class="mt-md-3 mt-5 d-dk-none homepage-sponsor">
				<img src="{{ "/assets/img/sponsor-uni-snt.png" | relative_url }}" alt="Interdisciplinary Centre
Interdisciplinary Centre for Security, Reliability and Trust" title="ACM CUI {{ site.conference.year }} is sponsored by the Interdisciplinary Centre
Interdisciplinary Centre for Security, Reliability and Trust" class="mt-md-3 mt-5 d-lt-none homepage-sponsor">
			</a>
		</div>
		-->
		
		
	</div>
</div>
