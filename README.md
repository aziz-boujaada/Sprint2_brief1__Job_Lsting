# 📄 Plateforme d’Offres d’Emploi

Une application web front-end permettant de **consulter, gérer et filtrer des offres d’emploi**.  
Ce projet inclut un système de profil utilisateur, la gestion des offres favorites et un panneau d’administration pour créer/modifier des offres.

---

## 🚀 Fonctionnalités principales

### 👤 Mon Profil
- Création et gestion du profil utilisateur (nom, poste recherché, compétences).
- Ajout de compétences dynamiquement (touche *Entrée*).
- Validation des champs et messages d’erreur personnalisés.

### ⭐ Mes Favoris
- Liste des offres d’emploi ajoutées aux favoris.
- Affichage dynamique du nombre de favoris.

### 🧾 Gérer les Offres
- Ajout, édition et suppression d’offres d’emploi via une interface modale.
- Champs obligatoires pour chaque offre : entreprise, poste, contrat, localisation, rôle, niveau, compétences, description.
- Possibilité d’ajouter un logo d’entreprise (URL).

### 🔍 Barre de recherche et filtres
- Recherche d’offres par poste, entreprise ou compétence.
- Système de filtres dynamiques avec tags.
- Bouton **Clear** pour réinitialiser les filtres.

### 📊 Statistiques
- Section affichant des statistiques générales sur les offres (chargement dynamique prévu en JavaScript).

### 🪟 Modales interactives
- **Modal “Détails de l’offre”** : affiche les informations complètes d’une offre sélectionnée.  
- **Modal “Ajouter / Modifier une offre”** : formulaire complet pour gérer les offres.


## 🛠️ Structure du projet
/Job_Listing
├── index.html             
├── assets/
│   ├── style.css           
│   └── starter.js       
└── README.md              


## 🧩 Technologies utilisées

- **HTML5** — Structure de la page et accessibilité.  
- **CSS3** — Mise en forme et responsive design.  
- **JavaScript (ES6)** — Gestion dynamique du contenu et interactions utilisateur.  
- **Google Fonts** — Police “League Spartan”.

---

## 💡 Fonctionnement prévu du script `starter.js`

Bien que le script ne soit pas fourni, voici les fonctionnalités qu’il devrait implémenter :

1. **Gestion des onglets (Profil, Favoris, Gérer)**  
   → Afficher/masquer le contenu associé à chaque onglet.

2. **Validation du formulaire de profil**  
   → Vérifier les champs requis, gérer les erreurs, sauvegarder les données localement.

3. **Ajout dynamique de compétences**  
   → Permettre l’ajout et la suppression de compétences via des tags.

4. **Gestion des offres d’emploi**  
   → Afficher la liste des offres disponibles, ouvrir les modales, ajouter/modifier/supprimer une offre.

5. **Favoris**  
   → Ajouter/retirer une offre des favoris et mettre à jour le compteur.

6. **Filtres et recherche**  
   → Filtrer les offres selon le texte saisi ou les tags sélectionnés.
