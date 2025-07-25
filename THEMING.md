# 🎨 TILTSHIFT Theme System

Maak je website eenvoudig **gedurfder**, **subtieler**, of **moderner** met één CSS class!

## 🚀 Quick Start

### Stap 1: Voeg het theme bestand toe
```html
<link rel="stylesheet" href="tiltshift-tokens.css">
<link rel="stylesheet" href="tiltshift-base.css">
<link rel="stylesheet" href="tiltshift-components.css">
<link rel="stylesheet" href="tiltshift-utilities.css">
<link rel="stylesheet" href="tiltshift-themes.css"> <!-- 👈 Nieuw! -->
```

### Stap 2: Kies je theme
Voeg een class toe aan je `<body>` tag:

```html
<!-- Normaal (standaard) -->
<body>

<!-- Gedurfder -->
<body class="ts-theme-bold">

<!-- Heel gedurfd -->
<body class="ts-theme-daring">

<!-- Subtieler -->
<body class="ts-theme-subtle">
```

## 🎭 Beschikbare Themes

### **Intensiteit Themes**
Perfect voor "maak het eens wat gedurfder" type aanpassingen:

```html
<!-- 70% van originele grootte/spacing - rustiger -->
<body class="ts-theme-subtle">

<!-- 130% - gedurfder, meer aanwezig -->
<body class="ts-theme-bold"> 

<!-- 160% - zeer gedurfd, dramatic -->
<body class="ts-theme-daring">
```

### **Persoonlijkheid Themes**
Voor complete stijl transformaties:

```html
<!-- Zakelijk, professioneel, rustiger -->
<body class="ts-theme-conservative">

<!-- Strak, modern, tech-achtig -->
<body class="ts-theme-modern">

<!-- Levendig, creatief, opvallend -->  
<body class="ts-theme-creative">

<!-- Verfijnd, minimaal, elegant -->
<body class="ts-theme-elegant">
```

## ⚡ Quick Modifiers

Voor specifieke aanpassingen:

```html
<!-- Alles 20% groter -->
<body class="ts-scale-up">

<!-- Alles 20% kleiner -->  
<body class="ts-scale-down">

<!-- Meer ruimte tussen elementen -->
<body class="ts-spacious">

<!-- Compacter -->
<body class="ts-compact">

<!-- Dramatische schaduwen -->
<body class="ts-dramatic-shadows">

<!-- Geen schaduwen -->
<body class="ts-no-shadows">
```

## 🔄 Combineren

Je kunt themes combineren voor precies het effect dat je wilt:

```html
<!-- Gedurfd + spacious = groot en ruim -->
<body class="ts-theme-bold ts-spacious">

<!-- Modern + dramatic shadows = tech met impact -->
<body class="ts-theme-modern ts-dramatic-shadows">

<!-- Elegant + subtle shadows = minimaal en verfijnd -->
<body class="ts-theme-elegant ts-subtle-shadows">
```

## 🎯 Wat verandert er?

### **Intensiteit Themes** wijzigen:
- ✅ Logo groottes
- ✅ Button padding  
- ✅ Spacing tussen elementen
- ✅ Schaduw intensiteit
- ✅ Algemene 'presence' van elementen

### **Persoonlijkheid Themes** wijzigen ook:
- 🎨 Kleuren (primary/secondary)
- 📐 Border radius (hoeken)
- 🎭 Complete visuele persoonlijkheid

## 📝 Voorbeelden

### "Maak het gedurfder"
```html
<!-- Van dit -->
<body>

<!-- Naar dit -->
<body class="ts-theme-bold">
<!-- Logo's 30% groter, meer spacing, sterkere schaduwen -->
```

### "Moderne, strakke uitstraling"
```html
<body class="ts-theme-modern ts-dramatic-shadows">
<!-- Fellere kleuren, strakke hoeken, sterke schaduwen -->
```

### "Rustiger en professioneler"
```html  
<body class="ts-theme-conservative ts-subtle-shadows">
<!-- Gedempte kleuren, minder spacing, subtiele schaduwen -->
```

### "Heel opvallend voor event"
```html
<body class="ts-theme-creative ts-scale-up ts-spacious">
<!-- Levendige kleuren, alles groter, veel ruimte -->
```

### "Ultra gedurfd met alle effecten"
```html
<body class="ts-ultra-bold ts-dramatic-shadows ts-spacious">
<!-- Maximum visual impact: dramatische kleuren, glows, grote spacing -->
```

## 🛠️ Custom Aanpassingen

Voor brand-specifieke aanpassingen kun je de CSS custom properties overschrijven:

```css
/* Jouw eigen "gedurfd" theme */
.my-custom-theme {
  --ts-spacing-multiplier: 1.5;    /* 50% meer spacing */
  --ts-scale-multiplier: 1.2;      /* 20% groter */  
  --ts-shadow-multiplier: 2;       /* 2x sterkere schaduwen */
  
  /* Custom kleuren */
  --ts-color-primary: #your-brand-color;
  --ts-color-primary-dark: #your-dark-color;
}
```

## ⚠️ Belangrijk

- Themes werken op alle bestaande componenten
- Geen breaking changes - alle existing code blijft werken
- Themes kunnen real-time gewisseld worden (bijv. met JavaScript)
- Alle spacing/sizing blijft proportioneel

## 🔧 JavaScript Toggle

```javascript
// Toggle tussen themes
function makeItBolder() {
  document.body.className = 'ts-theme-bold';
}

function makeItSubtle() {
  document.body.className = 'ts-theme-subtle';  
}

function makeItModern() {
  document.body.className = 'ts-theme-modern ts-dramatic-shadows';
}

// Ultra gedurfd met animaties (zoals de "Gedurfd" button)
function makeItUltraBold() {
  document.body.className = 'ts-ultra-bold ts-dramatic-shadows ts-spacious';
  
  // Voeg dramatische animatie toe
  document.body.style.transition = 'all 0.5s cubic-bezier(0.68, -0.55, 0.265, 1.55)';
  document.body.style.transform = 'scale(1.05)';
  
  setTimeout(() => {
    document.body.style.transform = 'scale(1)';
  }, 600);
}
```

Nu kun je eenvoudig zeggen: **"Maak het wat gedurfder"** → `ts-theme-bold` 🎯