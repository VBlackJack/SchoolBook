# Module 6 - Les fichiers et dossiers

!!! info "Objectifs du module"
    À la fin de ce module, tu sauras :

    - Comprendre ce qu'est un fichier et un dossier
    - Reconnaître les extensions de fichiers courantes
    - Organiser efficacement tes documents
    - Utiliser l'explorateur de fichiers

    **Durée estimée : 1-2 heures** | **Pré-requis : Module 5**

---

## Leçon 1 : Qu'est-ce qu'un fichier ?

### Définition

!!! tip "Un fichier"
    Un **fichier** est un ensemble de données enregistrées sur un support de stockage.

    Chaque fichier a :

    - Un **nom** (ex : "mon-devoir")
    - Une **extension** (ex : ".docx")
    - Une **taille** (ex : 25 Ko)
    - Une **date** de création/modification

### Types de fichiers

!!! info "Les grandes catégories"
    | Catégorie | Description | Exemples |
    |-----------|-------------|----------|
    | **Documents** | Textes, tableaux, présentations | .docx, .pdf, .xlsx |
    | **Images** | Photos, dessins | .jpg, .png, .gif |
    | **Audio** | Musique, sons | .mp3, .wav, .flac |
    | **Vidéo** | Films, clips | .mp4, .mkv, .avi |
    | **Archives** | Fichiers compressés | .zip, .rar, .7z |
    | **Exécutables** | Programmes | .exe, .msi |

### L'extension du fichier

!!! warning "C'est quoi l'extension ?"
    L'**extension** est le suffixe après le point dans le nom du fichier.
    Elle indique le **type** et le **programme** à utiliser.

    Exemples :
    - photo**.jpg** → image, s'ouvre avec une visionneuse
    - devoir**.docx** → document Word
    - musique**.mp3** → audio, s'ouvre avec un lecteur

!!! danger "Ne pas changer l'extension !"
    Si tu renommes "photo.jpg" en "photo.mp3", l'ordinateur essaiera de l'ouvrir comme un fichier audio... et ça ne marchera pas !

!!! example "L'extension, c'est l'étiquette du fichier ! 🏷️"
    ```
    FICHIER = NOM + EXTENSION

        mon-devoir.docx
        └────┬────┘└─┬─┘
             │       │
          Le NOM   L'EXTENSION
        (ce que    (le TYPE)
        tu choisis)

    ┌─────────────────────────────────────────────────────────────┐
    │  📄 TYPES DE FICHIERS ET LEURS ICÔNES                      │
    │                                                             │
    │  📝 .docx .odt .txt     = Documents texte                  │
    │  📊 .xlsx .ods          = Tableaux (Excel)                 │
    │  📑 .pdf                = Document figé                     │
    │  🖼️ .jpg .png .gif      = Images                           │
    │  🎵 .mp3 .wav .flac     = Musique                          │
    │  🎬 .mp4 .mkv .avi      = Vidéos                           │
    │  📦 .zip .rar           = Archives compressées             │
    │  ⚙️ .exe                = Programme Windows                │
    │                                                             │
    │  L'extension dit à l'ordinateur QUEL PROGRAMME utiliser !  │
    └─────────────────────────────────────────────────────────────┘
    ```

---

## Exercices guidés - Leçon 1

### Exercice 1.1 : Identifier le type

!!! question "De quel type est chaque fichier ?"
    a) vacances.jpg
    b) rapport.pdf
    c) chanson.mp3
    d) film.mp4
    e) archive.zip

??? success "Correction"
    a) **Image** (.jpg)
    b) **Document** (.pdf)
    c) **Audio** (.mp3)
    d) **Vidéo** (.mp4)
    e) **Archive compressée** (.zip)

---

## Leçon 2 : Les extensions courantes

### Documents

!!! info "Extensions de documents"
    | Extension | Type | Programme |
    |:---------:|------|-----------|
    | **.docx** | Document Word | Microsoft Word, LibreOffice |
    | **.xlsx** | Tableau Excel | Microsoft Excel, LibreOffice |
    | **.pptx** | Présentation | Microsoft PowerPoint |
    | **.pdf** | Document figé | Adobe Reader, navigateur |
    | **.txt** | Texte brut | Bloc-notes |
    | **.odt** | Document LibreOffice | LibreOffice Writer |

### Images

!!! info "Extensions d'images"
    | Extension | Caractéristiques |
    |:---------:|------------------|
    | **.jpg / .jpeg** | Photos, bonne compression |
    | **.png** | Images avec transparence |
    | **.gif** | Images animées |
    | **.bmp** | Image non compressée (lourd) |
    | **.svg** | Image vectorielle (redimensionnable) |
    | **.webp** | Format moderne, léger |

### Audio

!!! info "Extensions audio"
    | Extension | Caractéristiques |
    |:---------:|------------------|
    | **.mp3** | Le plus répandu, compressé |
    | **.wav** | Haute qualité, non compressé |
    | **.flac** | Haute qualité, compressé sans perte |
    | **.aac** | Utilisé par Apple |
    | **.ogg** | Format libre |

### Vidéo

!!! info "Extensions vidéo"
    | Extension | Caractéristiques |
    |:---------:|------------------|
    | **.mp4** | Le plus courant |
    | **.mkv** | Conteneur flexible |
    | **.avi** | Ancien format |
    | **.mov** | Format Apple |
    | **.webm** | Pour le web |

---

## Exercices guidés - Leçon 2

### Exercice 2.1 : Quel programme ?

!!! question "Avec quel programme ouvrir ces fichiers ?"
    a) presentation.pptx
    b) photo.png
    c) musique.flac
    d) document.pdf

??? success "Correction"
    a) **Microsoft PowerPoint** (ou LibreOffice Impress)
    b) Une **visionneuse d'images** (Photos, Paint, etc.)
    c) Un **lecteur audio** (VLC, Windows Media Player, etc.)
    d) **Adobe Reader** ou un **navigateur web**

---

## Leçon 3 : Les dossiers

### Qu'est-ce qu'un dossier ?

!!! tip "Définition"
    Un **dossier** (ou répertoire) est un conteneur qui permet d'**organiser** les fichiers.

    Pense à une armoire avec des tiroirs :
    - L'**armoire** = le disque dur
    - Les **tiroirs** = les dossiers
    - Les **documents** dans les tiroirs = les fichiers

!!! example "L'armoire et les tiroirs 🗄️"
    ```
    LE DISQUE DUR = UNE GRANDE ARMOIRE

    ┌────────────────────────────────────────────────┐
    │  🗄️ DISQUE DUR (C:)                           │
    │  ═══════════════════                           │
    │                                                │
    │  ┌──────────────────────────────────────────┐  │
    │  │ 📁 Documents                              │  │
    │  │  ├── 📁 Collège                          │  │
    │  │  │    ├── 📁 Maths                       │  │
    │  │  │    │    ├── 📄 devoir.docx            │  │
    │  │  │    │    └── 📄 cours.pdf              │  │
    │  │  │    └── 📁 Français                    │  │
    │  │  │         └── 📄 rédaction.docx         │  │
    │  │  └── 📁 Personnel                        │  │
    │  │       └── 📄 liste.txt                   │  │
    │  └──────────────────────────────────────────┘  │
    │                                                │
    │  ┌──────────────────────────────────────────┐  │
    │  │ 📁 Images                                 │  │
    │  │  ├── 🖼️ vacances.jpg                     │  │
    │  │  └── 🖼️ famille.png                      │  │
    │  └──────────────────────────────────────────┘  │
    │                                                │
    │  Les DOSSIERS (📁) sont comme des TIROIRS     │
    │  Les FICHIERS (📄🖼️) sont les DOCUMENTS dedans │
    └────────────────────────────────────────────────┘
    ```

### L'arborescence

!!! info "Structure en arbre"
    Les dossiers sont organisés en **arborescence** (comme un arbre) :

    ```
    C:\
    ├── Utilisateurs
    │   └── Thomas
    │       ├── Documents
    │       │   ├── Collège
    │       │   │   ├── Français
    │       │   │   └── Maths
    │       │   └── Personnel
    │       ├── Images
    │       ├── Musique
    │       └── Vidéos
    └── Program Files
    ```

### Le chemin d'accès

!!! warning "L'adresse du fichier"
    Le **chemin d'accès** indique où se trouve un fichier.

    Exemple : `C:\Utilisateurs\Thomas\Documents\Collège\Maths\devoir.docx`

    - **C:** = le disque
    - **\Utilisateurs\Thomas\Documents\Collège\Maths\** = les dossiers
    - **devoir.docx** = le fichier

!!! example "Le chemin, c'est comme une adresse postale ! 📬"
    ```
    ADRESSE POSTALE                    CHEMIN DE FICHIER
    ═══════════════                    ═════════════════

    France                             C:\
       ↓                                  ↓
    Paris                              Utilisateurs
       ↓                                  ↓
    Rue de la Paix                     Thomas
       ↓                                  ↓
    Immeuble 15                        Documents
       ↓                                  ↓
    Appartement 3B                     Collège
       ↓                                  ↓
    M. Dupont                          Maths
                                          ↓
                                       devoir.docx

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  C:\Utilisateurs\Thomas\Documents\Collège\Maths\devoir.docx │
    │  ──┬─────────────────────────────────────────────┬─────────│
    │    │                                             │          │
    │  DISQUE ────── CHEMIN (les dossiers) ────── FICHIER        │
    │                                                             │
    │  Chaque \ sépare un niveau (comme chaque ligne d'adresse)  │
    └─────────────────────────────────────────────────────────────┘
    ```

### Dossiers par défaut (Windows)

!!! info "Les dossiers de l'utilisateur"
    | Dossier | Contenu recommandé |
    |---------|-------------------|
    | **Documents** | Fichiers texte, PDF, travaux |
    | **Images** | Photos et images |
    | **Musique** | Fichiers audio |
    | **Vidéos** | Fichiers vidéo |
    | **Téléchargements** | Fichiers téléchargés |
    | **Bureau** | Raccourcis et fichiers temporaires |

---

## Exercices guidés - Leçon 3

### Exercice 3.1 : Lire un chemin

!!! question "Analyse ce chemin"
    `C:\Utilisateurs\Emma\Documents\Collège\SVT\exposé.pptx`

    a) Quel est le nom du fichier ?
    b) Dans quel dossier est-il ?
    c) Quel est le type de fichier ?

??? success "Correction"
    a) **exposé.pptx**
    b) Dans le dossier **SVT** (lui-même dans Collège > Documents > Emma > Utilisateurs)
    c) C'est une **présentation PowerPoint** (.pptx)

---

## Leçon 4 : L'explorateur de fichiers

### Ouvrir l'explorateur

!!! tip "Plusieurs méthodes"
    - Cliquer sur l'icône 📁 dans la barre des tâches
    - Raccourci : **Windows + E**
    - Clic droit sur le menu Démarrer → Explorateur de fichiers

### Les éléments de l'interface

!!! info "Interface de l'explorateur Windows"
    | Zone | Fonction |
    |------|----------|
    | **Barre d'adresse** | Affiche le chemin actuel |
    | **Volet de navigation** | Accès rapide aux dossiers (gauche) |
    | **Zone principale** | Affiche le contenu du dossier |
    | **Barre de recherche** | Pour chercher des fichiers |
    | **Boutons Précédent/Suivant** | Naviguer dans l'historique |

### Actions de base

!!! tip "Ce qu'on peut faire"
    | Action | Comment |
    |--------|---------|
    | **Créer un dossier** | Clic droit → Nouveau → Dossier |
    | **Renommer** | Clic droit → Renommer (ou F2) |
    | **Supprimer** | Clic droit → Supprimer (ou Suppr) |
    | **Copier** | Clic droit → Copier (ou Ctrl+C) |
    | **Coller** | Clic droit → Coller (ou Ctrl+V) |
    | **Déplacer** | Couper (Ctrl+X) puis Coller |
    | **Sélectionner tout** | Ctrl + A |

### La corbeille

!!! warning "Filet de sécurité"
    Quand tu supprimes un fichier, il va dans la **Corbeille**.
    Tu peux encore le récupérer !

    Pour supprimer définitivement : **Shift + Suppr** (attention !)

    Pour vider la corbeille : Clic droit sur la Corbeille → Vider la corbeille

---

## Exercices guidés - Leçon 4

### Exercice 4.1 : Raccourcis de l'explorateur

!!! question "Quel raccourci pour..."
    a) Ouvrir l'explorateur de fichiers ?
    b) Renommer un fichier sélectionné ?
    c) Sélectionner tous les fichiers ?
    d) Copier un fichier ?

??? success "Correction"
    a) **Windows + E**
    b) **F2**
    c) **Ctrl + A**
    d) **Ctrl + C**

---

## Leçon 5 : Bien organiser ses fichiers

### Pourquoi s'organiser ?

!!! tip "Les avantages"
    - **Retrouver** rapidement ses fichiers
    - **Éviter** de perdre des documents importants
    - **Gagner** du temps
    - **Faciliter** les sauvegardes

### Règles de nommage

!!! danger "Bonnes pratiques pour nommer"
    **À faire :**

    - Utiliser des noms **descriptifs** : "devoir-maths-fractions.docx"
    - Utiliser des **tirets** ou **underscores** : "photo_vacances_2024.jpg"
    - Inclure la **date** si utile : "2024-01-15_rapport.pdf"

    **À éviter :**

    - Noms trop courts : "doc1.docx" ❌
    - Caractères spéciaux : "devoir/maths?.docx" ❌
    - Espaces (parfois problématiques) : préférer les tirets

### Structure recommandée

!!! example "Exemple d'organisation pour le collège"
    ```
    Documents
    └── Collège
        ├── 6ème
        │   ├── Français
        │   │   ├── Cours
        │   │   └── Devoirs
        │   ├── Maths
        │   │   ├── Cours
        │   │   └── Devoirs
        │   ├── Histoire-Geo
        │   └── Sciences
        └── Projets
    ```

### La recherche de fichiers

!!! tip "Retrouver un fichier perdu"
    1. **Barre de recherche** de l'explorateur
    2. **Windows + S** pour recherche globale
    3. Taper le nom (même partiel) ou l'extension

    Astuces :
    - `*.jpg` → trouve toutes les images JPEG
    - `devoir*` → trouve tout ce qui commence par "devoir"

---

## Entraînement

### Série 1 : Fichiers

1. Qu'est-ce qu'une extension de fichier ?
2. Quelle extension pour un document Word ?
3. Quelle extension pour une photo ?

??? success "Corrections"
    1. Le suffixe après le point qui indique le type de fichier
    2. **.docx**
    3. **.jpg** ou .png, .gif, etc.

### Série 2 : Dossiers

1. Qu'est-ce qu'un dossier ?
2. Qu'est-ce que l'arborescence ?
3. Cite 3 dossiers par défaut dans Windows.

??? success "Corrections"
    1. Un conteneur pour organiser les fichiers
    2. L'organisation des dossiers en structure d'arbre (hiérarchie)
    3. Documents, Images, Musique, Vidéos, Téléchargements, Bureau (3 au choix)

### Série 3 : Manipulations

1. Comment créer un nouveau dossier ?
2. Quel raccourci pour renommer un fichier ?
3. Où vont les fichiers supprimés ?

??? success "Corrections"
    1. Clic droit → Nouveau → Dossier
    2. **F2**
    3. Dans la **Corbeille**

---

## Évaluation du module (sur 20)

**Q1.** Qu'est-ce qu'un fichier ? (2 pts)

**Q2.** À quoi sert l'extension d'un fichier ? (2 pts)

**Q3.** Associe ces extensions à leur type : .mp3, .docx, .jpg, .mp4 (4 pts)

**Q4.** Qu'est-ce qu'un dossier ? (2 pts)

**Q5.** Dans ce chemin `C:\Users\Leo\Documents\Collège\devoir.pdf`, quel est le nom du fichier et dans quel dossier est-il ? (2 pts)

**Q6.** Comment ouvrir l'explorateur de fichiers avec un raccourci ? (1 pt)

**Q7.** Cite 3 règles de bonne pratique pour nommer ses fichiers. (3 pts)

**Q8.** Où vont les fichiers supprimés et comment les récupérer ? (2 pts)

**Q9.** Comment rechercher un fichier dont on a oublié l'emplacement ? (2 pts)

??? success "Corrections"
    Q1. Un ensemble de données enregistrées sur un support de stockage
    Q2. Elle indique le type de fichier et le programme à utiliser pour l'ouvrir
    Q3. .mp3 = audio, .docx = document Word, .jpg = image, .mp4 = vidéo
    Q4. Un conteneur qui permet d'organiser les fichiers
    Q5. Le fichier est "devoir.pdf", il est dans le dossier "Collège"
    Q6. Windows + E
    Q7. Noms descriptifs, utiliser des tirets, inclure la date si utile, éviter les caractères spéciaux (3 au choix)
    Q8. Dans la Corbeille. Pour récupérer : ouvrir la Corbeille et clic droit → Restaurer
    Q9. Utiliser la barre de recherche de l'explorateur ou Windows + S

---

## Prochaine étape

!!! success "Bravo !"
    Tu sais maintenant organiser tes fichiers et dossiers !
    Dans le prochain module, on va découvrir **Internet et les réseaux**.

[Module 7 - Internet et les réseaux](module-07-internet.md){ .md-button .md-button--primary }

[Retour à l'index](index.md){ .md-button }
