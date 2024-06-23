---
title: Workshops
label: Workshops
description: CUI !!conference.year!! will feature a dedicated workshops track, allowing attendees to organise focused activities co-located at the conference. We are now open to workshops proposals.

maintainer: workshops
lastmod: page

cta:
  text: Submissions closed
  title: Submissions for workshop proposals are closed
#  link: 'mailto:cui2024-workshops@cui.acm.org'
  
track:
  chairs: workshops
  dates: workshops

menus:
  submit:
    text: Workshops
    title: Information about propsing a workshops at CUI !!conference.year!!
    weight: 4
    is_track: true
    sep_before: true
---

To propose a workshop, you should write a proposal about the topic and your plans for the workshop. If accepted, you will be expected to lead the organisation of the workshop. At least one workshop organiser is expected to attend the conference. Workshops can be planned to be entirely in-person or in hybrid mode. 

## Key dates

{% for date in site.data.track_dates[page.track.dates] -%}
{{ date.label }}: <br class="d-md-none">{% if date.extended_date %}<strike><em>{{ date.date }}</em></strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br><br {% unless forloop.last %}class="d-md-none"{% endunless %}>
{%- endfor -%}

<em class="small">All deadlines are at <a href="https://time.is/Anywhere_on_Earth" title="The current time in 'Anywhere on Earth'">23:59 Anywhere on Earth</a></em>

## The process

All submissions will proceed through the following process. Please contact the <a href="{{ site.data.oc['tracks']['roles'][page.track.chairs]['email'] }}" title="Contact the CUI {{ site.conference.year }} {{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }} if you have any questions">{{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }}</a> if you have any questions.

### 1. Prepare your proposal

Submissions of proposals for workshops must be in English, in PDF format. You should NOT anonymise your workshop proposal. Your proposal must include:

* a title,
* an abstract, 
* background to your workshop topic, 
* plans for the workshop, 
* how long the workshop will be (half-day or whole day), 
* how you will solicit papers/attendees, 
* how you will create an accessible and inclusive experience, 
* workshop’s website address, 
* biographies for the organisers.

Your proposal should be at most **5,000 words** (including figures, tables, proofs, appendixes, and other content, excluding references and acknowledgments).

You must use the [ACM LaTeX or Word templates](https://www.acm.org/publications/proceedings-template "ACM templates for Microsoft Word and LaTeX") to prepare your submission. We encourage the use of LaTeX and the official ACM template on [Overleaf](https://www.overleaf.com/latex/templates/acm-conference-proceedings-primary-article-template/wbvnghjbzwpc "ACM Primary Article Template templates on Overleaf"). LaTeX users should have the following document class: <code>\documentclass[manuscript,screen,review,anonymous]{acmart}</code>.

Word users should use [the one-column submission template](https://authors.acm.org/proceedings/production-information/preparing-your-article-with-microsoft-word "ACM Template for submissions") and should be prepared to submit to TAPS _approximately one week earlier_ than the stated camera-ready deadline.

ACM's CCS concepts and keywords are not required for submission and peer review but are required if your paper is accepted and published by the ACM.

### 2. Submit your proposal

You should submit your proposal to the <a href="{{ site.data.oc['tracks']['roles'][page.track.chairs]['email'] }}" title="Contact the CUI {{ site.conference.year }} {{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }} if you have any questions">CUI {{ site.conference.year }} {{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }}</a>: {{ site.data.oc['tracks']['roles'][page.track.chairs]['email'] | replace: "mailto:", "" }}<br>

Proposed workshop topics should be of interest to the conversational user interface research community. Possible topics include, but are not limited to: 

* Design considerations for conversational UX 
* Formatting content for conversation 
* Real-world applications of conversational agents 
* Working with foundational models (e.g., BERT, ChatGPT) 
* Hybrid approaches to voice and text 
* Understanding human conversation 
* Evaluating conversational agent performance 
* Turn-taking and interaction systems 
* Incorporating trust-worthiness into conversational agents
* Enabling multi-party collaboration with conversational agents
* Ethical considerations of conversational agents


Please follow the [SIGCHI Guide to an Accessible Submission](https://sigchi.org/conferences/author-resources/accessibility-guide/ "SIGCHI's guide to an Accessible Submission") to make your submission accessible for all users.

Submitting your article to an ACM Publication acknowledges that you and your co-authors are subject to all [ACM Publications Policies](https://www.acm.org/publications/policies "ACM Publications Policies and Procedures"). 

### 3. Await reviews

Each submission will be reviewed by one track chair and one expert reviewer through a curated process, in which reviewers will assess the novelty, feasibility, delivery and ability to engage attendees. Successful submissions will be invited to organize a workshop at CUI {{ site.conference.year }}.

### 4. Plan your workshop 

If your workshop proposal is accepted, we ask you to start work on the workshop organisation immediately. 
 
Workshop organization responsibilities include:  
* Setting up a website for the workshop 
* Publicizing the workshop and inviting potential participants to submit 
(Collecting submissions and selecting workshop participants based on the quality of their position papers (with or without external reviews) 
* Running the workshop at the conference (in-person) 
* Optionally, compiling and publishing workshop proceedings 
* Optionally, soliciting and coordinating invited speakers for the workshop 

### 5. Prepare your proposal for publication

If your proposal is accepted, you must include [CCS concepts](https://dl.acm.org/ccs "ACM Computing Classification System") and keywords for publication.

Programme Chairs will send information on preparing your proposal for the publishing process. If accepted, Word users may be required to reimplement their proposal into the correct format for publishing, while LaTeX users will have to adjust their <code>documentclass</code>.

At least one author of each accepted workshop proposal must register for the conference and attend the conference in-person; otherwise, we cannot guarantee publication of your proposal. Accepted proposals will be archived in the <a href="http://dl.acm.org/" title="The ACM Digital Library">ACM Digital Library</a>. All workshop organisers wishing to attend must register for the conference. 

You will receive an email from ACM to assign the rights for your proposal, following which you will receive an email from "The ACM Publishing System" (TAPS), which will handle the generation of the final version of your proposal. Accepted proposals will be produced from LaTeX or Word source files into a single-column HTML document and a two-column PDF for publication. We recommend all authors read ACM’s guidance for [TAPS Best Practice](https://www.acm.org/publications/taps/taps-best-practices "The ACM Publishing System (TAPS) Best Practices").

Please ensure that you and your co-authors [obtain an ORCID ID](https://orcid.org/register "Register for an ORCID ID") to complete the publishing process for your accepted paper.

All ACM publications follow the [Green Open Access route by default](https://www.acm.org/publications/openaccess#green "Details on ACM's Green Open Access policies"), although authors can independently pay a fee for [Gold Open Access](https://www.acm.org/publications/openaccess#oapricing "Details on Gold Open Access pricing for ACM publications"). The total fee payable depends on the author(s) ACM membership status.

### 6. Present your work

You will be provided details about the timings of your workshop closer to the time by the Workshops chairs.

Your proposal will be published in the CUI Proceedings in the [ACM Digital Library](http://dl.acm.org/ "ACM Digital Library"). [SIGCHI](https://sigchi.org " ACM Special Interest Group on Computer-Human Interaction") participates in the [ACM Open Table of Contents (OpenTOC)](https://www.acm.org/publications/openaccess "ACM Open Access information") service, which means proposals will be freely available from this website for the first year after publication.

## Submissions

Please send your submission to Workshops chairs Christine Murad and Sasha Vtyurina at [cui2024-workshops@cui.acm.org](mailto:cui2024-workshops@cui.acm.org "Make your submission to the workshop chairs"), with the subject line "CUI 2024 Workshop Submission".

## Questions?

{% for group in site.data.oc -%} {%- for role in group[1]['roles'] -%} {%- if role[0] == page.track.chairs -%} If you have any questions, please contact the [{{ role[1].label }}]({{ role[1].email }}), {% assign use_and = role[1]['people'] | size | plus: -1 -%} {%- for person in role[1]['people'] -%} {{- person.name -}} {%- if forloop.index == use_and %}{% if forloop.length > 2 %},{% endif %} and {% else -%}{%- unless forloop.last %}, {% endunless -%}{%- endif -%} {%- endfor %}, for support. {%- break -%} {%- endif -%} {%- endfor -%} {%- endfor -%}

