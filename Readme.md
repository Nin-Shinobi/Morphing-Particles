# Shape Morpher - README

<img src="Morphing Particles.png" alt="Shape Morpher"/>

## Introduction
Shape Morpher est une application interactive basée sur Three.js qui permet de transformer un nuage de particules en différentes formes 3D. Les utilisateurs peuvent sélectionner une forme, ajuster la taille des particules, la vitesse de rotation et d'autres paramètres visuels.

## Prérequis
Avant de lancer l'application, assurez-vous d'avoir :
- Un navigateur moderne prenant en charge WebGL (Google Chrome, Firefox, Edge, etc.).
- Une connexion Internet si vous utilisez les modules de Three.js via un CDN.

## Installation et Exécution
1. Téléchargez ou clonez le projet.
2. Ouvrez le fichier `index.html` dans un navigateur Web.

## Explication du Code
Le projet est structuré comme suit :

### 1. Structure HTML
Le fichier contient :
- Un `div` avec l'ID `container` qui sert de conteneur pour la scène Three.js.
- Une interface utilisateur (`div#ui`) permettant de sélectionner différentes formes.
- Un panneau de contrôle (`div#controls`) pour ajuster les paramètres des particules.

### 2. Styles CSS
Le CSS définit le style du fond, des boutons interactifs et des contrôles pour une meilleure expérience utilisateur.

### 3. Utilisation de Three.js
Le projet utilise Three.js pour :
- Créer une scène, une caméra et un moteur de rendu WebGL.
- Générer un système de particules avec une `BufferGeometry`.
- Appliquer des effets visuels tels que le flou lumineux (`UnrealBloomPass`).
- Ajouter un effet de mouvement des particules.

### 4. Interaction Utilisateur
- **Sélection des formes** : Cliquer sur un bouton modifie la disposition des particules pour former une sphère, un cube, un tore, etc.
- **Personnalisation** : L'utilisateur peut ajuster la taille des particules, la vitesse de rotation, la force du flou lumineux et la couleur.
- **Navigation** : Utilisation de la souris pour pivoter et zoomer dans la scène.

## Commandes
- **Faire glisser** : Rotation de la caméra.
- **Défiler** : Zoom avant/arrière.
- **Double-clic** : Réinitialisation de la vue.

## Développement et Personnalisation
Si vous souhaitez modifier le code :
- Ajoutez de nouvelles formes en définissant des positions cibles dans `morphToShape()`.
- Expérimentez avec différents shaders ou effets de post-traitement.
- Personnalisez l'interface utilisateur pour une meilleure ergonomie.

## Crédits
Ce projet utilise la bibliothèque [Three.js](https://threejs.org/) pour le rendu 3D et les effets visuels.

- **Auteur** : [𝕹𝖎𝖓_𝕾𝖍𝖎𝖓𝖔𝖇𝖎🥷🏾]
- **GitHub** : [@Nin-Shinobi](https://github.com/Nin-Shinobi)
- **Repository** : [Morphing Particles](https://github.com/Nin-Shinobi/Morphing-Particles)


