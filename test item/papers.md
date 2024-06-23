---
title: Papers
label: Papers
description: "The Papers track at CUI !!conference.year!! is for original contributions from a broad range of disciplines including: human-computer interaction, computer science, engineering, speech technology, linguistics, psychology, cognitive sciences, sociology and other cognate disciplines."

maintainer: papers
lastmod: page

cta:
  text: Submissions closed
  title: Submissions for the papers track have now closed
#  link: /2024/submit/pcs/

track:
  chairs: papers
  dates: papers

menus:
  submit:
    text: Papers
    title: Information about submitting to the Papers track at CUI !!conference.year!!
    weight: 0
    is_track: true
---

We invite the submission of research papers from a broad range of disciplines, including human-computer interaction, computer science, engineering, speech technology, linguistics, psychology, cognitive sciences, sociology, and other cognate disciplines. We encourage the submission of high-quality replication studies in addition to well-designed studies with null results.

Papers must describe original work that has not been previously published, not accepted for publication elsewhere, and is not simultaneously submitted or currently under review in another journal or conference (including [the other tracks of ACM CUI 2024]({{ "/submit/" | relative_url }} "All submission tracks at CUI {{ site.conference.year }}")).

## Key dates

{% for date in site.data.track_dates[page.track.dates] -%}
{{ date.label }}: <br class="d-md-none">{% if date.extended_date %}<strike><em>{{ date.date }}</em></strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br><br {% unless forloop.last %}class="d-md-none"{% endunless %}>
{%- endfor -%}

<em class="small">All deadlines are at <a href="https://time.is/Anywhere_on_Earth" title="The current time in 'Anywhere on Earth'">23:59 Anywhere on Earth</a></em>


## The process

All submissions will proceed through the following process. Please [contact the Papers chairs](mailto:cui2024-papers@cui.acm.org) if you have any questions.


### 1. Prepare your paper

Submissions of research papers must be in English, in PDF format, anonymised using the[ CHI anonymization policy](https://chi2024.acm.org/for-authors/presenting/papers/chi-anonymization-policy/ "CHI 2024 Anonymization Policy"), and approximately **6,000-8,000 words** (including figures, tables, proofs, appendixes, and any other content excluding references and acknowledgments). Submissions above 8,000 or below 5,000 words will be considered for desk rejection. Papers whose lengths are incommensurate with their contributions will be rejected.

You must use the [ACM LaTeX or Word templates](https://www.acm.org/publications/proceedings-template) to prepare your submission. We encourage the use of LaTeX and the official ACM template on [Overleaf](https://www.overleaf.com/latex/templates/acm-conference-proceedings-primary-article-template/wbvnghjbzwpc). LaTeX users must employ the following document class for submission: <code>\documentclass[manuscript,screen,review,anonymous]{acmart}</code>. Word users must use[ the one-column submission template](https://authors.acm.org/proceedings/production-information/preparing-your-article-with-microsoft-word) and should be prepared to submit to TAPS _approximately one week earlier_ than the stated camera-ready deadline.

ACM’s CCS concepts and keywords are not required for submission and peer review but are required if your paper is accepted and published by the ACM.


### 2. Submit your paper

You should submit your paper to the[ conference submission system]({{ "/submit/pcs/" | relative_url }} "CUI {{ site.conference.year }} submission system"). You must include your title, abstract, author details, and an anonymised paper as a PDF. Please follow the [SIGCHI Guide to an Accessible Submission](https://sigchi.org/conferences/author-resources/accessibility-guide/) to make your submission accessible for all users.

Submitting your article to an ACM Publication acknowledges that you and your co-authors are subject to all [ACM Publications Policies](https://www.acm.org/publications/policies).


### 3. Await reviews

Three reviewers will review all papers. Another programme committee member will lead the reviewing process, write a metareview, and later check on the paper for final acceptance if it got conditionally accepted (all accept decisions are conditional).


### 4. Prepare your paper for publication

If your paper is accepted, you will receive an email from us on how to ready your paper for publishing. At least one author of each accepted paper must register for the conference. Otherwise, we cannot guarantee the publication of your paper. Please ensure that you and your co-authors[ obtain an ORCID ID](https://orcid.org/register) to complete the publishing process for your accepted paper.

Your paper will be published in the ACM CUI Proceedings in the [ACM Digital Library](http://dl.acm.org/).[ SIGCHI](https://sigchi.org) participates in the [ACM Open Table of Contents (OpenTOC)](https://www.acm.org/publications/openaccess#h-acm-opentoc-service) service, which means papers will be freely available from this website for the first year after publication. Publications are [Green Open Access](https://www.acm.org/publications/openaccess#h-green-open-access) by default but can be upgraded to [Gold Open Access](https://www.acm.org/publications/openaccess#h-gold-open-access-publication) for a fee.


### 5. Present your paper

Authors will be given an oral presentation slot at the conference. The specific details of this presentation will be provided closer to the conference.


## Questions?

{% for group in site.data.oc -%} {%- for role in group[1]['roles'] -%} {%- if role[0] == page.track.chairs -%} If you have any questions, please contact the [{{ role[1].label }}]({{ role[1].email }}), {% assign use_and = role[1]['people'] | size | plus: -1 -%} {%- for person in role[1]['people'] -%} {{- person.name -}} {%- if forloop.index == use_and %}{% if forloop.length > 2 %},{% endif %} and {% else -%}{%- unless forloop.last %}, {% endunless -%}{%- endif -%} {%- endfor %}, for support. {%- break -%} {%- endif -%} {%- endfor -%} {%- endfor -%}
