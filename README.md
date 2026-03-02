# film
# 🎬 CineXplore — Explorateur de Films

CineXplore est une application web moderne permettant d’explorer, rechercher et sauvegarder des films grâce à l’API de The Movie Database (TMDb).

Interface immersive, design cinématographique, filtres par genres, pagination intelligente et gestion des favoris en local.

---

## 🚀 Fonctionnalités

* 🔥 Affichage des films populaires
* 🔎 Recherche dynamique de films
* 🎭 Filtres par genres (Action, Comédie, Romance, etc.)
* 📄 Pagination intelligente
* 🎬 Modal détaillée (synopsis, acteurs, réalisateur, pays…)
* ❤️ Système de favoris (stockage en `localStorage`)
* 🌍 Interface en français
* ⚡ Animations fluides & UI moderne
* 📱 Design responsive (mobile & desktop)

---

## 🛠️ Technologies utilisées

* HTML5
* CSS3 (Variables CSS, animations, responsive design)
* JavaScript (ES6+)
* API TMDb
* LocalStorage (gestion des favoris)
* Google Fonts
* Font Awesome

---


Aucune installation supplémentaire n’est nécessaire (projet 100% front-end).

---

## 📂 Architecture du projet

```
📁 CineXplore
 ├── film.html (HTML + CSS + JS intégré)
```

Le projet est structuré en :

* Sections UI (Header, Filters, Grid, Modal)
* Gestion d’état (mode courant, page, favoris)
* Fonctions d’appel API
* Système de rendu dynamique
* Gestion des événements

---

## 🧠 Modes de fonctionnement

L’application fonctionne selon plusieurs modes :

* `popular` → Films populaires
* `search` → Résultats de recherche
* `genre` → Films filtrés par genre
* `favorites` → Films sauvegardés localement

---

## ❤️ Gestion des favoris

Les favoris sont :

* Stockés dans `localStorage`
* Persistants après rechargement
* Synchronisés avec la modal
* Affichés avec compteur dynamique

Clé utilisée :

```
cinexplore_favs
```

---

## 📱 Responsive Design

Optimisé pour :

* Desktop
* Tablette
* Mobile (grille adaptée + modal optimisée)

---

## ✨ Améliorations possibles

* Authentification utilisateur
* Sauvegarde cloud des favoris
* Mode sombre / clair
* Ajout de bandes-annonces
* Filtres avancés (année, note minimale)
* Infinite scroll
* Déploiement sur Vercel ou Netlify

---

## 👩🏽‍💻 Auteur

**Awa Thiongane Gaye**

Projet réalisé dans un objectif d’apprentissage et de perfectionnement en développement front-end.

---
