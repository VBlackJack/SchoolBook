# SchoolBook

**Le compagnon numerique du Collegien** - Support de cours pedagogique, statique et evolutif.

[![MkDocs](https://img.shields.io/badge/Built%20with-MkDocs-blue)](https://www.mkdocs.org/)
[![Material](https://img.shields.io/badge/Theme-Material-teal)](https://squidfunk.github.io/mkdocs-material/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Deploy](https://github.com/VBlackJack/SchoolBook/actions/workflows/deploy.yml/badge.svg)](https://github.com/VBlackJack/SchoolBook/actions/workflows/deploy.yml)

## Presentation

SchoolBook est une plateforme de ressources pedagogiques pour les collegiens, construite avec MkDocs et le theme Material. Le site propose des cours, exercices et methodes pour accompagner les eleves tout au long de leur scolarite.

## Contenu

### 6eme (Cycle 3)

| Matiere | Contenu | Modules |
|---------|---------|:-------:|
| **Mathematiques** | Nombres & Calculs, Geometrie, Grandeurs & Mesures | 11 |
| **Francais** | Grammaire, Orthographe, Conjugaison, Litterature | 11 |
| **Histoire-Geo-EMC** | Histoire, Geographie, Education civique | 11 |
| **Sciences & Techno** | Matiere & Mouvement, Le Vivant, Planete Terre | 11 |
| **Anglais** | Vocabulaire, Grammaire, Culture anglophone | 11 |
| **Informatique** | Hardware, OS, Internet, Securite, Programmation | 11 |

**Total : 6 matieres, 66 modules, 600+ exercices**

### Structure des formations

Chaque matiere propose une formation complete en **11 modules** :

| Module | Description | Duree |
|:------:|-------------|:-----:|
| 0 | Test de positionnement initial | 20-30 min |
| 1-10 | Modules progressifs avec lecons et exercices | 1-3h chacun |

Chaque module comprend :
- Objectifs d'apprentissage clairs
- Lecons detaillees avec exemples concrets (jeux video, sport, vie quotidienne)
- Exercices guides avec corrections
- Entrainements progressifs
- Evaluation finale
- Pieges a eviter et astuces

### Methodologie

- Organiser son travail
- Apprendre une lecon efficacement
- Reussir en Maths (methodes pedagogiques)
- Faire son cartable

### Bonus

- Culture generale
- Enigmes et defis

## Installation locale

### Prerequis

- Python 3.8+
- pip

### Installation

```bash
# Cloner le depot
git clone https://github.com/VBlackJack/SchoolBook.git
cd SchoolBook

# Installer les dependances
pip install mkdocs-material mkdocs-minify-plugin

# Lancer le serveur de developpement
mkdocs serve
```

Le site sera accessible sur `http://127.0.0.1:8000`

### Build

```bash
mkdocs build
```

Les fichiers statiques seront generes dans le dossier `site/`.

## Deploiement

Le site est automatiquement deploye sur GitHub Pages via GitHub Actions a chaque push sur la branche `main`.

## Structure du projet

```
SchoolBook/
├── docs/
│   ├── index.md                    # Page d'accueil
│   ├── stylesheets/
│   │   └── extra.css               # Styles personnalises
│   ├── 6eme/
│   │   ├── index.md                # Hub 6eme
│   │   ├── maths/
│   │   │   ├── formation/          # 11 modules complets
│   │   │   ├── nombres.md
│   │   │   ├── geometrie.md
│   │   │   └── mesures.md
│   │   ├── francais/
│   │   │   ├── formation/          # 11 modules complets
│   │   │   ├── grammaire.md
│   │   │   ├── orthographe.md
│   │   │   ├── conjugaison.md
│   │   │   └── litterature.md
│   │   ├── histoire-geo/
│   │   │   ├── formation/          # 11 modules complets
│   │   │   ├── histoire.md
│   │   │   ├── geographie.md
│   │   │   └── emc.md
│   │   ├── sciences/
│   │   │   ├── formation/          # 11 modules complets
│   │   │   ├── matiere.md
│   │   │   ├── vivant.md
│   │   │   └── planete.md
│   │   ├── anglais/
│   │   │   ├── formation/          # 11 modules complets
│   │   │   ├── vocabulaire.md
│   │   │   └── grammaire.md
│   │   └── informatique/
│   │       └── formation/          # 11 modules complets
│   ├── methodologie/
│   │   ├── organisation.md
│   │   ├── memorisation.md
│   │   ├── reussir-maths.md
│   │   └── cartable.md
│   └── bonus/
│       ├── culture.md
│       └── enigmes.md
├── .github/
│   └── workflows/
│       └── deploy.yml              # CI/CD GitHub Actions
├── mkdocs.yml                      # Configuration MkDocs
├── CONTRIBUTING.md                 # Guide de contribution
├── LICENSE                         # Licence MIT
└── README.md
```

## Technologies

- [MkDocs](https://www.mkdocs.org/) - Generateur de site statique
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) - Theme moderne et responsive
- [Mermaid](https://mermaid.js.org/) - Diagrammes interactifs
- [GitHub Actions](https://github.com/features/actions) - CI/CD
- [GitHub Pages](https://pages.github.com/) - Hebergement

## Contribuer

Les contributions sont les bienvenues ! Consultez [CONTRIBUTING.md](CONTRIBUTING.md) pour les guidelines.

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de details.

---

*SchoolBook - Apprendre, comprendre, reussir.*
