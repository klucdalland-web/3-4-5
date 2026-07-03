# Fluxo

Page d'accueil pour un faux produit SaaS (gestion de projet). Projet réalisé dans le cadre du cours Fullstack, semaine 4 — CSS Layouts (Flexbox & Grid).

## Aperçu

La page contient 3 sections :

1. Hero — un fond et un bloc de texte superposés au même endroit avec CSS Grid.
2. Tarifs — 3 cartes de prix qui passent à la ligne automatiquement selon la largeur de l'écran, avec Flexbox.
3. Portfolio / cas clients — une mosaïque de blocs de tailles différentes avec CSS Grid (`grid-template-areas`).

## Contraintes du projet

- Uniquement Flexbox et CSS Grid pour la mise en page.
- Pas de media query — la réactivité vient seulement de `flex-wrap`, `flex-basis` et `minmax()`.
- Pas de JavaScript.

## Ce que j'ai appris

- Superposer plusieurs éléments avec `grid-template-areas: "stack"` et `grid-area: stack` sur les enfants.
- Faire en sorte que des cartes se réorganisent seules avec `flex: 1 1 250px` au lieu de fixer une largeur.
- Découper un layout complexe (mosaïque) en zones nommées plutôt qu'en calculant des tailles à la main.

## Ce qui reste à améliorer

- Sans media query, la mosaïque et les colonnes rétrécissent mais ne se réorganisent pas vraiment sur mobile. À revoir la semaine prochaine.
- Le hero pourrait être plus travaillé visuellement (dégradés, animations) mais je me suis limité à ce qu'on a vu en cours.
