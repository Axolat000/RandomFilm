# 🎬 La Suite Random Film™

![Project Status](https://img.shields.io/badge/Status-Live%20(Private)-success?style=for-the-badge)
![Security](https://img.shields.io/badge/Source-Closed--Source-red?style=for-the-badge)
![Tech](https://img.shields.io/badge/Stack-Full--Stack-blueviolet?style=for-the-badge)

> **Un écosystème Homelab personnel regroupant streaming vidéo, lecteur audio avancé, gestion de jeux et outils expérimentaux. Développé de A à Z.**

---

## 🌐 Le Concept

**La Suite Random Film** n'est pas juste un site web. C'est un **Système d'Exploitation Web (WebOS)** personnel conçu pour centraliser ma vie numérique.
Lassé des interfaces lourdes et des algorithmes commerciaux, j'ai construit ma propre solution : rapide, sombre, et sans compromis.

### 🛠️ Stack Technique
* **Backend :** PHP 8 (Vanilla), SQLite3.
* **Frontend :** HTML5, CSS3 (Variables & Thèmes dynamiques), JavaScript (SPA via History API).
* **Architecture :** Monolithique modulaire, hébergement sur aaPanel.
* **Performance :** 0 dépendance inutile, optimisation bas niveau.

---

## 🚀 Modules Principaux

### 1. Random Film (Core)
Une **Single Page Application (SPA)** fluide pour le streaming de ma bibliothèque locale.
* **Fonctionnalité clé :** Navigation sans rechargement (`pushState`), gestion des métadonnées (MP3/ID3).
* **Source :** Intégration "Gogoledrive" (Système de fichiers local).
* **UI :** Dark Mode natif, responsive.

![Random Film Home](https://github.com/ton-pseudo/ton-repo/blob/main/image_4e1762.png?raw=true)
*(Note : Remplace ce lien par l'URL de ton image une fois uploadée)*

### 2. Purple Music™
Un clone de Spotify/Deezer, mais contrôlable à 100%.
* **Features :** File d'attente dynamique, Upload de MP3 avec extraction automatique de cover/métadonnées, Playlists persistantes.
* **Admin :** Gestion complète des fichiers et des utilisateurs.

![Purple Music UI](https://github.com/ton-pseudo/ton-repo/blob/main/image_4dae25.png?raw=true)

### 3. Steam|Cooked & Game Center
Un launcher unifié pour ma bibliothèque de jeux PC et Web.
* **Optimisation Agressive :** Générateur de manifestes statiques pour éviter la latence.
* **Performance :** Capable de gérer des milliers de requêtes de synchronisation par jour sans sourciller.

![Steam Cooked](https://github.com/ton-pseudo/ton-repo/blob/main/image_4db9a5.jpg?raw=true)

### 4. Outils & Expérimentations (The "Chaos" Lab)
Un espace pour tester des concepts UX, du code "edgy" et des utilitaires.
* **Gogole Cloud :** Stockage de fichiers décentralisé (sur mon disque).
* **DoxBin Mini :** Pastebin minimaliste pour le partage rapide de texte.
* **Robux Generator & Merdouille :** Pages de test pour l'ingénierie sociale et les scripts JS improbables.

---

## ⚡ Performance & Engineering

Pourquoi utiliser des frameworks lourds quand on peut faire mieux soi-même ?
L'architecture de la suite est conçue pour supporter une charge intensive (Polling API, Streaming simultané) tout en restant hébergée sur une machine modeste.

![Traffic Graph](https://github.com/ton-pseudo/ton-repo/blob/main/image_4d9bc1.png?raw=true)
*Le rythme cardiaque du serveur : 26k+ requêtes journalières traitées en local.*

---

## 🔒 Pourquoi "Closed Source" ?

Ce projet contient :
1.  Des algorithmes propriétaires d'optimisation d'API (Steam|Cooked).
2.  Des méthodes d'accès au système de fichiers spécifiques à mon infrastructure.
3.  Des fonctionnalités de sécurité adaptées à un usage strictement privé.

Pour ces raisons, le code source n'est pas public. Ce dépôt sert de **portfolio** pour démontrer mes capacités en architecture logicielle, design UI/UX et développement Full Stack.

---

### 👤 Auteur
**Axolat**
*Full-stack Tinkerer & Chaos Engineer*
[Voir mon profil GitHub](https://github.com/Axolat000)
