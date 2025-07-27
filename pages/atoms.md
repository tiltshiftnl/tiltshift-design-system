---
layout: default
title: Atoms
description: Atoms zijn de kleinste bouwstenen van het TILTSHIFT Design System. Ze vormen de basis voor alle andere componenten en zijn essentieel voor het creëren van een consistente gebruikerservaring.
permalink: /atoms/
---

<section class="organism-section">
    <div class="organism-section__header">
        <h1 class="organism-section__title">Atoms</h1>
        <p class="organism-section__description">{{ page.description }}</p>
    </div>

    {% include atoms/logo.html %}
    {% include show-source.html component="logo" type="atoms" %}
    
    {% include atoms/buttons.html %}
    {% include show-source.html component="buttons" type="atoms" %}
    
    {% include atoms/labels.html %}
    {% include show-source.html component="labels" type="atoms" %}
    
    {% include atoms/typography.html %}
    {% include show-source.html component="typography" type="atoms" %}
    
    {% include atoms/interactive-elements.html %}
    {% include show-source.html component="interactive-elements" type="atoms" %}
</section>