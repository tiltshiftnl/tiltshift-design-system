---
layout: default
title: Molecules
description: Molecules zijn samengestelde componenten die zijn opgebouwd uit meerdere atomen. Ze bieden meer functionaliteit en complexiteit dan atomen, terwijl ze nog steeds eenvoudig en herbruikbaar blijven.
permalink: /molecules/
---

{% include molecules/page-intro.html 
    title=page.title 
    description=page.description %}

{% for molecule in site.data.elements.molecules %}
    {% include showcase.html element_id=molecule.id element_type="molecules" %}
{% endfor %}