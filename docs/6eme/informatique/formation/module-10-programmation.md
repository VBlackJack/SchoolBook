# Module 10 - Introduction à la programmation

!!! info "Objectifs du module"
    À la fin de ce module, tu sauras :

    - Comprendre ce qu'est la programmation
    - Connaître les bases des algorithmes
    - Découvrir les langages de programmation
    - Créer ton premier programme simple

    **Durée estimée : 2-3 heures** | **Pré-requis : Tous les modules précédents**

---

## Leçon 1 : Qu'est-ce que la programmation ?

### Définition

!!! tip "Programmer"
    **Programmer**, c'est donner des instructions à un ordinateur pour qu'il réalise des tâches.

    Ces instructions sont écrites dans un **langage de programmation** que l'ordinateur peut comprendre.

### Pourquoi programmer ?

!!! info "La programmation est partout"
    - Les **jeux vidéo** : Minecraft, Fortnite...
    - Les **applications** : Instagram, YouTube...
    - Les **sites web** : Google, Wikipedia...
    - Les **robots** et objets connectés
    - L'**intelligence artificielle**

    Tout ce qui est numérique a été **programmé** par quelqu'un !

### Le programmeur (développeur)

!!! tip "Un métier passionnant"
    Un **programmeur** (ou développeur) :

    - Écrit du code pour créer des programmes
    - Résout des problèmes
    - Travaille en équipe
    - Apprend constamment de nouvelles technologies

    C'est un métier très demandé et bien payé !

---

## Leçon 2 : Les algorithmes

### Qu'est-ce qu'un algorithme ?

!!! tip "Définition"
    Un **algorithme** est une suite d'instructions ordonnées pour résoudre un problème.

    C'est comme une **recette de cuisine** : des étapes à suivre dans l'ordre !

### Exemple de la vie quotidienne

!!! example "Algorithme : Faire des pâtes"
    ```
    1. Remplir une casserole d'eau
    2. Mettre la casserole sur le feu
    3. Attendre que l'eau bouille
    4. Ajouter du sel
    5. Verser les pâtes
    6. Attendre 10 minutes
    7. Égoutter les pâtes
    8. Servir
    ```

    C'est un algorithme ! Des étapes précises, dans un ordre logique.

### Les caractéristiques d'un bon algorithme

!!! warning "Règles importantes"
    Un algorithme doit être :

    - **Précis** : chaque étape est claire
    - **Ordonné** : les étapes sont dans le bon ordre
    - **Fini** : il a un début et une fin
    - **Sans ambiguïté** : une seule interprétation possible

### Les structures de base

!!! info "Les 3 structures fondamentales"
    | Structure | Description | Exemple |
    |-----------|-------------|---------|
    | **Séquence** | Instructions l'une après l'autre | Faire A, puis B, puis C |
    | **Condition** | SI quelque chose ALORS faire | SI il pleut ALORS prendre parapluie |
    | **Boucle** | Répéter plusieurs fois | Répéter 10 fois : sauter |

### La condition (SI... ALORS...)

!!! example "Exemple"
    ```
    SI il fait froid ALORS
        mettre un manteau
    SINON
        mettre un t-shirt
    FIN SI
    ```

### La boucle (RÉPÉTER)

!!! example "Exemple"
    ```
    RÉPÉTER 5 fois
        dire "Bonjour"
    FIN RÉPÉTER
    ```

    Résultat : "Bonjour" s'affiche 5 fois.

---

## Exercices guidés - Leçon 2

### Exercice 2.1 : Écrire un algorithme

!!! question "Écris un algorithme pour..."
    Traverser la route en sécurité.

??? success "Correction possible"
    ```
    1. S'arrêter au bord du trottoir
    2. Regarder à gauche
    3. Regarder à droite
    4. Regarder à nouveau à gauche
    5. SI une voiture arrive ALORS
           Attendre qu'elle passe
           Recommencer à l'étape 2
       SINON
           Traverser rapidement
       FIN SI
    ```

### Exercice 2.2 : Trouver l'erreur

!!! question "Cet algorithme pour faire un gâteau est-il correct ?"
    ```
    1. Mettre le gâteau au four
    2. Mélanger les ingrédients
    3. Verser dans un moule
    4. Sortir le gâteau du four
    ```

??? success "Correction"
    **Non !** L'ordre est faux. On ne peut pas mettre au four avant de mélanger !

    Ordre correct :
    1. Mélanger les ingrédients
    2. Verser dans un moule
    3. Mettre le gâteau au four
    4. Sortir le gâteau du four

---

## Leçon 3 : Les langages de programmation

### Pourquoi des langages ?

!!! info "Le problème"
    L'ordinateur ne comprend que le **binaire** (0 et 1).
    Impossible d'écrire des programmes en binaire pour un humain !

    Les **langages de programmation** permettent d'écrire du code compréhensible qui sera traduit en binaire.

### Les principaux langages

!!! tip "Langages populaires"
    | Langage | Utilisé pour | Difficulté |
    |---------|--------------|:----------:|
    | **Scratch** | Apprendre (blocs visuels) | ⭐ |
    | **Python** | Tout (IA, web, scripts) | ⭐⭐ |
    | **JavaScript** | Sites web, applications | ⭐⭐ |
    | **Java** | Applications, Android | ⭐⭐⭐ |
    | **C/C++** | Jeux, systèmes | ⭐⭐⭐⭐ |
    | **HTML/CSS** | Pages web (pas vraiment programmation) | ⭐ |

### Scratch : le langage pour débuter

!!! success "Idéal pour commencer"
    **Scratch** est un langage créé par le MIT pour apprendre à programmer :

    - Programmation par **blocs** (pas de texte à taper)
    - **Visuel** et coloré
    - **Gratuit** : scratch.mit.edu
    - Utilisé dans les écoles du monde entier

!!! example "Exemple en Scratch"
    Au lieu d'écrire du code, tu assembles des blocs :

    ```
    [Quand drapeau vert cliqué]
    [Répéter 10 fois]
        [Avancer de 10 pas]
        [Tourner de 15 degrés]
    ```

### Python : le langage universel

!!! info "Le plus populaire"
    **Python** est le langage le plus enseigné et utilisé :

    - Syntaxe simple et lisible
    - Utilisé par Google, Instagram, Netflix...
    - Parfait pour l'intelligence artificielle
    - Gratuit et open source

!!! example "Exemple en Python"
    ```python
    # Afficher un message
    print("Bonjour !")

    # Poser une question
    nom = input("Comment t'appelles-tu ? ")
    print("Salut " + nom + " !")

    # Une boucle
    for i in range(5):
        print("Coucou !")
    ```

---

## Exercices guidés - Leçon 3

### Exercice 3.1 : Associer

!!! question "Quel langage pour..."
    a) Apprendre avec des blocs visuels ?
    b) Créer un site web ?
    c) Créer une intelligence artificielle ?
    d) Créer un jeu vidéo performant ?

??? success "Correction"
    a) **Scratch**
    b) **HTML/CSS + JavaScript**
    c) **Python**
    d) **C/C++** ou **C#**

---

## Leçon 4 : Les concepts de base

### Les variables

!!! tip "C'est quoi une variable ?"
    Une **variable** est une boîte qui stocke une valeur.

    Tu lui donnes un **nom** et tu peux changer son **contenu**.

!!! example "Exemple"
    ```
    age = 12          (la boîte "age" contient 12)
    nom = "Thomas"    (la boîte "nom" contient "Thomas")
    score = score + 1 (on ajoute 1 au score)
    ```

### Les types de données

!!! info "Différents types"
    | Type | Description | Exemple |
    |------|-------------|---------|
    | **Entier** | Nombre sans virgule | 42, -7, 0 |
    | **Décimal** | Nombre avec virgule | 3.14, -0.5 |
    | **Texte (chaîne)** | Suite de caractères | "Bonjour", "ABC" |
    | **Booléen** | Vrai ou Faux | True, False |

### Les opérations

!!! tip "Calculs de base"
    | Opération | Symbole | Exemple |
    |-----------|:-------:|---------|
    | Addition | + | 5 + 3 = 8 |
    | Soustraction | - | 10 - 4 = 6 |
    | Multiplication | * | 3 * 4 = 12 |
    | Division | / | 10 / 2 = 5 |

### Les conditions

!!! info "SI... ALORS... SINON..."
    ```python
    if age >= 18:
        print("Tu es majeur")
    else:
        print("Tu es mineur")
    ```

### Les boucles

!!! info "Répéter des actions"
    ```python
    # Répéter 5 fois
    for i in range(5):
        print("Bonjour !")

    # Tant que la condition est vraie
    while score < 100:
        jouer()
    ```

---

## Leçon 5 : Ton premier programme

### En Scratch

!!! success "Exercice : Le chat qui parle"
    Va sur **scratch.mit.edu** et crée ce programme :

    1. Quand on clique sur le drapeau vert
    2. Le chat dit "Bonjour ! Comment t'appelles-tu ?"
    3. Demander le nom et attendre
    4. Dire "Enchanté, [nom] !"

### En Python

!!! success "Exercice : Devine le nombre"
    ```python
    # Programme : Devine le nombre

    import random

    # L'ordinateur choisit un nombre entre 1 et 10
    nombre_secret = random.randint(1, 10)

    # On demande au joueur de deviner
    essai = int(input("Devine un nombre entre 1 et 10 : "))

    # On vérifie la réponse
    if essai == nombre_secret:
        print("Bravo ! Tu as trouvé !")
    elif essai < nombre_secret:
        print("C'est plus grand !")
    else:
        print("C'est plus petit !")

    print("Le nombre était :", nombre_secret)
    ```

### Où pratiquer ?

!!! tip "Sites pour apprendre"
    | Site | Description |
    |------|-------------|
    | **Scratch** (scratch.mit.edu) | Programmation par blocs |
    | **Code.org** | Cours gratuits, tutoriels |
    | **France-IOI** | Exercices de programmation |
    | **Codecademy** | Cours interactifs |
    | **Replit** | Coder en ligne (Python) |

---

## Entraînement

### Série 1 : Concepts

1. Qu'est-ce que la programmation ?
2. Qu'est-ce qu'un algorithme ?
3. Cite les 3 structures de base d'un algorithme.

??? success "Corrections"
    1. Donner des instructions à un ordinateur dans un langage qu'il comprend
    2. Une suite d'instructions ordonnées pour résoudre un problème
    3. Séquence, condition (SI), boucle (RÉPÉTER)

### Série 2 : Langages

1. Quel langage utilise des blocs visuels ?
2. Quel langage est utilisé pour l'intelligence artificielle ?
3. Pourquoi a-t-on créé des langages de programmation ?

??? success "Corrections"
    1. Scratch
    2. Python
    3. Parce que l'ordinateur ne comprend que le binaire, trop difficile pour les humains

### Série 3 : Variables et opérations

1. Qu'est-ce qu'une variable ?
2. Que vaut x après : x = 5, puis x = x + 3 ?
3. Cite 3 types de données.

??? success "Corrections"
    1. Une boîte qui stocke une valeur
    2. x = 8
    3. Entier, décimal, texte (chaîne), booléen (3 au choix)

---

## Évaluation du module (sur 20)

**Q1.** Qu'est-ce que la programmation ? (2 pts)

**Q2.** Qu'est-ce qu'un algorithme ? Donne un exemple de la vie quotidienne. (3 pts)

**Q3.** Cite les 3 structures de base d'un algorithme avec une description. (3 pts)

**Q4.** Pourquoi a-t-on besoin de langages de programmation ? (2 pts)

**Q5.** Cite 3 langages de programmation et leur utilité. (3 pts)

**Q6.** Qu'est-ce qu'une variable ? (2 pts)

**Q7.** Écris un petit algorithme pour calculer la moyenne de deux notes. (3 pts)

**Q8.** Que fait ce code Python ? (2 pts)
```python
for i in range(3):
    print("Salut !")
```

??? success "Corrections"
    Q1. Donner des instructions à un ordinateur dans un langage qu'il peut comprendre

    Q2. Une suite d'instructions ordonnées pour résoudre un problème. Exemple : recette de cuisine, s'habiller le matin, etc.

    Q3.
    - Séquence : instructions l'une après l'autre
    - Condition : SI... ALORS... SINON
    - Boucle : RÉPÉTER plusieurs fois

    Q4. L'ordinateur ne comprend que le binaire (0 et 1), trop difficile pour les humains. Les langages permettent d'écrire du code lisible qui est traduit en binaire.

    Q5.
    - Scratch : apprendre avec des blocs
    - Python : IA, scripts, web
    - JavaScript : sites web
    - (ou autres réponses valides)

    Q6. Une boîte nommée qui stocke une valeur qu'on peut modifier

    Q7. Exemple :
    ```
    1. Demander la première note (note1)
    2. Demander la deuxième note (note2)
    3. Calculer moyenne = (note1 + note2) / 2
    4. Afficher la moyenne
    ```

    Q8. Il affiche "Salut !" trois fois (boucle qui répète 3 fois)

---

## Félicitations !

!!! success "Tu as terminé la formation informatique !"
    Tu maîtrises maintenant :

    - Le fonctionnement d'un ordinateur
    - Les composants matériels (hardware)
    - Le processeur et la mémoire
    - Le stockage des données
    - Les systèmes d'exploitation
    - L'organisation des fichiers
    - Internet et les réseaux
    - La sécurité informatique
    - Les logiciels
    - Les bases de la programmation

    **Tu es prêt à explorer davantage le monde numérique !**

---

## Pour aller plus loin

!!! tip "Prochaines étapes"
    - **Scratch** : Crée des jeux et animations
    - **Python** : Apprends à coder en texte
    - **HTML/CSS** : Crée ton propre site web
    - **Robotique** : Programme des robots (Arduino, Raspberry Pi)
    - **Intelligence Artificielle** : Découvre le machine learning

---

[Retour à l'index de la formation](index.md){ .md-button .md-button--primary }

[Refaire le test initial (Module 0)](module-00-depart.md){ .md-button }
