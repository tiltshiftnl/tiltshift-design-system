---
layout: default
title: Organisms
description: Organisms zijn complexe componenten die zijn opgebouwd uit meerdere atomen en moleculen. Ze bieden een hogere mate van functionaliteit en kunnen zelfstandig functioneren binnen de gebruikersinterface.
permalink: /organisms/
---

<section class="o-section">
    {% include molecules/page-intro.html 
       title=page.title 
       description=page.description %}

    {% for organism in site.data.elements.organisms %}
        {% include showcase.html element_id=organism.id element_type="organisms" %}
    {% endfor %}
</section>