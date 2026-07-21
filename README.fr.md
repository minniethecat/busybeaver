<div align="center">

# 🦫 BusyBeaver

### Une base de connaissances native pour agents des grands classiques de l'humanité

*Les grands livres du monde, décomposés en connaissances traçables et composables — conçus pour les agents IA, pas seulement pour les humains.*

**~500 livres · ~50 000 Memes · chaque affirmation traçable jusqu'à sa source**

<sub>🌐 [English (official)](./README.md) · [简体中文](./README.zh.md) · [Español](./README.es.md) · **Français** · [Deutsch](./README.de.md) · [日本語](./README.ja.md)</sub>

<sub>Ce README est proposé dans plusieurs grandes langues. La **version anglaise (English version) fait foi et constitue la version officielle.**</sub>

</div>

---

## Qu'est-ce que BusyBeaver ?

BusyBeaver est une base de connaissances construite par des LLM dont la mission est de prendre les connaissances qui comptent le plus pour l'humanité — les classiques, tirés principalement de livres — et de les transformer en une base de connaissances **conviviale pour les agents**.

Nous procédons en décomposant la connaissance en fragments petits, distribuables et richement sémantiques. Nous appelons chaque fragment un **Meme**.

> Le mot **Meme** a été inventé par le biologiste britannique **Richard Dawkins** dans *The Selfish Gene* (Le Gène égoïste, 1976), où il le définit comme **l'unité de base de la transmission culturelle**. BusyBeaver prend l'idée au pied de la lettre : un Meme est une unité de connaissance assez petite pour voyager, se répliquer et se recombiner.

- Chaque **Meme** porte ses propres **métadonnées**.
- Chaque **Meme** peut être **interrogé**.
- Les **Memes** peuvent être **librement composés** en wikis, briefings ou réponses.

Ce dépôt est un **dump** : la décomposition memifiée de plusieurs centaines de livres classiques. Ce corpus **croît rapidement** — notre premier jalon est **10 000 livres**.

> **Pourquoi « Busy Beaver » ?** En théorie de la calculabilité, la **fonction Busy Beaver** est l'archétype de la fonction qui **croît le plus vite** — elle dépasse tout ce qui est calculable. C'est l'ambition derrière ce nom : une **super base de connaissances** pour le monde des agents à venir, croissant aussi vite que possible.

Si vous pointez un agent vers BusyBeaver, il digère les classiques *nettement plus vite*, car le travail difficile — découper le texte, l'analyser et le relier — est déjà fait.

---

## Pourquoi BusyBeaver existe

Nous voulons prolonger la promesse inachevée du **Web sémantique** et des **graphes de connaissances**, tout en nous affranchissant des limites de la pile classique de représentation des connaissances.

Le changement crucial : **le consommateur de connaissance est désormais un agent.**

De ce fait, la connaissance n'a plus besoin d'être encodée en triplets RDF ou en expressions de logique formelle. Elle peut plutôt prendre la forme que les agents consomment le mieux — des **phrases en langage naturel, sémantiquement riches, associées à des métadonnées**, découpées en fragments qu'un agent peut librement diviser, recombiner et sur lesquels il peut raisonner.

> La représentation classique des connaissances forçait le sens humain à passer par une grammaire formelle étroite.
> BusyBeaver conserve le sens dans le langage, et laisse la structure vivre dans les métadonnées.

---

## Filiation et travaux antérieurs

BusyBeaver s'appuie sur les épaules des grands projets de connaissance structurée qui l'ont précédé. Nous devons une dette particulière à :

- **[Wikidata](https://www.wikidata.org/)** — des connaissances collaboratives, multilingues et lisibles par machine, à grande échelle.
- **[DBpedia](https://www.dbpedia.org/)** — l'extraction de connaissances structurées à partir des encyclopédies du monde.
- **[Freebase](https://en.wikipedia.org/wiki/Freebase_(database))** — un graphe ouvert d'entités et de relations.
- **[Semantic MediaWiki](https://www.semantic-mediawiki.org/)** — l'introduction de structure sémantique au sein même du wiki.

Pour construire BusyBeaver, nous avons conçu notre propre **nouvelle méthode de wiki sémantique** — une méthode où l'unité de connaissance est un Meme ancré dans sa source et consommable par des agents, plutôt qu'un triplet rigide. Cette méthode sera **publiée en open source séparément**.

---

## Le problème difficile : hallucination et provenance

La partie la plus difficile de la construction d'une base de connaissances avec des LLM est **la détection et le contrôle des hallucinations**.

La réponse de BusyBeaver est le **contrôle de la provenance**. Nous préservons l'*origine* de la connaissance aussi fidèlement que possible, de sorte que **chaque affirmation puisse être retracée jusqu'à sa source** — généralement un passage précis d'un livre précis.

Chaque source de connaissance se voit attribuer un **PN — un Purple Number**.

> Le Purple Number incarne **l'idéal de Doug Engelbart** : que *chaque élément de connaissance dans le monde ait une adresse.*

Avec les PN, une affirmation dans BusyBeaver n'est jamais un énoncé flottant. Elle est ancrée — adressable, vérifiable et citable jusqu'à sa source.

---

## Anatomie d'un Meme

Un Meme est l'unité atomique de BusyBeaver. Sur le plan conceptuel, chaque Meme regroupe :

| Partie | Description |
| --- | --- |
| **Assertion** | Un énoncé de connaissance autonome, en langage naturel, sémantiquement riche. |
| **Métadonnées** | Type, sujet, entités, relations et autres signaux structurés pour la recherche et la composition. |
| **Provenance (PN)** | Un Purple Number ancrant l'assertion à son passage source, afin que l'affirmation reste traçable. |

Parce que chaque Meme est petit, auto-descriptif et ancré dans sa source, les Memes sont **distribuables** (on peut en partager un sans expédier tout le livre) et **composables** (on peut en assembler plusieurs pour former une page de wiki, un briefing ou une réponse).

---

## Pourquoi une base de connaissances, et pas simplement du texte brut ?

Si les agents savent lire, pourquoi ne pas simplement leur fournir les livres ? Parce que BusyBeaver offre deux choses que le texte brut ne peut pas offrir :

### 1. Un cadre de provenance pour contrôler l'hallucination
Renvoyer du texte brut à travers un LLM rouvre la porte au plus grand défaut des bases de connaissances fondées sur les LLM : **l'hallucination**. BusyBeaver enveloppe chaque affirmation dans un **suivi de provenance** — chaque affirmation est ancrée par son PN au passage source dont elle provient. Cela vous donne un cadre pour *vérifier* ce que votre agent vous dit, au lieu de le prendre pour argent comptant.

### 2. Un squelette sémantique prêt à l'emploi
Nous avons déjà accompli le travail systématique de **décomposition** de la connaissance et de **mise en lien avec le texte original**. Les structures sémantiques clés enfouies dans la prose ont été extraites sous forme de **concepts et de propriétés** — un squelette sémantique sur lequel vous pouvez bâtir immédiatement. C'est bien moins de travail que de partir du texte brut et de tout reconstruire vous-même.

> Le texte brut donne à votre agent *des mots à lire.*
> BusyBeaver lui donne *une connaissance à laquelle il peut se fier, déjà structurée et interconnectée.*

### 🌿 L'herbe vs. 🥩 la viande

Voyez les choses ainsi : **le texte brut est de l'herbe ; la base de connaissances BusyBeaver est de la viande.**

Vous *pouvez* manger de l'herbe directement — mais il vous faut alors un système digestif volumineux et coûteux pour la décomposer. Mangez plutôt de la viande, et vous économisez toute l'énergie que vous auriez dépensée à digérer l'herbe — une énergie qui, pour votre agent, correspond à des **jetons LLM (LLM tokens)** — pour la consacrer à des choses plus intelligentes.

**La viande est une connaissance à haute densité : du contexte, hautement compressé.** BusyBeaver a déjà fait la digestion, pour que votre agent n'ait pas à le faire.

---

## Comment l'utiliser

BusyBeaver **n'impose aucune méthode particulière de stockage ou de récupération**. Chaque texte et chaque élément de connaissance dérivée a déjà été soigneusement segmenté, décomposé et analysé — vous pouvez donc le brancher sur la pile technique que vous utilisez déjà :

### 🔎 Base vectorielle / RAG
Indexez les Memes et récupérez-les par similarité sémantique. Les fragments sont déjà dimensionnés et nettoyés pour l'embedding — aucun pipeline de découpage supplémentaire n'est nécessaire.

### 🗂️ Recherche classique (Elasticsearch et ses semblables)
Chargez les Memes et leurs métadonnées dans Elasticsearch, ou tout moteur de recherche traditionnel, et interrogez-les par champs, facettes et texte intégral.

### 🤖 Agents de codage (par exemple Claude Code)
Pointez un agent de codage tel que **Claude Code** directement vers ce dépôt et laissez-le lire la base de connaissances directement — en lui demandant d'analyser, de croiser les références et de tirer des conclusions à travers le corpus.

Quelle que soit la voie choisie, la provenance PN voyage avec la connaissance, de sorte que les conclusions de votre agent restent **vérifiables (auditable)**.

---

## Statut et feuille de route

| | |
| --- | --- |
| **Livres memifiés** | ~500 |
| **Memes** | ~50 000 |
| **Prochain jalon** | 10 000 livres |

**Nous mettons continuellement à jour cette base de connaissances — de nouveaux livres sont ajoutés chaque jour.** Notre objectif est d'inclure à terme tous les livres qui comptent le plus pour la civilisation humaine. Ce dump est un instantané pris en cours de route.

### 🌍 Une base de connaissances multilingue

BusyBeaver est conçu pour être **international**. Le corpus initial est principalement en **anglais et en chinois**, et nous continuerons d'ajouter au fil du temps les grandes langues du monde — car les classiques qui ont façonné la civilisation humaine n'ont pas été écrits dans une seule langue.

### 🔮 Ce qui s'en vient

BusyBeaver est le corpus. Autour de lui, nous construisons :

- **Des wikis interactifs pour chaque livre** — parcourez et interrogez la connaissance de chaque livre comme un wiki vivant et relié, et non comme un simple dump plat.
- **Tout contenu → wiki** — un service qui transforme *n'importe quel* contenu en un wiki structuré et natif pour les agents — y compris **votre propre matériel protégé par le droit d'auteur** (manuels internes, textes sous licence, recherches propriétaires), afin que vous disposiez de votre propre base de connaissances privée.
- **Wiki sémantique fédéré** — un protocole partagé qui permet aux agents de connaissance d'**échanger, agréger et interroger librement** la connaissance à travers des wikis indépendants. Un seul espace d'adresses, de nombreux participants — le rêve du Purple Number, fédéré.

### 📚 Demander un livre

Y a-t-il un classique que vous aimeriez tout particulièrement voir memifié ? **Nous serions ravis de le savoir.** Ouvrez une issue sur ce dépôt, ou envoyez un e-mail à **Minnie Katz** à **minnie.sew.da@gmail.com** avec votre suggestion, et nous le prioriserons dans la file d'attente.

---

## Droits d'auteur et périmètre

Dans cette base de connaissances publique, nous ne publions **que des connaissances issues de livres libres de droits** (domaine public). Cela garantit que le dump reste propre à partager et sûr pour bâtir dessus.

Vous disposez de **matériel protégé par le droit d'auteur** que vous aimeriez transformer en une base de connaissances native pour agents ? C'est à cela que sert le service **Tout contenu → wiki** (voir **Ce qui s'en vient**). Intéressé dès maintenant ? Contactez-nous : **minnie.sew.da@gmail.com**.

---

## Licence

BusyBeaver est publié sous la **[PolyForm Noncommercial License 1.0.0](./LICENSE)**.

- ✅ **Gratuit pour tout usage non commercial** — étude personnelle, recherche, éducation, associations à but non lucratif et institutions publiques.
- 💼 **L'usage commercial nécessite une licence distincte.**

Pour obtenir une licence commerciale, contactez **Minnie Katz** à **minnie.sew.da@gmail.com**.

---

<div align="center">

*Donnez une adresse à chaque élément de connaissance.* — en prolongeant la vision de Doug Engelbart.

</div>
