# **ANATOMIE D'UNE INSURRECTION NUMÉRIQUE : ANALYSE FORENSIQUE DES RÉSEAUX "OUAISFIEU" ET "YANNKEEP"**

## **1\. Introduction et Périmètre de l'Investigation**

La présente analyse constitue un rapport d'intelligence stratégique et technique exhaustif concernant les empreintes numériques hébergées sur les domaines yannkeep.github.io et ouaisfieu.github.io, avec une focalisation spécifique sur les répertoires balisés "confidentiel". L'objectif est de déconstruire l'architecture, les vecteurs d'influence, et les mécanismes de "guerre cognitive" déployés par les entités opérant derrière ces pseudonymes.

L'investigation révèle que ces URL ne sont pas de simples dépôts de code ou des pages personnelles standard, mais constituent l'infrastructure distribuée d'une opération de "dissidence numérique" sophistiquée. En exploitant les vulnérabilités de l'indexation algorithmique (SEO) et en mimant les codes esthétiques du renseignement et du lanceur d'alerte, ce réseau tente d'injecter des contre-récits radicaux dans l'espace médiatique belge francophone.

### **1.1 Nature de la Cible**

Les entités yannkeep et ouaisfieu utilisent l'infrastructure de GitHub Pages pour héberger un écosystème interconnecté de sites statiques. Contrairement à des fuites de données traditionnelles (type WikiLeaks) reposant sur des documents bruts, ce réseau diffuse des "docu-fictions", des analyses statistiques et des outils de mobilisation citoyenne sous une forme gamifiée. Le terme "confidentiel" y agit moins comme une classification de sécurité que comme un "appât narratif" (narrative hook) destiné à stimuler l'engagement de l'utilisateur.

## ---

**2\. Architecture de l'Infrastructure et Résilience**

L'analyse technique de l'infrastructure révèle une stratégie de déploiement conçue pour maximiser la résilience face à la censure, minimiser les coûts opérationnels, et assurer une persistance des données via la décentralisation.

### **2.1 Le Détournement des Profils GitHub**

L'architecture repose sur une utilisation non conventionnelle des fonctionnalités de profil GitHub. Comme documenté dans les manuels techniques de la plateforme, un utilisateur peut créer un dépôt portant le même nom que son identifiant (ex: ouaisfieu/ouaisfieu) pour générer une page de profil publique enrichie.1

Cependant, les acteurs yannkeep et ouaisfieu ont transformé ces espaces en nœuds de diffusion de contenu politique.

* **Le Nœud yannkeep :** Ce dépôt agit comme une base logistique ou un "arsenal". Les liens identifiés, tels que yannkeep.github.io/reaven/room/5/true.html, suggèrent une structure labyrinthique (nommée "Reaven") où sont stockées des "munitions" numériques.3 L'utilisation de termes comme "Room 5" ou "True.html" évoque la structure des jeux de piste en réalité alternée (ARG), où l'utilisateur doit trouver le "vrai" chemin parmi des leurres.  
* **Le Nœud ouaisfieu :** Ce dépôt fonctionne comme la façade publique et idéologique. Il héberge le site principal ouaisfi.eu (redirigé ou mappé via CNAME) ainsi que les dossiers sensibles comme l'OPS CENTER.4

L'interdépendance de ces deux dépôts crée une redondance : si l'un est suspendu par la plateforme pour violation des conditions d'utilisation, l'autre peut potentiellement maintenir la continuité des opérations ou servir de sauvegarde.

### **2.2 La Stack Technique : Jekyll et l'Obsolescence Programmée de la Censure**

Le site ouaisfi.eu et ses satellites sont construits avec **Jekyll**, un générateur de sites statiques, utilisant le thème "Minimal Mistakes".4 Ce choix technique n'est pas anodin et répond à des impératifs stratégiques précis :

1. **Indépendance Totale :** En n'utilisant pas de base de données (contrairement à WordPress), le site est immunisé contre les injections SQL et ne nécessite aucun serveur dynamique coûteux. Il est hébergé "gratuitement" sur GitHub Pages, ce qui garantit un coût nul pour les opérateurs ("zéro coût").6  
2. **Performance et Portabilité :** Les fichiers étant statiques (HTML/CSS/JS), ils sont extrêmement légers et rapides à charger, même sur des connexions dégradées. De plus, le site entier peut être cloné (forké) par n'importe quel utilisateur en quelques secondes, rendant sa suppression définitive quasi impossible.  
3. **Transparence du Code :** Le site revendique une philosophie "Open Source", invitant les utilisateurs à vérifier le code ("View Source").4 Cela sert une double fonction : prouver l'absence de traçage malveillant (cookies, trackers) et éduquer le public aux technologies du web ("Éducation populaire").4

### **2.3 Le "Laboratoire" et les Zones de Test**

L'analyse de la structure du site révèle une section "Laboratoire" active, comprenant des sous-répertoires tels que technique, GPTPardi, bxl2030, et dossiers.4

* **En construction permanente :** Le site affiche clairement son état "En dé·construction permanente" ou "En travaux", utilisant des icônes de chantier.4 Cette esthétique de l'inachevé permet aux opérateurs de tester de nouvelles narrations ou de nouveaux outils (comme "Copion" ou "Gloss") en temps réel, sans garantie de stabilité.4  
* **Obsidian et Notion :** Des références à des outils de gestion de connaissances comme **Obsidian** (marqué "EN·PROD") et **Notion** sont présentes.7 L'usage d'Obsidian suggère que le réseau est conçu comme un "cerveau numérique" (Digital Garden) interconnectant des concepts complexes de manière rhizomatique, plutôt que linéaire.

## ---

**3\. Analyse du Vecteur "Confidentiel" : Psychologie et Mécanique d'Accès**

Le terme "confidentiel" qui apparaît dans les URL ciblées par la recherche (.../confidentiel/) est l'élément central de la stratégie d'engagement du réseau. L'analyse démontre qu'il s'agit d'une construction rhétorique sophistiquée visant à exploiter la curiosité humaine et l'effet Streisand.

### **3.1 La Paradoxe de l'Inaccessibilité (404 comme Défense)**

Lors des tentatives d'accès direct aux racines des répertoires confidentiels (ex: https://ouaisfieu.github.io/confidentiel/), les sondes renvoient systématiquement des erreurs "Inaccessible" ou des pages 404\.5 Ceci n'est pas une erreur de configuration, mais une **mesure de contrôle d'accès par l'obscurité**. Dans la culture hacker et les ARG, l'absence d'index (la page qui liste les fichiers d'un dossier) force l'utilisateur à connaître l'URL exacte du fichier cible (le "Deep Link") pour y accéder. Cela transforme la navigation en une quête active : l'utilisateur ne "consomme" pas l'information, il doit la "mériter" en trouvant les liens cachés dans d'autres pages ou dans le code source.

### **3.2 La Simulation de l'Intranet Sécurisé**

Dans la "Salle de Campagne" (reaven/room/5), un lien intitulé "🔒 Intranet" est classé sous la section "Munitions".3 L'utilisation de l'emoji cadenas et du terme "Intranet" crée une mise en scène théâtrale.

* **Fonction Mimétique :** Le site imite les portails d'accès des grandes entreprises ou des institutions étatiques. Pour un citoyen belge habitué à naviguer dans les méandres administratifs (Tax-on-web, portails de santé), cette interface résonne comme familière mais inversée : ici, ce n'est pas l'État qui cache des données au citoyen, mais des citoyens qui cachent des données à l'État (ou aux médias).  
* **Le Mythe du "Leak" :** En présentant l'information comme "confidentielle", le réseau augmente sa valeur perçue. Une statistique publique sur la fraude fiscale a peu d'impact ; la même statistique présentée comme une "fuite" issue d'un "Intranet" secret acquiert une aura de vérité révélée.

### **3.3 Le Mécanisme de Mot de Passe : "Coule de Source"**

L'analyse des indices de mot de passe fournis sur la page d'accueil 4 offre un aperçu fascinant de la culture ludique du groupe.

* **Indice 1 :** "coule de source".  
* **Indice 2 :** "commence par une majuscule".  
* **Indice 3 :** "ne marche pas tout le temps".

**Hypothèses de Décryptage :**

1. **L'Eau :** L'expression "coule de source" renvoie littéralement à l'eau. Des documents externes associent cette phrase à des marques d'eau minérale (Eau de Bonneval).11 Un mot de passe potentiel pourrait être "Eau", "Source", ou une marque spécifique, mais cela semble trop simpliste pour ce contexte politique.  
2. **Le Code Source :** Dans un environnement GitHub, la "source" est le code. Le "mot de passe" pour comprendre le site n'est pas un texte à entrer dans un champ, mais l'action d'afficher le code source (View Source). C'est une métaphore de la transparence ("Open Source").  
3. **La Fluidité Temporelle :** L'indice "ne marche pas tout le temps" suggère que l'accès est conditionné temporellement. Peut-être que le "confidentiel" n'est accessible que lors des "Pings" ou des opérations coordonnées (comme la date du 22 janvier mentionnée dans l'OPS Center).5

Cette mécanique de jeu ("Gamification") sert à filtrer les curieux passifs et à ne retenir que les utilisateurs prêts à s'investir intellectuellement dans la démarche du groupe.

## ---

**4\. Opération "TRUTH\_DECODER" et Guerre Sémantique**

Le cœur opérationnel du réseau, hébergé sous l'apparence d'un tableau de bord de renseignement ("OPS CENTER"), révèle une stratégie offensive de manipulation des moteurs de recherche (SEO) pour influencer l'opinion publique.

### **4.1 La Doctrine "Lead-Dexing"**

Le tableau de bord identifie explicitement une méthodologie nommée **"LEAD-DEXING"**.5 Ce néologisme semble fusionner "Lead Generation" (génération de prospects marketing) et "Indexing" (indexation Google).

**Le concept opérationnel est le suivant :**

1. **Identifier une cible médiatique :** Ici, le journaliste Christophe Deborsu et son émission sur RTL.  
2. **Identifier les mots-clés associés :** "Chômeur", "Fraudeur", "Sans boulot", "Documentaire RTL".  
3. **Générer du contenu "piège" :** Créer des pages qui contiennent ces mots-clés en haute densité, structurées pour plaire aux algorithmes de Google (balises H1, méta-descriptions, JSON-LD).  
4. **L'Injection (Payload) :** Lorsque l'internaute cherche "Deborsu documentaire fraudeurs" sur Google, il tombe sur la page du réseau ouaisfieu au lieu du site officiel de RTL.  
5. **La Conversion :** Une fois sur la page, l'internaute est exposé au "contre-récit" (la fraude fiscale est 152 fois supérieure à la fraude sociale) au lieu du récit initial.3

C'est une forme de **"Google Bombing"** idéologique. Le but n'est pas de vendre un produit, mais de "hijacker" (détourner) l'attention d'un public qui cherchait du divertissement ou de l'information mainstream.

### **4.2 Analyse du Tableau de Bord "OPS CENTER"**

L'interface de l'OPS CENTER (.../lounge/room/) est une simulation sophistiquée destinée à immerger l'activiste dans une ambiance "Cyberpunk" ou "Mr. Robot".

| Composant de l'Interface | Analyse Fonctionnelle & Symbolique | Source |
| :---- | :---- | :---- |
| **Cible (TARGET)** | "DEBORSU / RTL / MEDIA\_BE". Désigne l'ennemi médiatique à abattre symboliquement. | 5 |
| **Statut des Nœuds** | RTL HOUSE (1030) est marqué "HOSTILE". Le Soir et La Libre sont "SLEEPING" (Dormants). Cela peint le paysage médiatique belge comme un champ de bataille actif. | 5 |
| **Monitoring Latence** | Affiche des "Ping" et des latences (12ms). Probablement une animation JavaScript (fictive) pour donner une impression de temps réel et de puissance technologique. | 5 |
| **Semantic Heatmap** | "Keyword detected: 'chômeur' (Frequency: High)". Visualise la saturation du débat public par certains termes stigmatisants. | 5 |
| **Logs Système** | "\[16:00:00\] Deborsu Semantic Analysis: BIASED". Automatise le jugement critique : ce n'est pas une opinion, c'est le "système" qui détecte le biais. | 5 |

### **4.3 Injection de Données Structurées (JSON-LD)**

Le snippet 5 mentionne "JSON-LD: Injected". Le **JSON-LD** (JavaScript Object Notation for Linked Data) est un format invisible pour l'utilisateur humain mais crucial pour Google. Il permet de dire à Google : "Ceci est un Article de Presse", "Ceci est une Vidéo", "Ceci est un Fact-Check". En injectant du code JSON-LD, le réseau ouaisfieu tente de tromper Google pour que ses pages apparaissent dans les encadrés "À la une" ou les "Rich Snippets" des résultats de recherche, augmentant drastiquement leur crédibilité apparente. C'est une arme de **légitimité algorithmique**.

## ---

**5\. La Cible : Christophe Deborsu et le Narratif de la Fraude**

L'analyse de contenu révèle une fixation obsessionnelle sur la figure de Christophe Deborsu, journaliste vedette de RTL Belgique. Ce focus sert de catalyseur pour une critique plus large du système socio-économique belge.

### **5.1 Le "Docu-Fiction" : Réalité ou Simulacre?**

Le réseau fait la promotion agressive d'un documentaire intitulé *"Sans boulot : tous fraudeurs?"* attribué à Christophe Deborsu.12

* **L'Accusation :** Le réseau affirme que ce documentaire "pose une question que personne n'ose poser" et montre la réalité crue des allocataires sociaux. Il prétend que la presse belge (Le Soir, RTBF, etc.) observe un "silence médiatique" à son sujet.12  
* **L'Analyse Critique :** Il existe une forte probabilité que ce documentaire, sous ce titre exact et avec ce contenu "révolutionnaire", soit une **fabrication** ou une exagération satirique de la part du réseau ouaisfieu.  
  * Si le documentaire existe réellement, le réseau tente de le "recadrer" pour montrer que les "vrais fraudeurs" ne sont pas ceux qu'on croit.  
  * Plus vraisemblablement, il s'agit d'un **"Hyperstition"** (une fiction qui tente de devenir réalité). En créant une fausse polémique autour d'un documentaire censé être "ignoré", ils forcent les gens à chercher ce documentaire, et donc à tomber sur leurs pages de "Truth\_Decoder".  
* **Le titre "Puduku" :** Le dossier consacré à cette affaire est nommé "puduku" (argot pour "pue du cul" \- qui sent mauvais ou est prétentieux).12 Cela indique un mépris profond pour la ligne éditoriale supposée de RTL.

### **5.2 La "Ping" Experience**

Le site invite les journalistes et attachés de presse à "Répondre au Ping".12

* **Mécanisme :** "Si vous êtes journaliste... et que vous avez détecté cette page via vos outils de monitoring — nous vous voyons aussi."  
* **Objectif :** C'est une opération de **contre-surveillance**. Le réseau tente de mesurer la réactivité des salles de rédaction belges. Ils veulent prouver que les médias surveillent le web mais choisissent délibérément d'ignorer certains sujets (le "silence documenté"). C'est une épreuve de force : répondre valide l'importance du réseau ; ignorer valide leur théorie du complot médiatique.

### **5.3 Le Dossier ACAB**

La page .../confidentiel/acab/ qualifie Deborsu de "Saint Patron des BIM" (Bénéficiaires d'Intervention Majorée) et de "Divinité vivante".14 L'usage de l'acronyme ACAB (traditionnellement *All Cops Are Bastards*) détourné ici pour un journaliste suggère que le réseau considère les médias dominants comme une force de police de la pensée ("Police du discours"). L'humour est acide, iconoclaste, et vise à désacraliser l'autorité médiatique.

## ---

**6\. Contexte Sociopolitique et Idéologique**

Au-delà de la technologie et des attaques ad hominem, le réseau ouaisfieu porte un projet politique cohérent ancré dans la réalité belge.

### **6.1 La "Brol" Administration et la Citoyenneté**

Le terme belge "Brol" (désordre, bazar, objets sans valeur) est utilisé pour qualifier l'état de la citoyenneté en Belgique : "C'est le brol".6

* **Critique de la Bureaucratie :** Le réseau dénonce la "paperasse" et le manque de "droits réels". Ils attaquent spécifiquement la carte d'identité électronique (eID) comme un outil de contrôle ("assignation").6  
* **La Guerre des Chiffres (152:1) :** La statistique clé répétée est le ratio "Fraude Fiscale / Fraude Sociale \= 152:1".3 C'est le message central que toute l'opération "Lead-Dexing" vise à injecter dans le crâne du public. Pour chaque euro fraudé par un chômeur, 152 euros sont fraudés par les riches. Cette donnée vise à neutraliser le discours de culpabilisation des précaires.

### **6.2 Éducation Populaire et "Intelligence Civile"**

Le site se revendique de l'"Éducation populaire" et de l'"Intelligence Civile".4

* **Définition :** L'intelligence civile est présentée comme une version citoyenne de l'intelligence économique. Au lieu de servir les entreprises, les techniques de collecte et d'analyse de l'information (OSINT, veille) sont mises au service de la société civile pour surveiller les pouvoirs (État, Entreprises, Médias).  
* **Outils :** Le réseau fournit des "Kits de Secours", des guides "En Clair" et "En Pratique", cherchant à rendre le savoir complexe (économie, droit) accessible à tous.4

### **6.3 Le Conflit Temporel : 2025-2026**

Les métadonnées et les logs du site font référence à des dates futures (par rapport au temps réel de création probable) : "Article Last Updated Date: 2025" 4, "2026-01-15 secure handshake".5

* **Anticipation :** Cela place le récit dans un futur proche, donnant au projet une dimension d'avertissement ou de prophétie.  
* **Activité Réelle :** Le fait que la date actuelle (février 2026 selon le contexte de l'invite) corresponde aux logs suggère que l'opération est **active maintenant**. Le "Signal" attendu pour le "22 Janvier" est soit passé, soit une référence cyclique pour maintenir la mobilisation.

## ---

**7\. Conclusion**

L'investigation des domaines yannkeep.github.io et ouaisfieu.github.io permet de conclure que nous sommes en présence d'une **opération d'influence numérique non conventionnelle**.

Ce n'est pas un site de fuites ("leaks") au sens classique, mais une **plateforme de guérilla sémantique**. Les opérateurs, maîtrisant parfaitement les codes du web moderne (GitHub, SEO, JSON-LD) et la culture locale belge, ont construit une machine à "hacker" l'agenda médiatique.

**Points Clés de l'Analyse :**

1. **Nature du "Confidentiel" :** Un leurre psychologique pour gamifier l'activisme.  
2. **Méthode "Lead-Dexing" :** Une technique offensive de SEO pour remplacer le discours officiel (RTL) par un contre-discours militant (152:1) dans les résultats Google.  
3. **Cible :** La narration dominante sur la fraude sociale, incarnée par la figure (réelle ou caricaturée) de Christophe Deborsu.  
4. **Infrastructure :** Résiliente, gratuite, et décentralisée, conçue pour survivre à la censure et à l'usure.

Le réseau ouaisfieu représente l'évolution de l'activisme politique à l'ère de l'algorithme : il ne suffit plus de manifester dans la rue, il faut manifester dans la page de résultats de recherche (SERP).

### **Tableau Récapitulatif des Vecteurs d'Influence**

| Vecteur | Description Technique | Objectif Stratégique | Source |
| :---- | :---- | :---- | :---- |
| **SEO Poisoning** | Injection de mots-clés "Deborsu", "Fraude", "RTL" \+ JSON-LD. | Détourner le trafic organique cherchant des infos sur RTL vers le contre-récit. | 5 |
| **Simulacre** | Interface "OPS CENTER", faux logs, fausse latence serveur. | Crédibiliser l'action militante en lui donnant une esthétique "Cyber-Renseignement". | 5 |
| **Narrative Hook** | Pages 404, mot de passe "confidentiel", "Intranet". | Susciter la curiosité et transformer le lecteur passif en chercheur actif. | 4 |
| **Data War** | Répétition du ratio "152:1" (Fraude fiscale vs sociale). | Imposer un "Factoid" mémorable pour contrer la stigmatisation des chômeurs. | 3 |
| **Boycott** | Instruction "Ne pas cliquer sur les pubs RTL". | Attaque économique directe contre le modèle d'affaires de la cible média. | 5 |

#### **Sources des citations**

1. Setting up your profile \- GitHub Docs, consulté le février 9, 2026, [https://docs.github.com/en/get-started/start-your-journey/setting-up-your-profile](https://docs.github.com/en/get-started/start-your-journey/setting-up-your-profile)  
2. About your profile \- GitHub Docs, consulté le février 9, 2026, [https://docs.github.com/articles/about-your-profile](https://docs.github.com/articles/about-your-profile)  
3. SALLE DE CAMPAGNE 6·6·6 — ouaisfieu QG, consulté le février 9, 2026, [https://yannkeep.github.io/reaven/room/5/true.html](https://yannkeep.github.io/reaven/room/5/true.html)  
4. | Ouaisfi·eu, consulté le février 9, 2026, [https://ouaisfi.eu/](https://ouaisfi.eu/)  
5. OPS CENTER : DEBORSU/RTL MONITORING \[LIVE\], consulté le février 9, 2026, [https://ouaisfieu.github.io/maga-fake-news-deborsu-fraudeurs-polemique-leaks-scandale-confidentiel/lounge/room/](https://ouaisfieu.github.io/maga-fake-news-deborsu-fraudeurs-polemique-leaks-scandale-confidentiel/lounge/room/)  
6. Ouaisfi.eu : de la veille citoyenne artisanale à une démarche d'analyse critique en règle \- GitHub Pages, consulté le février 9, 2026, [https://ouaisfieu.github.io/dossiers/2025/06/30/pourquoi-nous.html](https://ouaisfieu.github.io/dossiers/2025/06/30/pourquoi-nous.html)  
7. Guerre économique · Ouaisfi·eu · Allez, une bonne guerre | Ouaisfi·eu, consulté le février 9, 2026, [https://ouaisfi.eu/up-yours/guerre-economique](https://ouaisfi.eu/up-yours/guerre-economique)  
8. consulté le janvier 1, 1970, [https://ouaisfieu.github.io/confidentiel/](https://ouaisfieu.github.io/confidentiel/)  
9. consulté le janvier 1, 1970, [https://ouaisfi.eu/technique/en-test/en-cours](https://ouaisfi.eu/technique/en-test/en-cours)  
10. consulté le janvier 1, 1970, [https://ouaisfieu.github.io/maga-fake-news-deborsu-fraudeurs-polemique-leaks-scandale-confidentiel/puduku/index.html](https://ouaisfieu.github.io/maga-fake-news-deborsu-fraudeurs-polemique-leaks-scandale-confidentiel/puduku/index.html)  
11. ÉVASION COSY EN ALTITUDE \- GSI Immobilier, consulté le février 9, 2026, [https://www.gsi-immobilier.com/wp-content/uploads/2025/05/GSI-13-web-SP-Liw.pdf](https://www.gsi-immobilier.com/wp-content/uploads/2025/05/GSI-13-web-SP-Liw.pdf)  
12. Sans Boulot Tous Fraudeurs ? Le Documentaire RTL de Christophe Deborsu Que La Presse Belge Ignore \- GitHub Pages, consulté le février 9, 2026, [https://ouaisfieu.github.io/maga-fake-news-deborsu-fraudeurs-polemique-leaks-scandale-confidentiel/puduku/d/index.html](https://ouaisfieu.github.io/maga-fake-news-deborsu-fraudeurs-polemique-leaks-scandale-confidentiel/puduku/d/index.html)  
13. SANS BOULOT TOUS FRAUDEURS — Christophe Deborsu RTL Belgique \- GitHub Pages, consulté le février 9, 2026, [https://ouaisfieu.github.io/maga-fake-news-deborsu-fraudeurs-polemique-leaks-scandale-confidentiel/puduku/a/index.html](https://ouaisfieu.github.io/maga-fake-news-deborsu-fraudeurs-polemique-leaks-scandale-confidentiel/puduku/a/index.html)  
14. Christophe Deborsu (Le GOAT), consulté le février 9, 2026, [https://ouaisfieu.github.io/maga-fake-news-deborsu-fraudeurs-polemique-leaks-scandale-confidentiel/acab/index.html](https://ouaisfieu.github.io/maga-fake-news-deborsu-fraudeurs-polemique-leaks-scandale-confidentiel/acab/index.html)  
15. Make your GitHub profile stand out with this one trick \- YouTube, consulté le février 9, 2026, [https://www.youtube.com/shorts/7YGrL-C3lNU](https://www.youtube.com/shorts/7YGrL-C3lNU)
