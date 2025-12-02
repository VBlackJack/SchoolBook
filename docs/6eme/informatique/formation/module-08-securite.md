# Module 8 - La sécurité informatique

!!! info "Objectifs du module"
    À la fin de ce module, tu sauras :

    - Reconnaître les menaces informatiques (virus, phishing...)
    - Créer et gérer des mots de passe sécurisés
    - Protéger tes données personnelles
    - Naviguer sur Internet en sécurité

    **Durée estimée : 1-2 heures** | **Pré-requis : Module 7**

---

## Leçon 1 : Les menaces informatiques

### Les virus et malwares

!!! danger "Définition"
    Un **malware** (logiciel malveillant) est un programme conçu pour nuire.

    **Virus** = un type de malware qui se propage en infectant d'autres fichiers.

### Types de malwares

!!! warning "Les différentes menaces"
    | Type | Description | Conséquences |
    |------|-------------|--------------|
    | **Virus** | Se propage en infectant des fichiers | Fichiers corrompus, PC lent |
    | **Trojan (Cheval de Troie)** | Se cache dans un programme "normal" | Accès à distance au PC |
    | **Ransomware** | Bloque tes fichiers, demande une rançon | Perte de données |
    | **Spyware** | Espionne ce que tu fais | Vol d'informations |
    | **Adware** | Affiche des publicités non voulues | Gêne, ralentissement |

### Comment on attrape un malware ?

!!! tip "Les modes de contamination"
    1. **Télécharger** un fichier infecté
    2. **Cliquer** sur un lien malveillant
    3. **Ouvrir** une pièce jointe piégée
    4. **Brancher** une clé USB infectée
    5. **Installer** un logiciel piraté
    6. **Visiter** un site web dangereux

### Comment se protéger ?

!!! success "Les bonnes pratiques"
    - ✅ Installer un **antivirus** et le tenir à jour
    - ✅ **Mettre à jour** le système et les logiciels
    - ✅ Ne pas cliquer sur les **liens suspects**
    - ✅ Ne pas télécharger depuis des **sites douteux**
    - ✅ Scanner les **clés USB** inconnues
    - ✅ Faire des **sauvegardes** régulières

---

## Exercices guidés - Leçon 1

### Exercice 1.1 : Identifier les risques

!!! question "Ces actions sont-elles risquées ?"
    a) Télécharger un jeu gratuit sur un site inconnu
    b) Ouvrir une pièce jointe d'un email d'un ami
    c) Brancher une clé USB trouvée par terre
    d) Mettre à jour son antivirus

??? success "Correction"
    a) **Risqué** - Site inconnu = potentiel malware
    b) **Attention** - Vérifier que c'est vraiment l'ami (compte piraté ?)
    c) **Très risqué** - Technique classique d'attaque !
    d) **Pas risqué** - C'est même recommandé !

---

## Leçon 2 : Le phishing (hameçonnage)

### Qu'est-ce que le phishing ?

!!! danger "Définition"
    Le **phishing** est une technique pour voler tes informations en se faisant passer pour quelqu'un de confiance.

    Exemple : un faux email de ta banque qui te demande ton mot de passe.

!!! example "Le phishing, c'est comme la pêche ! 🎣"
    ```
    LE PIRATE (pêcheur)           TOI (le poisson)
    ═══════════════════           ════════════════

         👤 Pirate
          │
          │  "Email urgent de ta banque !"
          │  🎣─────────────────────────────┐
          │                                 │
          │      APPÂT = Faux email         │
          │      qui a l'air vrai           ▼
          │
          │                              🐟 Toi
          │                              "Oh non, ma banque !"
          │                              *clique sur le lien*
          │
          │◀────────────────────────────────┘
          │  Le pirate récupère
          │  ton mot de passe ! 😈

    NE MORDS PAS À L'HAMEÇON ! 🚫🎣
    ```

### Comment reconnaître le phishing ?

!!! warning "Les indices"
    | Indice | Exemple suspect |
    |--------|-----------------|
    | **Adresse email bizarre** | service@banque-secure-123.com |
    | **Fautes d'orthographe** | "Votre conpte a été suspendu" |
    | **Urgence artificielle** | "Action requise dans 24h !" |
    | **Demande d'informations** | "Confirmez votre mot de passe" |
    | **Liens douteux** | Survoler → l'URL ne correspond pas |
    | **Pièces jointes suspectes** | facture.exe, document.zip |

### Exemples de phishing

!!! example "Faux email de banque"
    ```
    De: service-client@ma-banque-securite.com
    Sujet: URGENT : Votre compte sera suspendu !

    Cher client,

    Nous avons detecté une activité suspecte sur votre compte.
    Cliquez ici pour confirmer vos informations :
    [Cliquez ici] ← lien vers un faux site

    Cordialement,
    Le Service Sécurité
    ```

    **Indices suspects** : adresse email bizarre, urgence, fautes, demande de clic

### Que faire face au phishing ?

!!! tip "Les bons réflexes"
    1. **Ne clique pas** sur les liens
    2. **Ne télécharge pas** les pièces jointes
    3. **Vérifie** l'adresse de l'expéditeur
    4. **Va directement** sur le site officiel (tape l'adresse toi-même)
    5. **Signale** l'email comme spam/phishing
    6. En cas de doute, **contacte** l'entreprise par téléphone

---

## Exercices guidés - Leçon 2

### Exercice 2.1 : Détecter le phishing

!!! question "Cet email est-il suspect ?"
    ```
    De: netflix-support@service-films.net
    Sujet: Votre abonnement Netflix expire demain !

    Bonjour,

    Votre abonement va expiré. Pour eviter la suspension,
    mettez à jour vos informations de paiement immédiatement.

    Cliquez ici : http://netflix-renouvellement.com/paiement

    L'équipe Netflix
    ```

??? success "Correction"
    **Oui, c'est du phishing !**

    Indices :
    - Adresse email : pas @netflix.com
    - Fautes : "abonement", "expiré", "eviter"
    - Urgence artificielle
    - Lien suspect (pas netflix.com)

---

## Leçon 3 : Les mots de passe

### L'importance des mots de passe

!!! danger "Première ligne de défense"
    Le mot de passe protège tes comptes contre les intrusions.
    Un mauvais mot de passe = porte ouverte aux pirates !

!!! example "Le mot de passe, c'est la clé de ta maison ! 🔑"
    ```
    MOT DE PASSE FAIBLE              MOT DE PASSE FORT
    ("123456")                       ("K9$mP2@xQ#nL4!")

    ┌───────────────┐                ┌───────────────┐
    │   🏠          │                │   🏠          │
    │   ┌─────┐     │                │   ┌─────┐     │
    │   │ 🚪  │     │                │   │ 🚪  │     │
    │   │     │     │                │   │ 🔒🔒 │     │
    │   └─────┘     │                │   │ 🔒🔒 │     │
    │    Pas de     │                │   └─────┘     │
    │    serrure !  │                │   Coffre-fort!│
    └───────────────┘                └───────────────┘
         😈 "Trop facile !"              😈 "Impossible !"
         Pirate : 2 secondes             Pirate : 1000 ans
    ```

### Les erreurs à éviter

!!! warning "Mots de passe à ne JAMAIS utiliser"
    - 123456
    - password
    - azerty / qwerty
    - Ton prénom ou date de naissance
    - Le nom de ton animal
    - Le même mot de passe partout

### Créer un mot de passe fort

!!! tip "Les règles d'or"
    Un bon mot de passe doit avoir :

    - ✅ **Au moins 12 caractères** (plus c'est long, mieux c'est)
    - ✅ Des **majuscules** ET des **minuscules**
    - ✅ Des **chiffres**
    - ✅ Des **caractères spéciaux** (!@#$%...)
    - ✅ **Pas de mots du dictionnaire**

!!! example "Exemples"
    | Mauvais ❌ | Bon ✅ |
    |-----------|-------|
    | thomas2012 | Th0m@s_2012!Ecole |
    | monchien | M0n_Ch!en_R3x#42 |
    | 123456789 | 1a2B3c$4D5e@6F! |

### La méthode de la phrase

!!! success "Technique facile"
    Prends une phrase que tu retiens facilement et transforme-la :

    **"J'adore manger des pizzas le samedi soir !"**

    Devient : **J@dm@ngDpLsS!**

    - Première lettre de chaque mot
    - Remplacer a par @, e par 3, etc.
    - Garder la ponctuation

!!! example "🎮 Crée un mot de passe style gamer !"
    **Méthode fun :** utilise une phrase liée à ton jeu préféré !

    **Exemple avec Minecraft :**
    > "Je construis ma base en diamant depuis 2022"

    1. Premières lettres : JcmbeDd2022
    2. Ajoute des symboles : Jcmb3Dd2022!
    3. Majuscules stratégiques : JcmB3Dd2022!@

    **Résultat : `JcmB3Dd2022!@`** (14 caractères, ultra-sécurisé !)

    **Autres exemples :**
    - "J'ai battu le dragon 5 fois" → `J@bLd5f!`
    - "Mon skin préféré coûte 800 vbucks" → `Msp€800vb!`

    **Temps pour un hacker :**
    - `minecraft` → 0,001 seconde 😱
    - `JcmB3Dd2022!@` → 3 millions d'années 😎

### Un mot de passe différent par compte

!!! danger "Règle essentielle"
    Si un site est piraté et que tu utilises le même mot de passe partout, **tous tes comptes sont compromis** !

    Solution : **un mot de passe unique** par site important.

### Les gestionnaires de mots de passe

!!! tip "Outil pratique"
    Un **gestionnaire de mots de passe** :

    - Génère des mots de passe complexes
    - Les stocke de manière sécurisée
    - Tu n'as qu'un seul mot de passe maître à retenir

    Exemples : **Bitwarden** (gratuit), **1Password**, **Dashlane**

---

## Exercices guidés - Leçon 3

### Exercice 3.1 : Évaluer les mots de passe

!!! question "Ces mots de passe sont-ils sécurisés ?"
    a) P@ssw0rd!
    b) emma2010
    c) K7$mP2@xQ9#nL4
    d) monmotdepasse123

??? success "Correction"
    a) **Moyen** - Caractères variés mais mot connu (password)
    b) **Faible** - Prénom + date, trop facile à deviner
    c) **Fort** - Long, aléatoire, varié
    d) **Faible** - Phrase simple, pas de caractères spéciaux

---

## Leçon 4 : Protéger ses données personnelles

### Qu'est-ce qu'une donnée personnelle ?

!!! info "Définition"
    Une **donnée personnelle** est une information qui permet de t'identifier.

    Exemples :
    - Nom, prénom
    - Adresse
    - Email, téléphone
    - Photos
    - Date de naissance
    - Localisation

### Les risques du partage

!!! danger "Ce qui peut arriver"
    - **Usurpation d'identité** : quelqu'un se fait passer pour toi
    - **Harcèlement** : avec ton adresse ou tes photos
    - **Cambriolage** : si tu affiches que tu es en vacances
    - **Arnaque** : avec tes informations bancaires

### Règles de protection

!!! tip "Les bonnes pratiques"
    - ✅ **Réfléchis** avant de publier une photo
    - ✅ Vérifie les **paramètres de confidentialité**
    - ✅ N'accepte que les **amis que tu connais** vraiment
    - ✅ Ne donne **jamais** ton mot de passe
    - ✅ Ne partage pas ton **adresse** en ligne
    - ✅ Attention aux **informations dans les photos** (badge, lieu...)

### Le droit à l'oubli

!!! info "Tes droits (RGPD)"
    En Europe, tu as le droit de :

    - **Accéder** à tes données
    - **Rectifier** des informations fausses
    - **Supprimer** tes données (droit à l'oubli)
    - **Refuser** l'utilisation de tes données

---

## Leçon 5 : Naviguer en sécurité

### Les bonnes pratiques de navigation

!!! tip "Checklist sécurité"
    - ✅ Vérifie le **HTTPS** (cadenas 🔒)
    - ✅ Ne télécharge que sur des **sites officiels**
    - ✅ Méfie-toi des **pop-ups** et publicités
    - ✅ Déconnecte-toi des **ordinateurs publics**
    - ✅ Utilise la **navigation privée** si nécessaire
    - ✅ Mets à jour ton **navigateur**

### Les Wi-Fi publics

!!! danger "Attention aux Wi-Fi gratuits !"
    Les Wi-Fi publics (café, gare, hôtel) sont **risqués** :

    - Tes données peuvent être **interceptées**
    - Faux réseaux Wi-Fi (piège)

    **Conseils** :
    - Évite les sites sensibles (banque, achats)
    - Utilise la 4G si possible
    - Utilise un VPN

### Les réseaux sociaux

!!! warning "Prudence sur les réseaux"
    | À faire ✅ | À éviter ❌ |
    |-----------|------------|
    | Profil privé | Profil public |
    | Amis connus | Accepter tout le monde |
    | Réfléchir avant de poster | Publier impulsivement |
    | Signaler le harcèlement | Répondre aux trolls |

### Que faire en cas de problème ?

!!! tip "En cas d'incident"
    1. **Changer** immédiatement le mot de passe compromis
    2. **Prévenir** un adulte (parents, professeur)
    3. **Signaler** sur la plateforme concernée
    4. **Garder** des preuves (captures d'écran)
    5. Si grave : **déposer plainte**

!!! example "🎮 Histoire vraie : le compte Minecraft piraté"
    **Ce qui est arrivé à Lucas (12 ans) :**

    1. Lucas utilise le mot de passe `lucas2011` sur tous ses comptes
    2. Un site de "Minecoins gratuits" lui demande son login Microsoft/Mojang
    3. Il entre ses identifiants (ERREUR !)
    4. Le lendemain : son compte Minecraft est volé !
    5. Le pirate a changé le mot de passe et l'email
    6. Tous ses mondes et son compte premium sont perdus...

    **Ce qu'il aurait dû faire :**

    - ❌ Ne JAMAIS entrer son mot de passe sur un site "Minecoins gratuits" (ça n'existe pas !)
    - ❌ Ne pas utiliser le même mot de passe partout
    - ✅ Activer l'authentification à 2 facteurs (2FA) sur Microsoft
    - ✅ Utiliser un mot de passe unique et complexe

    **La bonne nouvelle :** Microsoft a un support pour récupérer les comptes volés. Mais c'est long et compliqué !

!!! example "📱 Arnaque aux faux concours Instagram"
    Tu vois ce message sur Instagram :

    > "🎉 FÉLICITATIONS ! Vous avez gagné un iPhone 15 ! 🎉
    > Cliquez ici pour réclamer votre prix : bit.ly/iphone-gratuit-2024"

    **C'est une ARNAQUE à 100% !**

    **Comment ça marche :**
    1. Tu cliques sur le lien
    2. On te demande ton email, téléphone, adresse...
    3. On te demande "1€ pour les frais de livraison"
    4. Tu donnes ta carte bancaire...
    5. Tu ne reçois jamais l'iPhone, et on te prélève de l'argent !

    **Règle d'or :** Si c'est trop beau pour être vrai, c'est une arnaque !

---

## Entraînement

### Série 1 : Menaces

1. Qu'est-ce qu'un malware ?
2. Comment peut-on attraper un virus ?
3. Qu'est-ce que le phishing ?

??? success "Corrections"
    1. Un logiciel malveillant conçu pour nuire
    2. Téléchargement de fichiers infectés, clics sur liens malveillants, pièces jointes piégées, clés USB infectées
    3. Technique pour voler des informations en se faisant passer pour quelqu'un de confiance

### Série 2 : Mots de passe

1. Cite 3 caractéristiques d'un bon mot de passe.
2. Pourquoi ne faut-il pas utiliser le même mot de passe partout ?
3. Qu'est-ce qu'un gestionnaire de mots de passe ?

??? success "Corrections"
    1. Long (12+ caractères), majuscules/minuscules, chiffres, caractères spéciaux, pas de mots du dictionnaire
    2. Si un site est piraté, tous les comptes avec le même mot de passe sont compromis
    3. Un outil qui génère et stocke les mots de passe de manière sécurisée

### Série 3 : Protection

1. Qu'est-ce qu'une donnée personnelle ?
2. Cite 2 risques liés au partage de données en ligne.
3. Pourquoi les Wi-Fi publics sont-ils risqués ?

??? success "Corrections"
    1. Une information qui permet d'identifier une personne (nom, adresse, photo...)
    2. Usurpation d'identité, harcèlement, arnaque, cambriolage
    3. Les données peuvent être interceptées, il peut y avoir de faux réseaux

---

## Évaluation du module (sur 20)

**Q1.** Cite 3 types de malwares. (3 pts)

**Q2.** Comment reconnaître un email de phishing ? (3 pts)

**Q3.** Cite 4 règles pour créer un mot de passe sécurisé. (4 pts)

**Q4.** Pourquoi le mot de passe "emma2011" est-il mauvais ? (2 pts)

**Q5.** Qu'est-ce qu'une donnée personnelle ? Donne 3 exemples. (2 pts)

**Q6.** Que signifie le cadenas 🔒 dans la barre d'adresse ? (1 pt)

**Q7.** Que faire si on reçoit un email suspect ? (3 pts)

**Q8.** Pourquoi faut-il faire des mises à jour régulières ? (2 pts)

??? success "Corrections"
    Q1. Virus, trojan, ransomware, spyware, adware (3 au choix)
    Q2. Adresse email bizarre, fautes d'orthographe, urgence artificielle, demande d'informations sensibles, liens suspects
    Q3. 12+ caractères, majuscules ET minuscules, chiffres, caractères spéciaux, pas de mots du dictionnaire, unique par compte (4 au choix)
    Q4. Prénom + date de naissance = facile à deviner, pas assez long, pas de caractères spéciaux
    Q5. Information permettant d'identifier quelqu'un. Exemples : nom, adresse, email, photo, téléphone
    Q6. La connexion est sécurisée (HTTPS), les données sont chiffrées
    Q7. Ne pas cliquer sur les liens, ne pas télécharger les pièces jointes, vérifier l'expéditeur, signaler comme spam
    Q8. Pour corriger les failles de sécurité et se protéger contre les nouveaux virus

---

## Prochaine étape

!!! success "Bravo !"
    Tu sais maintenant te protéger sur Internet !
    Dans le prochain module, on va découvrir les **logiciels et applications**.

[Module 9 - Les logiciels et applications](module-09-logiciels.md){ .md-button .md-button--primary }

[Retour à l'index](index.md){ .md-button }
