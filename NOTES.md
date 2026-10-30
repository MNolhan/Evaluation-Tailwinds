# Évalutation TailWind

## Contexte

Le dossier sujet/ contient un site vitrine complet et fonctionnel — La Table d'Amélie, un bistrot fictif — écrit en CSS classique : un seul fichier css/style.css, variables CSS, nomenclature BEM, Flexbox, Grid, media queries desktop-first. Aucune ligne de Tailwind.

3 pages : index.html (accueil), menu.html (la carte), contact.html (formulaire, horaires, FAQ). Le HTML est sémantiquement correct — il ne doit pas être réécrit en profondeur, seulement stylé différemment.

Consigne : convertir l'intégralité du site en Tailwind CSS v4, en supprimant le CSS classique au fur et à mesure qu'il est remplacé. Le site doit rester visuellement et fonctionnellement identique (ou amélioré) à la fin de l'exercice.

## Livré

- Site Intégralement convertit en tailwind
- HTML Sémantique préservé
- Responsive
- Une animation qui respecte prefers-reduce-motion

## Justification des utilisations des Apply

Je me suis fixé plusieurs règle : 

- une classe qui fait plus de 2 lignes --> `apply`
- une classe qui est répété --> `apply`


les pièges que j'ai rencontré : au début dès que je rencontré une classe qui ne nécessitait pas un `apply`, je la remplaçais partout et je la supprimais directement du fichier css, mais une fois arrivé au responsive à la fin `impossible de retrouver la classe`, ni dans le html, ni dans le css.
Il aurait fallu faire le responsive directement

## Installation

```
git clone https://github.com/MNolhan/Evaluation-Tailwinds.git
cd Evaluation-Tailwinds
npm install
npm run dev
```

##

Nolhan Marteau M1 - ESGI en Ingénierie du Web - Cours Introduction Tailwind
