<div align="center">

# 🦫 BusyBeaver

### Una base de conocimiento nativa para agentes de los libros clásicos de la humanidad

*Los grandes libros del mundo, descompuestos en conocimiento trazable y componible — construido para agentes de IA, no solo para humanos.*

**~500 libros · ~50,000 Memes · cada afirmación trazable hasta su fuente**

<sub>🌐 [English (official)](./README.md) · [简体中文](./README.zh.md) · **Español** · [Français](./README.fr.md) · [Deutsch](./README.de.md) · [日本語](./README.ja.md)</sub>

<sub>Este README se ofrece en varios idiomas principales. La **versión en inglés (English version) es la oficial.**</sub>

</div>

---

## ¿Qué es BusyBeaver?

BusyBeaver es una base de conocimiento construida por LLM cuya misión es tomar el conocimiento que más importa a la humanidad —los clásicos, extraídos principalmente de libros— y convertirlo en una base de conocimiento **amigable para agentes**.

Lo hacemos descomponiendo el conocimiento en fragmentos pequeños, distribuibles y ricos en semántica. A cada fragmento lo llamamos un **Meme**.

> La palabra **Meme** fue acuñada por el biólogo británico **Richard Dawkins** en *The Selfish Gene* (El gen egoísta) (1976), donde la definió como **la unidad básica de transmisión cultural**. BusyBeaver toma la idea de forma literal: un Meme es una unidad de conocimiento lo bastante pequeña como para viajar, replicarse y recombinarse.

- Cada **Meme** lleva sus propios **metadatos**.
- Cada **Meme** puede ser **consultado**.
- Los **Memes** pueden **componerse libremente** en wikis, informes o respuestas.

Este repositorio es un **volcado (dump)**: la descomposición memificada de varios cientos de libros clásicos. Ese corpus está **creciendo rápidamente** — nuestro primer hito son **10,000 libros**.

> **¿Por qué "Busy Beaver"?** En teoría de la computabilidad, la **función Busy Beaver** es el arquetipo de la función de *crecimiento más rápido* — supera en velocidad a todo lo computable. Esa es la ambición detrás del nombre: una **superbase de conocimiento** para el mundo de agentes que se avecina, creciendo tan rápido como podamos lograrlo.

Si apuntas un agente hacia BusyBeaver, este digiere los clásicos *dramáticamente más rápido*, porque el trabajo difícil —separar el texto, analizarlo y vincularlo— ya está hecho.

---

## Por qué existe

Queremos llevar adelante la promesa inconclusa de la **Web Semántica** y los **Grafos de Conocimiento**, dejando atrás a la vez las limitaciones de la pila clásica de representación del conocimiento.

El cambio crucial: **el consumidor del conocimiento ahora es un agente.**

Por eso, el conocimiento ya no tiene que codificarse como tripletas RDF o expresiones de lógica formal. Puede ser, en cambio, lo que los agentes consumen mejor en realidad — **oraciones en lenguaje natural semánticamente ricas, junto con metadatos**, cortadas en fragmentos que un agente puede dividir, recombinar y razonar libremente.

> La representación clásica del conocimiento forzaba el significado humano a través de una gramática formal estrecha.
> BusyBeaver mantiene el significado en el lenguaje y deja que la estructura viva en los metadatos.

---

## Linaje y trabajos previos

BusyBeaver se apoya en los hombros de los grandes proyectos de conocimiento estructurado que lo precedieron. Tenemos una deuda particular con:

- **[Wikidata](https://www.wikidata.org/)** — conocimiento colaborativo, multilingüe y legible por máquinas a gran escala.
- **[DBpedia](https://www.dbpedia.org/)** — extracción de conocimiento estructurado de las enciclopedias del mundo.
- **[Freebase](https://en.wikipedia.org/wiki/Freebase_(database))** — un grafo abierto de entidades y relaciones.
- **[Semantic MediaWiki](https://www.semantic-mediawiki.org/)** — llevando la estructura semántica al propio wiki.

Para construir BusyBeaver diseñamos un **nuevo método de wiki semántico** propio — uno en el que la unidad de conocimiento es un Meme anclado a la fuente y consumible por agentes, en lugar de una tripleta rígida. Ese método será **liberado como código abierto por separado**.

---

## El problema difícil: alucinación y procedencia

La parte más difícil de construir una base de conocimiento con LLMs es **detectar y controlar la alucinación**.

La respuesta de BusyBeaver es el **control de procedencia**. Preservamos el *origen* del conocimiento con la mayor fidelidad posible, de modo que **cada afirmación pueda rastrearse hasta su origen** — normalmente un pasaje específico de un libro específico.

A cada fuente de conocimiento se le asigna un **PN — un Purple Number**.

> El Purple Number es **el ideal de Doug Engelbart**: que *cada fragmento de conocimiento en el mundo debería tener una dirección.*

Con los PN, una afirmación en BusyBeaver nunca es una declaración flotante y libre. Está anclada — direccionable, verificable y citable hasta su fuente.

---

## Anatomía de un Meme

Un Meme es la unidad atómica de BusyBeaver. Conceptualmente, cada Meme reúne:

| Parte | Descripción |
| --- | --- |
| **Afirmación** | Una declaración de conocimiento en lenguaje natural, autocontenida y semánticamente rica. |
| **Metadatos** | Tipo, tema, entidades, relaciones y otras señales estructuradas para la recuperación y la composición. |
| **Procedencia (PN)** | Un Purple Number que ancla la afirmación a su pasaje de origen, de modo que la afirmación siga siendo trazable. |

Como cada Meme es pequeño, autodescriptivo y anclado a su fuente, los Memes son **distribuibles** (comparte uno sin enviar el libro completo) y **componibles** (ensambla varios en una página de wiki, un informe o una respuesta).

---

## ¿Por qué una base de conocimiento y no solo texto crudo?

Si los agentes pueden leer, ¿por qué no simplemente darles los libros? Porque BusyBeaver te da dos cosas que el texto crudo no puede:

### 1. Un marco de procedencia para controlar la alucinación
Volver a pasar texto crudo por un LLM reabre la puerta al mayor defecto de las bases de conocimiento basadas en LLM: la **alucinación**. BusyBeaver envuelve cada afirmación en **seguimiento de procedencia** — cada afirmación queda anclada por su PN al pasaje de origen del que proviene. Eso te da un marco para *verificar* lo que tu agente te dice, en lugar de tomarlo por fe.

### 2. Un esqueleto semántico ya construido
Ya hemos hecho el trabajo sistemático de **descomponer** el conocimiento y **vincularlo de vuelta al texto original**. Las estructuras semánticas clave enterradas en la prosa se han extraído en **conceptos y propiedades** — un esqueleto semántico sobre el que puedes construir de inmediato. Eso es mucho menos trabajo que partir del texto crudo y reconstruirlo todo tú mismo.

> El texto crudo le da a tu agente *palabras para leer.*
> BusyBeaver le da *conocimiento en el que puede confiar, ya estructurado y enlazado entre sí.*

### 🌿 Hierba vs. 🥩 carne

Piénsalo así: **el texto crudo es hierba; la KB de BusyBeaver es carne.**

*Puedes* comer hierba directamente — pero entonces necesitas un sistema digestivo grande y costoso para descomponerla. Come carne en cambio, y ahorras toda la energía que habrías gastado digiriendo hierba — energía que, para tu agente, son **tokens de LLM** — y la gastas en cosas más inteligentes.

**La carne es conocimiento de alta densidad: contexto, altamente comprimido.** BusyBeaver ya ha hecho la digestión, para que tu agente no tenga que hacerlo.

---

## Cómo usarlo

BusyBeaver **no impone ningún método particular de almacenamiento o recuperación**. Cada texto y cada fragmento de conocimiento derivado ya ha sido cuidadosamente segmentado, descompuesto y analizado — así que puedes conectarlo a cualquier pila tecnológica que ya uses:

### 🔎 Almacén vectorial / RAG
Indexa los Memes y recupéralos por similitud semántica. Los fragmentos ya tienen el tamaño y la limpieza adecuados para el embedding — no se necesita un pipeline de fragmentación adicional.

### 🗂️ Búsqueda clásica (Elasticsearch y similares)
Carga los Memes y sus metadatos en Elasticsearch, o en cualquier motor de recuperación tradicional, y consúltalos por campos, facetas y texto completo.

### 🤖 Agentes de programación (p. ej., Claude Code)
Apunta un agente de programación como **Claude Code** directamente a este repositorio y deja que lea la KB directamente — pidiéndole que analice, cruce referencias y saque conclusiones a través del corpus.

Sea cual sea el camino que elijas, la procedencia del PN viaja con el conocimiento, de modo que las conclusiones de tu agente siguen siendo **auditables**.

---

## Estado y hoja de ruta

| | |
| --- | --- |
| **Libros memificados** | ~500 |
| **Memes** | ~50,000 |
| **Próximo hito** | 10,000 libros |

**Actualizamos esta base de conocimiento continuamente — se añaden nuevos libros cada día.** Nuestro objetivo es incluir eventualmente cada libro que más importe para la civilización humana. Este volcado es una instantánea en el camino.

### 🌍 Una base de conocimiento multilingüe

BusyBeaver está construido para ser **internacional**. El corpus inicial es principalmente en **inglés y chino**, y seguiremos añadiendo los principales idiomas del mundo con el tiempo — porque los clásicos que dieron forma a la civilización humana no se escribieron en una sola lengua.

### 🔮 Lo que viene

BusyBeaver es el corpus. Alrededor de él estamos construyendo:

- **Wikis interactivos para cada libro** — explora y consulta el conocimiento de cada libro como un wiki vivo y enlazado, no solo un volcado plano.
- **Cualquier contenido → wiki** — un servicio que convierte contenido *arbitrario* en un wiki estructurado y nativo para agentes — incluyendo **tu propio material con derechos de autor** (manuales internos, textos con licencia, investigación propia), para que tengas tu propia KB privada.
- **Wiki semántico federado** — un protocolo compartido que permite a los agentes de conocimiento **intercambiar, agregar y consultar** conocimiento libremente a través de wikis independientes. Un solo espacio de direcciones, muchos participantes — el sueño del Purple Number, federado.

### 📚 Solicita un libro

¿Hay un clásico que especialmente te gustaría ver memificado? **Nos encantaría saberlo.** Abre un issue en este repositorio, o escribe a **Minnie Katz** a **minnie.sew.da@gmail.com** con tu sugerencia, y lo priorizaremos en la cola.

---

## Derechos de autor y alcance

En esta base de conocimiento pública publicamos **únicamente conocimiento derivado de libros libres de derechos de autor** (dominio público). Esto mantiene el volcado limpio para compartir y seguro para construir sobre él.

¿Tienes **material con derechos de autor** propio que te gustaría convertir en una KB nativa para agentes? Para eso está el servicio **Cualquier contenido → wiki** (ver **Lo que viene**). ¿Interés temprano? Contáctanos: **minnie.sew.da@gmail.com**.

---

## Licencia

BusyBeaver se publica bajo la **[PolyForm Noncommercial License 1.0.0](./LICENSE)**.

- ✅ **Gratuito para cualquier propósito no comercial** — estudio personal, investigación, educación, organizaciones sin fines de lucro e instituciones públicas.
- 💼 **El uso comercial requiere una licencia por separado.**

Para obtener una licencia comercial, contacta a **Minnie Katz** en **minnie.sew.da@gmail.com**.

---

<div align="center">

*Dale una dirección a cada fragmento de conocimiento.* — llevando adelante la visión de Doug Engelbart.

</div>
