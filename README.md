<div align="center">

# 🦫 BusyBeaver

### An agent-native knowledge base of humanity's classic books

*The world's great books, broken down into traceable, composable knowledge — built for AI agents, not just for humans.*

**~500 books · ~50,000 Memes · every assertion traceable to its source**

</div>

---

## What is BusyBeaver?

BusyBeaver is an LLM-built knowledge base whose mission is to take the knowledge that matters most to humanity — the classics, drawn primarily from books — and turn it into a knowledge base that is **friendly to agents**.

We do this by breaking knowledge down into small, distributable, richly-semantic fragments. We call each fragment a **Meme**.

> The word **Meme** was coined by the British biologist **Richard Dawkins** in *The Selfish Gene* (1976), where he defined it as **the basic unit of cultural transmission**. BusyBeaver takes the idea literally: a Meme is a unit of knowledge small enough to travel, replicate, and recombine.

- Every **Meme** carries its own **metadata**.
- Every **Meme** can be **queried**.
- **Memes** can be **freely composed** into wikis, briefings, or answers.

This repository is a **dump**: the memified breakdown of several hundred classic books. That corpus is **growing fast** — our first milestone is **10,000 books**.

> **Why "Busy Beaver"?** In computability theory, the **Busy Beaver function** is the archetype of the *fastest-growing* function — it outruns everything computable. That's the ambition behind the name: a **super knowledge base** for the coming world of agents, growing as fast as we can make it.

If you point an agent at BusyBeaver, it digests the classics *dramatically faster*, because the hard work — splitting the text apart, analyzing it, and linking it together — is already done.

---

## Why it exists

We want to carry forward the unfinished promise of the **Semantic Web** and **Knowledge Graphs**, while shedding the limits of the classic knowledge-representation stack.

The crucial shift: **the consumer of knowledge is now an agent.**

Because of that, knowledge no longer has to be encoded as RDF triples or formal logic expressions. It can instead be what agents actually consume best — **semantically rich natural-language sentences, paired with metadata**, cut into fragments that an agent can freely divide, recombine, and reason over.

> Classic knowledge representation forced human meaning through a narrow formal grammar.
> BusyBeaver keeps the meaning in language, and lets the structure live in the metadata.

---

## Lineage & prior art

BusyBeaver stands on the shoulders of the great structured-knowledge projects that came before it. We owe a particular debt to:

- **[Wikidata](https://www.wikidata.org/)** — collaborative, multilingual, machine-readable knowledge at scale.
- **[DBpedia](https://www.dbpedia.org/)** — extracting structured knowledge from the world's encyclopedias.
- **[Freebase](https://en.wikipedia.org/wiki/Freebase_(database))** — an open graph of entities and relationships.
- **[Semantic MediaWiki](https://www.semantic-mediawiki.org/)** — bringing semantic structure into the wiki itself.

To build BusyBeaver we designed a **new semantic-wiki method** of our own — one where the unit of knowledge is a source-anchored, agent-consumable Meme rather than a rigid triple. That method will be **open-sourced separately**.

---

## The hard problem: hallucination & provenance

The single hardest part of building a knowledge base with LLMs is **detecting and controlling hallucination**.

BusyBeaver's answer is **provenance control**. We preserve the *origin* of knowledge as faithfully as we can, so that **every assertion can be traced back to where it came from** — usually a specific passage in a specific book.

Each knowledge source is assigned a **PN — a Purple Number**.

> The Purple Number is **Doug Engelbart's ideal**: that *every piece of knowledge in the world should have an address.*

With PNs, a claim in BusyBeaver is never a free-floating statement. It is anchored — addressable, checkable, and citable back to its source.

---

## Anatomy of a Meme

A Meme is the atomic unit of BusyBeaver. Conceptually, each Meme bundles:

| Part | Description |
| --- | --- |
| **Assertion** | A self-contained, semantically rich natural-language statement of knowledge. |
| **Metadata** | Type, topic, entities, relationships, and other structured signals for retrieval and composition. |
| **Provenance (PN)** | A Purple Number anchoring the assertion to its source passage, so the claim stays traceable. |

Because every Meme is small, self-describing, and source-anchored, Memes are **distributable** (share one without shipping the whole book) and **composable** (assemble many into a wiki page, a briefing, or an answer).

---

## Why a knowledge base, not just raw text?

If agents can read, why not just feed them the books? Because BusyBeaver gives you two things raw text can't:

### 1. A provenance framework to control hallucination
Feeding raw text back through an LLM re-opens the door to the single biggest flaw of LLM-based knowledge bases: **hallucination**. BusyBeaver wraps every assertion in **provenance tracking** — each claim is anchored by its PN to the source passage it came from. That gives you a framework to *verify* what your agent tells you, instead of taking it on faith.

### 2. A ready-made semantic skeleton
We've already done the systematic work of **decomposing** the knowledge and **linking it back to the original text**. The key semantic structures buried in the prose have been lifted out into **concepts and properties** — a semantic skeleton you can build on immediately. That is far less work than starting from raw text and reconstructing all of it yourself.

> Raw text gives your agent *words to read.*
> BusyBeaver gives it *knowledge it can trust, already structured and cross-linked.*

### 🌿 Grass vs. 🥩 meat

Think of it this way: **raw text is grass; the BusyBeaver KB is meat.**

You *can* eat grass directly — but then you need a big, expensive digestive system to break it down. Eat meat instead, and you save all the energy you'd have spent digesting grass — energy that, for your agent, is **LLM tokens** — and spend it on smarter things instead.

**Meat is high-density knowledge: context, highly compressed.** BusyBeaver has already done the digesting, so your agent doesn't have to.

---

## How to use it

BusyBeaver **does not force any particular storage or retrieval method**. Every text and every piece of derived knowledge has already been carefully segmented, decomposed, and analyzed — so you can plug it into whatever stack you already run:

### 🔎 Vector store / RAG
Index the Memes and retrieve by semantic similarity. The fragments are already sized and cleaned for embedding — no extra chunking pipeline required.

### 🗂️ Classic search (Elasticsearch & friends)
Load the Memes and their metadata into Elasticsearch, or any traditional retrieval engine, and query by fields, facets, and full text.

### 🤖 Coding agents (e.g. Claude Code)
Point a coding agent such as **Claude Code** straight at this repository and let it read the KB directly — asking it to analyze, cross-reference, and draw conclusions across the corpus.

Whatever path you choose, the PN provenance travels with the knowledge, so your agent's conclusions stay **auditable**.

---

## Status & roadmap

| | |
| --- | --- |
| **Books memified** | ~500 |
| **Memes** | ~50,000 |
| **Next milestone** | 10,000 books |

**We update this knowledge base continuously — new books are added every day.** Our goal is to eventually include every book that matters most to human civilization. This dump is a snapshot along the way.

### 📚 Request a book

Is there a classic you especially want memified? **We'd love to hear it.** Open an issue on this repository, or email **Minnie Katz** at **minnie.sew.da@gmail.com** with your suggestion, and we'll prioritize it in the queue.

---

## Copyright & scope

In this public knowledge base we publish **only knowledge derived from books that are free of copyright** (public domain). This keeps the dump clean to share and safe to build on.

Want to memify your **own copyrighted material** — internal handbooks, licensed texts, proprietary research — into an agent-native knowledge base of your own? We're building a **service** for exactly that. **Stay tuned.** 📬

*(Interested early? Reach out: **minnie.sew.da@gmail.com**.)*

---

## License

BusyBeaver is released under the **[PolyForm Noncommercial License 1.0.0](./LICENSE)**.

- ✅ **Free for any noncommercial purpose** — personal study, research, education, nonprofits, and public institutions.
- 💼 **Commercial use requires a separate license.**

To obtain a commercial license, contact **Minnie Katz** at **minnie.sew.da@gmail.com**.

---

<div align="center">

*Give every piece of knowledge an address.* — carrying forward Doug Engelbart's vision.

</div>
