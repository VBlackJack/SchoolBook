# Guide de contribution

Merci de votre interet pour contribuer a SchoolBook ! Ce guide vous explique comment participer au projet.

## Comment contribuer

### Signaler un probleme

1. Verifiez que le probleme n'a pas deja ete signale dans les [Issues](https://github.com/VBlackJack/SchoolBook/issues)
2. Creez une nouvelle issue en decrivant :
   - Le probleme rencontre
   - Les etapes pour le reproduire
   - Le comportement attendu
   - Des captures d'ecran si necessaire

### Proposer une amelioration

1. Ouvrez une issue pour discuter de votre idee
2. Attendez la validation avant de commencer le developpement
3. Suivez le processus de Pull Request ci-dessous

### Corriger une erreur dans le contenu

Les corrections de fautes d'orthographe, erreurs pedagogiques ou informations obsoletes sont les bienvenues !

## Processus de Pull Request

1. **Fork** le repository
2. **Clonez** votre fork localement
3. **Creez une branche** pour vos modifications :
   ```bash
   git checkout -b type/description-courte
   ```
   Types : `fix/`, `feat/`, `docs/`, `style/`

4. **Faites vos modifications**
5. **Testez localement** :
   ```bash
   pip install mkdocs-material mkdocs-minify-plugin
   mkdocs serve
   ```
6. **Commitez** avec un message clair :
   ```bash
   git commit -m "fix(maths): correction exercice fractions module 4"
   ```
7. **Poussez** votre branche :
   ```bash
   git push origin type/description-courte
   ```
8. **Ouvrez une Pull Request** vers la branche `main`

## Standards de contenu

### Structure d'un module

Chaque module doit contenir :

```markdown
# Module X - Titre

!!! info "Objectifs du module"
    A la fin de ce module, tu sauras :
    - Objectif 1
    - Objectif 2

    **Duree estimee : X heures** | **Pre-requis : ...**

---

## Dans la vraie vie : pourquoi [sujet] ?

[Exemples concrets avec jeux video, sport, vie quotidienne]

---

## Lecon

[Contenu pedagogique]

---

## Exercices guides

[Exercices avec corrections detaillees]

---

## Entrainement

[Exercices autonomes]

---

## Evaluation

[Quiz ou exercices notes]

---

## Navigation

[Liens vers module precedent/suivant]
```

### Style d'ecriture

- **Tutoiement** : On s'adresse directement a l'eleve ("tu vas apprendre...")
- **Exemples concrets** : Utiliser des references aux jeux video, sport, reseaux sociaux
- **Progressivite** : Du simple au complexe
- **Pieges a eviter** : Anticiper les erreurs courantes

### Elements visuels

- Utiliser les **admonitions** MkDocs (`!!! tip`, `!!! warning`, `!!! example`)
- Utiliser les **onglets** pour les explications alternatives
- Utiliser **Mermaid** pour les diagrammes
- Privilegier l'**ASCII art** aux images quand possible

### Conventions de nommage

- Fichiers : `module-XX-nom.md` (XX = numero a 2 chiffres)
- Pas d'accents dans les noms de fichiers
- Tout en minuscules avec tirets

## Installation locale

```bash
# Cloner votre fork
git clone https://github.com/VOTRE_USERNAME/SchoolBook.git
cd SchoolBook

# Installer les dependances
pip install mkdocs-material mkdocs-minify-plugin

# Lancer le serveur de dev
mkdocs serve
```

Le site sera accessible sur http://127.0.0.1:8000

## Questions ?

N'hesitez pas a ouvrir une issue pour toute question !

---

Merci de contribuer a SchoolBook !
