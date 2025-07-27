---
layout: default
title: Molecules
description: Molecules zijn samengestelde componenten die zijn opgebouwd uit meerdere atomen. Ze bieden meer functionaliteit en complexiteit dan atomen, terwijl ze nog steeds eenvoudig en herbruikbaar blijven.
permalink: /molecules/
---

<section class="organism-section">
    <div class="organism-section__header">
        <h1 class="organism-section__title">Molecules</h1>
        <p class="organism-section__description">{{ page.description }}</p>
    </div>

    {% include molecules/card.html %}
    {% include show-source.html component="card" type="molecules" %}
    
    {% include molecules/container.html %}
    {% include show-source.html component="container" type="molecules" %}
    
    {% include molecules/title.html %}
    {% include show-source.html component="title" type="molecules" %}
    
    {% include molecules/tags.html %}
    {% include show-source.html component="tags" type="molecules" %}
    
    {% include molecules/image-container.html %}
    {% include show-source.html component="image-container" type="molecules" %}
    
    {% include molecules/contact-info.html %}
    {% include show-source.html component="contact-info" type="molecules" %}
    
    {% include molecules/social-links.html %}
    {% include show-source.html component="social-links" type="molecules" %}
    
    {% include molecules/map.html %}
    {% include show-source.html component="map" type="molecules" %}
</section>
