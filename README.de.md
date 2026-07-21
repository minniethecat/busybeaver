<div align="center">

<img src="./assets/logo.png" alt="BusyBeaver logo" width="220" />

# 🦫 BusyBeaver

### Eine agentennative Wissensbasis der klassischen Bücher der Menschheit

*Die großen Bücher der Welt, aufgebrochen in nachvollziehbares, komponierbares Wissen — gebaut für KI-Agenten, nicht nur für Menschen.*

**Eine kontinuierlich wachsende Wissensbasis — sich weiterentwickelnd, überprüfbar, destilliert aus den Klassikern der Menschheit**

<sub>🌐 [English (official)](./README.md) · [简体中文](./README.zh.md) · [Español](./README.es.md) · [Français](./README.fr.md) · **Deutsch** · [日本語](./README.ja.md)</sub>

<sub>Dieses README wird in mehreren wichtigen Sprachen angeboten. Die **[English version](./README.md) (dieses Dokument in der Originalsprache) ist die offizielle Version.**</sub>

</div>

---

## Was ist BusyBeaver?

BusyBeaver ist eine von einem LLM erbaute Wissensbasis, deren Mission es ist, das für die Menschheit wichtigste Wissen — die Klassiker, vor allem aus Büchern geschöpft — in eine Wissensbasis zu verwandeln, die **agentenfreundlich** ist.

Wir tun dies, indem wir Wissen in kleine, verteilbare, semantisch reichhaltige Fragmente zerlegen. Jedes dieser Fragmente nennen wir ein **Meme**.

> Das Wort **Meme** wurde vom britischen Biologen **Richard Dawkins** in *The Selfish Gene* (Das egoistische Gen) (1976) geprägt, wo er es als **die grundlegende Einheit kultureller Übertragung** definierte. BusyBeaver nimmt die Idee wörtlich: Ein Meme ist eine Wissenseinheit, klein genug, um zu reisen, sich zu replizieren und sich neu zu kombinieren.

- Jedes **Meme** trägt seine eigenen **Metadaten**.
- Jedes **Meme** kann **abgefragt** werden.
- **Memes** können **frei komponiert** werden — zu Wikis, Briefings oder Antworten.

Dieses Repository ist ein **Dump**: die memifizierte Aufschlüsselung mehrerer hundert klassischer Bücher. Dieser Korpus **wächst schnell** — unser erster Meilenstein sind **10.000 Bücher**.

> **Warum „Busy Beaver“?** In der Berechenbarkeitstheorie ist die **Busy-Beaver-Funktion** der Archetyp der *am schnellsten wachsenden* Funktion — sie überholt alles Berechenbare. Das ist der Ehrgeiz hinter dem Namen: eine **Superwissensbasis** für die kommende Welt der Agenten, die so schnell wächst, wie wir es ermöglichen können.

Wenn Sie einen Agenten auf BusyBeaver ansetzen, verarbeitet er die Klassiker *dramatisch schneller*, denn die harte Arbeit — den Text zu zerlegen, zu analysieren und zu verknüpfen — ist bereits getan.

---

## Warum es das gibt

Wir wollen das unvollendete Versprechen des **Semantic Web** und der **Knowledge Graphs** weitertragen, dabei aber die Grenzen des klassischen Stapels der Wissensrepräsentation abstreifen.

Die entscheidende Verschiebung: **Der Konsument von Wissen ist jetzt ein Agent.**

Deshalb muss Wissen nicht mehr als RDF-Tripel oder formale logische Ausdrücke kodiert werden. Es kann stattdessen das sein, was Agenten tatsächlich am besten konsumieren — **semantisch reichhaltige, natürlichsprachliche Sätze, gepaart mit Metadaten**, in Fragmente geschnitten, die ein Agent frei aufteilen, neu kombinieren und über die er schlussfolgern kann.

> Die klassische Wissensrepräsentation zwang menschliche Bedeutung durch eine enge formale Grammatik.
> BusyBeaver belässt die Bedeutung in der Sprache und lässt die Struktur in den Metadaten leben.

---

## Herkunft & Vorarbeiten

BusyBeaver steht auf den Schultern der großen Projekte für strukturiertes Wissen, die zuvor kamen. Wir stehen besonders in der Schuld von:

- **[Wikidata](https://www.wikidata.org/)** — kollaboratives, mehrsprachiges, maschinenlesbares Wissen im großen Maßstab.
- **[DBpedia](https://www.dbpedia.org/)** — Extraktion strukturierten Wissens aus den Enzyklopädien der Welt.
- **[Freebase](https://en.wikipedia.org/wiki/Freebase_(database))** — ein offener Graph von Entitäten und Beziehungen.
- **[Semantic MediaWiki](https://www.semantic-mediawiki.org/)** — bringt semantische Struktur direkt ins Wiki.

Um BusyBeaver zu bauen, haben wir eine **neue Methode für semantische Wikis** eigens entworfen — eine, bei der die Wissenseinheit ein quellenverankertes, agentenkonsumierbares Meme ist statt eines starren Tripels. Diese Methode wird **separat als Open Source veröffentlicht**.

---

## Das schwierige Problem: Halluzination & Provenienz

Der mit Abstand schwierigste Teil beim Aufbau einer Wissensbasis mit LLMs ist das **Erkennen und Kontrollieren von Halluzinationen**.

BusyBeavers Antwort darauf ist **Provenienzkontrolle**. Wir bewahren die *Herkunft* des Wissens so getreu wie möglich, sodass **jede Aussage zu ihrem Ursprung zurückverfolgt werden kann** — meist eine bestimmte Passage in einem bestimmten Buch.

Jeder Wissensquelle wird eine **PN — eine Purple Number** — zugewiesen.

> Die Purple Number verkörpert **Doug Engelbarts Ideal**: dass *jedes Wissensstück der Welt eine Adresse haben sollte.*

Mit PNs ist eine Behauptung in BusyBeaver niemals eine frei schwebende Aussage. Sie ist verankert — adressierbar, überprüfbar und bis zu ihrer Quelle zitierbar.

---

## Anatomie eines Memes

Ein Meme ist die atomare Einheit von BusyBeaver. Konzeptionell bündelt jedes Meme:

| Teil | Beschreibung |
| --- | --- |
| **Assertion (Aussage)** | Eine in sich geschlossene, semantisch reichhaltige, natürlichsprachliche Wissensaussage. |
| **Metadaten** | Typ, Thema, Entitäten, Beziehungen und andere strukturierte Signale für Retrieval und Komposition. |
| **Provenienz (PN)** | Eine Purple Number, die die Aussage an ihrer Quellpassage verankert, sodass die Behauptung rückverfolgbar bleibt. |

Weil jedes Meme klein, selbstbeschreibend und quellenverankert ist, sind Memes **verteilbar** (man kann eines teilen, ohne das ganze Buch zu versenden) und **komponierbar** (viele lassen sich zu einer Wiki-Seite, einem Briefing oder einer Antwort zusammensetzen).

---

## 📦 Paketvermittlung für Wissen

Jeder Sprung in der globalen Infrastruktur entstand aus einer neuen **Austauscheinheit**:

- Die **Paketvermittlung von Daten** zerlegte Information in kleine, routbare Pakete — und schenkte uns das **Internet**.
- Der **Containertransport** zerlegte Fracht in standardisierte, austauschbare Boxen — und globalisierte den **Handel**.

Das **Meme ist diese Einheit für Wissen**: ein kleines, selbstbeschreibendes, an seine Quelle gebundenes Paket, das über Systeme und Organisationen hinweg geroutet, ausgetauscht, aggregiert und neu kombiniert werden kann. Die **Paketvermittlung von Wissen** zum Laufen zu bringen — so wollen wir eine **globale Wissensinfrastruktur** aufbauen.

---

## Warum eine Wissensbasis, nicht einfach Rohtext?

Wenn Agenten lesen können, warum ihnen dann nicht einfach die Bücher füttern? Weil BusyBeaver zwei Dinge bietet, die Rohtext nicht kann:

### 1. Ein Provenienz-Framework zur Kontrolle von Halluzinationen
Rohtext erneut durch ein LLM zu schicken, öffnet wieder die Tür zum größten Einzelfehler LLM-basierter Wissensbasen: **Halluzination**. BusyBeaver umhüllt jede Aussage mit **Provenienz-Tracking** — jede Behauptung wird durch ihre PN an der Quellpassage verankert, aus der sie stammt. Das gibt Ihnen ein Framework, um zu *verifizieren*, was Ihr Agent Ihnen sagt, statt es einfach zu glauben.

### 2. Ein fertiges semantisches Skelett
Wir haben bereits die systematische Arbeit geleistet, das Wissen zu **zerlegen** und es **mit dem Originaltext zu verknüpfen**. Die im Fließtext verborgenen semantischen Kernstrukturen wurden herausgelöst in **Konzepte und Eigenschaften** — ein semantisches Skelett, auf dem Sie sofort aufbauen können. Das ist weit weniger Arbeit, als bei Rohtext zu beginnen und alles selbst zu rekonstruieren.

> Rohtext gibt Ihrem Agenten *Wörter zum Lesen.*
> BusyBeaver gibt ihm *Wissen, dem er vertrauen kann — bereits strukturiert und quervernetzt.*

### 🌿 Gras vs. 🥩 Fleisch

Stellen Sie es sich so vor: **Rohtext ist Gras; die BusyBeaver-Wissensbasis ist Fleisch.**

Man *kann* Gras direkt essen — aber dann braucht man ein großes, teures Verdauungssystem, um es aufzuschließen. Essen Sie stattdessen Fleisch, sparen Sie sich all die Energie, die Sie sonst für die Verdauung von Gras aufgewendet hätten — Energie, die für Ihren Agenten **LLM-Tokens** sind — und investieren sie stattdessen in klügere Dinge.

**Fleisch ist hochverdichtetes Wissen: Kontext, stark komprimiert.** BusyBeaver hat das Verdauen bereits erledigt, damit Ihr Agent es nicht tun muss.

---

## Wie man es nutzt

BusyBeaver **erzwingt keine bestimmte Speicher- oder Retrieval-Methode**. Jeder Text und jedes abgeleitete Wissensstück wurde bereits sorgfältig segmentiert, zerlegt und analysiert — Sie können es also in jeden bereits vorhandenen Stack einbinden:

### 🔎 Vektorspeicher / RAG
Indexieren Sie die Memes und rufen Sie sie nach semantischer Ähnlichkeit ab. Die Fragmente sind bereits für das Embedding passend zugeschnitten und bereinigt — keine zusätzliche Chunking-Pipeline nötig.

### 🗂️ Klassische Suche (Elasticsearch & Verwandte)
Laden Sie die Memes und ihre Metadaten in Elasticsearch oder jede andere klassische Retrieval-Engine und fragen Sie nach Feldern, Facetten und Volltext ab.

### 🤖 Coding-Agenten (z. B. Claude Code)
Setzen Sie einen Coding-Agenten wie **Claude Code** direkt auf dieses Repository an und lassen Sie ihn die Wissensbasis direkt lesen — bitten Sie ihn, den Korpus zu analysieren, quer zu referenzieren und Schlussfolgerungen zu ziehen.

Welchen Weg Sie auch wählen, die PN-Provenienz reist mit dem Wissen mit, sodass die Schlussfolgerungen Ihres Agenten **auditierbar** bleiben.

---

## 🛠️ Was können Sie mit BusyBeaver tun?

- **Neues daraus erschaffen.** Nutzen Sie das Wissen als Rohstoff für *Zweitschöpfungen*: Ihren Blog, Präsentationen, Romane, Drehbücher, Aufsätze, Comics, Videos und mehr.
- **Ihrem Agenten Experten-Kontext geben.** Füttern Sie ihn mit einer ausgewählten Menge an Themen, damit er zu einem echten Experten für eine Sache wird.
- **Ihre Modelle trainieren.** Trainieren Sie auf strukturierten Memes — effizienter und weit token-sparsamer als das Lesen von Rohtext.
- **Ihre eigene KB wachsen lassen.** Nutzen Sie BusyBeaver als grundlegende Wissensschicht, um Ihre eigene Wissensbasis (etwa Ihr Wiki) zu säen und auszubauen.
- **Integrieren und entdecken.** Weil das Wissen *abfragbar* ist, können Sie wissensbasierte Datenintegration betreiben — und mit Abfragen Serendipität erzeugen, indem Sie Verbindungen aufdecken, nach denen Sie gar nicht gesucht haben.

---

## Status & Fahrplan

| | |
| --- | --- |
| **Memifizierte Bücher** | ~500 |
| **Memes** | ~50.000 |
| **Nächster Meilenstein** | 10.000 Bücher |

**Wir aktualisieren diese Wissensbasis fortlaufend — jeden Tag kommen neue Bücher hinzu.** Unser Ziel ist es, letztlich jedes Buch einzuschließen, das für die menschliche Zivilisation am wichtigsten ist. Dieser Dump ist eine Momentaufnahme auf diesem Weg.

### 🌍 Eine mehrsprachige Wissensbasis

BusyBeaver ist auf **Internationalität** ausgelegt. Der Anfangskorpus ist vor allem **Englisch und Chinesisch**, und wir werden im Laufe der Zeit weiter die großen Sprachen der Welt hinzufügen — denn die Klassiker, die die menschliche Zivilisation geprägt haben, wurden nicht in einer einzigen Sprache verfasst.

### 🔮 Was als Nächstes kommt

BusyBeaver ist der Korpus. Darum herum bauen wir:

- **Interaktive Wikis für jedes Buch** — das Wissen jedes Buches als lebendiges, verknüpftes Wiki durchsuchen und abfragen, nicht nur als flachen Dump.
- **Beliebiger Inhalt → Wiki** — ein Dienst, der *beliebige* Inhalte in ein strukturiertes, agentennatives Wiki verwandelt — einschließlich **Ihres eigenen urheberrechtlich geschützten Materials** (interne Handbücher, lizenzierte Texte, proprietäre Forschung) —, sodass Sie eine eigene, private Wissensbasis erhalten.
- **Föderiertes semantisches Wiki** — ein gemeinsames Protokoll, das es Wissensagenten erlaubt, Wissen über unabhängige Wikis hinweg **frei auszutauschen, zu aggregieren und abzufragen**. Ein Adressraum, viele Teilnehmer — der Traum der Purple Number, föderiert.

### 📚 Ein Buch vorschlagen

Gibt es einen Klassiker, den Sie besonders gerne memifiziert sehen würden? **Wir würden es gerne erfahren.** Eröffnen Sie ein Issue in diesem Repository oder schreiben Sie **Minnie Katz** unter **minnie.sew.da@gmail.com** mit Ihrem Vorschlag, und wir werden ihn in der Warteschlange priorisieren.

---

## Urheberrecht & Umfang

In dieser öffentlichen Wissensbasis veröffentlichen wir **nur Wissen, das aus urheberrechtsfreien Büchern stammt** (gemeinfrei). Das hält den Dump sauber teilbar und sicher, um darauf aufzubauen.

Haben Sie eigenes **urheberrechtlich geschütztes Material**, das Sie in eine agentennative Wissensbasis verwandeln möchten? Dafür ist der Dienst **Beliebiger Inhalt → Wiki** (siehe **Was als Nächstes kommt**) gedacht. Frühes Interesse? Melden Sie sich: **minnie.sew.da@gmail.com**.

---

## 🚀 Ihr Wissen, memifiziert

BusyBeaver ist erst der Anfang. Wir wollen **Ihnen** helfen, *Ihr eigenes* Wissen — **persönliche Notizen wie auch Unternehmens-Know-how** — in dieselbe Art von KB zu verwandeln: **verteilbar, kombinierbar und mühelos von Agenten konsumierbar.**

Und es bleibt **unter Ihrer Kontrolle.** Geben Sie einzelnen Memes unterschiedliche **Sichtbarkeit** — halten Sie manche privat, teilen Sie andere mit Ihrem Team, veröffentlichen Sie wieder andere für die ganze Welt. Verbreiten Sie Ihr Wissen **gezielt, an bestimmte Zielgruppen — oder verkaufen Sie es sogar**, Meme für Meme.

Die Klassiker sind unser Anfang. Die größere Vision ist eine offene, föderierte Ökonomie vertrauenswürdigen, agenten-nativen Wissens — und Ihr Wissen hat darin seinen Platz.

---

## Lizenz

BusyBeaver wird unter der **[PolyForm Noncommercial License 1.0.0](./LICENSE)** veröffentlicht.

- ✅ **Kostenlos für jeden nichtkommerziellen Zweck** — Privatstudium, Forschung, Bildung, gemeinnützige Organisationen und öffentliche Einrichtungen.
- 💼 **Kommerzielle Nutzung erfordert eine separate Lizenz.**

Um eine kommerzielle Lizenz zu erhalten, kontaktieren Sie **Minnie Katz** unter **minnie.sew.da@gmail.com**.

---

<div align="center">

*Gib jedem Wissensstück eine Adresse.* — in Fortführung von Doug Engelbarts Vision.

</div>
