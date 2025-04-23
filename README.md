# CosmoMix - Boutique de pulls inspirée par l'univers

## Aperçu du projet

**CosmoMix** est un site web de e-commerce fictif créé dans le cadre d'un projet éducatif. Le thème du site est centré sur l'univers spatial, et il propose une collection de pulls, cailloux, voitures et ballons inspirés par cet univers. L'objectif est de concevoir un site simple, fonctionnel et esthétique, avec une navigation intuitive et un design cohérent qui reflète le thème spatial.

Le site est développé en HTML et CSS, avec des touches d'interactivité légère (effets de survol, animations simples). Il est destiné à être utilisé comme une vitrine pour présenter les pulls, avec des pages supplémentaires pour l'à-propos, le contact...

## Fonctionnalités principales

- **Page d'accueil** : Présente les différentes sections du site (Pulls,  Cailloux, Voitures, Ballons, Bibliographie) sous forme de grille avec des cases stylisées.
- **Page "Bibliographie"** : Liste les sources et références utilisées pour le projet.
- **Responsive** : La grille s'adapte aux différentes tailles d'écran grâce à `grid-template-columns: repeat(auto-fit, minmax(200px, 1fr))`.

## Structure du projet

```
cosmomix/
├── index.html            # Page d'accueil
├── Lucas/
│   ├── CosmoSweat.html   # Page "Pulls"
│   └── images/           # Images (logo, pulls, etc.)
├── Mylo/
│   └── ComoCailloux.html # Page "À propos"
├── Axel/
│   └── CosmoVoiture.html # Page "Contact"
├── Timeo/
│   └── CosmoBallons.html # Page "Promotions"
├── bibliographie.html    # Page "Bibliographie"
├── styles.css            # Feuille de style principale
├── fonts/
│   └── Questrial-regular.ttf # Police utilisée
└── images/
    ├── planete-saturne.png   # Image décorative
    ├── planete-jupiter.png   # Image décorative
    ├── fusée.png             # Image décorative
    └── nebuleuse-inspiration.jpg # Image pour la section inspiration
```

## Technologies utilisées

- **HTML5** : Structure des pages.
- **CSS3** : Mise en page, design, animations (effets de survol, étoiles flottantes, etc.).
- **Google Fonts** : Police `Questrial` pour un style moderne.

## Design et thème

Le design est simple et fonctionnel, avec une palette de couleurs inspirée par l'espace :

- **Bleu principal** : `#1404aa` (utilisé pour les titres, icônes, barre de navigation).
- **Gris clair** : `#f5f5f5` (fonds des cases et articles).
- **Texte** : `#3b3b3b` (texte principal pour une bonne lisibilité).
- **Bleu clair** : `#649acc` (accents, liens).

## Prochaines étapes éventuellement à améliorer ou faire

- Ajouter un panier fonctionnel avec JavaScript.
- Intégrer un formulaire de contact dynamique (avec validation et envoi).
- Améliorer la responsivité pour les écrans mobiles.
- Ajouter des animations plus complexes (par exemple, une transition de page en forme de "trou noir").
- Créer une page "Guide des tailles" avec un tableau interactif.

---

**CosmoMix** - Explorez l’univers, un pull à la fois ! 🚀
