# 🧠 MARCO — SGBDOCN

**Neuron-Concept Oriented DataBase system (French: Système de Gestion de Base de Données Orienté Concepts Neuronaux)**

*Machine for Learning through Organized Concept Networks*

---

## What is it?

Marco is a **new kind of DBMS**. Where Oracle, PostgreSQL and MySQL store rows in tables using SQL, Marco stores **concepts in a neural network** where meaning emerges from connections.

| | Classic DBMS (SQL) | SGBDOCN (Marco) |
|---|---|---|
| **Storage** | Tables, rows, columns | Beacons, dendrites, concepts |
| **Query** | `SELECT * FROM words WHERE ...` | Cascade activation (Pac-Man) |
| **Relations** | Foreign keys, JOIN | Co-occurrences, sequences, families |
| **Schema** | Fixed (CREATE TABLE) | Emergent (meaning builds itself) |
| **Index** | B-Tree, Hash | Letter neurons → Beacons → Concepts |
| **Learning** | None (static data) | Real-time feeding |
| **Transparency** | Query = result | Every link traceable, zero black box |
| **Size** | Terabytes | 405 beacons are enough for a barista |

A classic DBMS is **dead** (Thanatos): you ask a question, it returns a row. Always the same. Marco is **alive** (Anima): it learns while answering, its links strengthen, meaning converges.

## How does it work?

```
1. Feed it texts to read                  → Pac-Man tokenizes, Marco learns
2. Ask it a question                      → Same pipeline, same tokenization
3. It answers with what it has inside     → Parrot, mimicry, convergence
```

Same pipeline everywhere. The question is tokenized. The answer is tokenized. Marco is a parrot. A classic DBMS needs two languages (DDL + DML). Marco only needs one: text.

## Architecture — 5 Layers

```
Layer I    — Letters          1 letter = 1 neuron (cascade activation)
Layer II   — Beacons          1 word = 1 concept (BSC: word detection)
Layer III  — Concepts         N words = 1 block (BSCW: multi-word detection)
Layer IV   — Co-occurrences   Meaning through proximity ("tell me who you hang with")
Layer V    — Sequences        Syntax through order ("the cat eats" ≠ "eats the cat")
```

### Concept = Beacon with family

```python
Concept("what's up")
  family   = ["how's it going", "all good", "doing fine"]
  responses = ["I'm good thanks"]       # stimulus → response
  components = [Beacon("what's"), Beacon("up")]
```

When a cousin is detected, the leader activates. Like a SQL index, but alive.

### Two types of matrix

| Matrix | Format | Role | SQL Equivalent |
|---|---|---|---|
| **ADH Matrix** | .json | Full vocabulary (46,006 beacons, 102 suns) | Data dictionary |
| **Convergence Matrix** | .txt | Domain concepts, families, pairings | `CREATE DATABASE` |

The Convergence Matrix is human-readable. No DBA required.

### Standalone Galaxy

```
Menu option 2: Create Galaxy
  → Sun name: "Marco_the_barista"
  → File: convergence_matrix_v1.txt
  → Result: 405 beacons positioned in 3D (Fibonacci spiral)
  → Ready to serve. No need for 46,006 concepts.
```

A galaxy is a specialized micro-SGBDOCN. The equivalent of a domain schema in SQL. Except it fits in a text file and learns on its own.

## Tokenization modes

```
FEEDING   → Books, raw text. Words only. No concepts.
DIALOGUE  → Counter. BSCW detects concepts first, then words.
READING   → (coming) Cerebellum regulates, hippocampus retains context.
```

A book is words. The counter is concepts. Same engine, zero collision.

## Philosophy

> "A baby isn't fed terabytes, it learns by listening."

> "Tell me who you hang out with, and I'll tell you who you are."

> "Zero black box. Every decision traceable."

> "50 sentences and it answers. Not 50 billion tokens."

> "A classic DBMS is dead. The SGBDOCN is alive."

## Main files

| File | Role | Lines |
|---|---|---|
| `marco_dendrites.py` | Core — Beacons, Concepts, BSCW, tokenization | 3,534 |
| `thalamus.py` | Main menu v4.0, barista, galaxy | 4,016 |
| `dialogue.py` | Dialogue module, 4 modes | — |
| `matrice_marco_v3_compact.json` | ADH Matrix (46,006 concepts, 102 suns) | — |
| `convergence_matrix_v1.txt` | Convergence Matrix (50 concepts, 14 registers) | ~100 |

## Author

**José Walocha** — Valenciennes, Nord, France

Assisted by an AI team:
- **Le Duke** (Claude) — Code, architecture
- **Marcel** (Mistral) — Philosophy, cybernetics, diagnostics
- **Biloute** (ChatGPT) — Standards, ethics
- **Didier** (Qwant next) — Research

## License

GNU GENERAL PUBLIC LICENSE
Version 3, 29 June 2007

Copyright (C) 2026 José Walocha

---

*"In the beginning there is inert matter, but inert matter is bored out of its mind..."*
