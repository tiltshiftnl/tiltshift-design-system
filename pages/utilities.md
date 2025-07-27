---
layout: default
title: Utilities
description: Utilities zijn herbruikbare stijlen die kunnen worden toegepast op verschillende elementen om consistentie en efficiëntie te waarborgen in het TILTSHIFT Design System. Ze zijn ontworpen om snel en eenvoudig toe te passen, waardoor ontwikkelaars en ontwerpers flexibeler kunnen werken zonder dat ze telkens nieuwe CSS moeten schrijven.
permalink: /utilities/
---

<section class="organism-section">
    <div class="organism-section__header">
        <h1 class="organism-section__title">Utilities</h1>
        <p class="organism-section__description">{{ page.description }}</p>
    </div>

    {% include utilities/layout.html %}
    {% include show-source.html component="layout" type="utilities" %}
    
    {% include utilities/spacing.html %}
    {% include show-source.html component="spacing" type="utilities" %}
    
    {% include utilities/typography.html %}
    {% include show-source.html component="typography" type="utilities" %}
    
    {% include utilities/colors.html %}
    {% include show-source.html component="colors" type="utilities" %}
    
    {% include utilities/showcase.html %}
    {% include show-source.html component="showcase" type="utilities" %}
</section>