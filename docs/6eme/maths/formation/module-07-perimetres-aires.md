# Module 7 - Périmètres et aires

!!! info "Objectifs du module"
    À la fin de ce module, tu sauras :

    - Calculer le périmètre de n'importe quel polygone
    - Calculer l'aire du carré et du rectangle
    - Calculer l'aire du triangle
    - Calculer le périmètre et l'aire du disque
    - Distinguer périmètre et aire

    **Durée estimée : 3 heures** | **Pré-requis : Modules 2, 3, 6**

---

## 🎮 Dans la vraie vie : périmètres et aires !

!!! tip "Périmètre = le tour, Aire = l'intérieur"

    **Périmètre - Quand tu fais le tour :**
    - Courir autour du terrain de foot = calculer le **périmètre**
    - Mettre une clôture autour du jardin = le **périmètre** du jardin
    - La longueur de ta ceinture = le **périmètre** de ta taille
    - Faire le tour de ta chambre en marchant = son **périmètre**

    **Aire - Quand tu remplis l'intérieur :**
    - Peindre un mur = calculer l'**aire** pour savoir combien de peinture
    - Carreler une pièce = l'**aire** pour savoir combien de carreaux
    - Gazon pour le jardin = l'**aire** du terrain
    - La taille de ton écran de TV = son **aire** (55 pouces = la diagonale !)

    **Dans les jeux vidéo :**
    - Construire un mur dans Minecraft : compter les blocs = **aire** (ex: mur 5×3 = 15 blocs)
    - Surface d'une piste dans Forza : l'**aire** du circuit
    - Carte du Monde des Sorciers dans Hogwarts : mesurer les **distances** = périmètre

    **Mesures courantes à connaître :**
    - Chambre moyenne : **10 à 15 m²** (aire)
    - Terrain de foot : **7 140 m²** (105m × 68m)
    - Feuille A4 : **623,7 cm²** (21 × 29,7)
    - Écran de téléphone 6 pouces : environ **80 cm²**

!!! example "Situation concrète : décorer ta chambre"
    Ta chambre fait **4m × 3m** :

    - **Périmètre** = 4 + 3 + 4 + 3 = **14 m**
      → Tu veux mettre une guirlande lumineuse tout autour

    - **Aire** = 4 × 3 = **12 m²**
      → Tu veux acheter du parquet (vendu au m²)
      → Un paquet couvre 2 m², il te faut **6 paquets**

---

## Leçon 1 : Périmètre et aire - La différence

### Comprendre la différence

!!! info "Définitions"
    | Concept | Définition | Unité | Mesure quoi ? |
    |---------|------------|-------|---------------|
    | **Périmètre** | Longueur du contour | cm, m, km... | Le tour |
    | **Aire** | Surface à l'intérieur | cm², m², km²... | L'intérieur |

!!! example "Analogie de la piscine"
    ![Périmètre vs Aire : analogie de la piscine](../../../../assets/images/maths/perimetre-vs-aire.jpeg){ loading=lazy }

    Périmètre = le tour de la piscine (pour le ménage du bord)
    Aire = la surface de l'eau (combien de litres d'eau)

!!! tip "Astuce mémo"
    - **Périmètre** → **P**our marcher autour (le **P**arcours)
    - **Aire** → la surface de l'**A**ir dans la pièce

### Unités

!!! warning "Attention aux unités !"
    | Périmètre | Aire |
    |:---------:|:----:|
    | mm, cm, m, km | mm², cm², m², km² |
    | (longueur) | (longueur × longueur) |

??? warning "⚠️ Pièges à éviter : périmètre et aire"
    **Piège 1 : Confondre périmètre et aire**

    - **Périmètre** = le TOUR (une longueur, en cm, m...)
    - **Aire** = la SURFACE (en cm², m²...)

    Un rectangle 5 cm × 3 cm :
    - Périmètre = 2 × (5 + 3) = **16 cm** (pas cm² !)
    - Aire = 5 × 3 = **15 cm²** (pas cm !)

    ---

    **Piège 2 : Oublier le "÷2" dans l'aire du triangle**

    Aire du triangle = (base × hauteur) **÷ 2**

    - ❌ A = 6 × 4 = 24 cm² → FAUX !
    - ✅ A = (6 × 4) ÷ 2 = **12 cm²**

    ---

    **Piège 3 : Utiliser le diamètre au lieu du rayon**

    Pour le disque : A = π × **r²** (rayon au carré, pas diamètre !)

    Si on te donne le diamètre = 10 cm :
    - ❌ A = π × 10² = 314 cm² → FAUX !
    - ✅ Rayon = 10 ÷ 2 = 5 cm, puis A = π × 5² = **78,5 cm²**

    ---

    **Piège 4 : Mauvaise formule du périmètre du rectangle**

    - ❌ P = L × l → c'est l'AIRE !
    - ✅ P = 2 × (L + l) ou P = 2L + 2l

??? abstract "🔄 Autre façon de comprendre : périmètre vs aire"
    **Imagine une piscine :**

    - **Périmètre** = la longueur de la **barrière** autour de la piscine (tu marches le long du bord)
    - **Aire** = la quantité d'**eau** pour remplir la piscine (tu couvres la surface)

    ---

    **Autre image : un cadre photo**

    - **Périmètre** = la longueur du **cadre** (le tour)
    - **Aire** = la taille de la **photo** (ce qu'on voit à l'intérieur)

    ---

    **Pourquoi le ² pour l'aire ?**

    Parce qu'on multiplie deux longueurs ensemble :
    - 3 cm × 4 cm = 12 cm² (centimètres carrés)
    - cm × cm = cm²

    **C'est comme des petits carrés de 1 cm de côté qu'on compte !**

---

## Leçon 2 : Périmètre des polygones

### Formule générale

!!! info "Périmètre d'un polygone"
    **Périmètre = somme de tous les côtés**

### Périmètre du carré

!!! tip "Formule"
    $$P_{carré} = 4 \times côté = 4c$$

!!! example "Exemple : carré de côté 5 cm"
    ![Périmètre du carré](../../../../assets/images/maths/perimetre-carre.jpeg){ loading=lazy }

    P = 4 × 5 = **20 cm**

### Périmètre du rectangle

!!! tip "Formule"
    $$P_{rectangle} = 2 \times (Longueur + largeur) = 2(L + l)$$

!!! example "Exemple : rectangle 8 cm × 3 cm"
    ![Périmètre du rectangle](../../../../assets/images/maths/perimetre-rectangle.jpeg){ loading=lazy }

    P = 2 × (8 + 3) = 2 × 11 = **22 cm**

!!! tip "Astuce mémo"
    **"Deux L et deux l, c'est le tour du rectangle !"**

### Périmètre du triangle

!!! tip "Formule"
    $$P_{triangle} = côté_1 + côté_2 + côté_3$$

!!! example "Exemple : triangle 5 cm, 4 cm, 3 cm"
    P = 5 + 4 + 3 = **12 cm**

---

## Exercices guidés - Leçon 2

### Exercice 2.1 : Périmètre du carré

!!! question "Calcule le périmètre"
    a) Carré de côté 7 cm

    b) Carré de côté 2,5 m

??? success "Correction"
    a) P = 4 × 7 = **28 cm**

    b) P = 4 × 2,5 = **10 m**

### Exercice 2.2 : Périmètre du rectangle

!!! question "Calcule le périmètre"
    a) Rectangle 12 cm × 5 cm

    b) Rectangle 4,5 m × 3 m

??? success "Correction"
    a) P = 2 × (12 + 5) = 2 × 17 = **34 cm**

    b) P = 2 × (4,5 + 3) = 2 × 7,5 = **15 m**

### Exercice 2.3 : Problème inverse

!!! question "Un carré a un périmètre de 36 cm. Quelle est la mesure de son côté ?"

??? success "Correction"
    P = 4 × c, donc c = P ÷ 4

    c = 36 ÷ 4 = **9 cm**

---

## Leçon 3 : Aires des quadrilatères

### Aire du carré

!!! tip "Formule"
    $$A_{carré} = côté \times côté = c^2$$

!!! example "Exemple : carré de côté 4 cm"
    ![Aire du carré](../../../../assets/images/maths/aire-carre.jpeg){ loading=lazy }

    A = 4 × 4 = **16 cm²** (on compte 16 petits carrés de 1 cm²)

### Aire du rectangle

!!! tip "Formule"
    $$A_{rectangle} = Longueur \times largeur = L \times l$$

!!! example "Exemple : rectangle 6 cm × 3 cm"
    ![Aire du rectangle](../../../../assets/images/maths/aire-rectangle.jpeg){ loading=lazy }

    A = 6 × 3 = **18 cm²** (on compte 18 petits carrés de 1 cm²)

### Tableau récapitulatif

| Figure | Périmètre | Aire |
|:------:|:---------:|:----:|
| Carré | P = 4 × c | A = c × c = c² |
| Rectangle | P = 2 × (L + l) | A = L × l |

---

## Exercices guidés - Leçon 3

### Exercice 3.1 : Aire du carré

!!! question "Calcule l'aire"
    a) Carré de côté 9 cm

    b) Carré de côté 2,5 m

??? success "Correction"
    a) A = 9 × 9 = **81 cm²**

    b) A = 2,5 × 2,5 = **6,25 m²**

### Exercice 3.2 : Aire du rectangle

!!! question "Calcule l'aire"
    a) Rectangle 15 cm × 8 cm

    b) Rectangle 3,5 m × 2 m

??? success "Correction"
    a) A = 15 × 8 = **120 cm²**

    b) A = 3,5 × 2 = **7 m²**

### Exercice 3.3 : Problème inverse

!!! question "Un rectangle a une aire de 48 cm² et une longueur de 8 cm. Quelle est sa largeur ?"

??? success "Correction"
    A = L × l, donc l = A ÷ L

    l = 48 ÷ 8 = **6 cm**

---

## Leçon 4 : Aire du triangle

### La formule

!!! tip "Formule de l'aire du triangle"
    $$A_{triangle} = \frac{base \times hauteur}{2}$$

!!! info "Qu'est-ce que la hauteur ?"
    La **hauteur** est le segment **perpendiculaire** à la base,
    qui va du sommet opposé à la base.

    ![Hauteur du triangle](../../../../assets/images/maths/hauteur-triangle.jpeg){ loading=lazy }

!!! example "Visualisation"
    ![Triangle : base et hauteur](../../../../assets/images/maths/aire-triangle.jpeg){ loading=lazy }

    A = (base × hauteur) ÷ 2

### Pourquoi diviser par 2 ?

!!! example "Le triangle = la moitié du rectangle"
    ![Triangle = moitié du rectangle](../../../../assets/images/maths/aire-triangle-moitie-rectangle.jpeg){ loading=lazy }

    Le triangle prend exactement la moitié du rectangle → A = (b × h) ÷ 2

!!! example "Exemple : triangle base 8 cm, hauteur 5 cm"
    A = (8 × 5) ÷ 2 = 40 ÷ 2 = **20 cm²**

---

## Exercices guidés - Leçon 4

### Exercice 4.1 : Aire du triangle

!!! question "Calcule l'aire"
    a) Base = 10 cm, hauteur = 6 cm

    b) Base = 7 m, hauteur = 4 m

    c) Base = 5,4 cm, hauteur = 3 cm

??? success "Correction"
    a) A = (10 × 6) ÷ 2 = 60 ÷ 2 = **30 cm²**

    b) A = (7 × 4) ÷ 2 = 28 ÷ 2 = **14 m²**

    c) A = (5,4 × 3) ÷ 2 = 16,2 ÷ 2 = **8,1 cm²**

### Exercice 4.2 : Problème inverse

!!! question "Un triangle a une aire de 24 cm² et une base de 8 cm. Quelle est sa hauteur ?"

??? success "Correction"
    A = (b × h) ÷ 2, donc b × h = 2 × A, donc h = (2 × A) ÷ b

    h = (2 × 24) ÷ 8 = 48 ÷ 8 = **6 cm**

---

## Leçon 5 : Le cercle et le disque

### Vocabulaire

![Éléments du cercle](../../../../assets/images/maths/cercle-elements-sith.jpeg){ loading=lazy }

!!! info "Cercle vs Disque"
    - **Cercle** = le contour (la ligne)
    - **Disque** = l'intérieur (la surface)

    On calcule le **périmètre du cercle** et l'**aire du disque**.

### Le nombre π (pi)

!!! info "Le nombre π"
    π ≈ 3,14 (ou 3,14159...)

    C'est le rapport entre le périmètre d'un cercle et son diamètre.

!!! tip "Astuce mémo pour π"
    **"Que j'aime à faire apprendre un nombre utile aux sages"**

    Compte les lettres de chaque mot : 3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5 → π = 3,14159265...

### Périmètre du cercle (circonférence)

!!! tip "Formule"
    $$P = \pi \times diamètre = \pi \times d$$

    Ou : $P = 2 \times \pi \times rayon = 2\pi r$

!!! example "Exemple : cercle de rayon 5 cm"
    P = 2 × π × 5 = 2 × 3,14 × 5 = **31,4 cm**

### Aire du disque

![Aire du disque](../../../../assets/images/maths/aire-disque.jpeg){ loading=lazy }

!!! tip "Formule"
    $$A = \pi \times rayon^2 = \pi r^2$$

!!! example "Exemple : disque de rayon 5 cm"
    A = π × 5² = 3,14 × 25 = **78,5 cm²**

### Tableau récapitulatif

| | Périmètre | Aire |
|:-:|:---------:|:----:|
| Cercle/Disque | P = π × d = 2πr | A = π × r² |

---

## Exercices guidés - Leçon 5

### Exercice 5.1 : Périmètre du cercle

!!! question "Calcule le périmètre (π ≈ 3,14)"
    a) Cercle de rayon 7 cm

    b) Cercle de diamètre 10 m

??? success "Correction"
    a) P = 2 × 3,14 × 7 = **43,96 cm**

    b) P = 3,14 × 10 = **31,4 m**

### Exercice 5.2 : Aire du disque

!!! question "Calcule l'aire (π ≈ 3,14)"
    a) Disque de rayon 4 cm

    b) Disque de diamètre 6 m (attention : trouve d'abord le rayon !)

??? success "Correction"
    a) A = 3,14 × 4² = 3,14 × 16 = **50,24 cm²**

    b) Rayon = 6 ÷ 2 = 3 m
       A = 3,14 × 3² = 3,14 × 9 = **28,26 m²**

---

## Entraînement

### Série 1 : Périmètres

1. Périmètre d'un carré de côté 11 cm
2. Périmètre d'un rectangle 9 m × 4 m
3. Périmètre d'un triangle avec des côtés de 7 cm, 8 cm et 10 cm

??? success "Corrections"
    1. P = 4 × 11 = **44 cm**
    2. P = 2 × (9 + 4) = 2 × 13 = **26 m**
    3. P = 7 + 8 + 10 = **25 cm**

### Série 2 : Aires

1. Aire d'un carré de côté 12 cm
2. Aire d'un rectangle 7 m × 5 m
3. Aire d'un triangle de base 14 cm et hauteur 8 cm

??? success "Corrections"
    1. A = 12 × 12 = **144 cm²**
    2. A = 7 × 5 = **35 m²**
    3. A = (14 × 8) ÷ 2 = 112 ÷ 2 = **56 cm²**

### Série 3 : Cercle et disque

1. Périmètre d'un cercle de rayon 10 cm
2. Aire d'un disque de rayon 6 m
3. Périmètre d'un cercle de diamètre 20 cm

??? success "Corrections"
    1. P = 2 × 3,14 × 10 = **62,8 cm**
    2. A = 3,14 × 36 = **113,04 m²**
    3. P = 3,14 × 20 = **62,8 cm**

---

## Récapitulatif des formules

!!! warning "À mémoriser !"
    | Figure | Périmètre | Aire |
    |:------:|:---------:|:----:|
    | Carré | P = 4c | A = c² |
    | Rectangle | P = 2(L + l) | A = L × l |
    | Triangle | P = a + b + c | A = (b × h) ÷ 2 |
    | Cercle/Disque | P = 2πr = πd | A = πr² |

---

## Évaluation du module (sur 20)

**Q1.** Quelle est la différence entre périmètre et aire ? (2 pts)

**Q2.** Périmètre d'un carré de côté 8 cm (1 pt)

**Q3.** Aire d'un carré de côté 8 cm (1 pt)

**Q4.** Périmètre d'un rectangle 12 cm × 7 cm (1 pt)

**Q5.** Aire d'un rectangle 12 cm × 7 cm (1 pt)

**Q6.** Aire d'un triangle de base 10 cm et hauteur 6 cm (2 pts)

**Q7.** Un rectangle a une aire de 56 cm² et une longueur de 8 cm. Largeur ? (2 pts)

**Q8.** Périmètre d'un cercle de rayon 5 cm (2 pts)

**Q9.** Aire d'un disque de rayon 3 cm (2 pts)

**Q10-11.** Problème (6 pts) :
Un jardin rectangulaire mesure 15 m sur 10 m.
a) Quelle est son aire ?
b) On veut l'entourer d'une clôture. Quelle longueur de clôture faut-il ?
c) Au milieu, on installe une piscine circulaire de rayon 2 m. Quelle est l'aire de la piscine ?

??? success "Corrections"
    Q1. Périmètre = tour/contour (unité de longueur). Aire = surface intérieure (unité au carré).
    Q2. P = 4 × 8 = **32 cm**
    Q3. A = 8 × 8 = **64 cm²**
    Q4. P = 2 × (12 + 7) = **38 cm**
    Q5. A = 12 × 7 = **84 cm²**
    Q6. A = (10 × 6) ÷ 2 = **30 cm²**
    Q7. l = 56 ÷ 8 = **7 cm**
    Q8. P = 2 × 3,14 × 5 = **31,4 cm**
    Q9. A = 3,14 × 9 = **28,26 cm²**
    Q10-11.
    a) A_jardin = 15 × 10 = **150 m²**
    b) P_clôture = 2 × (15 + 10) = **50 m**
    c) A_piscine = 3,14 × 4 = **12,56 m²**

---

## Prochaine étape

[Module 8 - La symétrie axiale](module-08-symetrie.md){ .md-button .md-button--primary }

[Retour à l'index](index.md){ .md-button }
