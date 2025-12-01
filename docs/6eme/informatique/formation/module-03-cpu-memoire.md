# Module 3 - Le processeur et la mémoire

!!! info "Objectifs du module"
    À la fin de ce module, tu sauras :

    - Comprendre le fonctionnement du processeur (CPU)
    - Distinguer les différents types de mémoire
    - Comprendre le rôle de la mémoire RAM
    - Lire les caractéristiques techniques d'un processeur

    **Durée estimée : 1-2 heures** | **Pré-requis : Module 2**

---

## Leçon 1 : Le processeur (CPU)

### Qu'est-ce que le processeur ?

!!! tip "Définition"
    Le **processeur** (CPU = Central Processing Unit) est le composant qui :

    - Exécute les **instructions** des programmes
    - Effectue les **calculs** mathématiques et logiques
    - Coordonne le fonctionnement de l'ordinateur

    C'est le **cerveau** de l'ordinateur !

### Comment fonctionne un processeur ?

!!! info "Le cycle du processeur"
    Le processeur répète sans cesse ces 4 étapes :

    ```mermaid
    graph LR
        A[1. FETCH<br>Chercher l'instruction] --> B[2. DECODE<br>Comprendre l'instruction]
        B --> C[3. EXECUTE<br>Exécuter l'instruction]
        C --> D[4. STORE<br>Stocker le résultat]
        D --> A
    ```

    Et il fait ça des **milliards de fois par seconde** !

### Les caractéristiques d'un processeur

!!! info "Ce qu'il faut regarder"
    | Caractéristique | Signification | Exemple |
    |-----------------|---------------|---------|
    | **Fréquence (GHz)** | Vitesse d'exécution | 3.5 GHz |
    | **Nombre de cœurs** | Capacité multitâche | 8 cœurs |
    | **Cache** | Mémoire ultra-rapide intégrée | 16 Mo |
    | **Architecture** | Génération du processeur | Intel 13e gen |

### La fréquence (GHz)

!!! tip "Comprendre les GHz"
    - **Hz (Hertz)** = 1 opération par seconde
    - **MHz (Mégahertz)** = 1 million d'opérations par seconde
    - **GHz (Gigahertz)** = 1 milliard d'opérations par seconde

    Un processeur à **3.5 GHz** effectue **3,5 milliards d'opérations par seconde** !

### Les cœurs du processeur

!!! info "C'est quoi un cœur ?"
    Un **cœur** est une unité de calcul indépendante.

    - **1 cœur** = 1 tâche à la fois
    - **4 cœurs** = 4 tâches en parallèle
    - **8 cœurs** = 8 tâches en parallèle

!!! example "Analogie : La cuisine ! 👨‍🍳"
    Imagine une cuisine :

    - **1 cœur** = 1 cuisinier
    - **8 cœurs** = 8 cuisiniers travaillant ensemble

    Plus il y a de cuisiniers, plus on peut préparer de plats en même temps !

    ```
    1 CŒUR (1 cuisinier)              8 CŒURS (8 cuisiniers)
    ┌─────────────────────┐           ┌─────────────────────┐
    │  👨‍🍳                  │           │ 👨‍🍳👨‍🍳👨‍🍳👨‍🍳           │
    │  🍳                  │           │ 👨‍🍳👨‍🍳👨‍🍳👨‍🍳           │
    │                     │           │ 🍳🍳🍳🍳🍳🍳🍳🍳      │
    │  1 plat à la fois   │           │ 8 plats en même temps│
    └─────────────────────┘           └─────────────────────┘
    ```

### Les grandes marques

!!! info "Les fabricants de processeurs"
    | Marque | Gamme PC | Gamme performante |
    |--------|----------|-------------------|
    | **Intel** | Core i3, i5 | Core i7, i9 |
    | **AMD** | Ryzen 3, 5 | Ryzen 7, 9 |
    | **Apple** | M1 | M2, M3 Pro/Max |

---

## Exercices guidés - Leçon 1

### Exercice 1.1 : Comprendre les specs

!!! question "Quel processeur est le plus puissant ?"
    a) Intel Core i5 - 2.4 GHz - 4 cœurs
    b) Intel Core i7 - 3.6 GHz - 8 cœurs
    c) Intel Core i3 - 3.0 GHz - 2 cœurs

??? success "Correction"
    **b) Intel Core i7 - 3.6 GHz - 8 cœurs**

    - Plus haute fréquence (3.6 GHz > 3.0 GHz > 2.4 GHz)
    - Plus de cœurs (8 > 4 > 2)
    - Meilleure gamme (i7 > i5 > i3)

---

## Leçon 2 : Les différents types de mémoire

### Hiérarchie des mémoires

!!! info "Du plus rapide au plus lent"
    ```mermaid
    graph TD
        A[Registres CPU<br>Ultra rapide, minuscule] --> B[Mémoire cache<br>Très rapide, petite]
        B --> C[Mémoire RAM<br>Rapide, moyenne]
        C --> D[SSD<br>Assez rapide, grande]
        D --> E[Disque dur HDD<br>Lent, très grande]
    ```

### Comparaison des mémoires

!!! tip "Caractéristiques"
    | Type | Vitesse | Capacité | Persistance | Prix |
    |------|:-------:|:--------:|:-----------:|:----:|
    | **Registres** | ⚡⚡⚡⚡⚡ | Octets | Non | - |
    | **Cache** | ⚡⚡⚡⚡ | Mo | Non | Inclus |
    | **RAM** | ⚡⚡⚡ | Go | Non | €€ |
    | **SSD** | ⚡⚡ | To | Oui | €€€ |
    | **HDD** | ⚡ | To | Oui | € |

!!! example "La pyramide des mémoires 🏔️"
    ```
    Plus RAPIDE mais PETIT                    Plus LENT mais GRAND
           ▲                                         ▼
           │    ┌─────┐                              │
           │    │Cache│ ← Hyper rapide (dans le CPU) │
           │    │ 🏃💨 │   Quelques Mo                │
           │    └──┬──┘                              │
           │  ┌────┴────┐                            │
           │  │   RAM   │ ← Rapide                   │
           │  │   🚗    │   8-32 Go                  │
           │  └────┬────┘                            │
           │ ┌─────┴─────┐                           │
           │ │    SSD    │ ← Assez rapide            │
           │ │    🚲     │   256 Go - 2 To           │
           │ └─────┬─────┘                           │
           │┌──────┴──────┐                          │
           ││    HDD     │ ← Lent mais énorme        │
           ││    🐢      │   1-4 To                  │
           │└────────────┘                           │
           ▼                                         ▲
    ```

### Mémoire volatile vs non-volatile

!!! warning "Important !"
    - **Volatile** (RAM, cache) : les données disparaissent quand on éteint
    - **Non-volatile** (SSD, HDD) : les données restent quand on éteint

    C'est pour ça qu'il faut **sauvegarder** son travail !

---

## Leçon 3 : La mémoire RAM

### Qu'est-ce que la RAM ?

!!! tip "Définition"
    La **RAM** (Random Access Memory) est la mémoire vive qui :

    - Stocke **temporairement** les données en cours d'utilisation
    - Permet au processeur d'accéder **rapidement** aux informations
    - Se vide quand on éteint l'ordinateur

    C'est le **bureau de travail** de l'ordinateur !

### Pourquoi la RAM est importante ?

!!! info "Rôle de la RAM"
    Quand tu ouvres un programme :

    1. Le programme est copié du **disque dur** vers la **RAM**
    2. Le **processeur** travaille avec les données en RAM
    3. C'est beaucoup plus rapide que d'aller chercher sur le disque !

!!! example "Analogie : Ton bureau de travail ! 📚"
    Imagine que tu fais tes devoirs :

    - **Disque dur** = ton armoire de rangement (grande, mais loin)
    - **RAM** = ton bureau (plus petit, mais tout est à portée de main)

    Tu sors tes cahiers de l'armoire et tu les poses sur le bureau pour travailler !

    ```
    ┌─────────────────────────────────────────────────────────────────┐
    │  TA CHAMBRE                                                     │
    │                                                                 │
    │   🗄️ ARMOIRE (Disque dur)         📝 BUREAU (RAM)               │
    │   ┌─────────────┐                 ┌─────────────────┐           │
    │   │ 📚📚📚📚📚 │                 │  📖 📓 ✏️       │           │
    │   │ 📚📚📚📚📚 │  ──Sortir──▶   │  Tes devoirs    │           │
    │   │ 📚📚📚📚📚 │   un livre     │  en cours !     │           │
    │   │ BEAUCOUP   │                 │  (Plus rapide)  │           │
    │   │ de livres  │  ◀──Ranger──   │                 │           │
    │   └─────────────┘                 └─────────────────┘           │
    │                                                                 │
    │   💡 Quand tu éteins la lumière, le bureau est "vidé"          │
    │      (tu ranges tout), mais l'armoire garde tes affaires !     │
    └─────────────────────────────────────────────────────────────────┘
    ```

### Combien de RAM faut-il ?

!!! tip "Recommandations"
    | Usage | RAM recommandée |
    |-------|:---------------:|
    | Basique (web, bureautique) | 4-8 Go |
    | Standard (multimédia, travail) | 8-16 Go |
    | Gaming | 16-32 Go |
    | Professionnel (vidéo, 3D) | 32-64 Go |

### Caractéristiques de la RAM

!!! info "Ce qu'il faut regarder"
    | Caractéristique | Signification | Exemple |
    |-----------------|---------------|---------|
    | **Capacité** | Quantité de données stockables | 16 Go |
    | **Type** | Génération de RAM | DDR4, DDR5 |
    | **Fréquence** | Vitesse de transfert | 3200 MHz |

### DDR4 vs DDR5

!!! info "Les générations de RAM"
    - **DDR4** : Standard actuel, bon rapport qualité/prix
    - **DDR5** : Nouvelle génération, plus rapide, plus chère

    *Attention : une carte mère DDR4 n'accepte PAS de RAM DDR5 (et vice-versa) !*

---

## Exercices guidés - Leçon 3

### Exercice 3.1 : Vrai ou Faux

!!! question "Réponds"
    a) La RAM garde les données quand on éteint l'ordinateur.
    b) Plus on a de RAM, plus on peut ouvrir de programmes en même temps.
    c) 4 Go de RAM suffisent pour jouer aux jeux vidéo récents.
    d) La RAM est plus rapide que le disque dur.

??? success "Correction"
    a) **Faux** - La RAM est volatile, elle se vide à l'extinction
    b) **Vrai** - Plus de RAM = plus d'espace pour les programmes
    c) **Faux** - Il faut au moins 16 Go pour les jeux récents
    d) **Vrai** - La RAM est beaucoup plus rapide que le disque dur

---

## Leçon 4 : La mémoire cache

### Qu'est-ce que le cache ?

!!! info "Définition"
    Le **cache** est une mémoire ultra-rapide intégrée au processeur qui :

    - Stocke les données les plus utilisées
    - Évite d'aller chercher dans la RAM (plus lente)
    - Accélère le fonctionnement du processeur

### Les niveaux de cache

!!! tip "L1, L2, L3"
    | Niveau | Taille | Vitesse | Localisation |
    |:------:|:------:|:-------:|--------------|
    | **L1** | 32-64 Ko | Ultra rapide | Dans chaque cœur |
    | **L2** | 256 Ko - 1 Mo | Très rapide | Proche des cœurs |
    | **L3** | 8-64 Mo | Rapide | Partagé entre les cœurs |

!!! example "Analogie"
    - **L1** = Ta poche (petit, très accessible)
    - **L2** = Ton sac (plus grand, un peu moins accessible)
    - **L3** = Ton casier (encore plus grand, un peu plus loin)
    - **RAM** = Ton armoire à la maison

---

## Leçon 5 : Processeur et mémoire en action

### Comment tout fonctionne ensemble

!!! info "Scénario : tu ouvres un jeu vidéo"
    1. Tu double-cliques sur l'icône du jeu
    2. Le **système d'exploitation** demande au **disque dur/SSD** de charger le jeu
    3. Le jeu est copié dans la **RAM**
    4. Le **processeur** exécute les instructions du jeu
    5. Les données les plus utilisées sont mises en **cache**
    6. La **carte graphique** affiche les images à l'écran

### Goulot d'étranglement (bottleneck)

!!! warning "Équilibre important"
    Si un composant est trop faible par rapport aux autres, il ralentit tout !

    - Processeur puissant + peu de RAM = lenteur
    - Beaucoup de RAM + vieux processeur = gaspillage
    - SSD lent + processeur rapide = temps de chargement

    C'est pour ça qu'il faut des composants **équilibrés** !

### Surveiller l'utilisation

!!! tip "Gestionnaire des tâches (Windows)"
    Tu peux voir l'utilisation du processeur et de la RAM :

    1. Appuie sur **Ctrl + Shift + Échap**
    2. Regarde les onglets **Processeur** et **Mémoire**
    3. Si c'est à 100% tout le temps, il faut peut-être plus de ressources !

---

## Entraînement

### Série 1 : Le processeur

1. Que signifie CPU ?
2. À quoi correspond la fréquence en GHz ?
3. Pourquoi avoir plusieurs cœurs est utile ?

??? success "Corrections"
    1. Central Processing Unit (Unité Centrale de Traitement)
    2. La vitesse d'exécution (nombre d'opérations par seconde)
    3. Pour exécuter plusieurs tâches en parallèle (multitâche)

### Série 2 : La mémoire

1. Quelle est la différence entre mémoire volatile et non-volatile ?
2. Pourquoi la RAM est-elle plus rapide que le disque dur ?
3. Combien de RAM recommande-t-on pour le gaming ?

??? success "Corrections"
    1. Volatile = se vide à l'extinction / Non-volatile = garde les données
    2. La RAM utilise des puces électroniques, le disque dur a des pièces mécaniques
    3. 16 à 32 Go

### Série 3 : Cache et fonctionnement

1. Qu'est-ce que le cache L1 ?
2. Pourquoi le cache est-il plus rapide que la RAM ?
3. Qu'est-ce qu'un goulot d'étranglement ?

??? success "Corrections"
    1. La mémoire cache la plus rapide, intégrée dans chaque cœur du processeur
    2. Il est intégré directement dans le processeur et plus proche des unités de calcul
    3. Quand un composant est trop faible et ralentit les autres

---

## Évaluation du module (sur 20)

**Q1.** Quel est le rôle du processeur ? (2 pts)

**Q2.** Un processeur à 4 GHz effectue combien d'opérations par seconde ? (1 pt)

**Q3.** Qu'est-ce qu'un cœur de processeur ? (2 pts)

**Q4.** Cite les deux grandes marques de processeurs pour PC. (2 pts)

**Q5.** Qu'est-ce que la RAM et pourquoi est-elle importante ? (3 pts)

**Q6.** La RAM est-elle volatile ou non-volatile ? Explique. (2 pts)

**Q7.** Combien de RAM recommande-t-on pour un usage bureautique ? (1 pt)

**Q8.** Qu'est-ce que le cache processeur ? (2 pts)

**Q9.** Classe du plus rapide au plus lent : RAM, Cache L1, SSD, HDD (2 pts)

**Q10.** Explique ce qu'est un "goulot d'étranglement". (3 pts)

??? success "Corrections"
    Q1. Exécuter les instructions des programmes et effectuer les calculs
    Q2. 4 milliards d'opérations par seconde
    Q3. Une unité de calcul indépendante qui peut exécuter des tâches
    Q4. Intel et AMD
    Q5. Mémoire vive temporaire qui stocke les données en cours d'utilisation pour que le processeur y accède rapidement
    Q6. Volatile : elle se vide quand on éteint l'ordinateur
    Q7. 4 à 8 Go
    Q8. Mémoire ultra-rapide intégrée au processeur pour stocker les données les plus utilisées
    Q9. Cache L1 > RAM > SSD > HDD
    Q10. Quand un composant est trop faible par rapport aux autres et ralentit l'ensemble du système

---

## Prochaine étape

!!! success "Bravo !"
    Tu comprends maintenant comment fonctionnent le processeur et la mémoire !
    Dans le prochain module, on va explorer le **stockage des données**.

[Module 4 - Le stockage des données](module-04-stockage.md){ .md-button .md-button--primary }

[Retour à l'index](index.md){ .md-button }
