---
layout: default
title: Tiltshift Design System
description: Een modulair design systeem gebaseerd op atomic design principes voor digitale transformatie projecten.
---


{% include molecules/page-intro.html 
    title=page.title
    description=page.description %}


## Kernprincipes

{% assign principes = "" | split: "" %}
{% assign principe1 = "title:Atomic Design|description:Componenten zijn opgebouwd vanuit de kleinste onderdelen (atomen) naar complexe interfaces (organismen).|category:Architecture" | split: "|" %}
{% assign principe2 = "title:Design Tokens|description:Centrale waardes voor kleuren, spacing, typography en andere designbeslissingen.|category:Styling" | split: "|" %}
{% assign principe3 = "title:Responsive|description:Alle componenten werken perfect op desktop, tablet en mobiele apparaten.|category:Experience" | split: "|" %}
{% assign principe4 = "title:Toegankelijk|description:Gebouwd volgens WCAG richtlijnen met focus op inclusief design.|category:Accessibility" | split: "|" %}

<div class="o-subject-grid ts-grid ts-grid--cols-3">
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="Atomic Design"
           description="Componenten zijn opgebouwd vanuit de kleinste onderdelen (atomen) naar complexe interfaces (organismen)."
           category="Architecture"
        %}
    </div>
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="Design Tokens"
           description="Centrale waardes voor kleuren, spacing, typography en andere designbeslissingen."
           category="Styling"
        %}
    </div>
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="Responsive"
           description="Alle componenten werken perfect op desktop, tablet en mobiele apparaten."
           category="Experience"
        %}
    </div>
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="Toegankelijk"
           description="Gebouwd volgens WCAG richtlijnen met focus op inclusief design."
           category="Accessibility"
        %}
    </div>
</div>

{% include molecules/page-intro.html 
   title="Begin direct met het Tiltshift Design System"
   title_element="h3" %}

### 1. CSS Bestanden

Voeg alle CSS bestanden toe aan je HTML:

```html
<link rel="stylesheet" href="{{ site.url }}/tiltshift-tokens.css">
<link rel="stylesheet" href="{{ site.url }}/tiltshift-base.css">
<link rel="stylesheet" href="{{ site.url }}/tiltshift-atomic.css">
<link rel="stylesheet" href="{{ site.url }}/tiltshift-components.css">
<link rel="stylesheet" href="{{ site.url }}/tiltshift-utilities.css">
<link rel="stylesheet" href="{{ site.url }}/tiltshift-themes.css">
```

### 2. Gebruik Components

Begin met atomic klassen en componenten:

```html
<button class="ts-button ts-button--primary">
  Primaire actie
</button>

<div class="a-flex a-gap-3">
  <span class="a-tag">Tag</span>
</div>
```

### 3. Style Modifiers

Pas de hele huisstijl aan met één class:

```html
<!-- Normale stijl -->
<body>

<!-- Gedurfde variant -->
<body class="ts-style-gedurfd">

<!-- Moderne variant -->
<body class="ts-style-modern">
```

{% include molecules/page-intro.html 
   title="Het Tiltshift merk"
   title_element="h3" %}

{% include molecules/text-block.html 
   title="Het Tiltshift Logo"
   content="Het Tiltshift-logo laat zien wat we doen: we helpen organisaties om net even anders te kijken. Tiltshift betekent letterlijk: de lens kantelen, spelen met perspectief. Dat is precies wat we doen bij digitale transformatie: het is geen revolutie, maar een andere invalshoek kiezen." %}

{% include atoms/logo.html size="large" %}


## Merkwaarden

<div class="o-subject-grid ts-grid ts-grid--cols-3">
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="Durven Doen"
           description="Gedoe komt er toch. Het begint met doen. Iemand moet het doen. Daar zijn wij voor."
           category="Waarde"
        %}
    </div>
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="Eerlijk Er Zijn"
           description="Er zijn is het halve werk. Betrokken zijn is alles. Eerlijk zijn is een teken van betrokkenheid."
           category="Waarde"
        %}
    </div>
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="In Beweging"
           description="Waar dingen vast zitten, is beweging stap één. Pas als dingen in beweging zijn kun je (bij)sturen. Rust roest."
           category="Waarde"
        %}
    </div>
</div>


## Taglines

<div class="o-subject-grid ts-grid ts-grid--cols-3">
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="Voelbaar Anders"
           description="Geen kille analyses van de zijlijn, maar verandering van binnenuit. Dat is voelbaar anders."
           category="Tagline"
        %}
    </div>
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="We Doen Het Echt"
           description="Geen agile in name only. De mens écht centraal. Open samenwerken. We doen het echt, samen met de mensen die het moeten doen."
           category="Tagline"
        %}
    </div>
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="Maak Het Echt"
           description="Niet blijven praten en filosoferen. We maken dingen echt. Dat levert hele andere gesprekken op."
           category="Tagline"
        %}
    </div>
</div>


## Beeldgebruik

{% include molecules/text-block.html 
   title="Fotografie Richtlijnen"
   content="We gebruiken authentieke fotografie die de werkelijkheid van digitale transformatie laat zien. Geen geposeerde stockfoto's, maar echte mensen in echte werksituaties."
   variant="highlight" %}

<div class="o-subject-grid ts-grid ts-grid--cols-3">
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="Mensen aan het werk"
           description="We tonen mensen in hun natuurlijke werkomgeving. Bezig met echte taken, niet kijkend naar de camera."
           category="Beeld"
        %}
    </div>
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="Zwart-wit fotografie"
           description="Krachtige zwart-wit beelden met grote korrel voor een rauwe, authentieke uitstraling."
           category="Beeld"
        %}
    </div>
    <div class="o-subject-grid__item">
        {% include molecules/subject-card.html 
           title="Niet geposeerd"
           description="Spontane momenten vastgelegd. Geen geforceerde lachjes, maar oprechte interacties."
           category="Beeld"
        %}
    </div>
</div>


## Favicon

Voor een consistente merkbeleving over alle digitale kanalen gebruikt het design system de Tiltshift favicon.

```html
<!-- Favicon implementatie -->
<link rel="icon" type="image/png" sizes="32x32" href="{{ site.url }}/assets/favicon/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="{{ site.url }}/assets/favicon/favicon-16x16.png">
<link rel="shortcut icon" href="{{ site.url }}/assets/favicon/favicon.ico">
```

De favicon bestanden zijn beschikbaar in `/assets/favicon/`


## Kleuren

{% include molecules/text-block.html 
   content="Onze kleurenpalet is direct en krachtig - net als onze aanpak." %}

<div class="a-grid-auto a-gap-4">
    {% include atoms/color-swatch.html 
       color="#E64544"
       name="Primary Red"
       description="Energie & Actie" %}
    
    {% include atoms/color-swatch.html 
       color="#1E59A6"
       name="Primary Blue"
       description="Vertrouwen & Stabiliteit" %}
    
    {% include atoms/color-swatch.html 
       color="#1D1621"
       name="Black"
       description="Kracht & Professionaliteit" %}
    
    {% include atoms/color-swatch.html 
       color="#FFFFFF"
       name="White"
       description="Helderheid & Eenvoud"
       class="a-border" %}
</div>


## Entity Patterns

Het Tiltshift Design System kent vier core entiteiten:

### People
Team members, medewerkers, contactpersonen
- `people-card` (molecule)
- `people-grid` (organism)

### Projects
Projecten, case studies, portfolio items
- `project-card` (molecule)
- `project-grid` (organism)

### Organizations
Opdrachtgevers, partners, stakeholders
- `organization-card` (molecule)
- `organization-grid` (organism)

### Subjects
Onderwerpen, diensten, expertise gebieden
- `subject-card` (molecule)
- `subject-grid` (organism)

{% include molecules/cta.html 
   text="Start met het Design System"
   link="/atoms"
   type="primary" %}

<script>
    // Mobile sidebar functionality
    function toggleSidebar() {
        const sidebar = document.getElementById('sidebar');
        const overlay = document.getElementById('overlay');
        
        if (sidebar && overlay) {
            sidebar.classList.toggle('is-active');
            overlay.classList.toggle('is-active');
            
            // Prevent body scroll when sidebar is open
            if (sidebar.classList.contains('is-active')) {
                document.body.style.overflow = 'hidden';
            } else {
                document.body.style.overflow = '';
            }
        }
    }
    
    // Close sidebar when clicking overlay
    document.addEventListener('DOMContentLoaded', function() {
        const overlay = document.getElementById('overlay');
        if (overlay) {
            overlay.addEventListener('click', toggleSidebar);
        }
    });
    
    // Handle resize events - close sidebar on larger screens
    window.addEventListener('resize', function() {
        const sidebar = document.getElementById('sidebar');
        const overlay = document.getElementById('overlay');
        
        if (window.innerWidth >= 768) {
            if (sidebar && sidebar.classList.contains('is-active')) {
                sidebar.classList.remove('is-active');
                overlay.classList.remove('is-active');
                document.body.style.overflow = '';
            }
            // Reset sidebar styles
            sidebar.style.position = '';
            sidebar.style.top = '';
            sidebar.style.left = '';
            sidebar.style.right = '';
            sidebar.style.zIndex = '';
            sidebar.style.backgroundColor = '';
            sidebar.style.padding = '';
            sidebar.style.boxShadow = '';
        }
    });
</script>