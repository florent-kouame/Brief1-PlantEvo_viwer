# PlantEvo Viewer

### Explorer l'évolution du monde végétal

## 1. Présentation du projet

**PlantEvo Viewer** est une application web pédagogique conçue pour présenter et explorer l'évolution du monde végétal.

Elle permet de découvrir les différents groupes de végétaux, leur évolution, leurs caractéristiques morphologiques, leurs modes de reproduction ainsi que leur adaptation aux différents milieux de vie.

Le projet vise à rendre les connaissances botaniques accessibles grâce à une interface visuelle, interactive et facile à utiliser.

## 2. Objectifs du projet

Les principaux objectifs sont :

- Présenter les grandes étapes de l'évolution des végétaux.
- Découvrir les différents groupes végétaux.
- Comprendre l'évolution de l'appareil végétatif.
- Explorer les différents modes de reproduction.
- Présenter les caractéristiques des espèces végétales.
- Illustrer les observations à travers des images et des cartes.
- Faciliter l'apprentissage de la botanique grâce à une interface intuitive.

## 3. Technologies utilisées

Le développement de PlantEvo Viewer repose sur les technologies suivantes :

| Technologie | Utilisation |
|---|---|
| HTML5 | Structure et organisation des pages web |
| CSS3 | Mise en forme et design de l'interface |
| Figma | Conception de la maquette et du prototype |
| QGIS | Réalisation et préparation des cartes d'observation |

## 4. Fonctionnalités et rubriques du site

### Accueil
La page d'accueil présente le projet PlantEvo Viewer, son objectif et les différentes rubriques accessibles depuis le menu de navigation.

### 🌱 Évolution des végétaux
Cette rubrique présente les grandes étapes de l'évolution du monde végétal et la colonisation progressive des milieux.

### 🌿 Les groupes végétaux

Le site présente cinq grands groupes :

1. **Les algues :** organismes principalement aquatiques.
2. **Les bryophytes :** mousses et végétaux non vasculaires.
3. **Les ptéridophytes :** fougères et autres végétaux vasculaires sans graines.
4. **Les gymnospermes :** végétaux à graines nues, notamment les conifères.
5. **Les angiospermes :** plantes à fleurs dont les graines sont enfermées dans un fruit.

Chaque groupe est présenté à travers des images et de courts textes explicatifs.

### 🔬 Appareil végétatif
Présentation des caractéristiques morphologiques des végétaux et de l'évolution de leurs structures végétatives.

### 🌼 Reproduction
Découverte des différents modes de reproduction des végétaux et de leur évolution.

### 🗺️ Carte
Espace consacré à la visualisation des cartes d'observation réalisées avec QGIS.

### ℹ️ À propos
Présentation du projet, de sa finalité pédagogique et des informations relatives à sa conception.

## 5. Présentation des observations

Les fiches d'observation peuvent présenter les informations suivantes :

- Nom de l'espèce.
- Groupe végétal.
- Milieu d'observation.
- Coordonnées GPS.
- Date d'observation.
- Photographies de l'espèce.

Les photographies occupent une place importante dans la présentation afin de privilégier l'apprentissage visuel.

## 6. Navigation du site

La navigation repose sur un menu principal composé de plusieurs rubriques :

- Accueil
- Groupes végétaux
- Carte
- À propos

Les liens hypertextes permettent de passer d'une rubrique à une autre ou d'accéder aux pages détaillées des différents groupes végétaux.

## 7. Organisation des fichiers

Exemple d'organisation du projet :

```text
PlantEvo-Viewer/
│
├── index.html
├── style.css
│
├── pages/
│   ├── evolution.html
│   ├── groupes.html
│   ├── algues.html
│   ├── bryophytes.html
│   ├── pteridophytes.html
│   ├── gymnospermes.html
│   ├── angiospermes.html
│   ├── carte.html
│   └── apropos.html
│
├── images/
│   ├── logo.png
│   ├── algues/
│   ├── bryophytes/
│   ├── fougeres/
│   ├── coniferes/
│   └── angiospermes/
│
└── cartes/
    └── carte-observation.png
```

*Cette arborescence est une proposition d'organisation à adapter aux fichiers réellement présents dans le projet.*

## 8. Design et interface utilisateur

L'interface est pensée pour être :

- Simple et intuitive.
- Visuellement attractive.
- Facile à parcourir.
- Adaptée à la consultation des images et des informations botaniques.

Les choix typographiques envisagés sont :

- **Poppins Bold :** titres principaux.
- **Inter Medium :** sous-titres.
- **Inter Regular :** paragraphes et descriptions.

Le CSS permet notamment de gérer :

- La taille et le positionnement des images.
- L'espacement entre les différents blocs.
- La disposition des éléments parents et enfants.
- Les couleurs et les arrière-plans.
- Les liens de navigation.
- L'alignement des textes et des images.

## 9. Installation et utilisation

PlantEvo Viewer est une application web statique.

Pour consulter le projet :

1. Télécharger ou cloner le dépôt GitHub.
2. Ouvrir le dossier du projet dans Visual Studio Code.
3. Ouvrir le fichier `index.html` dans un navigateur.
4. Parcourir les différentes rubriques du site.

Aucune installation de serveur ou de base de données n'est nécessaire pour la version statique.

## 10. Perspectives d'amélioration

Les évolutions envisagées comprennent :

- Amélioration de l'affichage sur smartphones et tablettes.
- Ajout de nouvelles espèces végétales.
- Enrichissement des fiches d'observation.
- Intégration de cartes interactives.
- Amélioration de l'expérience utilisateur.
- Ajout de nouvelles ressources pédagogiques.

## 11. Auteur

**KOUAME Kouadio Konan Florent**

Projet réalisé dans le cadre de la formation à la Digital Farming School (DFS).

**Nom du projet :** PlantEvo Viewer  
**Type :** Application web pédagogique  
**Domaine :** Botanique, évolution végétale et observation des espèces.

---
