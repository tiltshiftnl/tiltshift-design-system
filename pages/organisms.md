---
layout: default
title: Organisms
description: Organisms zijn complexe componenten die zijn opgebouwd uit meerdere atomen en moleculen. Ze bieden een hogere mate van functionaliteit en kunnen zelfstandig functioneren binnen de gebruikersinterface.
permalink: /organisms/
---

<section class="organism-section">
    <div class="organism-section__header">
        <h1 class="organism-section__title">Organisms</h1>
        <p class="organism-section__description">{{ page.description }}</p>
    </div>

    {% include organisms/project-preview.html %}
    {% include show-source.html component="project-preview" type="organisms" %}
    
    {% include organisms/team-member.html %}
    {% include show-source.html component="team-member" type="organisms" %}
    
    {% include organisms/form.html %}
    {% include show-source.html component="form" type="organisms" %}
    
    {% include organisms/alert.html %}
    {% include show-source.html component="alert" type="organisms" %}
    
    {% include organisms/blockquote.html %}
    {% include show-source.html component="blockquote" type="organisms" %}
    
    {% include organisms/text-block.html %}
    {% include show-source.html component="text-block" type="organisms" %}
    
    {% include organisms/text-block-highlight.html %}
    {% include show-source.html component="text-block-highlight" type="organisms" %}
    
    {% include organisms/grid-system.html %}
    {% include show-source.html component="grid-system" type="organisms" %}
    
    {% include organisms/footer.html %}
    {% include show-source.html component="footer" type="organisms" %}
    
    {% include organisms/navigation.html %}
    {% include show-source.html component="navigation" type="organisms" %}
    
    {% include organisms/breadcrumbs.html %}
    {% include show-source.html component="breadcrumbs" type="organisms" %}
    
    {% include organisms/auto-tint.html %}
    {% include show-source.html component="auto-tint" type="organisms" %}
    
    {% include organisms/cta.html %}
    {% include show-source.html component="cta" type="organisms" %}
    
    {% include organisms/project-grid.html %}
    {% include show-source.html component="project-grid" type="organisms" %}
    
    {% include organisms/hero.html %}
    {% include show-source.html component="hero" type="organisms" %}
</section>
