# Nombres & Calculs

## Les nombres entiers

### Écriture et lecture des grands nombres

Pour lire un grand nombre, on le découpe en **tranches de 3 chiffres** (classes) de droite à gauche :

| Classe des milliards | Classe des millions | Classe des milliers | Classe des unités |
|:---:|:---:|:---:|:---:|
| C D U | C D U | C D U | C D U |

!!! example "Exemple"
    **2 450 183** se lit : deux millions quatre cent cinquante mille cent quatre-vingt-trois

!!! tip "Astuce"
    Les espaces entre les tranches facilitent la lecture !

---

## Les nombres décimaux

### Structure d'un nombre décimal

Un nombre décimal a deux parties séparées par une **virgule** :

```
    345,72
    ───┬───
       │
  Partie    Partie
  entière   décimale
```

| Position | Nom | Exemple (345,72) |
|----------|-----|:---:|
| Centaines | 3 | 3 × 100 |
| Dizaines | 4 | 4 × 10 |
| Unités | 5 | 5 × 1 |
| Dixièmes | 7 | 7 × 0,1 |
| Centièmes | 2 | 2 × 0,01 |

### Comparer des nombres décimaux

!!! note "Méthode"
    1. Comparer d'abord les **parties entières**
    2. Si égales, comparer les **dixièmes**
    3. Si égaux, comparer les **centièmes**, etc.

!!! example "Exemple"
    **3,45** et **3,7** → parties entières égales (3)
    Dixièmes : 4 < 7, donc **3,45 < 3,7**

!!! warning "Attention"
    3,7 = 3,70 = 3,700 (on peut ajouter des zéros à droite)
    Mais 3,7 ≠ 3,07 !

---

## Les fractions

### Vocabulaire

```
    3     ← Numérateur (ce qu'on prend)
   ───
    4     ← Dénominateur (en combien de parts)
```

!!! info "À retenir"
    $\dfrac{3}{4}$ signifie : on divise en **4 parts égales** et on en prend **3**

### Fractions usuelles

| Fraction | Décimal | Pourcentage |
|:---:|:---:|:---:|
| $\dfrac{1}{2}$ | 0,5 | 50% |
| $\dfrac{1}{4}$ | 0,25 | 25% |
| $\dfrac{3}{4}$ | 0,75 | 75% |
| $\dfrac{1}{10}$ | 0,1 | 10% |
| $\dfrac{1}{5}$ | 0,2 | 20% |

### Fractions égales

!!! note "Règle d'or"
    On peut **multiplier** ou **diviser** le numérateur et le dénominateur par le même nombre (≠ 0)

    $$\dfrac{2}{3} = \dfrac{2 \times 4}{3 \times 4} = \dfrac{8}{12}$$

---

## Les quatre opérations

### L'addition

!!! note "Méthode"
    1. Aligner les virgules
    2. Additionner de droite à gauche
    3. Reporter les retenues

```
    23,45
  + 12,30
  ───────
    35,75
```

### La soustraction

!!! note "Méthode"
    1. Aligner les virgules
    2. Soustraire de droite à gauche
    3. Emprunter si nécessaire

```
    45,80
  - 23,25
  ───────
    22,55
```

### La multiplication

#### Par 10, 100, 1000

!!! tip "Astuce magique"
    - × 10 → virgule **1 rang à droite**
    - × 100 → virgule **2 rangs à droite**
    - × 1000 → virgule **3 rangs à droite**

| Calcul | Résultat |
|:---:|:---:|
| 3,45 × 10 | 34,5 |
| 3,45 × 100 | 345 |
| 3,45 × 1000 | 3 450 |

#### Multiplication posée

!!! note "Méthode"
    1. Multiplier sans s'occuper des virgules
    2. Compter le nombre total de chiffres après les virgules
    3. Placer la virgule dans le résultat

!!! example "Exemple"
    2,3 × 1,5 = ?
    23 × 15 = 345
    1 chiffre + 1 chiffre = 2 chiffres après la virgule
    **Résultat : 3,45**

### La division

#### Par 10, 100, 1000

!!! tip "Astuce magique"
    - ÷ 10 → virgule **1 rang à gauche**
    - ÷ 100 → virgule **2 rangs à gauche**
    - ÷ 1000 → virgule **3 rangs à gauche**

| Calcul | Résultat |
|:---:|:---:|
| 345 ÷ 10 | 34,5 |
| 345 ÷ 100 | 3,45 |
| 345 ÷ 1000 | 0,345 |

#### Division euclidienne

!!! info "Vocabulaire"
    **Dividende = Diviseur × Quotient + Reste**

    45 = 7 × 6 + 3
    (45 divisé par 7 donne 6 et il reste 3)

---

## Multiples et diviseurs

### Multiples

!!! info "Définition"
    Les **multiples** d'un nombre sont les résultats de ses tables de multiplication

!!! example "Multiples de 7"
    7, 14, 21, 28, 35, 42, 49, 56, 63, 70...

### Diviseurs

!!! info "Définition"
    Les **diviseurs** d'un nombre sont les nombres qui le divisent exactement (reste = 0)

!!! example "Diviseurs de 12"
    1, 2, 3, 4, 6, 12

### Critères de divisibilité

| Divisible par | Critère | Exemple |
|:---:|---|:---:|
| **2** | Chiffre des unités : 0, 2, 4, 6, 8 | 246 ✓ |
| **3** | Somme des chiffres divisible par 3 | 123 → 1+2+3=6 ✓ |
| **5** | Chiffre des unités : 0 ou 5 | 135 ✓ |
| **9** | Somme des chiffres divisible par 9 | 234 → 2+3+4=9 ✓ |
| **10** | Chiffre des unités : 0 | 250 ✓ |

---

## Priorités opératoires

!!! warning "Ordre de calcul"
    1. **Parenthèses** en premier
    2. **Multiplications** et **divisions** (de gauche à droite)
    3. **Additions** et **soustractions** (de gauche à droite)

!!! example "Exemple"
    $3 + 4 \times 2 = 3 + 8 = 11$ (pas 14 !)

    $(3 + 4) \times 2 = 7 \times 2 = 14$

---

## Quiz express

??? question "3,5 ou 3,45 : lequel est le plus grand ?"
    **3,5** est le plus grand !
    3,5 = 3,50 et 50 centièmes > 45 centièmes

??? question "Combien vaut $\dfrac{3}{4}$ en décimal ?"
    $\dfrac{3}{4} = 3 ÷ 4 = 0,75$

??? question "45,6 × 100 = ?"
    4 560 (virgule 2 rangs à droite)

??? question "Quel est le reste de 47 ÷ 6 ?"
    47 = 6 × 7 + **5**
    Le reste est **5**
