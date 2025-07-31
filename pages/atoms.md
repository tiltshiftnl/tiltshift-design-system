---
layout: default
title: Atoms
description: Atoms zijn de kleinste bouwstenen van het Tiltshift Design System. Ze vormen de basis voor alle andere componenten en zijn essentieel voor het creëren van een consistente gebruikerservaring.
permalink: /atoms/
---

{% include molecules/page-intro.html 
    title=page.title 
    description=page.description %}

{% for atom in site.data.elements.atoms %}
    {% include showcase.html element_id=atom.id element_type="atoms" %}
{% endfor %}

<div class="a-card a-p-4 a-mb-4 a-mt-5">
    <h2 class="a-heading a-text-xl a-mb-3">Atomic Utility Classes</h2>
    <p class="a-text a-mb-4">Naast componenten bieden we ook utility classes voor snelle styling. Alle volgen het ABEM pattern met <code>a-</code> prefix.</p>
    
    <div class="a-grid-auto a-gap-4">
        <div>
            <h3 class="a-heading a-text-lg a-mb-2">Layout</h3>
            <ul class="a-text-sm">
                <li><code>a-block</code>, <code>a-inline-block</code></li>
                <li><code>a-flex</code>, <code>a-inline-flex</code></li>
                <li><code>a-grid</code>, <code>a-grid-auto</code></li>
                <li><code>a-relative</code>, <code>a-absolute</code>, <code>a-fixed</code></li>
            </ul>
        </div>
        
        <div>
            <h3 class="a-heading a-text-lg a-mb-2">Spacing</h3>
            <ul class="a-text-sm">
                <li><code>a-p-{0-5}</code> - padding</li>
                <li><code>a-m-{0-5}</code> - margin</li>
                <li><code>a-gap-{1-5}</code> - gap</li>
            </ul>
        </div>
        
        <div>
            <h3 class="a-heading a-text-lg a-mb-2">Typography</h3>
            <ul class="a-text-sm">
                <li><code>a-text-{xs,sm,md,lg,xl,2xl}</code></li>
                <li><code>a-font-{normal,semibold,bold}</code></li>
                <li><code>a-text-{color}</code></li>
            </ul>
        </div>
        
        <div>
            <h3 class="a-heading a-text-lg a-mb-2">Colors & Effects</h3>
            <ul class="a-text-sm">
                <li><code>a-bg-{color}</code></li>
                <li><code>a-border</code></li>
                <li><code>a-rounded-{sm,md,lg}</code></li>
                <li><code>a-shadow-{sm,md,lg}</code></li>
            </ul>
        </div>
    </div>
</div>