# Journal d'Usage des Outils d'Intelligence Artificielle — Studio Flexarion

> **BUT Informatique — 2e Année | IUT d'Aix-Marseille**  
> *Module : Plan de communication & webmarketing à l'ère de l'IA*  
> *Projet : Concours SEO — Studio Flexarion (Aix-en-Provence)*  
> *Document tenu au fil de l'eau conformément aux consignes des sections 4, 6 et 7 du brief étudiant.*

---

## 1. Contexte & Démarche

Dans le cadre du concours SEO et de communication autour de l'entité imposée **« Flexarion »**, notre groupe a intégré l'intelligence artificielle générative comme un outil d'assistance opérationnelle, de brainstorming créatif, d'ingénierie logicielle et d'optimisation pour les moteurs de recherche (SEO).

Ce document constitue la **partie 1 (« Le journal d'usage »)** exigée pour l'évaluation des critères d'usage documenté de l'IA (Note 1 : 4 points / Note 2 : 5 points).

> ⚠️ **Rappel déontologique (Section 6 du brief) :**  
> Conformément au règlement, la **synthèse réflexive finale** (1 à 2 pages de regard critique personnel) doit être **rédigée intégralement sans IA par les membres du groupe**. La section finale de ce document fournit le guide de cadrage et les questions directrices pour guider cette rédaction humaine.

---

## 2. Inventaire Factuel des Outils Mobilisés

| Outil / Modèle | Usage Principal | Fréquence |
|---|---|---|
| **Gemini 1.5 Pro / Flash & Antigravity Agent** | Audit de code, restructuration sémantique HTML5, architecture en silo, Schema.org JSON-LD, optimisation Core Web Vitals | Continue |
| **Claude 3.5 Sonnet / Claude Code** | Rédaction technique poussée des 29 devlogs (équations physiques, shaders Vulkan, algorithmes WFC), worldbuilding hard-SF | Phases TD1 à TD3 |
| **ChatGPT (GPT-4o)** | Idéation narrative, brainstorming des titres et noms de projets du catalogue (Nexus Void, Helios Protocol, Chronos Drift, Stellar Forge) | Phase initiale CM2 |
| **Outils d'Audit SEO (Google Search Console, PageSpeed Insights, Umami)** | Monitoring d'indexation, analyse des Core Web Vitals, vérification du balisage mobile | TD2 à TD4 |

---

## 3. Historique Chronologique des Phases & Prompts

### Phase 1 : Idéation du Studio, Univers Hard-SF & Identité Visuelle (CM2)

* **Objectif :** Définir le positionnement différenciant du studio Flexarion à Aix-en-Provence par rapport aux autres groupes concurrents, tout en respectant le concept imposé.
* **Choix stratégique :** Positionner Flexarion non pas sur la SF grand public ou « space fantasy », mais sur la **Hard Science-Fiction rigoureuse**, appuyée par la physique newtonienne et un moteur C++ propriétaire.
* **Exemple de Prompt utilisé :**
  ```text
  "Nous participons à un concours universitaire où nous devons incarner 'Flexarion', 
  un studio indépendant de jeux vidéo de science-fiction basé à Aix-en-Provence. 
  Propose-nous un concept de jeu phare original qui se démarque de la concurrence 
  par une rigueur scientifique absolue (hard-SF, mécanique céleste, physique newtonienne) 
  et un moteur propriétaire. Donne-nous un pitch narratif fort et des mécaniques clés."
  ```
* **Résultat obtenu :** Genèse du jeu phare **Anni 2810**, centré sur l'Explorateur Anni et la découverte de l'Artefact dans la ceinture de Kuiper.

---

### Phase 2 : Rédaction des Carnets de Bord Techniques (Devlogs) (TD1 / TD2)

* **Objectif :** Créer une profondeur éditoriale crédible et dense démontrant l'expertise technique du studio (E-E-A-T : Experience, Expertise, Authoritativeness, Trustworthiness).
* **Méthodologie :** Chaque devlog a été structuré comme un carnet de bord d'ingénierie réel abordant une problématique logicielle précise (mécanique orbitale, compute shaders, structures de données lock-free).
* **Exemples de Prompts utilisés :**
  ```text
  "Rédige un carnet de bord de développement (Devlog #3) pour Anni 2810. 
  Sujet : Pourquoi un intégrateur standard d'Euler échoue pour la mécanique orbitale 
  à longue période, et comment notre équipe a implémenté un intégrateur symplectique 
  de Verlet d'ordre 4 dans notre moteur C++ pour simuler le problème à N corps à 60 FPS. 
  Ton : sérieux, passionné, rigoureux sur le plan physique."
  ```
  ```text
  "Rédige le Devlog #26 expliquant l'algorithme Wave Function Collapse (WFC) en 3D 
  utilisé pour la génération procédurale d'intérieurs modulaires de mégastructures spatiales, 
  avec contraintes de connecteurs de faces et résolution de contradictions par backtracking."
  ```
* **Ajustements humains :** Relecture technique, reformulation des termes pour assurer la cohérence entre les 29 devlogs, suppression de toute répétition stylistique de l'IA.

---

### Phase 3 : Structuration Front-End & Architecture en Silo (TD3)

* **Objectif :** Structurer le site en silos sémantiques étanches et complémentaires, maximisant la diffusion du PageRank interne sur le mot-clé principal **« Flexarion »**.
* **Organisation des 4 silos :**
  1. **Silo Studio / Ancrage Local :** `studio.html` (Histoire, équipe, ancrage à Aix-en-Provence, valeurs).
  2. **Silo Jeu Phare & Catalogue :** `anni-2810.html` (Page dédiée complète) + `jeux.html` (Catalogue des 5 titres).
  3. **Silo R&D & Carnets Techniques :** `devlogs.html` (29 articles classés par thématiques avec index TOC).
  4. **Silo Relations Extérieures & Légal :** `contact.html` (Presse, Formulaire, Fast facts) + `mentions-legales.html`.
* **Prompt utilisé :**
  ```text
  "Analyse l'arborescence de notre site statique pour le Studio Flexarion. 
  Comment organiser un cocon sémantique (architecture en silo) strict reliant 
  l'accueil, la page studio à Aix-en-Provence, la page dédiée à notre jeu phare Anni 2810, 
  les 29 devlogs techniques et l'espace presse ? Propose les balises de fil d'Ariane 
  (BreadcrumbList) et le maillage interne contextuel adapté."
  ```

---

### Phase 4 : SEO Technique, Données Structurées & Core Web Vitals (TD3 / TD4)

* **Objectif :** Optimiser les critères techniques qui influent directement sur l'algorithme de positionnement Google et sur l'audit SEO de secours prévu au TD4 :
  * Données structurées **Schema.org** en JSON-LD : `Organization`, `LocalBusiness`, `VideoGame`, `Blog`, `ContactPage`, `FAQPage`, `BreadcrumbList`.
  * Balises méta canoniques (`canonical`), réseaux sociaux (`og:*`, `twitter:*`), et `manifest.json`.
  * Optimisation du poids des images : réduction du JPEG de gameplay de 3,3 Mo à ~630 Ko pour un LCP (Largest Contentful Paint) ultra-rapide.
  * Hiérarchie stricte des titres (`h1` unique par page, `h2`, `h3`, `h4` sans saut de niveau).
* **Vérification d'équité :** Suppression formelle de tout lien sortant vers d'autres sites de groupes concurrents (respect de la règle d'équité 3.4 interdisant les liens entre groupes).

---

## 4. Bilan Critique : Ce que l'IA a bien fait vs Ses limites

### Ce que l'IA a parfaitement accompli :
1. **Accélération rédactionnelle et rigueur lexicale :** Capacité à mobiliser un vocabulaire technique pointu (astrophysique, C++, API Vulkan, équations différentielles) en un temps record.
2. **Standardisation du code :** Génération de schémas JSON-LD impeccables selon les normes Schema.org, évitant les erreurs de syntaxe.
3. **Brainstorming créatif :** Élaboration de mécaniques systémiques complexes (synergie entre dépression explosive, support de vie ECLSS et stress psychologique).

### Ce que l'IA a mal fait ou ses limites constatées :
1. **Risque de sur-optimisation (bourrage de mots-clés) :** Si on ne la cadre pas, l'IA a tendance à répéter « Studio Flexarion à Aix-en-Provence » à chaque phrase, ce qui aurait pu être assimilé à du black hat SEO. Un travail humain de filtrage a été nécessaire pour préserver le naturel du texte.
2. **Manque de sensibilité locale :** L'IA produit facilement du contenu générique sur Aix-en-Provence sans réelle saveur locale. Nous avons dû réinjecter des références précises (la montagne Sainte-Victoire, le Technopôle de l'Arbois, la proximité avec le Laboratoire d'Astrophysique de Marseille).
3. **Uniformité stylistique des devlogs :** Les premiers jets avaient tous une structure identique (Introduction pompeuse / 3 sous-parties / Conclusion enthousiaste). Il a fallu diversifier les formats de devlogs (certains courts et très ciblés, d'autres longs avec extraits de pseudo-code).

---

## 5. Guide de Cadrage pour la Synthèse Réflexive Finale (Note pour les Étudiants)

> 🛑 **RÈGLE DU BRIEF (Section 6) :**  
> *« La synthèse réflexive finale (1 à 2 pages) doit être intégralement rédigée par vous, sans l'aide d'une IA générative, du début à la fin. Une réflexion sur l'IA rédigée par une IA n'a aucune valeur d'évaluation et sera sanctionnée si elle est détectée. »*

Pour rédiger votre synthèse réflexive personnelle, appuyez-vous sur les questions suivantes :
1. **Votre sentiment face au rôle d'« éditeur / relecteur » :** Dans ce projet, avez-vous eu l'impression d'être programmeur/rédacteur, ou plutôt directeur de publication validant et corrigeant le travail d'une IA ?
2. **L'esprit critique exercé :** À quel moment avez-vous dû dire « non » à l'IA ou modifier en profondeur sa proposition (ex. trop verbeuse, pas assez réaliste, mauvaise structure SEO) ?
3. **Le futur du webmarketing et du SEO :** Avec l'arrivée des moteurs de recherche génératifs (Google Search Generative Experience, Perplexity), que pensez-vous de la valeur du contenu généré par IA face au besoin d'authenticité et d'expérience humaine (E-E-A-T) ?
4. **Ce que vous retenez pour vos futurs projets en BUT Informatique :** Comment doser efficacement l'usage de l'IA sans perdre la maîtrise de ses outils et de sa pensée ?
