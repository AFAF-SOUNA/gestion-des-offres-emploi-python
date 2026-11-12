# LinkedIn Portal – Espace Emploi (Maroc)

Application de bureau de gestion d'offres d'emploi développée en **Python (Tkinter + SQLite)**.

Projet réalisé dans le cadre du module **Python avancé** à l'**ENSAM Casablanca** (Année universitaire : 2026/2027).

##  Auteurs
- **Aya Zeggar**

- **Aya ElKhair**

- **Afaf Souna**

- *Encadré par : M. Hain Mustapha*


---

##  Fonctionnalités
- **Mode Invité** : Consultation libre de toutes les offres d'emploi disponibles au Maroc.

- **Authentification sécurisée** : Inscription et connexion avec distinction des rôles (**Candidat** et **Entreprise**).

- **Espace Candidat** : Sélection d'une offre et envoi de candidature avec enregistrement automatique de la date.

- **Espace Entreprise** (Géré via un panneau à onglets) : 

  - Publication de nouvelles offres d'emploi.
  - Consultation des annonces publiées.
  - Suivi et consultation des candidatures reçues (avec jointures multi-tables).

  ---

##  Structure du projet
```text
├── main.py          # Point d'entrée de l'application
├── database.py      # Couche d'accès aux données SQLite (tables, requêtes, jointures)
├── login.py         # Fenêtres modales de connexion et d'inscription
└── dashboard_ui.py  # Interface principale (dashboard) et espace entreprise point de vue
