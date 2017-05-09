---
title: Guides
layout: standard
permalink: /standard/design-guides/
breadcrumb: Guides
lede: Helping you meet the Digital Service Standard.
weight: 50
phase: 'Alpha'
redirect_from: /design-guides/
---

We are working to make guidance about the [Digital Service Standard](/standard/) simpler, clearer and faster.

## GOV.AU Guides

The <a href="https://guides.service.gov.au/" rel="external">GOV.AU Guides</a> include a <a href="https://guides.service.gov.au/content-guide/" rel="external">Content Guide</a> and the <a href="https://github.com/govau/uikit" rel="external">UI-Kit CSS and JavaScript framework</a>.

### Please get involved

**Service Design Government Community**: email [leisa.reichelt@digital.gov.au](mailto:leisa.reichelt@digital.gov.au) Head of Service Design and Professional Communities.

**Content Design Government Community**: email [content@digital.gov.au](mailto:content@digital.gov.au).

**Guides team**: email <a href="mailto:guides@digital.gov.au">guides@digital.gov.au</a>.

## Other guidance

<div class="dss-guides">

<ul>

  {% for guide in site.pages %}
    {% if guide.layout == 'guide' %}
      <li><a href="{{guide.url}}">{{guide.title}}</a></li>
    {% endif %}
  {% endfor %}  

</ul>

</div>

**Last updated**: 9 May 2017
