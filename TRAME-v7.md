# Trame de la formation IA — v7

Refonte complète de la structure. Document de travail : il sert à valider le découpage
avant d'écrire une ligne d'`index.html`. Établi le 20 novembre 2026.

---

## 1. Les trois règles de la refonte

**Un chapitre par intention, pas par produit ni par fonctionnalité.**
Un chapitre « ChatGPT » et un chapitre « Claude » obligent à tout écrire deux fois, et à
tout réécrire deux fois à chaque changement de nom. Un chapitre « Deep Research » meurt
avec le nom commercial. Un chapitre « chercher sur le web et obtenir des sources
ouvrables » survit aux deux.

**Le stable et le périssable sont séparés physiquement.**
Modèles, prix, noms de menus, paliers d'abonnement : tout part dans une page unique
« État des lieux au JJ/MM/AAAA ». C'est la seule qu'on rouvre tous les six mois. Dans les
34 leçons actuelles, ces faits sont éparpillés partout : c'est pour ça que chaque mise à
jour est un chantier.

**Chaque chapitre du cœur porte un encadré daté à deux colonnes.**
Le principe est dans le corps du texte ; « où ça se clique aujourd'hui » est dans
l'encadré, visuellement distinct, avec sa date. Quand ça change, on remplace l'encadré,
pas le chapitre.

---

## 2. Pourquoi ça tombe maintenant : les deux outils ont convergé

Relevé direct dans les interfaces le 20 novembre 2026 (compte ChatGPT Business et compte
Claude Team de l'utilisateur).

| Ce qu'on veut faire | ChatGPT | Claude |
|---|---|---|
| Contexte permanent | Paramètres → Personnalisation | Paramètres → Your Claude |
| Spécialiser une tâche | **Skills** | **Skills** |
| Brancher ses outils | **Plugins** | **Connectors** |
| Corpus de documents | **Projets** | **Projects** |
| Chercher sur le web | Recherche sur le Web / Recherche approfondie | Web search / Research |
| Doser la profondeur | Effort : Instant → Pro | Effort : Low → Max |
| Produire un livrable | Espace (Pages, Présentations, Feuilles, Images, Sites) | Artifacts + Design |
| Automatiser | **Planifié** | **Scheduled** |
| Déléguer plusieurs étapes | Work, Agents, Codex | Cowork, Code |
| Mode de composition | Chat / **Work** | Chat / **Cowork** |

Mêmes briques, mêmes mots, deux habillages. Les seules divergences de fond : ChatGPT
**cache** le modèle derrière le curseur d'effort (deux modèles au sélecteur), Claude le
**montre** (quatre) ; ChatGPT unifie les livrables dans « Espace », Claude les sépare en
Artifacts et Design.

---

## 3. Carte de migration : 34 leçons → 15 chapitres

| Nouveau chapitre | Reprend les leçons |
|---|---|
| A1 Ce que fait réellement la machine | 12 (partiel), 23 (partiel) |
| A2 Pourquoi elle se trompe avec aplomb | 18 (partiel), 23 |
| A3 Vérifier sans tout recopier | neuf |
| A4 Formuler une demande qui tient | 18 |
| B1 Donner un contexte permanent | 1, 4, 13, 14 |
| B2 Spécialiser par des Skills | 5, 30 |
| B3 Brancher ses outils | 6 (partiel), 24, 26 |
| B4 Travailler sur ses documents | 4, 20, 24, 26 |
| B5 Chercher et exiger des sources | 2, 19 |
| B6 Doser l'effort et ce qu'il coûte | **neuf** |
| B7 Produire un livrable | 9, 15, 21, 22, 26 |
| B8 Déléguer et automatiser | 7, 8, 10, 11, 16, 25, 29, 31 |
| C1 AI Act | 33 |
| C2 Ce qui ne sort jamais du Resort | 34 |
| D État des lieux | 3, 17, 28, 32 |

**Supprimées sans reprise :** 12 à 16 (chapitre produit Claude, redistribué par
intention), 19, 21, 22 (fiches produit Perplexity, ElevenLabs, Google AI Studio :
deviennent des mentions), 17 (ChatGPT vs Claude : devient l'encadré de chaque chapitre).
**Déplacée en annexe :** 27 (demandes Event — c'est un cas, pas une leçon).

---

## PARTIE A — Les fondamentaux

Quatre chapitres quasi intemporels. Aucun nom de produit, aucune capture d'écran.
C'est la partie qu'on ne rouvrira pas dans deux ans.

### A1 — Ce que fait réellement la machine

**Intention du lecteur :** « je veux savoir à quoi j'ai affaire ».

Un modèle de langage prédit la suite d'un texte ; tout le reste — chercher, calculer,
lire un fichier, agir — est un outil branché autour. Pourquoi c'est la bonne image
mentale : elle explique à la fois les réussites et les échecs. Ce que « raisonner » veut
dire concrètement aujourd'hui, et pourquoi ça change la nature des erreurs.

**Piège :** croire que l'outil « sait » ce qu'il a lu hier dans une autre conversation.

**Recyclé de :** 12, 23.

### A2 — Pourquoi elle se trompe avec aplomb

**Intention :** « comment je repère une réponse fausse ».

L'erreur n'est pas un bug : elle a exactement la même forme que la réponse juste. Les
trois familles de fautes — l'invention pure, le détail plausible greffé sur du vrai, le
chiffre recopié de travers. Le signal le plus fiable : plus la demande est précise et
vérifiable, plus la fausse réponse se distingue.

**À ne surtout pas faire :** les exercices « pièges » (l'œuvre inventée, l'erreur de
calcul). Ils ne déclenchent plus sur les modèles actuels, c'est testé.

**Recyclé de :** 18, 23.

### A3 — Vérifier sans tout recopier

**Intention :** « je dois pouvoir signer ce que je rends ».

La règle de proportion : on vérifie à hauteur de l'enjeu, pas systématiquement. Trois
méthodes qui coûtent peu — demander la source et l'ouvrir ; refaire le calcul ailleurs ;
poser la même question autrement et comparer. Ce qui ne se délègue jamais.

**Chapitre neuf.** C'est le manque le plus net de la version actuelle.

### A4 — Formuler une demande qui tient

**Intention :** « pourquoi ma demande donne un résultat tiède ».

Non pas « écrire un bon prompt », mais : dire ce qu'on veut obtenir, donner la matière,
dire ce qui ferait que c'est raté. Trois leviers qui valent tous les autres — le contexte,
le format attendu, le critère de refus.

**Volontairement court.** Ce n'est pas une formation à la formulation.

**Recyclé de :** 18.

---

## PARTIE B — Le cœur : huit chapitres par intention

Gabarit identique pour les huit : *l'intention · le principe · l'encadré daté à deux
colonnes · le piège · un cas du Resort*.

### B1 — Donner un contexte permanent

**Intention :** « j'en ai assez de réexpliquer qui je suis à chaque conversation ».

Trois niveaux empilés, du plus large au plus étroit : les instructions valables partout,
la mémoire qui se remplit toute seule, le projet qui ne vaut que pour un dossier. Ce
qu'on met dans chacun et, surtout, ce qu'on n'y met pas. Comment relire et corriger ce
que l'outil a retenu de travers.

> **Encadré — novembre 2026**
> **ChatGPT** · Paramètres → Personnalisation : Mémoire (activer, Résumé de la mémoire →
> Gérer, éléments mémorisés) et le lien « instructions personnalisées ». Nouveauté :
> « Utiliser mon style d'écriture comme référence ».
> **Claude** · Paramètres → Your Claude : Instructions en texte libre, puis Memory
> (rechercher dans les conversations passées, générer la mémoire, ouvrir et éditer son
> contenu). Entrée « Import memory from other AI providers » pour reprendre le contexte
> accumulé chez l'autre.

**Piège :** écrire ses instructions comme une fiche de poste. Ce qui marche, ce sont les
contraintes de sortie, pas la présentation de soi.

**Recyclé de :** 1, 4, 13, 14.

### B2 — Spécialiser l'assistant par des Skills

**Intention :** « je refais la même tâche vingt fois par mois ».

Une skill, c'est une consigne maison écrite une fois et rappelée automatiquement quand le
sujet revient. Différence avec une instruction permanente : la skill ne se déclenche que
sur son sujet. Différence avec un projet : elle suit la personne, pas le dossier.
Partager une skill à toute l'équipe.

> **Encadré — novembre 2026**
> **ChatGPT** · Personnaliser → Skills. Installables, partageables au niveau de l'espace
> de travail. Les GPT personnalisés sont en fin de vie : une bannière annonce leur
> **retrait au 11 décembre 2026** et propose « Migrer les GPT » vers les plugins.
> **Claude** · Customize → Skills, avec « Yours » et « Discover » et un annuaire Anthropic.

**Action datée :** les GPT du Resort non migrés disparaissent le 11 décembre 2026.

**Piège :** empiler des skills qui se contredisent.

**Recyclé de :** 5 (à réécrire entièrement), 30.

### B3 — Brancher ses outils

**Intention :** « je veux qu'il voie mes mails, mon agenda, mes fichiers ».

Ce qu'un connecteur donne et ce qu'il ne donne pas. La question à se poser avant de
brancher : qui voit quoi, et pendant combien de temps. Les droits héritent de ceux de
l'utilisateur — ce n'est pas une porte dérobée, mais ce n'est pas rien non plus.

> **Encadré — novembre 2026**
> **ChatGPT** · Personnaliser → Plugins, onglets Public et Espace de travail. Catalogue :
> Google Drive, Gmail, Outlook, Slack, Atlassian, Dropbox, SharePoint, Canva… Certains
> facturés en crédits.
> **Claude** · Customize → Connectors (et, à part, Plugins). Dans le composeur : menu « + »
> → Connectors.

**Piège :** brancher un connecteur « pour voir ». Chaque branchement élargit ce qui peut
sortir.

**Recyclé de :** 6, 24, 26.

### B4 — Travailler sur ses propres documents

**Intention :** « j'ai 40 pages de contrat, je veux une réponse sourcée dedans ».

La différence entre joindre un fichier à une question et constituer un corpus durable.
Quand le projet devient le bon réflexe. Ce qui se passe quand le document dépasse ce que
l'outil peut lire d'un coup, et comment le détecter — une réponse qui ne cite que le début.

> **Encadré — novembre 2026**
> **ChatGPT** · Projets dans la barre latérale ; menu « + » → Travailler dans un projet,
> Ajouter depuis la bibliothèque. Connecteur SharePoint pour les documents Microsoft.
> **Claude** · Projects ; menu « + » → Upload or add files, Add to project, Google Drive,
> Add from GitHub.

**Piège :** croire qu'un fichier déposé dans un projet est relu intégralement à chaque
question.

**Recyclé de :** 4, 20, 24, 26.

### B5 — Chercher et exiger des sources

**Intention :** « je veux des faits récents, pas des souvenirs ».

Trois régimes à distinguer : la réponse de mémoire, la recherche web courte, le rapport
approfondi. Lequel pour quoi, et surtout comment obliger à citer — puis pourquoi il faut
ouvrir les liens. La recherche approfondie coûte du temps et du quota : elle se réserve
aux questions dont on relira vraiment les sources.

> **Encadré — novembre 2026**
> **ChatGPT** · menu « + » → Recherche sur le Web, ou Recherche approfondie (« obtenez un
> rapport détaillé »). Les deux coexistent : Deep Research n'a pas disparu.
> **Claude** · menu « + » → Web search, ou Research.

**Piège :** prendre une réponse sourcée pour une réponse vérifiée. Les liens existent, ils
ne disent pas toujours ce que le résumé prétend.

**Recyclé de :** 2 (à corriger), 19 (Perplexity réduit à une mention).

### B6 — Doser l'effort, et ce que ça coûte

**Chapitre entièrement neuf.** Aucun équivalent dans les 34 leçons.

**Intention :** « pourquoi ma réponse est bâclée, et pourquoi j'ai épuisé mon quota ».

Les deux outils exposent désormais un curseur qui arbitre entre vitesse, profondeur et
consommation. C'est un arbitrage à faire plusieurs fois par jour, et personne ne l'a
expliqué à personne. Quand monter : raisonnement en plusieurs étapes, calcul, synthèse de
beaucoup de matière. Quand ne pas monter : reformuler, traduire, répondre à un mail —
l'effort élevé n'améliore rien et coûte cher.

> **Encadré — novembre 2026**
> **ChatGPT** · Le sélecteur de modèle a disparu du composeur, remplacé par « Effort de
> réflexion » à cinq crans : **Instant · Medium · High · Extra High · Pro**. Medium par
> défaut. Pro s'affiche verrouillé ou « limite d'utilisation atteinte » selon les droits du
> siège. Les modèles passent en second rideau : GPT-6 et GPT-5.6 Sol.
> **Claude** · Modèle et effort côte à côte. Modèles : Fable 5.2, Opus 5.5 (défaut),
> Sonnet 5.5, Haiku 5.5. Effort : **Low · Medium (recommandé) · High · Extra · Max**, ce
> dernier étiqueté « 5,5× ou plus de consommation ».

**Piège :** mettre le curseur au maximum « au cas où ». On épuise son forfait sans rien
gagner en justesse sur les tâches simples.

### B7 — Produire un livrable utilisable

**Intention :** « je veux un document, pas une réponse dans une bulle ».

Du texte dans la conversation au livrable qu'on envoie : tableau, note, présentation, page
web, image. Ce qui se reprend dans Word ou Excel sans tout reformater. Quand une page web
interactive vaut mieux qu'un document figé. Les livrables se stockent et se partagent : ils
ne meurent plus avec la conversation.

> **Encadré — novembre 2026**
> **ChatGPT** · « Espace » dans la barre latérale, onglets Tout, Pages, Présentations,
> Feuilles de calcul, Images, Sites. Partageable. Menu « + » → Créer une image, Dessiner.
> **Claude** · Artifacts dans la barre latérale, et Design pour le visuel. Menu « + » →
> Design system.

**Piège :** demander « fais-moi un beau document » sans dire à qui il s'adresse ni ce qu'il
doit déclencher.

**Recyclé de :** 9, 15, 21, 22, 26.

### B8 — Déléguer et automatiser

**Intention :** « je veux qu'il fasse, pas qu'il explique comment faire ».

Trois degrés, du plus encadré au plus autonome : le mode de travail sur plusieurs étapes
(sous surveillance), la tâche planifiée qui tourne sans personne, l'agent qui agit dans des
outils tiers. La règle commune : **on automatise un geste qu'on sait déjà faire à la main
et dont on sait reconnaître le résultat faux.** Ce qui ne s'automatise jamais : ce qui
engage le Resort vis-à-vis d'un tiers sans relecture.

> **Encadré — novembre 2026**
> **ChatGPT** · Commutateur Chat / **Work** dans le composeur. « Planifié » dans la barre
> latérale (tâches, états En pause / Terminée). Agents et Codex dans le menu de débordement.
> **Claude** · Commutateur Chat / **Cowork**. « Scheduled » dans la barre latérale.
> Paramètres → Code et Cowork.

**Piège :** laisser tourner une tâche planifiée dont plus personne ne lit la sortie.

**Recyclé de :** 7, 8, 10, 11, 16, 25, 29, 31.

---

## PARTIE C — Le cadre

### C1 — AI Act : ce qui s'applique, ce qui arrive

Les obligations réellement opposables à une entreprise utilisatrice — pas le texte
intégral. L'échéance du marquage des contenus au 2 décembre 2026. Ce que l'omnibus a
décalé.

**Recyclé de :** 33, à réviser.

### C2 — Ce qui ne sort jamais du Resort

Les catégories de données à ne jamais déposer, et pourquoi la règle ne dépend pas de
l'outil. Le cas particulier des connecteurs, qui déplacent la question : ce n'est plus ce
qu'on colle, c'est ce qu'on autorise à lire.

**Recyclé de :** 34, à compléter.

---

## PARTIE D — État des lieux au 20 novembre 2026

Page unique, périssable, assumée comme telle. Bandeau en haut : « cette page est à jour au
JJ/MM ; le reste de la formation ne dépend pas d'elle ».

Contenu : les modèles disponibles chez chaque éditeur ; les paliers d'effort et leurs noms ;
ce qui a disparu ou changé de nom depuis six mois ; les quotas par type de siège ; les
échéances connues.

---

## 4. Ce qui reste à trancher

1. **La formation est publique** (GitHub Pages, dépôt `resortnamur/formation-IA`). Les cas
   du Resort restent-ils génériques (« un avis client », « un contrat »), ou garde-t-on les
   cas nommés comme l'actuelle leçon 27 ? Recommandation : génériques.
2. **Le sort de la leçon 27** (demandes Event) : annexe, ou suppression ?
3. **Copilot** : trois leçons actuelles. Troisième colonne dans les encadrés, ou chapitre
   unique en annexe ? Recommandation : troisième colonne, et seulement là où il est
   réellement utilisé.
4. **L'atelier des 11 chantiers** (`exercices.html`) n'est pas touché : il est construit sur
   la rigueur, pas sur des fonctionnalités, et ne vieillit pas de la même façon.

## 5. État des vérifications

- **Vérifié en interface le 20/11/2026** : tous les encadrés ChatGPT et Claude ci-dessus.
- **Non vérifié** : le tableau des retraits fourni par ChatGPT (Canvas, Pulse, Atlas,
  Advanced Voice au 11/12, GPT-5.5 retiré le 14/10). Plausible — Atlas est déjà cité dans
  la leçon 28 actuelle — à recouper sur les notes de version avant d'écrire la partie D.
- **Non vérifié** : les quotas Pro annoncés par ChatGPT (15 messages/mois en Business
  Standard, 50/semaine en Premium).
- **Contredit par l'interface** : ChatGPT présente « GPT-6 Pro » comme un modèle distinct ;
  dans le sélecteur réel, Pro est le cinquième cran d'effort, pas un modèle.
- **Omission de ChatGPT** : sa réponse ne mentionne nulle part les Skills, alors qu'elles
  existent et qu'une skill du Resort est déjà partagée dans l'espace de travail.
- **Pas encore regardé** : Copilot.
