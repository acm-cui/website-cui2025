---
title: Tutorials
label: Tutorials 
description: CUI !!conference.year!! will feature a dedicated tutorials track. Tutorials are in-depth presentations of fundamental or state-of-the-art topics presented by researchers or practitioners within the field of CUI.

maintainer: workshops
lastmod: page

track:
  chairs: tutorials
  dates: tutorials

menus:
  submit:
    text: Tutorials
    title: Information about propsing a tutorial at CUI !!conference.year!!
    weight: 4
    is_track: true
    sep_before: true
---

## Call for Tutorials

CUI 2025 tutorials are in-depth presentations of fundamental or state-of-the-art topics presented by researchers or practitioners within the field of CUI. The tutorials offer attendees an introduction to novel concepts and technologies, empower them to learn new skills, and present them with possibilities to meet new people and discuss topics of shared interest. The scope for tutorials is broad and includes topics, such as LLMs, context-aware conversational-agents, chatbots, Natural Language Processing for CA, personas in CA, Human-AI collaboration for different settings such as healthcare, education, home, public etc.

A tutorial should focus on its topic in detail and include references to the "must-read" papers or materials within its domain. A participatory approach in which the tutorial participants actively engage in exercises is strongly encouraged, though not strictly required. The expected audience will vary in terms of prior knowledge, but will largely consist of researchers, PhD students, practitioners, and educators. Tutorial proposal submissions by industrial researchers or practitioners are welcomed as well.

The overall conference theme in 2025 is “Weaving Conversations Through Tradition and Innovation", so we invite tutorials to discuss ethical aspects of their work, as part of their problem definitions, system design, experiment design, instrument and metric adoption and conclusions.
CUI2025 will be held in person in July 2025 in Waterloo, Ontario, Canada. Tutorials with the physical presence of the instructors are highly recommended.

## Deadlines

{% for date in site.data.track_dates[page.track.dates] -%}
{{ date.label }}: <br class="d-md-none">{% if date.extended_date %}<strike><em>{{ date.date }}</em></strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br><br {% unless forloop.last %}class="d-md-none"{% endunless %}>
{%- endfor -%}

<em class="small">All deadlines are at <a href="https://time.is/Anywhere_on_Earth" title="The current time in 'Anywhere on Earth'">23:59 Anywhere on Earth</a></em>

## Submission Platform

* All materials must be submitted electronically to [PCS](https://new.precisionconference.com/submissions) by the deadline.
* In PCS, first, click "Submissions" at the top of the page. Then, from the dropdown menu, select "SIGCHI", "CUI 2025", and the "Tutorials" track.

## Submission Format and Length

* Use the SIGCHI conference proceedings primary template
    * [ACM Templates and publishing process](https://authors.acm.org/proceedings/production-information/taps-production-workflow) | [Overleaf template](https://www.overleaf.com/gallery/tagged/acm-official#.WOuOk2e1taQ) "Computing Machinery (ACM) - Official Primary Article Templates")
    * [Guide to accessible submissions](https://sigchi.org/resources/guides-for-authors/accessibility/ "Accessibility guide for authors
")
    * [Accessible PDF Author Guide](https://www.sigaccess.org/welcome-to-sigaccess/resources/accessible-pdf-author-guide/ "Accessible PDF Author Guide
")
    * [Accessible Presentation Guide](https://www.sigaccess.org/welcome-to-sigaccess/resources/accessible-presentation-guide/ "Accessible Presentation Guide
")
    * [Adding Document Tags](https://chi2021.acm.org/for-authors/presenting/papers/guide-to-an-accessible-submission#:~:text=Add%20document%20tags.&text=You%20can%20check%20to%20see,menu%2C%20then%20click%20Full%20Check "Adding Document Tags")
    * [PDF Accessibility Checker](https://checkers.eiii.eu/en/pdfcheck/ "Check the Accessibility of a PDF Document")
* Maximum 6 pages (excluding references)

## Preparing the Submission

In your proposal please include:

* The title of the tutorial
* Abstract (approximately 200 words)
* <strong>Description:</strong> The covered topics and the depths to which you will cover them.
* <strong>Relevance to CUI:</strong> Why is this tutorial relevant to CUI and of potential interest to attendees?
* <strong>Learning Outcomes:</strong> What will attendees have learned/achieved after your tutorial?
* <strong>Structure of the tutorial:</strong> A timeline and description of activities taking place during the tutorial (e.g. talks, discussion, group work, hands-on coding or design activities, panel discussions, demonstrations, Q&A). Tutorials have a recommended length between one and three hours.
The intended audience(s) of the tutorial: Please outline likely attendees for your tutorial. Any prerequisite knowledge or background must be explicitly described (e.g. “basic Python programming skills”).
Overview of the learning materials provided to the participants before and after the tutorial.
* <strong>A brief biography of the instructor(s):</strong> We encourage a maximum of 3 presenters. Please provide adequate justification in case more are needed. If you plan to hold a panel or invited speakers during the tutorial, please provide brief details on these persons as well. Information on previous experience in organising tutorials (e.g. name, dates, conference, number of participants) is highly desirable.

## Anonymity

Tutorials are not submitted anonymously, i.e. instructors do not remove their names and affiliations from their submission materials.

## Selection Process

The selection will be curated by the Tutorials Chairs.

## Publication

Accepted tutorial proposals will be included in the ACM Digital Library as part of the CUI 2025 Adjunct Proceedings. ACM will send the organizers a copyright form, which they have to complete. Once completed, ACM will provide organizers with the copyright information to put into the camera-ready paper. Then, the camera-ready version (including the copyright notice) can be submitted through the submission system. The official publication date is the date the proceedings are made available in the ACM Digital Library.

