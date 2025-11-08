# Projet - Site Web

## Informations du projet

**Titre** : XXX  
**Type** : Projet - Développement web  
**Année** : 2025 HE-Arc

### Équipe

- **Professeur** : M. Janser
- **Étudiants** :
  - Sommariva
  - Akram

## Description

Site web professionnel conçu pour promouvoir des cours privés d'allemand. Le projet comprend des pages  présentant les services, le parcours de la professeure et les différentes formules de cours proposées.

### Objectifs pédagogiques

- Maîtriser HTML5 et la structure sémantique
- Apprendre le préprocesseur SCSS et l'architecture CSS modulaire
- Appliquer la méthodologie BEM
- Créer un design responsive (mobile-first)
- Optimiser pour le référencement (SEO)
- Respecter les standards d'accessibilité web

## Technologies utilisées

- **HTML5** : Structure sémantique des pages
- **CSS3** : Styles et mise en page
- **SCSS** : Préprocesseur CSS pour code maintenable
- **Git** : Versioning du code

## Structure du projet

```
Projet/
├── index.html              # Page d'accueil
├── a_propos.html          # Page à propos
├── page_reservation.html  # Page tarifs et réservation
├── css/
│   ├── style.css          # CSS compilé
│   └── style.min.css      # CSS minifié
├── scss/
│   ├── style.scss         # Point d'entrée
│   ├── _variables.scss    # Variables globales
│   ├── _reset.scss        # Reset CSS
│   ├── _typography.scss   # Typographie
│   ├── _layout.scss       # Layouts
│   ├── _header.scss       # En-tête
│   ├── _navigation.scss   # Navigation
│   ├── _footer.scss       # Pied de page
│   ├── _additional_components.scss
│   └── _print.scss        # Styles impression
├── img/
│   └── favicon/
└── README.md
```

## Design

### Palette de couleurs

Inspirée du drapeau allemand :
- Noir (#1A1A1A) : Professionnalisme
- Rouge (#C41E3A) : Accents et boutons
- Or (#FFCF00) : Éléments secondaires

### Responsive Design

Le site est optimisé pour :
- Mobile : < 768px
- Tablette : 768px - 991px
- Desktop : > 992px

### Méthodologie BEM

Classes CSS suivant la convention Block Element Modifier :
```css
.block {}
.block__element {}
.block--modifier {}
```

## Installation et développement

### Prérequis

- Un navigateur web moderne
- Un éditeur de code (VS Code recommandé)
- Sass installé pour compiler le SCSS

### Compilation SCSS

```bash
# Compiler le SCSS en CSS
sass scss/style.scss css/style.css

# Mode watch (recompilation automatique)
sass --watch scss:css

# Version minifiée
sass scss/style.scss css/style.min.css --style=compressed
```

### Lancer le projet

Option 1 : Ouvrir directement index.html dans un navigateur

Option 2 : Serveur local Python
```bash
python -m http.server 8000
```
Puis ouvrir http://localhost:8000

Option 3 : Extension Live Server dans VS Code

## Ressources et références

### Documentation officielle

- [MDN Web Docs](https://developer.mozilla.org/fr/) 
- [Sass Documentation](https://sass-lang.com/documentation) 
- [W3Schools](https://www.w3schools.com/) 

### Forums et communautés

- [Stack Overflow](https://stackoverflow.com/)
- [Reddit - r/webdev](https://www.reddit.com/r/webdev/)
- [Dev.to](https://dev.to/) 

### Outils

- [Google Fonts](https://fonts.google.com/) - Polices web gratuites
- [Coolors](https://coolors.co/) - Générateur de palettes de couleurs
- [Favicon Generator](https://realfavicongenerator.net/) - Création de favicons multi-formats

### Validation et tests

- 

---

**Projet réalisé par** : Sommariva & Akram  
**Supervisé par** : M. Janser  
**Date** :  2025  
**École** : HE-Arc
