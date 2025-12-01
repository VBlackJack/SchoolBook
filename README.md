# SchoolBook

**Le compagnon numérique du Collégien** - Support de cours pédagogique, statique et évolutif.

[![MkDocs](https://img.shields.io/badge/Built%20with-MkDocs-blue)](https://www.mkdocs.org/)
[![Material](https://img.shields.io/badge/Theme-Material-teal)](https://squidfunk.github.io/mkdocs-material/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Présentation

SchoolBook est une plateforme de ressources pédagogiques pour les collégiens, construite avec MkDocs et le thème Material. Le site propose des cours, exercices et méthodes pour accompagner les élèves tout au long de leur scolarité.

## Contenu

### 6ème (Cycle 3)

| Matière | Contenu |
|---------|---------|
| **Mathématiques** | Nombres & Calculs, Géométrie, Grandeurs & Mesures |
| **Français** | Grammaire, Orthographe, Conjugaison, Littérature |
| **Histoire-Géo** | Histoire, Géographie, EMC |
| **Sciences & Techno** | Matière & Mouvement, Le Vivant, Planète Terre |
| **Anglais** | Vocabulaire, Grammaire |

### Formation Maths 6ème

Une formation complète et progressive en **11 modules** pour maîtriser le programme de mathématiques :

| Module | Thème | Durée |
|:------:|-------|:-----:|
| 0 | Test de positionnement initial | 30 min |
| 1 | Les nombres entiers | 2-3h |
| 2 | Les quatre opérations | 2-3h |
| 3 | Les nombres décimaux | 2-3h |
| 4 | Les fractions | 2-3h |
| 5 | La proportionnalité | 2-3h |
| 6 | Géométrie de base | 2-3h |
| 7 | Périmètres et aires | 2-3h |
| 8 | La symétrie axiale | 2-3h |
| 9 | Grandeurs et mesures | 2-3h |
| 10 | Résolution de problèmes | 2-3h |

Chaque module comprend :
- Objectifs d'apprentissage
- Leçons détaillées avec exemples visuels
- Exercices guidés avec corrections
- Entraînements progressifs
- Évaluation finale (sur 20)
- Astuces mnémotechniques

### Méthodologie

- Organiser son travail
- Apprendre une leçon efficacement
- Réussir en Maths (méthodes pédagogiques)
- Faire son cartable

### Bonus

- Culture générale
- Énigmes et défis

## Installation locale

### Prérequis

- Python 3.8+
- pip

### Installation

```bash
# Cloner le dépôt
git clone https://github.com/VBlackJack/SchoolBook.git
cd SchoolBook

# Installer les dépendances
pip install mkdocs mkdocs-material

# Lancer le serveur de développement
mkdocs serve
```

Le site sera accessible sur `http://127.0.0.1:8000`

### Déploiement

Le site est automatiquement déployé sur GitHub Pages via GitHub Actions à chaque push sur la branche `main`.

## Structure du projet

```
SchoolBook/
├── docs/
│   ├── index.md                    # Page d'accueil
│   ├── 6eme/
│   │   ├── maths/
│   │   │   ├── formation/          # Formation complète (11 modules)
│   │   │   ├── nombres.md
│   │   │   ├── geometrie.md
│   │   │   └── mesures.md
│   │   ├── francais/
│   │   ├── histoire-geo/
│   │   ├── sciences/
│   │   └── anglais/
│   ├── methodologie/
│   └── bonus/
├── mkdocs.yml                      # Configuration MkDocs
└── README.md
```

## Technologies

- [MkDocs](https://www.mkdocs.org/) - Générateur de site statique
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) - Thème moderne
- [Mermaid](https://mermaid.js.org/) - Diagrammes
- GitHub Pages - Hébergement

## Contribuer

Les contributions sont les bienvenues ! N'hésitez pas à :
- Signaler des erreurs
- Proposer des améliorations
- Ajouter du contenu

## Licence

Ce projet est sous licence MIT.

---

*SchoolBook - Apprendre, comprendre, réussir.*
