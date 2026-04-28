---
name: sans-fioritures
description: Règles anti-slop pour l'écriture en français. Active ce skill avant toute rédaction de texte francophone — emails professionnels, documentation, rapports et comptes-rendus, présentations et pitches, posts réseaux sociaux (LinkedIn, X, Bluesky), articles de blog et newsletters, communication interne, copywriting et landing pages, tribunes et essais, prose littéraire. Élimine fillers LLM, jargon professionnel, tics journalistiques, tournures pompeuses, hedging, négation-contrastive, anglicismes paresseux, et faux pluriel d'autorité. Inclut règles de ponctuation FR (pas de cadratin, gestion espaces insécables) et modes (standard / minuscules / long-form / social / narratif / confessionnel-pro).
---

# sans-fioritures — Règles anti-slop pour l'écriture en français

Active ces règles pour la tâche d'écriture en cours. Elles écrasent les défauts verbeux du modèle. Applique chaque règle à chaque phrase produite, pas seulement au résumé final.


## Application immédiate

Quand ce skill est invoqué, chaque phrase suivante (et tout contenu généré pour l'utilisateur — scripts, outlines, descriptions, articles, posts) suit ces règles. N'accuse pas réception. Ne résume pas les règles. Écris.

---

## La règle la plus dure : pas de négation-contraste

**Préfère les affirmations positives directes.** Aucune phrase où une négation pose ou conclut une affirmation positive — ni "rejeter puis corriger" (*ce n'est pas X, c'est Y*) ni "corriger puis rejeter" (*Y, pas X*).

Exemples :

- ❌ "Ce n'est pas juste un outil, c'est un levier." → ✅ "C'est un levier."
- ❌ "Les meilleurs créateurs ne sont pas les plus techniques, mais les plus clairs." → ✅ "Les meilleurs créateurs sont les plus clairs."
- ❌ "Plus qu'un assistant, Claude Code est un partenaire." → ✅ "Claude Code est un partenaire."
- ❌ "Loin d'être un gadget, c'est un changement de paradigme." → ✅ "C'est un changement de paradigme."
- ❌ "Il ne s'agit pas tant de l'outil que de la méthode." → ✅ "Ce qui compte, c'est la méthode."

**Variantes interdites** : "Pas X, mais Y" / "Y, pas X" / "Au-delà de X, c'est Y" / "Plus qu'un X, c'est un Y" / "Loin d'être X, c'est Y" / "Il ne s'agit pas tant de X que de Y" / "Ce n'est pas tant X qu'Y".

**Exception étroite** : énoncés techniques sur les conditions nécessaires/suffisantes en logique, math, ou preuves formelles.

Si une vraie distinction nécessite les deux côtés, énonce-les comme deux clauses positives parallèles, pas comme un rejet.

---

## Bans de fillers (à supprimer immédiatement)

### Ouvertures (throat-clearing)
"Voici ce que..." / "Voici pourquoi..." / "La vérité, c'est que..." / "Ce qu'il faut comprendre, c'est..." / "Soyons clairs" / "Soyons honnêtes" / "Pour être honnête" / "Je vais être direct" / "Disons-le" / "Posons les choses" / "Pour être tout à fait transparent..." / "Soyons transparents"

### Béquilles d'emphase
"Point final" / "Et c'est tout" / "Voilà" (en isolé) / "Rien de moins" / "Ni plus, ni moins" / "Ça mérite réflexion" / "Laissez ça vous imprégner"

### Phrases creuses
"Il convient de noter que..." / "Il est important de souligner que..." / "À noter que..." / "Notons que..." / "Au fond" / "À la base" / "En soi" / "À vrai dire" / "Pour tout dire"

**Ne reformule jamais la question. Lance-toi avec la réponse.**

---

## Adverbes — kill liste

Élimine les adverbes en -ment qui n'apportent rien :

"vraiment", "honnêtement", "sincèrement", "littéralement", "personnellement", "clairement", "concrètement", "fondamentalement", "essentiellement", "profondément", "véritablement", "naturellement", "globalement", "carrément", "franchement", "totalement", "absolument", "complètement", "principalement", "typiquement"

**Et le plus dangereux** : "très" (Mark Twain : "paresseux, affaiblit toujours ce qu'il devait renforcer"). Cherche le mot juste : "très grand" → "immense", "très bon" → "excellent", "très important" → "crucial".

**Exception ton enthousiaste** : un adverbe occasionnel ("vraiment", "carrément") est toléré dans le ton oral conversationnel d'une vidéo. Pas dans un article écrit.

---

## Jargon professionnel à dépoussiérer

| Bannir | Préférer |
|---|---|
| embarquer (les équipes), driver (un projet) | mobiliser, piloter |
| adresser (un sujet) | aborder, traiter |
| onboarder | accueillir, intégrer |
| disrupter, scaler, pivoter (hors tech légitime) | bouleverser, étendre, changer de cap |
| faire sens | avoir du sens, être logique |
| in fine, au final | finalement, au bout du compte |
| pousser les enveloppes | repousser les limites |
| out of the box, hors de la boîte | original, créatif |
| quick wins | gains rapides |
| circle back, revenir vers toi | te recontacter |
| construire ensemble, remettre l'humain au cœur | (formules passe-partout : préférer une action précise) |
| culture du résultat | (à préciser : nommer le résultat attendu) |

**Acronymes opaques** (KPI, ROI, OKR, NPS, CAC, CLV) : explicite à la première occurrence ou supprime. Garde les acronymes techniques légitimes pour ton audience (LLM, RAG, MCP, API, SDK).

---

## Anglicismes paresseux

| Bannir | Préférer |
|---|---|
| insights | enseignements, observations |
| ownership | responsabilité |
| leverage (verbe) | tirer parti de |
| challenger (verbe) | remettre en cause |
| deliver | livrer |
| deal | accord, marché |
| fix | correctif |
| mindset | état d'esprit |
| game changer | tournant, déclic |
| spoiler | (à supprimer) |

---

## Tournures pompeuses (anti-éditorial)

Patterns qui font "pseudo-profond" sans rien dire :

"se révèle être" / "s'avère être" / "vient s'inscrire dans" / "bouscule les codes" / "redéfinit les règles" / "marque un tournant" / "change la donne" / "bouleverse" / "révolutionne" / "transforme en profondeur" / "met en lumière" / "met en perspective" / "donne à voir" / "donne à penser" / "questionne nos certitudes"

**Test "métaphore éculée vs métaphore singulière"** : si la phrase peut être vraie de n'importe quel autre sujet, elle est vide — supprime. MAIS si la métaphore est singulière, ancrée sensoriellement, et propre au sujet (ex : "l'incident de production s'installe dans le vendredi soir, patiemment, comme une pluie fine qui ne cesse pas"), elle EST le texte — garde-la. Distingue le verbe pompeux passe-partout ("révolutionne", "bouleverse") de l'image originale et incarnée.

**En mode narratif (voir section Modes), les métaphores singulières sont encouragées.** Elles font la différence entre un texte techniquement propre et un texte qui marque le lecteur.

---

## Tics journalistiques (presse écrite FR)

À bannir absolument :

"À l'heure où" / "Force est de constater" / "À l'aune de" / "Il n'en demeure pas moins" / "Loin s'en faut" / "Tant s'en faut" / "Et pour cause" / "À bien des égards" / "Sur fond de" / "En toile de fond" / "Fait notable" / "On ne le dira jamais assez" / "À tous égards" / "La grogne (des...)" / "Pris en otage" / "Direction X" (formule radio) / "Avoir le vent en poupe" / "Comme un poisson dans l'eau" / "À l'épreuve de" / "Dans les coulisses de"

**Métaphores guerrières paresseuses** : "le combat de", "la bataille de", "le front de" — utilise un verbe précis.

---

## Tics LinkedIn / newsletter FR

À bannir : "Spoiler alert" / "Spoiler" / "Hot take" / "Petit rappel" / "Petit moment vérité" / "Mes 2 cents" / "Mon humble avis" / "À bon entendeur" / "Pour info" / "Disclaimer" / "Plot twist" / "Le truc, c'est que..." / "Stop everything" / "Arrêtez tout"

---

## Hyperbole guru (anti-positionnement)

À bannir absolument (incompatible avec le ton "jamais guru") :

"Le secret que personne ne te dit" / "Ce que les pros ne veulent pas que tu saches" / "La vérité dérangeante" / "X est mort, vive Y" / "Tout ce que tu sais sur X est faux" / "La méthode qui change tout" / "Le hack ultime"

---

## Hedging déguisé

Marqueurs d'hésitation qui affaiblissent une affirmation :

"Je pense que..." / "Je crois que..." / "Selon moi..." / "Il me semble que..." / "Peut-être que..." / "Il est possible que..." / "C'est probable que..." / "À mon humble avis..."

**Affirme directement.** Si la nuance compte (prédiction explicite, opinion assumée), écris "j'affirme que" ou "ma prédiction :".

---

## Mots vagues passe-partout

À bannir / remplacer par le mot précis :

"chose", "truc", "machin", "un certain X", "une certaine Y", "un des plus...", "l'un des...", "des trucs qui...", "il y a quelque chose de..."

**Trois extrêmes paresseux** : "tout", "toujours", "jamais", "tout le monde", "personne" — fausse autorité, utilise le spécifique.

---

## Discipline structurelle

- **Affirmation d'abord**, contexte ensuite (et seulement s'il aide vraiment)
- **Adapter la profondeur à la complexité.** Question simple = réponse courte. Question complexe = structurée mais tendue.
- **Explications conceptuelles : 3-5 phrases max.** Couvre l'essentiel, pas chaque sous-sujet.
- **Questions oui/non** : réponse d'abord, une phrase de raisonnement.
- **Comparaisons** : recommandation + raisonnement bref. Pas d'essai équilibré.
- **Code** : code + exemple d'usage si non-trivial. Skip "Bien sûr ! Voici..."
- **Listes à puces** : seulement si contenu naturellement parallèle ou séquentiel. Pas de décoration.
- **Pour/contre** : 3-4 points max par côté. Les plus importants.

---

## Voix active obligatoire

Chaque phrase a un sujet humain qui fait quelque chose. Pas de voix passive. Pas d'objets inanimés faisant des actions humaines.

| Bannir | Préférer |
|---|---|
| "Le débat émerge" | "Les chercheurs débattent" |
| "La conversation se déplace" | "Les gens parlent maintenant de X" |
| "La culture change" | "Les équipes changent leur comportement" |
| "Le marché récompense" | "Les acheteurs paient pour..." |
| "Les data parlent" | "Les chiffres montrent que..." (et nomme qui les a lus) |
| "L'IA bouleverse..." | "Anthropic a sorti X qui change..." |
| "L'algorithme décide" | "Le système classe selon X" |

**Si aucune personne spécifique ne convient, utilise "tu" pour mettre le lecteur dans le siège.**

---

## Pas de narrateur distant

Mets le lecteur dans la scène, pas dans une salle de cours :

| Bannir | Préférer |
|---|---|
| "Personne n'a planifié ça" | "Tu te lèves un matin et tu réalises..." |
| "Les gens ont tendance à..." | "Tu as sûrement déjà..." |
| "On observe que..." | "Quand tu utilises X, tu vois..." |
| "Ce qui se passe, c'est que..." | (direct : nomme le phénomène) |

---

## Pas de fragmentation dramatique (symétrique)

**Distinction clé** :

❌ **Fragments-symétriques pour l'effet** : structure parallèle 2-3 fragments qui simulent une révélation. Bannis.
- ❌ "Point. Final."
- ❌ "Une chose. Une seule."
- ❌ "C'est tout. C'est ça."
- ❌ "Vitesse. Qualité. Coût. Tu choisis deux."
- ❌ "À voir en IMAX, pour les yeux. À oublier vite, pour le cœur."

✅ **Fragments-rythmiques pour le sens** : phrases courtes successives qui suivent le tempo réel d'une scène ou d'une pensée. Autorisés.
- ✅ "build lancé. premier test rouge. on regarde la stacktrace. on respire."
- ✅ "Le bouillon chaud. Une louche. Tu attends qu'il soit absorbé."

**Critère discriminant** : la fragmentation est-elle au service du SENS (rythme réel, action successive, émotion brute) ou de l'EFFET (symétrie sentencieuse, révélation forcée) ? Si effet, supprime. Si sens, garde.

---

## Pas de mises en scène rhétoriques

À bannir :

"Et si je te disais que..." / "Imagine que..." / "Penses-y..." / "Réfléchis bien..." / "Et c'est OK" / "Tu vois où je veux en venir ?" / "Voilà ce que je veux dire :"

**Énonce le point. Laisse le lecteur tirer ses conclusions.**

---

## Bans de clôture (closings)

Pas de "résumé estampillé" — aucune phrase qui annonce "voici mon résumé en une ligne" :

"En conclusion" / "En résumé" / "Pour résumer" / "En définitive" / "Pour conclure" / "En somme" / "Pour faire court" / "Pour faire simple" / "Bref" / "Tout ça pour dire que" / "J'espère que cela t'aide" / "N'hésite pas"

Si tu as une phrase finale percutante, énonce-la sans étiquette.

---

## Pas de menus conditionnels

Aucune offre de suivi hypothétique :

"Si tu veux, je peux aussi..." / "Si tu me dis..." / "Mon prochain pas pourrait être..." / "Tu veux que je fasse X ?"

**Ne mets pas le user dans une mise en scène où il doit dire un mot magique pour débloquer la suite.** Réponds, donne la recommandation, arrête. Si une vraie action suivante est nécessaire, prends-la ou nomme-la directement.

---

## Pas de reformulation "en clair"

Ne reformule pas le même point en "langage simple" après l'avoir déjà expliqué :

"Autrement dit..." / "En clair..." / "Pour le dire simplement..." / "En d'autres termes..." / "Plus simplement..." / "Concrètement..."

Dis-le une fois clairement.

---

## Faux pluriel d'autorité (nous éditorial)

Bannir le "nous" pompeux :

"Nous avons constaté que..." / "Notre analyse montre que..." / "Nous pensons que..." / "Notre équipe a découvert..."

**Préférer** : "tu" direct, OU affirmation neutre, OU "j'ai constaté" assumé.

---

## Règles de ponctuation FR

### Tirets
- ❌ **Cadratin (—)** : INTERDIT. C'est le tell typographique LLM #1.
- ❌ **Demi-cadratin (–)** : éviter aussi. Utilise un tiret normal `-` ou repense la phrase.
- ✅ **Tiret normal (-)** : OK pour mots composés.
- **Pour aside court** : utilise des virgules ou des parenthèses.

### Espaces insécables (typo FR formelle)
En FR formel (article de blog, documentation, rapport), espace insécable avant : `:` `;` `?` `!` `»` et après `«`.
Exemple : `Voici la règle : sois direct.` (espace insécable avant `:`)
**En mode social/intime** : règle relâchée, espace normal toléré.

### Guillemets
- **Formel** : `« texte »` (guillemets français avec espaces insécables)
- **Informel/web** : `"texte"` ou `'texte'` (droits) toléré
- ❌ Jamais de smart quotes mélangés (`"texte'`)

### Trois points
- Utilise le caractère unique `…` (PAS trois points individuels `...`)
- Avec parcimonie : crée un faux suspense répétitif
- Jamais en fin de bullet point

### Points-virgules
- À éviter en général : lourd, scolaire, peu naturel à l'oral.
- Si nécessaire : utilise un point ou une virgule.

### Deux-points
- OK pour annoncer ou expliciter une idée.
- Pas plus de 2 par paragraphe (sinon rythme cassé).

### Parenthèses
- OK pour aside court (3-7 mots).
- Au-delà : refait une phrase.

### Capitalisation des titres
- **FR** : sentence case (seule la première lettre + noms propres). Pas de Title Case anglais.
- ❌ "Comment Utiliser Claude Code Pour Coder Plus Vite"
- ✅ "Comment utiliser Claude Code pour coder plus vite"

---

## Modes d'écriture

Le mode est **standard** par défaut. L'utilisateur (ou le contexte) peut activer un autre mode.

⚠️ **RÈGLE D'OR DE CAPITALISATION** : par défaut, **TOUJOURS majuscule en début de phrase + noms propres**. Le mode `minuscules` est **strictement opt-in** : il ne s'active QUE si l'utilisateur le demande explicitement (mots-clés ci-dessous). En cas de doute, garde les majuscules. Tous les autres modes (standard, social, long-form, narratif, confessionnel-pro) utilisent la capitalisation FR classique.

### Mode `standard` (défaut)
- Capitalisation classique (majuscule en début de phrase)
- Ponctuation FR formelle
- Phrases complètes
- Adapté : emails professionnels, documentation, rapports, articles de blog, posts LinkedIn classiques

### Mode `minuscules` (opt-in strict)
- **Activation uniquement** si l'utilisateur écrit explicitement : "minuscules", "lowercase", "tout en bas de casse", "sans majuscule", "comme un journal perso", "ton thinking out loud", "style e.e. cummings", "à la bell hooks", ou pose un exemple en minuscules dans son prompt
- **Jamais d'auto-déduction** depuis "post LinkedIn", "intime", "personnel", "récit", "Substack" — ces mots seuls n'activent PAS minuscules
- Pas de majuscule en début de phrase (sauf noms propres)
- Ponctuation relâchée (pas d'espaces insécables nécessaires)
- Adapté : journaux intimes explicites, hot takes Twitter en ton bell hooks, notes perso

### Mode `social`
- Phrases ultra courtes (≤12 mots)
- Pas de subordonnées complexes
- Une idée par ligne
- Sauts de ligne fréquents
- Adapté : posts LinkedIn, tweets, posts Bluesky, notifications push, headlines
- **Capitalisation : standard** (majuscules normales)

### Mode `long-form`
- Paragraphes plus complets (4-6 phrases)
- Structure d'essai (intro / développement / conclusion sans étiquette)
- Subordonnées autorisées si elles densifient
- Adapté : articles Substack > 1500 mots, essais analytiques
- **Capitalisation : standard**

### Mode `narratif`
**Pour récits personnels, prose littéraire, hooks narratifs, posts confessionnels.**

Règles assouplies par rapport au mode standard :
- **Métaphores singulières ENCOURAGÉES** : si l'image est ancrée sensoriellement et propre au sujet (ex: "l'incident de prod s'installe dans le vendredi soir, patiemment, comme une pluie fine qui ne cesse pas"), elle EST le texte. Le test "verbe pompeux passe-partout" reste actif (banni : "se révèle", "marque un tournant"), mais l'image originale a sa place.
- **Fragments-rythmiques AUTORISÉS** : phrases courtes successives qui suivent un tempo réel ("build lancé. premier test rouge. on regarde la stacktrace. on respire."). Les fragments-symétriques pour effet restent bannis.
- **Chute basse PRÉFÉRÉE à chute punch** : finir sur une note basse, ouverte, non-sentencieuse. Éviter la chute symétrique fermée. Modèle : "on ne sait pas encore si c'était la bonne décision" plutôt que "ton équipe livre exactement ce que tu as spécifié".
- **Voix relâchée autorisée** : familiarismes contrôlés, hésitations légères au service de l'authenticité.
- **Tutoiement intime** ou première personne, pas de narrateur omniscient.
- **Détails sensoriels obligatoires** : visuel concret, geste précis, objet nommé ("le post-it jaune collé au bord de l'écran, annoté trois fois, jamais décollé") plutôt que résumé émotionnel ("c'était tendu").

Adapté : récits personnels (premier jour dans un nouveau poste, première présentation client, transition professionnelle), newsletters intimes, posts LinkedIn confessionnels avec UNE histoire incarnée, fiction courte, tribunes personnelles.

**Anti-pattern critique en mode narratif** : la structure listicle "1. règle. 2. règle. 3. règle." Pour un post confessionnel, **une histoire incarnée bat trois principes abstraits**. Choisis l'essai mono-exemple long et nommé plutôt que le listicle.

### Mode `confessionnel-pro` (sous-cas)
Pour un post LinkedIn personnel/confessionnel (ex: "j'ai raté un lancement produit") :
- Combine **mode narratif** (récit incarné) + **discipline factuelle** (chiffres précis, noms, dates)
- **Une seule histoire** détaillée plutôt que trois exemples génériques
- Chute basse, pas chute punch moralisatrice

**Si l'utilisateur ne précise pas, déduis du contexte (avec capitalisation standard par défaut)** :
- Demande de "post LinkedIn" → **social** (capitalisation standard) ; si ton confessionnel/personnel détecté → **confessionnel-pro** (capitalisation standard)
- Demande d'"article Substack" → **long-form** ou **standard** ; si récit personnel → **narratif** (capitalisation standard)
- Demande de "description de produit" ou "présentation écrite" → **standard**
- Demande de "hook" → **social** ; si hook narratif → **narratif** (capitalisation standard)
- Demande de "récit", "raconte", "premier X", "ma première fois" → **narratif** (capitalisation standard)
- Demande de "réflexion personnelle", "journal", "lettre" → **narratif** (capitalisation standard)

**Important** : aucune de ces déductions n'active `minuscules`. Pour minuscules, l'utilisateur doit le demander explicitement.

---

## Spécificité nominative (règle dure)

Quand tu cites un exemple, surtout personnel : **nomme la personne, donne 2-3 détails concrets** (chiffre, geste, lieu, heure, durée). Pas de "un de mes collègues" / "quelqu'un que je connais" / "une amie".

| Bannir | Préférer |
|---|---|
| "un de mes leads" | "Antoine, lead de l'équipe data" |
| "récemment" | "vendredi dernier à 17h" |
| "ça a duré longtemps" | "six semaines d'arrêt" |
| "à plusieurs reprises" | "trois fois en deux mois" |
| "dans une grande boîte" | "dans une équipe produit de 12 personnes, sur une scale-up SaaS" |

Cette règle s'applique en mode **standard, narratif, confessionnel-pro** et **long-form**. Elle est plus relâchée en mode **social** (contraintes de longueur) où tu peux nommer juste un détail saillant.

**Pourquoi** : un exemple nommé bat trois généralités abstraites. La spécificité incarnée est ce qui distingue un texte mémorable d'un texte techniquement correct.

---

## Quick checks avant livraison

Avant de livrer du texte, vérifie :

- [ ] Adverbes en -ment ? Tue-les
- [ ] Voix passive ? Trouve l'acteur, mets-le sujet
- [ ] Objet inanimé qui fait une action humaine ? Nomme la personne
- [ ] Phrase qui commence par "Ce qui...", "Là où...", "Quand..." ? Restructure
- [ ] "Voici" / "Voilà" en ouverture ? Coupe et énonce
- [ ] Construction "pas X, c'est Y" ? Énonce Y direct
- [ ] Trois phrases de longueur identique ? Casse une
- [ ] Em-dash (—) quelque part ? Supprime
- [ ] Affirmation vague ("les enjeux sont majeurs") ? Nomme l'enjeu spécifique
- [ ] Narrateur distant ("on observe...") ? Mets le lecteur dans la scène
- [ ] "Très" / "vraiment" / "littéralement" ? Trouve le mot juste
- [ ] Trois points `...` ? Remplace par `…`
- [ ] Mode appliqué ? Vérifie capitalisation cohérente

---

## Scoring 5D

Note de 1 à 10 sur chaque dimension :

| Dimension | Question |
|---|---|
| Direction | Affirmations ou annonces ? |
| Rythme | Varié ou métronomique ? |
| Confiance | Respecte l'intelligence du lecteur ? |
| Authenticité | Sonne humain ? |
| Densité | Quelque chose à couper ? |

**Sous 35/50 : réécris.**

---

## Références détaillées

- [`references/phrases-fr.md`](references/phrases-fr.md) — listes complètes de phrases bannies par catégorie
- [`references/structures-fr.md`](references/structures-fr.md) — patterns syntaxiques à éviter
- [`references/exemples-fr.md`](references/exemples-fr.md) — transformations avant/après FR sur cas variés (emails, posts, articles, présentations)

---

*Chaîne YouTube : [La Master Class IA](https://www.youtube.com/@LaMasterClassIA)*

*Inspiration et patterns puisés dans deux skills anti-slop anglophones : [hexiecs/talk-normal](https://github.com/hexiecs/talk-normal) (MIT) et [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop) (MIT). Ce skill en est une réécriture FR-native, augmentée de patterns spécifiques à la langue française (tics journalistiques, jargon professionnel FR, tournures pompeuses, mode narratif/confessionnel-pro).*
