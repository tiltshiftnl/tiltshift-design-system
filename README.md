# Tiltshift Design System

Een complete component library voor digitale transformatie projecten.

## CDN Usage

Include de CSS bestanden in de juiste volgorde:

```html
<!-- Tiltshift Design System -->
<link rel="stylesheet" href="https://cdn.tiltshift.nl/tiltshift-tokens.css">
<link rel="stylesheet" href="https://cdn.tiltshift.nl/tiltshift-base.css">
<link rel="stylesheet" href="https://cdn.tiltshift.nl/tiltshift-atomic.css">
<link rel="stylesheet" href="https://cdn.tiltshift.nl/tiltshift-components.css">
<link rel="stylesheet" href="https://cdn.tiltshift.nl/tiltshift-utilities.css">
<link rel="stylesheet" href="https://cdn.tiltshift.nl/tiltshift-themes.css">
```

## Bestanden

- `tiltshift-tokens.css` - Design tokens (kleuren, fonts, spacing, font-faces)
- `tiltshift-base.css` - Base element styling (reset, typography, forms)
- `tiltshift-atomic.css` - Atomic design componenten (atoms)
- `tiltshift-components.css` - UI componenten (molecules, organisms)
- `tiltshift-utilities.css` - Utility classes (margin, padding, flex, etc.)
- `tiltshift-themes.css` - Theme varianten (bold, subtle, modern)
- `assets/` - Logo's, fonts, afbeeldingen en favicon

## Development

Voor lokale ontwikkeling met Jekyll:

```bash
# Install dependencies
bundle install

# Start development server
./run.sh

# Website is beschikbaar op http://localhost:4001
```

## Features

- ✅ Atomic Design methodology
- ✅ BEM naming convention
- ✅ CSS custom properties 
- ✅ Responsive design
- ✅ Accessibility fonts (AtkinsonHyperlegible)
- ✅ Cross-domain asset support
- ✅ Theme varianten (subtle/bold/modern)

## Brand Guidelines

Het design system bevat volledige brand guidelines inclusief:

- Logo gebruik en betekenis  
- Kleurenpalet (Primary Red, Primary Blue, Black, White)
- Typografie (HelveticaNeue voor headers, AtkinsonHyperlegible voor body)
- Fotografie stijl (zwart-wit, authentiek, niet geposeerd)
- Favicon implementatie
- Merkwaarden en taglines

## Themes

Pas de intensiteit aan met één CSS class op de body:

```html
<body class="ts-theme-subtle">  <!-- 70% grootte/spacing -->
<body class="ts-theme-bold">    <!-- 130% grootte/spacing -->
<body class="ts-theme-modern">  <!-- Moderne variant -->
```