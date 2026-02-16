---
title: Tetris
publishDate: 2019-12-01 00:00:00
img: /assets/tetris.webp
img_alt: Image du jeu tetris
description: |
  Dans le cadre d’un projet personnel, j’ai développé une version complète du célèbre jeu Tetris en Java.
tags:
  - Réaliser
---

### 🎮 Projet Solo – Développement du jeu Tetris
### 🧑‍💻 Projet personnel – Développement Java
### 🌟 Contexte du projet

Consolider mes compétences en programmation orientée objet

Approfondir la gestion des événements, collisions et logiques temps réel

Développer une interface graphique interactive

Ce projet m’a permis de travailler en autonomie complète, de la conception à l’implémentation.

#### 🛠 Stack technique

Java

Swing (javax.swing) pour l’interface graphique

Programmation orientée objet (POO)

Gestion des événements clavier

#### ⚙️ Fonctionnalités développées
#### 🧩 Gestion des pièces (Tetrominos)

Génération aléatoire des pièces

Rotation des pièces (gestion des collisions et des bords)

Détection des collisions avec les murs et les blocs existants

Système de verrouillage automatique lorsqu’une pièce touche le sol

#### 🎮 Gameplay

Déplacement gauche / droite

Rotation

Accélération de la descente

Suppression automatique des lignes complètes

Système de score basé sur le nombre de lignes supprimées

Augmentation progressive de la vitesse

#### 🧠 Logique de jeu

Le cœur du projet repose sur :

Une grille  représentant le plateau

Une gestion dynamique des coordonnées X/Y

Un système de vérification des collisions avant chaque mouvement

Une boucle de jeu basée sur un Timer Swing

Chaque action utilisateur déclenche une vérification logique afin d’éviter tout dépassement ou collision invalide.

#### 🏗 Architecture du projet

Le projet est structuré autour de plusieurs classes principales :

PlayManager → Gestion principale de la partie

GamePanel → Gestion de l'update graphique, de la boucle de jeu

tetrimino → Modélisation des tetrominos

start → Point d’entrée de l’application

L’architecture repose sur une séparation claire entre :

🎨 Interface graphique

🧠 Logique métier

📦 Modélisation des objets

#### 🚧 Difficultés rencontrées

Gestion correcte des rotations près des bords

Synchronisation entre affichage graphique et logique interne

Suppression propre des lignes sans bug visuel

Gestion du score

Ces problématiques m’ont permis d’approfondir :

Les collisions via les positions

Les algorithmes de timer custom

Les loop de jeu 

La gestion des événements clavier en Java

#### 📈 Compétences développées

Programmation orientée objet avancée

Gestion d’un moteur de jeu simple

Manipulation de matrices

Logique algorithmique

Développement d’interface graphique avec Swing

Gestion du temps et boucle de jeu

#### 🏁 Bilan personnel

Ce projet m’a permis de comprendre concrètement la logique derrière un jeu en temps réel.

Développer Tetris en Java m’a obligé à réfléchir à :

L’optimisation des algorithmes

La robustesse des contrôles

L’expérience utilisateur

C’est un projet formateur qui démontre ma capacité à concevoir un système interactif complet de manière autonome.