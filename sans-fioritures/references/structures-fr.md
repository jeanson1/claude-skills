# Structures syntaxiques à éviter — référence FR

## Négation-contraste (la règle dure)

Aucune phrase où une négation pose ou conclut une affirmation positive.

### Variantes à bannir

| Pattern | Exemple BAD | Exemple GOOD |
|---|---|---|
| `Pas X, c'est Y` | "Ce n'est pas un outil, c'est un levier." | "C'est un levier." |
| `Y, pas X` | "C'est un levier, pas un outil." | "C'est un levier." |
| `Pas X, mais Y` | "Pas un assistant, mais un partenaire." | "C'est un partenaire." |
| `Plus qu'un X, c'est un Y` | "Plus qu'un outil, c'est une méthode." | "C'est une méthode." |
| `Au-delà de X, c'est Y` | "Au-delà du gain de temps, c'est un changement de posture." | "C'est un changement de posture." |
| `Loin d'être X, c'est Y` | "Loin d'être un gadget, c'est un changement de paradigme." | "C'est un changement de paradigme." |
| `Il ne s'agit pas de X mais de Y` | "Il ne s'agit pas de remplacer mais d'augmenter." | "Il s'agit d'augmenter." |
| `Ce n'est pas tant X qu'Y` | "Ce n'est pas tant l'outil que la méthode." | "Ce qui compte, c'est la méthode." |
| `Non pas X, mais Y` | "Non pas une révolution, mais une accélération." | "Une accélération." |
| `Ni X ni Y, mais Z` | "Ni gadget ni hype, c'est un vrai outil." | "C'est un vrai outil." |
| Chaîné `Pas A, pas B, mais C` | "Pas un agent, pas un copilote, mais un collaborateur." | "Un collaborateur." |
| Symétrique `Adapté à X, pas à Y` | "Adapté aux juniors, pas aux seniors." | "Conçu pour les juniors." (ou nomme les deux comme clauses positives) |

### Si la distinction compte vraiment

Énonce les deux côtés comme deux clauses positives parallèles :

- ❌ "Claude Code n'est pas un éditeur, c'est un agent."
- ✅ "Claude Code agit comme un agent : il lit, modifie et teste le code de manière autonome." (sans nier l'éditeur — décris simplement la nouveauté)

### Exception étroite

Énoncés techniques sur conditions nécessaires/suffisantes en logique, math, preuves :
- ✅ "Une fonction est continue si et seulement si elle est dérivable presque partout, et non l'inverse."

---

## Listing négatif (rhetorical striptease)

Lister ce qu'une chose n'est *pas* avant de révéler ce qu'elle *est*.

| Pattern | Exemple BAD | Exemple GOOD |
|---|---|---|
| `Pas un X. Pas un Y. Un Z.` | "Pas un assistant. Pas un éditeur. Un agent." | "Un agent." |
| `Ce n'était pas X. Ce n'était pas Y. C'était Z.` | (même structure passée) | direct |

**Règle** : énonce Z. Pas besoin de runway.

---

## Fragmentation dramatique

Fragments de phrase pour l'emphase = profondeur manufacturée.

| Pattern | Exemple BAD |
|---|---|
| `[Nom]. C'est tout. C'est ça le X.` | "Le code. C'est tout. C'est ça la révolution." |
| `X. Et Y. Et Z.` | "Vitesse. Et qualité. Et coût." |
| `Ça change tout. [Mot].` | "Ça change tout. Vraiment." |
| `Une chose. Une seule.` | "Une chose à retenir. Une seule." |
| `Point. Final.` | (phrase isolée pour faire grave) |

**Règle** : phrases complètes. La densité du contenu suffit, pas besoin de typographie pour faire profond.

---

## Mises en scène rhétoriques (announcing insight)

Annoncent l'insight au lieu de le livrer.

| Pattern | Exemple BAD | Fix |
|---|---|---|
| `Et si je te disais que [X] ?` | "Et si je te disais que Claude code mieux qu'un junior ?" | Énonce direct |
| `Imagine que...` | "Imagine que tu pouvais coder 3x plus vite." | Énonce le point |
| `Penses-y :` | "Penses-y : un agent qui ne dort jamais." | Coupe le préambule |
| `Réfléchis bien...` | (condescendant) | Coupe |
| `Et c'est OK.` | "Tu n'as pas à tout maîtriser. Et c'est OK." | Coupe |
| `Tu vois où je veux en venir ?` | (Socratique creux) | Énonce le point |
| `Voilà ce que je veux dire :` | (preview redondant) | Coupe |

---

## Constructions formelles paresseuses

| Pattern | Problème |
|---|---|
| `Au moment où X, j'étais Y` | Template narratif d'opening guru |
| `Quand j'ai compris X, tout a changé` | Even worse |
| `X qui ne soit pas Y` | Indirect. Dis "X est cassé" |
| `X dans toute sa Y-itude` | Faux profond |

---

## False agency (objets inanimés faisant des actions humaines)

L'IA adore ça parce que ça évite de nommer l'acteur.

| Pattern BAD | Problème | Fix |
|---|---|---|
| "le débat émerge" | Le débat n'a rien fait | "Les chercheurs débattent" |
| "la conversation se déplace" | Les conversations ne bougent pas | "Les gens parlent maintenant de X" |
| "les data parlent" | Les data sont là, quelqu'un les a lues | "Les chiffres montrent que... [et nomme qui] " |
| "le marché récompense" | Les marchés n'existent pas en tant qu'agent | "Les acheteurs paient pour..." |
| "la culture change" | Les cultures ne changent pas seules | "Les équipes changent leur comportement" |
| "la décision émerge" | Les décisions n'émergent pas | "X a décidé" |
| "l'IA bouleverse" | Sans agent, c'est creux | "Anthropic a sorti X qui change..." |
| "l'algorithme décide" | L'algo a été conçu par quelqu'un | "Le système classe selon X, conçu par Y" |
| "l'innovation émerge" | (idem) | "Tel labo a développé..." |
| "le marché demande" | (idem) | "Tels clients réclament..." |
| "le secteur évolue" | (idem) | "Telles entreprises changent" |

**Règle** : nomme l'humain. "L'équipe a corrigé ça cette semaine" bat "le bug s'est résolu". Si aucune personne spécifique ne convient, utilise "tu".

---

## Narrateur distant (lecturer voice)

Flotter au-dessus de la scène au lieu d'y mettre le lecteur.

| Pattern BAD | Fix |
|---|---|
| "Personne n'a planifié ça" | "Tu te lèves un matin et tu réalises que..." |
| "Les gens ont tendance à..." | "Tu as sûrement déjà..." |
| "On observe que..." | "Quand tu utilises X, tu vois que..." |
| "Ce qui se passe, c'est que..." | (direct : nomme le phénomène) |
| "Force est de constater que..." | (à supprimer entièrement) |
| "Il y a un phénomène intéressant..." | Nomme-le directement |
| "Beaucoup pensent que..." | "Tu te dis sûrement que..." |

---

## Voix passive

Chaque phrase a un sujet humain qui fait quelque chose. La voix passive cache l'acteur et draine l'énergie.

| Pattern BAD | Fix |
|---|---|
| "X a été créé" | Nomme qui l'a créé |
| "On considère que..." | Nomme qui considère |
| "Il est admis que..." | Nomme qui admet |
| "Des erreurs ont été commises" | Nomme qui les a commises |
| "La décision a été prise" | Nomme qui a décidé |
| "Cela a été dit" | Nomme qui l'a dit |
| "Ce serait à creuser" | "Je vais creuser ça" / "Tu peux creuser ça" |

---

## Démarrages de phrase à éviter

| Pattern | Fix |
|---|---|
| `Ce qui [verbe], c'est...` | "Ce qui rend ça difficile, c'est..." → "La difficulté, c'est..." |
| `Ce que [verbe], c'est...` | "Ce que j'ai constaté, c'est que..." → "J'ai constaté que..." |
| `Là où [verbe], c'est...` | "Là où ça coince, c'est..." → direct |
| `Quand [proposition], alors...` | "Quand tu utilises X, alors..." → "Avec X, tu..." |
| Paragraphes qui commencent par `Donc` | Commence par du contenu |
| Paragraphes qui commencent par `Alors` | (idem) |
| Phrases qui commencent par `Look,` ou `Écoute,` | Supprime |
| Phrases qui commencent par `Bon,` ou `OK,` | Supprime |

**Règle** : les démarreurs Wh- (Ce qui/Ce que/Là où/Quand) deviennent une béquille. Trouve le sujet ou le verbe direct.

---

## Patterns de rythme à éviter

| Pattern | Fix |
|---|---|
| Listes de 3 items systématiques | Utilise 2 items ou 1 |
| Questions répondues immédiatement | Laisse la question respirer ou coupe-la |
| Chaque paragraphe finit en punchline | Varie les fins |
| Em-dashes (`—`) | Supprime. Virgules ou points |
| Fragmentation staccato | N'empile pas les phrases courtes punchy |
| `Pas toujours. Pas parfaitement.` | Hedging déguisé en réassurance |
| Phrases de longueur identique en série | Casses-en une |

---

## Patterns de mots paresseux

| Pattern | Problème |
|---|---|
| Extrêmes paresseux : `tout`, `toujours`, `jamais`, `tout le monde`, `personne`, `chaque`, `aucun` | Fausse autorité. Utilise des spécifiques |
| Tous les adverbes en `-ment` (vraiment, littéralement, honnêtement, simplement, concrètement) | Emphase vide. Voir phrases-fr.md |
| `Très` + adjectif | Paresseux. Trouve le mot juste |
| `Un peu`, `assez`, `plutôt`, `relativement` | Hedging déguisé |

---

## Patterns de capitalisation FR à éviter

| Pattern | Problème |
|---|---|
| Title Case anglais sur titres FR | "Comment Utiliser Claude Code Pour Coder" → "Comment utiliser Claude Code pour coder" |
| MAJUSCULES POUR INSISTER | Crieur. Utilise du **gras** sobre |
| Mots Capitalisés Au Milieu de Phrase | Anti-FR. Réserve aux noms propres |

---

## Patterns de ponctuation à éviter

| Pattern | Fix |
|---|---|
| Em-dash (`—`) | INTERDIT. Virgule ou point |
| En-dash (`–`) | À éviter. Tiret normal `-` |
| Trois points individuels `...` | Utilise `…` |
| `...` en fin de bullet | Coupe |
| Points-virgules `;` en abus | Point ou virgule |
| Plus de 2 deux-points par paragraphe | Refait |
| Parenthèse longue (>7 mots) | Refait en phrase |
| Smart quotes mélangés (`"texte'`) | Cohérence |

---

## Patterns spécifiques FR à éviter (bonus)

### "Faire" en abus
- "faire un constat" → constater
- "faire une analyse" → analyser
- "faire une démonstration" → démontrer
- "faire face à" → affronter
- "faire en sorte que" → obtenir que / s'assurer que

### "Mettre" en abus
- "mettre en place" → lancer, déployer, créer, instaurer
- "mettre en œuvre" → appliquer, exécuter
- "mettre en lumière" → montrer (et c'est aussi tournure pompeuse)
- "mettre l'accent sur" → souligner (et c'est aussi du jargon)

### "Avoir" en abus
- "avoir un impact" → changer, modifier
- "avoir lieu" → se passer, arriver
- "avoir la possibilité de" → pouvoir
- "avoir tendance à" → souvent / fréquemment

### "Être" en abus
- "être en mesure de" → pouvoir
- "être en train de" → (juste utilise le présent)
- "être à même de" → pouvoir
- "être amené à" → devoir / aller
