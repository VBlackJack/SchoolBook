# Module 7 - Internet et les réseaux

!!! info "Objectifs du module"
    À la fin de ce module, tu sauras :

    - Comprendre ce qu'est Internet et comment il fonctionne
    - Connaître la différence entre Internet et le Web
    - Comprendre les adresses IP et les noms de domaine
    - Utiliser Internet de manière responsable

    **Durée estimée : 1-2 heures** | **Pré-requis : Module 6**

---

## Leçon 1 : Qu'est-ce qu'un réseau ?

### Définition

!!! tip "Un réseau informatique"
    Un **réseau** est un ensemble d'ordinateurs et d'appareils **connectés** entre eux pour **échanger des données**.

    Exemples :
    - Les ordinateurs de ton collège connectés entre eux
    - Ta box Internet qui connecte tes appareils à la maison
    - Ton smartphone connecté en Wi-Fi

### Types de réseaux

!!! info "Classification par taille"
    | Type | Signification | Exemple |
    |------|---------------|---------|
    | **PAN** | Personal Area Network | Bluetooth (téléphone ↔ écouteurs) |
    | **LAN** | Local Area Network | Réseau de la maison ou du collège |
    | **WAN** | Wide Area Network | Réseau d'une entreprise multi-sites |
    | **Internet** | Réseau mondial | Le plus grand réseau du monde ! |

### Le réseau local (LAN)

!!! example "Chez toi"
    ```mermaid
    graph TD
        BOX[Box Internet] --> PC[Ordinateur]
        BOX --> TEL[Smartphone]
        BOX --> TAB[Tablette]
        BOX --> TV[Smart TV]
        BOX --> IMP[Imprimante]
        BOX <--> INET[Internet]
    ```

    Ta **box** est le centre du réseau. Elle connecte tous tes appareils entre eux ET à Internet.

---

## Exercices guidés - Leçon 1

### Exercice 1.1 : Identifier le type de réseau

!!! question "Quel type de réseau ?"
    a) Les ordinateurs d'une salle informatique
    b) Ton téléphone connecté à tes écouteurs Bluetooth
    c) Tous les ordinateurs du monde connectés ensemble

??? success "Correction"
    a) **LAN** (réseau local)
    b) **PAN** (réseau personnel)
    c) **Internet** (réseau mondial)

---

## Leçon 2 : Internet, c'est quoi ?

### Définition

!!! tip "Internet"
    **Internet** est un réseau mondial qui connecte des **milliards** d'appareils entre eux.

    "Inter" + "Net" = réseau **inter**connecté

    Ce n'est pas une entreprise ni un lieu physique, c'est une **infrastructure mondiale**.

### Histoire d'Internet

!!! info "Les dates clés"
    | Année | Événement |
    |-------|-----------|
    | 1969 | **ARPANET** : ancêtre d'Internet (4 ordinateurs) |
    | 1983 | Adoption du protocole **TCP/IP** |
    | 1989 | Invention du **World Wide Web** (Tim Berners-Lee) |
    | 1991 | Internet devient public |
    | 2000s | Explosion d'Internet grand public |
    | 2020s | Plus de 5 milliards d'utilisateurs |

### Internet ≠ Web

!!! warning "Ne pas confondre !"
    | Internet | World Wide Web (WWW) |
    |----------|---------------------|
    | L'**infrastructure** (les câbles, serveurs) | Un **service** qui utilise Internet |
    | Comme les routes | Comme les voitures sur les routes |
    | Existe depuis 1969 | Existe depuis 1989 |

    **Internet** = le réseau physique
    **Web** = les sites web qu'on consulte via Internet

!!! example "Analogie : La route et les voitures 🛣️"
    ```mermaid
    graph LR
        subgraph INTERNET["🛣️ INTERNET = Les routes"]
            A["🏠 Maison"] ---|Câbles & serveurs| B["🏢 Entreprise"]
        end
        subgraph WEB["🚗 WEB = Les voitures"]
            C["Sites web qui circulent sur ces câbles"]
        end
        INTERNET --> WEB
    ```

    - Internet existe sans le Web (emails, jeux...)
    - Le Web a BESOIN d'Internet pour fonctionner

### Les services d'Internet

!!! info "Ce qu'on peut faire sur Internet"
    | Service | Description | Exemples |
    |---------|-------------|----------|
    | **Web (WWW)** | Consulter des sites | Google, Wikipedia |
    | **Email** | Envoyer des messages | Gmail, Outlook |
    | **Streaming** | Regarder des vidéos/musique | YouTube, Netflix, Spotify |
    | **Messagerie** | Discuter en direct | WhatsApp, Discord |
    | **Jeux en ligne** | Jouer avec d'autres | Minecraft, Forza, Hogwarts |
    | **Cloud** | Stocker des fichiers | Google Drive, Dropbox |

!!! example "🎮 Que se passe-t-il quand tu joues à Minecraft en ligne ?"
    Quand tu rejoins un serveur Minecraft avec tes amis :

    1. **Ton PC/console** → envoie ta position, tes actions sur Internet
    2. **Le serveur Minecraft** (un gros ordinateur) reçoit les infos de tous les joueurs
    3. **Le serveur calcule** : "Ce joueur a cassé un bloc, ce joueur a crafté une épée..."
    4. **Le serveur renvoie** les mises à jour à tout le monde
    5. **Ton écran affiche** : ton ami a construit une maison pendant que tu minais !

    **Tout ça en moins de 0,05 seconde !** (C'est le "ping" dont parlent les gamers)

    ```
    TOI 🎮 ──────────────────► SERVEUR MINECRAFT 🖥️ ◄─────────────── AMI 🎮
         "Je casse un bloc !"   "OK, bloc cassé !"    "Je construis !"
              ◄──────────────── "Monde mis à jour !" ────────────────►
    ```

    **C'est pour ça que :**
    - Quand Internet rame → tu "lagues" dans le jeu
    - Plus le serveur est loin → plus le ping est élevé → plus de retard
    - Les pros veulent un ping < 20ms (millisecondes)

---

## Leçon 3 : Comment fonctionne Internet ?

### Les éléments du réseau

!!! info "L'infrastructure"
    ```mermaid
    graph LR
        A[Ton ordinateur] --> B[Ta box]
        B --> C[Fournisseur d'accès<br>FAI]
        C --> D[Dorsale Internet<br>Câbles sous-marins]
        D --> E[Serveur du site web]
    ```

### Le fournisseur d'accès (FAI)

!!! tip "C'est quoi un FAI ?"
    Le **Fournisseur d'Accès à Internet** (FAI) est l'entreprise qui te connecte à Internet.

    Exemples en France : **Orange, Free, SFR, Bouygues**

    C'est lui qui t'apporte la "route" vers Internet.

### L'adresse IP

!!! info "L'identité sur le réseau"
    Chaque appareil connecté a une **adresse IP** (Internet Protocol).
    C'est comme une adresse postale, mais pour les ordinateurs.

    Exemples :
    - **IPv4** : 192.168.1.1 (4 nombres de 0 à 255)
    - **IPv6** : 2001:0db8:85a3:0000:0000:8a2e:0370:7334 (plus long, plus d'adresses)

!!! tip "IP publique vs IP privée"
    - **IP publique** : ton adresse sur Internet (donnée par le FAI)
    - **IP privée** : ton adresse sur le réseau local (ex: 192.168.1.x)

### Les noms de domaine

!!! warning "Plus facile que l'IP !"
    Retenir "142.250.185.78" c'est difficile...
    Mais retenir "**google.com**" c'est facile !

    Le **nom de domaine** est l'adresse "humaine" d'un site.
    Le **DNS** (Domain Name System) traduit le nom en adresse IP.

!!! example "Comment ça marche : Le DNS, l'annuaire d'Internet 📖"
    1. Tu tapes **google.com** dans ton navigateur
    2. Le DNS cherche l'IP correspondante : **142.250.185.78**
    3. Ton navigateur se connecte à cette IP
    4. Google s'affiche !

    ```
    TOI                     DNS                      SERVEUR
    👤                      📖                       🖥️

    "Je veux google.com"
         ──────────────▶
                        "google.com = 142.250.185.78"
         ◀──────────────

    "Connexion à 142.250.185.78"
         ─────────────────────────────────────────▶
                                        "Voici la page !"
         ◀─────────────────────────────────────────

    C'est comme demander à un annuaire le numéro de téléphone
    de quelqu'un en donnant juste son nom !
    ```

### Structure d'un nom de domaine

!!! info "Anatomie"
    ```
    https://www.exemple.fr/page.html
    └─┬──┘ └┬┘ └──┬───┘└┬┘└───┬────┘
      │     │     │     │     │
      │     │     │     │     └── Chemin de la page
      │     │     │     └── Extension (TLD)
      │     │     └── Nom de domaine
      │     └── Sous-domaine
      └── Protocole (sécurisé)
    ```

### Les extensions (TLD)

!!! tip "Top Level Domain"
    | Extension | Signification |
    |:---------:|---------------|
    | **.com** | Commercial (international) |
    | **.fr** | France |
    | **.org** | Organisation |
    | **.edu** | Éducation |
    | **.gouv.fr** | Gouvernement français |
    | **.net** | Réseau |

---

## Exercices guidés - Leçon 3

### Exercice 3.1 : Vrai ou Faux

!!! question "Réponds"
    a) Une adresse IP est comme une adresse postale pour les ordinateurs.
    b) Le DNS traduit les adresses IP en noms de domaine.
    c) Un FAI fournit l'accès à Internet.
    d) Le Web et Internet sont la même chose.

??? success "Correction"
    a) **Vrai**
    b) **Vrai** (et inversement : noms en IP)
    c) **Vrai**
    d) **Faux** - Internet est l'infrastructure, le Web est un service sur Internet

---

## Leçon 4 : Les connexions

### Les types de connexion

!!! info "Se connecter à Internet"
    | Type | Technologie | Vitesse | Mobilité |
    |------|-------------|:-------:|:--------:|
    | **ADSL** | Ligne téléphonique | ⚡ | Non |
    | **Fibre optique** | Câble de verre | ⚡⚡⚡⚡⚡ | Non |
    | **Wi-Fi** | Ondes radio | ⚡⚡⚡ | Oui (maison) |
    | **4G/5G** | Réseau mobile | ⚡⚡⚡(⚡) | Oui (partout) |
    | **Ethernet** | Câble réseau | ⚡⚡⚡⚡ | Non |

### Wi-Fi vs Ethernet

!!! tip "Comparaison"
    | Critère | Wi-Fi | Ethernet (câble) |
    |---------|:-----:|:----------------:|
    | **Mobilité** | ✅ | ❌ |
    | **Vitesse** | Variable | Stable et rapide |
    | **Latence** | Plus haute | Plus basse |
    | **Sécurité** | Moins sécurisé | Plus sécurisé |
    | **Installation** | Simple | Câbles à tirer |

!!! example "🎮 Pourquoi les streamers et pros utilisent un câble Ethernet ?"
    Si tu regardes les streamers sur Twitch ou les joueurs pro en compétition, ils utilisent toujours un **câble Ethernet** branché à leur PC. Pourquoi ?

    **Test réel de ping (temps de réponse) :**

    | Connexion | Ping moyen | Stabilité |
    |-----------|------------|-----------|
    | **Wi-Fi** | 30-80 ms | Variable (parfois 200ms !) |
    | **Ethernet** | 5-15 ms | Toujours stable |

    **En pratique dans Forza Horizon 5 (courses en ligne) :**

    - **Wi-Fi instable** : Tu freines au bon moment... mais côté serveur tu as déjà percuté un mur → tu perds !
    - **Ethernet stable** : Ce que tu vois = ce qui se passe vraiment → tu gagnes !

    **Conseil :** Si tu joues en compétition ou que tu veux le meilleur ping, branche un câble Ethernet à ton PC/console. C'est beaucoup plus stable que le Wi-Fi !

### Le Wi-Fi

!!! info "Comment ça marche"
    - La **box** émet des ondes radio
    - Tes appareils captent ces ondes
    - Protection par **mot de passe** (WPA2/WPA3)

!!! warning "Portée limitée"
    Le Wi-Fi a une portée de **20-50 mètres** environ.
    Les murs et obstacles réduisent le signal.

### La 4G et 5G

!!! info "Internet mobile"
    - Utilise les **antennes relais** (comme pour téléphoner)
    - Fonctionne **partout** où il y a du réseau
    - **5G** = plus rapide que la 4G
    - Consomme les **données mobiles** (forfait limité)

---

## Leçon 5 : Le navigateur web

### Qu'est-ce qu'un navigateur ?

!!! tip "Définition"
    Un **navigateur web** est un logiciel qui permet de consulter des sites web.

    Exemples : **Chrome, Firefox, Edge, Safari, Opera**

### Anatomie du navigateur

!!! info "Éléments de l'interface"
    | Élément | Fonction |
    |---------|----------|
    | **Barre d'adresse** | Taper l'URL du site |
    | **Boutons ← →** | Revenir / Avancer |
    | **Bouton 🔄** | Actualiser la page |
    | **Onglets** | Ouvrir plusieurs pages |
    | **Favoris** | Sauvegarder des sites |
    | **Menu** | Paramètres, historique... |

### Le protocole HTTPS

!!! warning "Sécurité importante !"
    - **HTTP** = Non sécurisé ⚠️
    - **HTTPS** = Sécurisé (cadenas 🔒)

    Vérifie toujours le **cadenas** avant d'entrer des informations personnelles !

### Moteur de recherche vs Navigateur

!!! danger "Ne pas confondre !"
    | Navigateur | Moteur de recherche |
    |------------|---------------------|
    | Le **logiciel** pour afficher les sites | Le **site** pour chercher des informations |
    | Chrome, Firefox, Edge | Google, Bing, DuckDuckGo |

---

## Entraînement

### Série 1 : Définitions

1. Qu'est-ce qu'Internet ?
2. Quelle est la différence entre Internet et le Web ?
3. Qu'est-ce qu'un FAI ?

??? success "Corrections"
    1. Un réseau mondial connectant des milliards d'appareils
    2. Internet = l'infrastructure (câbles, serveurs) / Web = un service sur Internet (les sites)
    3. Fournisseur d'Accès à Internet (Orange, Free, etc.)

### Série 2 : Technique

1. À quoi sert une adresse IP ?
2. À quoi sert le DNS ?
3. Que signifie le cadenas 🔒 dans la barre d'adresse ?

??? success "Corrections"
    1. Identifier un appareil sur le réseau (comme une adresse postale)
    2. Traduire les noms de domaine en adresses IP
    3. La connexion est sécurisée (HTTPS)

### Série 3 : Connexions

1. Quelle connexion est la plus rapide : ADSL ou Fibre ?
2. Avantage du Wi-Fi par rapport à l'Ethernet ?
3. Quelle est la différence entre 4G et Wi-Fi ?

??? success "Corrections"
    1. La **Fibre optique**
    2. La **mobilité** (pas de câble)
    3. 4G = réseau mobile (antennes, partout) / Wi-Fi = réseau local (box, à la maison)

---

## Évaluation du module (sur 20)

**Q1.** Qu'est-ce qu'un réseau informatique ? (2 pts)

**Q2.** Qu'est-ce qu'Internet ? (2 pts)

**Q3.** Quelle est la différence entre Internet et le Web ? (2 pts)

**Q4.** À quoi sert une adresse IP ? (2 pts)

**Q5.** Qu'est-ce que le DNS ? (2 pts)

**Q6.** Cite 2 façons de se connecter à Internet. (2 pts)

**Q7.** Qu'est-ce qu'un navigateur web ? Cite 2 exemples. (2 pts)

**Q8.** Que signifie HTTPS et pourquoi est-ce important ? (2 pts)

**Q9.** Quelle est la différence entre un navigateur et un moteur de recherche ? (2 pts)

**Q10.** Dans l'URL `https://www.college-dupont.fr/accueil.html`, identifie le nom de domaine et l'extension. (2 pts)

??? success "Corrections"
    Q1. Un ensemble d'ordinateurs connectés pour échanger des données
    Q2. Un réseau mondial connectant des milliards d'appareils
    Q3. Internet = infrastructure physique / Web = service de sites web sur Internet
    Q4. Identifier de manière unique un appareil sur le réseau
    Q5. Système qui traduit les noms de domaine en adresses IP
    Q6. Wi-Fi, Ethernet, Fibre, ADSL, 4G/5G (2 au choix)
    Q7. Logiciel pour consulter des sites web. Exemples : Chrome, Firefox, Edge, Safari (2 au choix)
    Q8. HTTP Secure, connexion chiffrée et sécurisée. Important pour protéger les données personnelles
    Q9. Navigateur = logiciel (Chrome) / Moteur de recherche = site web pour chercher (Google)
    Q10. Nom de domaine : college-dupont / Extension (TLD) : .fr

---

## Prochaine étape

!!! success "Bravo !"
    Tu comprends maintenant comment fonctionne Internet !
    Dans le prochain module, on va parler de **sécurité informatique**.

[Module 8 - La sécurité informatique](module-08-securite.md){ .md-button .md-button--primary }

[Retour à l'index](index.md){ .md-button }
