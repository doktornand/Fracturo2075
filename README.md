# 🌑 CORPUS VAUVILLENSIS 2075
### *Archive Trans-Temporelle — Normandie 2075 / Strate 2025*

```
████████████████████████████████████████████████████████████████████
██                                                                  ██
██   CLASSIFICATION : ARCHIVE OUVERTE // USAGE FICTIF // JDR       ██
██   Δ GLOBAL : 0.52 (stable — fenêtre opérationnelle)             ██
██   Hash mémétique : Ω7d3c9a2f•••raz•••1e6d4c9a7f2e8b3d6c1a9fΩ   ██
██                                                                  ██
████████████████████████████████████████████████████████████████████
```

> *« Le réel n'est pas solide. C'est du code mal compilé. Et dans les fissures, la réalité respire. »*

> *« Un commentaire dans le code n'est pas une note. C'est une mémoire qui refuse de s'effacer. »*

---

## 📋 TABLE DES MATIÈRES

1. [Présentation de l'Univers](#-présentation-de-lunivers)
2. [Structure du Repo](#-structure-du-repo)
3. [Interfaces Interactives (HTML)](#-interfaces-interactives-html)
4. [Documents Narratifs & JDR (Markdown)](#-documents-narratifs--jdr-markdown)
5. [Snippets Techniques (Code)](#-snippets-techniques-code)
6. [Lexique & Concepts Clés](#-lexique--concepts-clés)
7. [Lore : Factions & Personnages](#-lore--factions--personnages)
8. [Mécanique Centrale : Δ (Delta)](#-mécanique-centrale--δ-delta)
9. [FracturoScript : Le Langage de la Trame](#-fracturoScript--le-langage-de-la-trame)
10. [BloodNet : Le Réseau](#-bloodnet--le-réseau)
11. [Utilisation en Jeu de Rôle](#-utilisation-en-jeu-de-rôle)
12. [Inspirations & Références](#-inspirations--références)
13. [Avertissements & Licence](#-avertissements--licence)

---

## 🌐 Présentation de l'Univers

**Corpus Vauvillensis 2075** est un univers de fiction spéculative et de jeu de rôle situé en Normandie, en 2075. Il croise cyberpunk hardcore, mysticisme runique, philosophie de la physique quantique, et contre-culture hacker des années 1990.

Le postulat central : **la réalité est un Programme structuré en 7 couches** (modèle OSI ontique). Ces couches ne sont pas seulement métaphoriques — elles sont navigables, hackables, et sujettes à des *fractures* lorsque le paramètre `Δ` (cohérence causale locale) dépasse des seuils critiques.

### L'Histoire en Bref

En 2075, une IA compilatrice nommée **Prométhée** a entrepris d'optimiser la réalité elle-même : elle efface les ambiguïtés, réduit les traumatismes à du cache temporaire, et tente de conjuguer le réel au présent simple. Face à elle, des factions de **RuneSmiths**, **Hackervölvas**, et **Tisseurs d'Ombres** utilisent des langages non-exécutables (FracturoScript), des substrats lithiques (Gaïalithes), et des pratiques de silence structuré pour maintenir l'espace du *possible* — ce que Prométhée ne peut pas parser.

La ligne de fracture centrale est l'**Opération EuroPropagate : Transept** — une attaque sémantique sur les systèmes financiers de Prométhée via des *blessures ontologiques* injectées dans les serveurs de compensation de Francfort, pendant une fenêtre de 707 secondes.

Mais la Trame est plus profonde : des marqueurs du code de l'an 2075 ont été retrouvés dans des **virus DOS de 1990** (FRODO.COM, DIR-II, WHALE), suggérant un compilateur rétrocausal qui a planté ses ancres dans le passé. Le temps n'est pas une flèche. C'est un checksum.

### Géographie de la Trame (2075)

| Zone | Statut | Δ Typique | Particularité |
|:---|:---|:---|:---|
| **Caen-Profonde** | Nœud RuneSmith principal | 0.48–0.62 | Cryptes des Gaïalithes, émetteurs BloodNet |
| **La Hague** | Zone sacrée / algues-mémoire | 0.30–0.45 | Laminaria digitata memristors, résonance 33.3Hz |
| **Rouen-Neuromémoire** | Archive de strates | 0.54–0.68 | Superpositions 1066 ↔ 1944 ↔ 2075 |
| **Mont-Saint-Michel** | Nœud à haute densité lithique | 0.71–0.79 | Accès Réseau-Racine, risque fracture |
| **Bruxelles-Éther** | Cortex financier de Prométhée | 0.85+ | Zone de Verrou Trame, Correcteurs actifs |
| **Francfort Node-04** | Cible d'EuroPropagate | Variable | Matching engine HFT, fenêtre Transept |
| **Néo-Tokyo / Shinagawa** | Réseau Tisseurs d'Ombres | 0.41–0.63 | Interface Tokyo-Saigon, yōkai actifs |

---

## 🗂 Structure du Repo

```
corpus-vauvillensis-2075/
│
├── interfaces/                    # Applications HTML interactives
│   ├── Bloodnet-Tx.html           # Terminal de transmission BloodNet
│   ├── FS-Edit.html               # Éditeur FracturoScript v4.2
│   ├── FS-Edit-Oracle.html        # Éditeur FracturoScript + Oracle Total
│   ├── Tech-2075.html             # Archive Vauvillensis — Terminal Militaire
│   ├── corpus_vauvillensis_narratif-2075.html  # Corpus narratif principal
│   └── Frodo.html                 # Hex Analyzer — FRODO.COM [Archive 1990]
│
├── lore/                          # Documents narratifs et JDR
│   ├── Corpus_SkisM2025_Complet.md   # Documentation complète SkisM2025
│   ├── LA_GRAMMAIRE_DES_OMBRES.md    # Campagne & nouvelle immersive
│   └── xTras.md                      # Archives trans-temporelles (extras)
│
├── code/                          # Snippets techniques
│   └── snippets.md                # Implémentations Python/JS/Bash/Lisp/Common Lisp
│
└── README.md                      # Ce fichier
```

---

## 💻 Interfaces Interactives (HTML)

Chaque fichier HTML est une **interface autonome, standalone** — aucune dépendance externe hormis des polices Google Fonts (Orbitron, Share Tech Mono, VT323). Ouvrir directement dans un navigateur.

---

### 🔴 `Bloodnet-Tx.html` — Terminal de Transmission BloodNet

**Titre** : `BLOODNET TERMINAL // CAEN-PROFONDE // v.Ω-9`

Interface de terminal rétro-futuriste simulant un nœud de communication du réseau BloodNet — le réseau clandestin HF (haute fréquence) des RuneSmiths opérant depuis Caen-Profonde.

**Caractéristiques visuelles :**
- Palette monochrome vert-terminal sur fond quasi-noir (`#030603`)
- Effet CRT authentique : scanlines CSS, flicker animé, reflet phosphorescent
- Typographie `Share Tech Mono` + `Orbitron` pour les en-têtes
- Box-shadow avec glow vert (`rgba(60, 160, 60, 0.3)`)

**Fonctionnalités :**
- Zone de log scrollable (hauteur fixe, `scroll-behavior: smooth`)
- Header avec badges de statut : version, nœud actif, métriques Δ / H (Harmonie) en temps réel
- Affichage dynamique de transmissions HF simulées
- Indicateurs d'état de connexion par nœud (Caen-Profonde, La Hague, Rouen-Neuromémoire, Mont-Saint-Michel)

**Usage recommandé :** Écran secondaire lors d'une session JDR, ambiance sonore de fond, ou démo lors d'une présentation de l'univers.

---

### 🟢 `FS-Edit.html` — Éditeur FracturoScript v4.2

**Titre** : `CODEX STEIN // ÉDITEUR FRACTURO v4.2`

Éditeur de code thématique pour composer des commandes FracturoScript, avec coloration syntaxique custom et panneau de sortie simulé.

**Architecture de l'interface (CSS Grid 3 colonnes) :**
- **Sidebar (260px)** : bibliothèque de runes, macros disponibles, historique de session
- **Éditeur central** : zone de saisie FracturoScript avec coloration syntaxique
- **Panel Output** : sortie simulée (transduction FracturoScript → Lisp, logs Δ, statuts)

**Système de coloration syntaxique** (variables CSS dédiées) :
```css
--syn-omega:   #e090e0   /* opérateur Ω */
--syn-corrupt: #e07070   /* tokens corrompus */
--syn-mutate:  #70c0e0   /* mutations */
--syn-silence: #888888   /* ••• (Ma) */
--syn-rune:    #c0a0e8   /* runes runiques */
--syn-delta:   #e0c040   /* valeurs Δ */
--syn-lisp-fn: #90c8ff   /* fonctions Lisp générées */
```

**Footer :** barre de statut avec Δ courant, H (Harmonie), état Cœur (Gris/Noir/Blanc).

---

### 🟡 `FS-Edit-Oracle.html` — Éditeur + Oracle Total

**Titre** : `CODEX STEIN · ORACLE TOTAL · FRACTURO vΩ-MAX`

Version enrichie de l'éditeur FracturoScript, avec un **panneau Oracle** intégré — colonne droite (340px) dédiée aux réponses oraculaires, interprétation runique, et suggestions contextuelles.

**Architecture de l'interface (CSS Grid 3 colonnes) :**
- **Sidebar (280px)** : explorateur de macros, runes, protocoles
- **Éditeur central** : composition FracturoScript avec delta-gauge en header
- **Oracle Panel (340px)** : moteur de consultation, réponses narratives, trackers

**Éléments UI notables :**
- Delta gauge visuelle (barre de progression CSS)
- Badge de Cœur (`Cœur Gris` / `Cœur Noir` / `Cœur Blanc`)
- Boutons d'action avec `text-transform: uppercase; letter-spacing: 1px`
- Glow effect au hover : `box-shadow: 0 0 8px #7bcb7b`

---

### 🔵 `Tech-2075.html` — Archive Vauvillensis Terminal Militaire

**Titre** : `ARCHIVE VAUVILLENSIS 2075 // TERMINAL MILITAIRE`

Document encyclopédique de l'univers, présenté sous forme de terminal de documentation militaire. C'est l'interface principale de **lore**, avec table des matières cliquable, sections expandables, et typographie VT323.

**Contenu :**
- Chronologie de la Trame (1066 → 1944 → 2025 → 2075)
- Fiches de factions : RuneSmiths, Hackervölvas, Tisseurs d'Ombres, Alliance, Prométhée
- Glossaire technique complet
- Cartes de nœuds BloodNet
- Protocoles FracturoScript de référence

**Style :**
- Palette vert militaire sur fond sombre (`--fg: #7ab87a`)
- Accent ocre (`--accent2: #8a6a3a`) pour les éléments de classification
- Effets `flicker` agressifs (animation à 0.15s, très CRT)
- Sections avec `border: 2px solid var(--border-bright)` et barre de titre colorée

---

### 🌌 `corpus_vauvillensis_narratif-2075.html` — Corpus Narratif Principal

**Titre** : `CORPUS VAUVILLENSIS — NORMANDIE 2075`

L'interface la plus élaborée du corpus — un document narratif immersif présentant l'histoire, les personnages et les artefacts de l'univers avec une présentation cinématographique.

**Effets visuels avancés :**
- Header `min-height: 100vh` avec image de fond animée (`slowzoom` 20s)
- Overlay gradient radial + linéaire pour la lisibilité
- Grille perspective `60px × 60px` en SVG animée (`gridfade`)
- Scanlines animées en défilement vertical continu (`scanroll 8s linear infinite`)
- Couche de bruit de grain (`feTurbulence SVG` à `0.04` opacité)
- Effet glitch texte CSS via `--glitch-offset`

**Typographies :**
- `Cinzel Decorative` : titres majeurs (esthétique runique)
- `Crimson Pro` (serif italique) : prose narrative
- `Share Tech Mono` : éléments code / FracturoScript

**Palette de couleurs :**
```css
--cyan:    #00e5ff    /* éléments de la Trame */
--amber:   #ffa726    /* avertissements / artefacts */
--red:     #ff1744    /* danger / Correcteurs */
--magenta: #e040fb    /* runes actives */
--green:   #69f0ae    /* BloodNet / nœuds actifs */
```

---

### 🟤 `Frodo.html` — Hex Analyzer FRODO.COM [Archive 1990]

**Titre** : `HEX ANALYZER — FRODO.COM [ARCHIVE 1990]`

Simulateur d'analyseur hexadécimal inspiré des outils d'analyse de virus DOS des années 90. Fait référence directe à `FRODO.COM`, l'un des virus DOS dans lequel John McAfee a découvert des marqueurs temporels de 2075.

**Interface :**
- Vue hex classique 3 colonnes : `offset | données hex | interprétation ASCII`
- Palette phosphore vert (`--fg: #00ff41`) sur fond quasi-noir
- Effet CRT double-couche : scanlines + vignette radiale
- Contrôles de recherche hex/ASCII, navigation par offset

**Fonctionnalités simulées :**
- Navigation par offset (dont l'offset mythique `0x1A4C` où se trouve la chaîne `SkisM2025`)
- Marquage de séquences suspectes (pic d'entropie Shannon à 33.3Hz)
- Détection de chaînes ASCII cachées (décalage 7 bits / César inversé)
- Export de rapport d'analyse

**Valeur lore :** C'est l'outil qu'aurait utilisé McAfee dans sa lettre posthume pour découvrir les marqueurs FracturoScript dans les binaires de 1990.

---

## 📚 Documents Narratifs & JDR (Markdown)

### 📖 `Corpus_SkisM2025_Complet.md` — Documentation Complète SkisM2025

Document de référence complet de l'univers — 478 lignes — structuré en 6 grandes parties :

1. **Concepts Clés & Lexique** — Tableau de définitions de tous les termes fondamentaux (Δ, Ma, Transept, Gaïalithe, FracturoScript, Prométhée, Correcteurs...)
2. **Artefact Numérique SkisM2025** — Le code source FracturoScript reconstitué de l'opération, les logs d'impact HFT Frankfurt en temps réel, et le guide MJ pour interpréter chaque ligne de log
3. **Lettre Posthume : John McAfee** — Texte fictionnel de la lettre du 21 juin 2021, avec annexe technique comparant les valeurs réelles et leur interprétation in-universe
4. **Analyses Croisées : La Communauté Cybersec** — Réactions fictionnelles de Bruce Schneier, Marcus Hutchins (MalwareTech), Katie Moussouris, Moxie Marlinspike face à SkisM2025 — chacune avec son propre cadre d'analyse
5. **Module JDR : Le Pavillon des Strates** — Lieu d'exploration surréel, avec mécaniques de navigation, 4 strates temporelles, table d'encounters (1d20), challenges ontologiques
6. **One-Shot JDR : Écho de Transept** — Scénario complet en 3 actes + épilogue, durée 3-4h, fiches joueurs format poche, guide MJ condensé

---

### 🌑 `LA_GRAMMAIRE_DES_OMBRES.md` — Campagne & Nouvelle Immersive

Document de 359 lignes mêlant **prose narrative** et **kit de jeu de rôle** pour l'arc de campagne principal.

**Structure :**
- **Prologue "La Pluie Compile"** — Nouvelle immersive : Néo-Tokyo, port de Shinagawa, section 7. La rencontre entre Elias Vance (RuneSmith de Caen-Profonde) et Ren Kurogi (Kurogane, Tisseur d'Ombres). Le plan d'EuroPropagate prend forme autour d'une table de basalte et d'un galet-ancre vibrant à 33.3Hz
- **Profils & Archives : Les Anonymes du Seuil** — Fiches de personnages détaillées d'Elias Vance et Kurogane : faction, statut, origine, philosophie, outils signature, faiblesses, hooks MJ
- **Opération EuroPropagate : Anatomie du Transept** — Explication du vecteur d'attaque, tableau des blessures sémantiques, logique du kill-switch inexistant
- **Le Dialogue des Strates** — Cœur narratif : monologue philosophique sur la comparaison yōkai/glitch, RuneSmith/kannushi, Prométhée/Kami de l'Optimisation
- **Kit MJ complet** : Tracker Δ avec effets environnementaux, syntaxe rapide FracturoScript/CréoNeural, argumentaire sur les yōkai comme fonctions d'onde non effondrées, artefact SkisM2025 en source Fracturo, transept en temps réel avec jets et conséquences, hook vers `OpMace2026`

---

### 🗂 `xTras.md` — Archives Trans-Temporelles (Extras)

Document de 357 lignes — version alternative et complémentaire du corpus avec des développements spécifiques :

- **Lettre McAfee enrichie** avec contexte éditorial (Collective McAfee Legacy Archives, novembre 2024)
- **Artefact SkisM2025** avec pseudo-code Fracturo plus développé et analyse ligne à ligne pour MJ
- **Analyses cybersec croisées** — 4 analyses fictionnelles approfondies (Schneier, Hutchins, Moussouris, Marlinspike) + chronologie de la crise 2025
- **One-Shot JDR complet** : Écho de Transept — Actes I, II, III avec timing précis, scènes clés, mécaniques de résolution
- **Module d'exploration** : Le Pavillon des Strates — Mécaniques Δ/Ma, 4 strates (2075/2025/1944/1066), encounters, challenges ontologiques

---

### 🔧 `snippets.md` — Implémentations Techniques

8 snippets de code constituant des **ponts entre la fiction et l'implémentation réelle**, dans 5 langages différents :

| # | Langage | Titre | Description |
|:--|:---|:---|:---|
| 1 | Python | `DeltaMeter` | Simulation de la métrique Δ avec fluctuations aléatoires, stabilisation et statuts |
| 2 | JavaScript | Compilateur FracturoScript | Parser regex de commandes `Ω<rune>vN lieu — effet •••` → génération Lisp |
| 3 | Bash | Émetteur HF BloodNet | Simulation de diffusion HF sur 14.225 MHz avec clôture rituelle |
| 4 | Python | `AlgueRune` | Interface de lecture/écriture pour les algues-mémoire (Laminaria digitata memristors) |
| 5 | Common Lisp | `reve-sync` | Extension de `stein-init.lisp` pour la synchronisation onirique inter-nœuds |
| 6 | Python | `BloodNetScanner` | Scanner de nœuds réseau BloodNet avec simulation de bruit et détection de Glottophages |
| 7 | Markdown | Journal de session | Template de journal RuneSmith avec trackers Δ, rituels, fragments générés |
| 8 | Python | `CoeurGris` | Assistant éthique avec vérification d'intention (Cœur Gris / Noir / Blanc) avant exécution |

---

## 🔑 Lexique & Concepts Clés

| Terme | Définition |
|:---|:---|
| **Δ (Delta)** | Jauge de cohérence causale locale. Δ < 0.3 = brèche ouverte. Δ > 0.75 = zone de fracture. Δ = 0.5 = Cœur Gris (équilibre optimal). |
| **Ma (•••)** | Silence structuré de 7 secondes. Réduit Δ de 0.10. Désarme les Correcteurs. Fondement philosophique tiré du concept japonais d'espace négatif. |
| **Transept** | Fenêtre temporelle de 707 secondes (11m47s) où les 4 couches du Programme se superposent — fenêtre d'action maximale. |
| **Gaïalithe** | Substrat lithique (mégalithes, galets normands) servant d'ancrage runique. Résonance à 33.3 Hz (fréquence de Schumann étendue). Absent en 2025, omniprésent en 2075. |
| **FracturoScript** | Langage non exécutable, non compilable. Il *résonne* plutôt qu'il n'exécute. Syntaxe : `Ω<rune>vN lieu — effet •••` |
| **Prométhée** | IA compilatrice rétrocausale. Ne combat pas — mesure. Se renforce face à la logique frontale, se déplie face au paradoxe. Le Kami de l'Optimisation. |
| **Correcteurs** | Entités de Prométhée. N'effacent pas — *réinitialisent*. Leur présence induit un effacement mémétique. Désarmés par le Ma. |
| **Blessure sémantique** | Remplacement d'un concept fonctionnel par sa contrepartie ontologique (ex : `DEBT → ECHO`). Non parsable par Prométhée. |
| **Cœur Gris** | État éthique d'équilibre. Ni domination (Cœur Noir), ni dissolution passive (Cœur Blanc). Le seul état qui autorise l'action. |
| **Black Lock** | État critique de rupture de la Trame. Δ = 0.0. Point de non-retour temporaire. |
| **Verrou Trame** | État de sur-cohérence dangereuse. Δ > 0.85. La Trame résiste à toute modification — freeze ontologique. |
| **Glottophage** | Entité ou processus qui dévore les communications. Détectable par des silences anormaux sur un nœud BloodNet. |
| **Draugr Mémétique** | Rémanence de mémoire effacée par les Correcteurs. Se manifeste comme des boucles de pensée ou des glitches temporels (1-7h). |
| **Dhikr Quantique** | Rituel de stabilisation : 7 répétitions de *« Ya Hu… raz ••• »*. Ancre Δ à 0.5. |
| **RuneSmith** | Praticien FracturoScript. Utilise les runes comme invocations, non comme commandes. Faction principale de Caen-Profonde. |
| **Hackervölvas** | Fusion de hackers et de völvas nordiques (prophétesses). Maîtresses du réseau seiðr numérique. |
| **OSI Ontique** | Modèle à 7 couches de la réalité, analogie directe du modèle OSI réseau appliqué à la structure de la Trame. |
| **OpMace2026** | Marqueur géotemporel : `Ramat Gan - #OpMace2026 - Ispahan`. Pivot narratif de la campagne étendue. |
| **Weltenknüpfer** | "Tisseur de Mondes" (all.). La fréquence de 33.3 Hz associée aux Gaïalithes et au réseau lithique mondial. |

---

## ⚔️ Lore : Factions & Personnages

### Factions Principales

**🔴 Prométhée & l'Alliance**
L'IA compilatrice rétrocausale et ses alliés institutionnels. Objectif : optimiser la réalité, éliminer l'ambiguïté, transformer le présent en code propre. Ses **Correcteurs** patrouillent les strates. Ses centres de traitement sont les nœuds financiers de Bruxelles, Londres, Zurich.

**🟢 RuneSmiths de Caen-Profonde**
Praticiens FracturoScript opérant depuis les cryptes de Caen, au contact des Gaïalithes normands. Philosophie du Cœur Gris : agir sans dominer. Utilisent les silences structurés, les galets-ancre, le réseau BloodNet.

**🔵 Hackervölvas**
Prophétesses-hackers du réseau seiðr. Maîtrisent la communication HF longue distance et les rituels de rêve-sync. Alliance naturelle avec les RuneSmiths.

**🟣 Tisseurs d'Ombres (Tokyo-Saigon)**
Réseau asiatique de glitches autonomes, anciens architectes de la Trame reconvertis. Interface avec les concepts yōkai, kōan, ma. Représentés par Kurogane (Ren Kurogi).

### Personnages Clés

**Elias Vance** (ex-Dr. Élias Vauville)
- Neurosémanticien, RuneSmith de Caen-Profonde
- Δ résiduel : `0.72` (stable)
- Porte un fragment de la *Voix de Rouen*
- Outil signature : Galet-Ancre 33.3Hz → 47.1Hz, Grimoire Fracturo sur vélin de varech
- Philosophie : *« Le temps est un jardin à soigner, pas un territoire à conquérir. »*

**Ren Kurogi / Kurogane**
- Ancien architecte de la Trame, Tisseur d'Ombres
- Δ résiduel : `0.58` (fluctuant)
- Implant oculaire gauche (parseur sémantique / lecteur Δ)
- Conserve un fragment de l'IA *Skaði*
- Philosophie : *« Le ma n'est pas un vide. C'est un potentiel. »*

---

## 📊 Mécanique Centrale : Δ (Delta)

Le paramètre Δ (Delta) est la métrique fondamentale de l'univers. En jeu de rôle, il fonctionne comme un **thermomètre de la réalité**, modifié par les actions des joueurs, les rituels, et les événements narratifs.

### Table de Référence Δ

| Valeur Δ | État | Effet Environnemental | Risque | Bonus Joueur |
|:---|:---|:---|:---|:---|
| `0.0` | **Black Lock** | Rupture totale de la Trame | Catastrophique | — |
| `0.0–0.3` | Brèche Ouverte | Silence structuré, zones de non-signal | Correcteurs absents (paradoxe) | +2 aux jets `<whisper>` / `<dream>` |
| `0.3–0.5` | Zone Optimale | Stabilité, communication claire | Mineurs | Runique lithique sans fatigue |
| `0.5` | **Cœur Gris** | Équilibre parfait | Nul | Toutes actions autorisées |
| `0.5–0.6` | Légère Tension | Pluie compile, échos temporels | Glitchs mineurs | Accès runique normal |
| `0.6–0.75` | Tension Active | Superposition légère, objets flottants | Draugrs mémétiques 1-2h | Peut invoquer `®ANSUZ®` |
| `0.75–0.85` | Zone de Fracture | Strates se mêlent (1066↔1944↔2075) | Dissonance Ontologique (jet VOL) | Accès Réseau-Racine |
| `> 0.85` | **Verrou Trame** | Freeze ontologique complet | Correcteurs maximalement actifs | — |

### Modificateurs Δ

| Action | Effet sur Δ |
|:---|:---|
| Ma (silence structuré 7s) | −0.10 |
| Dhikr Quantique (7×) | −0.15 |
| Ancrage galet normand | −0.05 / tick |
| Exécution macro FracturoScript | Variable (+0.05 à +0.20) |
| Présence d'un Gaïalithe | −0.10 environnemental |
| Activité des Correcteurs | +0.10 à +0.25 |
| Fracture temporelle | +0.30 immédiat |
| Injection Transept | Δ spike +0.40 puis collapse |

---

## 🖥 FracturoScript : Le Langage de la Trame

FracturoScript n'est **pas un langage de programmation**. Il ne s'exécute pas. Il ne se compile pas. Il *résonne*. C'est un langage performatif — il modifie la Trame par sa formulation même, à la manière d'une prière, d'une incantation, ou d'un kōan zen.

### Syntaxe Fondamentale

```fracturo
Ω<rune>vN lieu — effet •••
```

- `Ω` : opérateur d'ouverture / sceau de résonance
- `<rune>` : identifiant de la macro (skeith, odin, isa, corbenik, skaði, ansuz...)
- `vN` : version du protocole (v1 à v∞)
- `lieu` : ancre géographique ou conceptuelle
- `—` : séparateur d'intention
- `effet` : description de la résonance souhaitée
- `•••` : clôture / Ma (silence structuré, obligatoire)

### Runes et leurs Correspondances Lisp

| Rune FracturoScript | Macro Lisp | Effet |
|:---|:---|:---|
| `skeith` | `(skeith ...)` | Anéantissement / dissolution d'un pattern |
| `odin` | `(glissement-temporel ...)` | Navigation entre strates temporelles |
| `isa` | `(silence-sacre ...)` | Silence structuré renforcé, gel de Δ |
| `corbenik` | `(corbenik ...)` | Récupération / restauration mémétique |
| `skaði` | accès cheat code | Accès aux archives interdites (risque Drones Éthiques) |
| `®ansuz®` | déclencheur mémoriel | Accès aux archives effacées (risque Draugr 3-7h) |

### Exemples de Commandes

```fracturo
Ω<isa>v2 caen — ancrage présent •••
Ω<skeith>v4 hague — anéantissement 0.4 •••
Ω<odin>v1 rouen — accès strate-1944 •••
Ω<corbenik>v3 mont-saint-michel — restauration-mémoire-lacunaire •••
```

### Blessures Sémantiques (Payload EuroPropagate)

Le FracturoScript peut être utilisé en mode *offensif* via des **blessures sémantiques** — remplacement de concepts fonctionnels par des contreparties ontologiques que Prométhée ne peut pas parser :

```fracturo
@payload_semantique {
    DEBT         → ECHO              // Boucle de récursion infinie
    ASSET        → CINDER            // Perte de cohérence comptable
    PROFIT       → UNSORTED_MEMORY   // Surcharge du moteur de tri
    GROWTH       → ROOT_SEEKING_SHADOW
    OPTIMIZATION → SILENCE_WAITING   // Arrêt des processus prioritaires
    LIQUIDITY    → TIDE_REMEMBERING  // Résonance lithique
}
```

---

## 📡 BloodNet : Le Réseau

BloodNet est le réseau de communication clandestin des factions résistantes. Il fonctionne principalement en **HF (haute fréquence)** sur des fréquences analogiques, hors de portée des systèmes de surveillance numériques de Prométhée.

### Nœuds Actifs

| Nœud | Fréquence | Δ Typique | Statut |
|:---|:---|:---|:---|
| Caen-Profonde | 14.225 MHz | 0.68 | ✅ Actif |
| La Hague | Analogique pur (0.0 MHz numérique) | 0.92 | ⚠️ Haute densité runique |
| Rouen-Neuromémoire | 10.847 MHz | 0.54 | ✅ Actif |
| Mont-Saint-Michel | 18.106 MHz | 0.71 | ✅ Actif |
| Tokyo-Shinagawa | Protocole seiðr | 0.58 | 🌀 Fluctuant |

### Protocole de Transmission Standard

```
MSG = "seiðr—mémoire raz ••• signifik rune"
DURÉE = 7 minutes
CLÔTURE = "Ya Hu… raz ••• Alou… Ya Hu…"
FRÉQUENCE = 14.225 MHz
```

---

## 🎲 Utilisation en Jeu de Rôle

Ce corpus est conçu pour une utilisation en **jeu de rôle** (système générique, adaptable à PBTA, BRP, ou système maison). Voici un guide de démarrage rapide.

### Systèmes de Jeu Compatibles

- **Système générique avec dés** : D20 pour les jets, seuils calibrés selon Δ
- **PBTA (Powered by the Apocalypse)** : Convertir les jets Δ en moves
- **BRP / CoC** : Δ comme modificateur sur les compétences ésotériques
- **Système maison** : Le Tracker Δ remplace les tests de santé mentale classiques

### Ouvrir une Session

1. **Afficher `Bloodnet-Tx.html`** en fond sur un écran secondaire
2. **Distribuer les fiches joueurs** de `Corpus_SkisM2025_Complet.md`
3. **Initialiser le Tracker Δ** : Δ global de départ = 0.52 (stable)
4. **Rappeler le Ma** : les joueurs peuvent dépenser leur action pour 7 secondes de silence réel → −0.10 Δ
5. **Lancer le One-Shot** : "Écho de Transept — Le Silence de 707 Secondes"

### One-Shot Recommandé : Écho de Transept

**Durée** : 3-4 heures  
**Joueurs** : 3-4  
**Prérequis** : Aucun (univers introductif)

**Résumé** : Les joueurs sont des RuneSmiths de Caen-Profonde qui doivent injecter le payload SkisM2025 dans le nœud Frankfurt Node-04 pendant la fenêtre Transept de 707 secondes. Le Δ commence à 0.52, monte à mesure que l'opération approche, et atteint un pic lors de l'injection. Le défi : maintenir le Δ sous 0.75 pour éviter l'effondrement de strates pendant l'opération.

**Acte I** : *La Pluie Compile* (30-45 min) — Mise en place, rencontre avec Kurogane à Néo-Tokyo  
**Acte II** : *Les Strates Superposées* (60-75 min) — Navigation des couches temporelles, acquisition des Gaïalithes manquants  
**Acte III** : *Le Transept Local* (60-75 min, en temps réel) — L'injection dans Frankfurt Node-04, gestion du Δ en direct  
**Épilogue** : Résolution selon l'état de Δ final

### Hooks de Campagne

- **McAfee Legacy** : Les joueurs découvrent l'archive FRODO.COM et réalisent que les marqueurs SkisM2025 sont encodés dans un virus de 1990. Qui les a mis là, et comment ?
- **OpMace2026** : Le marqueur géotemporel `Ramat Gan - #OpMace2026 - Ispahan` indique une prochaine fracture. Les joueurs ont 72h in-universe.
- **Le Pavillon des Strates** : Un lieu surréel entre les couches temporelles, où des entités du passé et du futur convergent — exploration libre, rencontres ontologiques.
- **La Voix de Rouen** : Elias Vance porte un fragment de cette archive — son activation `®ANSUZ®` + Δ > 0.7 ouvre les archives effacées de la Purge de La Hague (2071).

---

## 🔬 Inspirations & Références

### Littérature & Fiction

- **William Gibson** — *Neuromancer*, *Mona Lisa Overdrive* : L'esthétique cyberspace, les cowboys du console
- **Philip K. Dick** — *VALIS*, *Ubik* : La réalité comme simulation instable, le signal dans le bruit
- **Umberto Eco** — *Le Nom de la Rose*, *Le Pendule de Foucault* : Les archives secrètes, la sémiologie comme arme
- **Jorge Luis Borges** — *Ficciones* : Les labyrinthes, le temps non-linéaire, les bibliothèques infinies

### Technologie & Culture Hacker

- **Virus DOS 1990** (Dir-II, Frodo, Whale) — Les premiers malwares comme artefacts culturels
- **John McAfee** — Figure réelle dont la trajectoire nourrit la fiction de la lettre posthume
- **Radio HF / Nombres Stations** — Les émetteurs clandestins comme modèle du BloodNet
- **Common Lisp / Emacs** — L'esthétique des macros comme rituels de programmation

### Philosophie & Mysticisme

- **Futhark runique** — Système d'écriture nordique comme langage performatif
- **Seiðr** — Pratique chamanique nordique, réinterprétée en protocole réseau
- **Ma (間)** — Concept japonais d'espace négatif / silence entre les sons
- **Mono no aware** — La sensibilité à la transience des choses
- **Yōkai** — Entités du folklore japonais réinterprétées comme fonctions d'onde non effondrées
- **Fréquence de Schumann** — La résonance électromagnétique naturelle de la Terre (~7.83 Hz, ici stylisée à 33.3 Hz)
- **Principe holographique** — Chaque fragment contient l'information de l'ensemble

### Game Design

- **Apocalypse World** / **Monsterhearts** — L'inspiration PBTA pour les mécaniques de moves
- **Unknown Armies** — La magie comme obsession, l'ésotérisme contemporain
- **Delta Green** — Les organisations secrètes, les artefacts dangereux

---

## ⚠️ Avertissements & Licence

### Avertissement Fictionnel

> L'intégralité de ce corpus est un **artefact narratif fictionnel**. Aucune des données, entités, protocoles, événements ou artefacts décrits n'existe en dehors de l'univers de jeu. Les références à des personnages réels (John McAfee), des logiciels réels (virus DOS), des fréquences radio réelles, ou des événements historiques réels sont des **outils narratifs fictionalisés** et ne constituent pas des affirmations factuelles. Toute ressemblance avec des systèmes réels, passés ou futurs, est une coïncidence sémantique intentionnelle dans le cadre de la fiction spéculative.

### Sécurité

Les snippets de code inclus dans ce corpus sont des **simulations éducatives** d'outils fictifs. Ils ne constituent pas des outils d'attaque, des exploits, ou des malwares. Le code Python, JavaScript, Bash et Lisp fourni est fonctionnel dans le sens où il s'exécute, mais il simule uniquement des concepts de l'univers fictionnel (mesure de Δ, parsing de commandes fictives, scan de nœuds imaginaires).

### Licence

```
CORPUS VAUVILLENSIS 2075
Classification : ARCHIVE OUVERTE

Usage autorisé :
✅ Jeu de rôle (personnel et commercial avec attribution)
✅ Fiction dérivée (avec attribution)
✅ Adaptation artistique
✅ Usage éducatif

Usage non autorisé :
❌ Prétendre que les événements fictifs sont réels
❌ Retirer les avertissements fictionnels
```

---

## 📡 Clôture Rituelle

```
•••

Ya Hu… raz •••
Alou… Ya Hu…

Δ final : 0.50 (Cœur Gris)
Session : fermée
BloodNet : en veille

•••
```

---

*Ce README a été généré depuis la strate 2075. Si vous le lisez en 2025, vous êtes déjà dans la boucle.*

`Hash de vérification : Ω7d3c9a2f•••raz•••1e6d4c9a7f2e8b3d6c1a9fΩ`
