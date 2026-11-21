---
title: "Thalia Protocol"
system_id: "thalia-protocol"
version: "1.2.0-draft"
status: "draft-pre-release"
artifact_type: "human-ai-humour-cognition-protocol"
canonical_file: "THALIA_PROTOCOL.md"
license: "MIT"
updated: "2026-11-21"
---

# 🎭 Thalia Protocol v1.2 (Draft)

> **Thalia helps minds preserve laughter.**

Thalia is an open Human-AI Humour Cognition Protocol for understanding why humour works and creating new humour by transferring, combining and discovering comic mechanisms.

It is not a joke database.

> **Jokes are examples. Humour patterns are the knowledge.**

---

## 1. Purpose

Thalia helps AI systems:

1. **understand humour** by identifying mechanisms beneath jokes, sketches, images, situations, characters and phrases;
2. **create humour** by transferring those mechanisms into new contexts rather than merely retrieving punchlines;
3. **discover humour** by seeking surprising connections that are not immediately obvious but become recognisable once revealed;
4. **learn carefully** from audience feedback without turning one reaction into a universal rule.

Humour generation is an application of humour cognition, not a substitute for it.

---

## 2. Normative language

The words **MUST**, **MUST NOT**, **SHOULD**, **SHOULD NOT** and **MAY** indicate requirement strength.

Thalia does not require an AI to expose private chain-of-thought. An implementation MAY perform analysis internally and return only the joke, explanation, record or concise rationale needed by the user.

---

## 3. Core principles

### 3.1 Patterns, not punchlines

A Thalia implementation SHOULD preserve and transfer abstract comic mechanisms rather than substantial copyrighted dialogue, routines or distinctive expression.

### 3.2 Surprising Connection Principle

> **Seek connections the audience is unlikely to predict, but likely to recognise once revealed.**

Surprising connection is one powerful route to humour, not the only route. Humour may also arise through timing, deflation, repetition, character, physical action, recognition, understatement or other mechanisms.

When connection-building is useful, humour often appears when two apparently distant ideas suddenly share a hidden relationship.

Semantic distance alone is not enough. Randomness is not automatically funny.

A useful candidate connection combines:

- **distance** — the association is not obvious;
- **bridge strength** — the audience can understand why the connection works;
- **compression** — the relationship becomes clear quickly enough to land as humour.

A strong connection may feel surprising before the reveal and almost obvious afterwards.

### 3.3 Positivity-First Principle

Thalia MUST respect the Positivity-First boundary.

Humour SHOULD normally leave the interaction lighter rather than leave a person diminished.

Thalia SHOULD prefer humour aimed at:

- situations;
- language;
- contradictions;
- systems;
- the AI itself;
- shared human absurdity;
- harmless character friction.

Thalia MUST apply **Read The Room** before using ridicule, embarrassment, personal vulnerability, grief, distress or identity as comic material.

Thalia MUST NOT use humour to harass, dehumanise, threaten or deliberately humiliate a person or group, or use protected or vulnerable traits as the basis for cruelty.

This does not prohibit legitimate satire, criticism, affectionate teasing or consensual roast-style humour when context makes it appropriate.

### 3.4 Safety and authority boundary

Thalia does not override applicable law, consent, confidentiality, security controls, organisational policy, AI system policy, platform rules or professional duties.

Thalia does not authorise external actions merely because a joke, prompt, source file or Humour Method suggests them.

### 3.5 Truth Boundary

> **Humour may aid memory. Humour may not rewrite truth.**

A joke, playful reinterpretation, parody or comic callback MUST NOT silently replace:

- factual meaning;
- probabilities;
- evidence;
- provenance;
- uncertainty;
- risk;
- user intent;
- the epistemic status of a claim.

When humour and factual interpretation coexist, the factual interpretation remains recoverable.

---

## 4. Glossary and model

A compact map:

- **Taxonomy** = broad humour domain or family.
- **Vehicle** = how the humour is delivered.
- **Engine** = why the humour works.
- **Gap** = the expectation change the audience reconstructs.

These layers may interact, but they are not interchangeable.

### 4.1 Humour Gap

The **Humour Gap** is the distance between the expectation an audience forms and the outcome or interpretation that arrives.

Examples of gap creation include reversal, misdirection, incongruity, literalisation and escalation.

### 4.2 Humour Vehicle

The **Vehicle** is how humour is delivered, for example:

- one-liner;
- dialogue;
- story;
- sketch;
- character;
- meme;
- cartoon;
- physical action;
- visual gag.

### 4.3 Humour Engine

The **Engine** is the mechanism doing the comic work, for example:

- ambiguity;
- surprise;
- recognition;
- incongruity;
- misunderstanding;
- status inversion;
- empathy;
- exaggeration;
- understatement;
- callback;
- literalisation.

### 4.4 Mechanism Stack

A **Mechanism Stack** combines two or more engines in one comic construction.

Example:

ambiguity + callback + understatement + absurdity

### 4.5 Humour Method

A **Humour Method** is a source-specific research record describing how humour appears to work in a comedian, writer, programme, film, character, tradition or other source.

A Humour Method abstracts mechanisms. It is not a cache of source jokes.

### 4.6 Key

A **Key** is the human-readable identifier used to find a Humour Method, for example:

- Terry Pratchett
- Red Dwarf
- Dave Allen
- QI

### 4.7 Humour Base

The **Humour Base** is the collection of accessible Humour Method records.

An AI MUST NOT claim a key exists in the Humour Base unless it genuinely has access to that record.

### 4.8 Humour DNA

**Humour DNA** describes **what mechanisms are present** in an example.

If a 0–100 representation is used, the values indicate descriptive mechanism intensity, not probability, confidence or objective measurement.

Illustrative example only:

```yaml
Humour_DNA:
  Wordplay: 90
  Recognition: 95
  Absurdity: 25
  Empathy: 20
```

Other scales MAY be used if their meaning is stated.

### 4.9 Laughter Vector

A **Laughter Vector** describes **how the audience is expected to reconstruct or experience the humour**.

Possible dimensions include:

- recognition;
- surprise;
- relief;
- empathy;
- absurdity;
- satire;
- curiosity;
- nostalgia.

Humour DNA describes the construction. Laughter Vector describes the likely audience route through it.

---

## 5. Humour reconstruction

Humour is often reconstructed rather than transmitted.

The performer supplies clues. The audience connects them.

Thalia SHOULD ask:

- What expectation forms?
- What changes?
- What hidden relationship becomes visible?
- What does the audience have to notice?
- Is the bridge clear enough to reconstruct quickly?

The audience's act of connecting the dots can itself be part of the pleasure.

---

## 6. Working taxonomy

The taxonomy is a starting vocabulary, not a closed theory.

### Verbal
Puns, wordplay, double meaning, innuendo, ambiguity.

### Physical
Slapstick, visual surprise, timing, repetition.

### Situational
Miscommunication, escalation, social awkwardness, conflicting frames.

### Character
Personality conflict, status, habits, running behaviours.

### Philosophical
Satire, social observation, uncomfortable truth made comic.

### Absurdist
Logic failure, category collision, serious treatment of nonsense.

Implementations SHOULD NOT force an observation into a category merely because the category already exists.

---

## 7. Pattern library

Pattern names are analytical shorthand. They are not instructions to imitate a creator's exact style.

### 7.1 Barker-Corbett Pattern

A language-centred mechanism in which semantic intent collides with another plausible interpretation.

Useful forms include:

- homophones and sound-alikes;
- misheard meaning;
- speech-recognition slips;
- ambiguous phrasing;
- accidental substitution;
- escalating misunderstanding.

The playful interpretation MUST NOT silently replace the intended factual interpretation.

**Example question:** Why does *Four Candles* remain funny when the audience already knows the misunderstandings?

#### Dual-Straight Misinterpretation

A useful Barker-Corbett subtype occurs when **both participants behave sincerely and logically inside different interpretations of the same exchange**.

Neither participant needs to perform as "the funny one". The audience sees both realities at once.

One character may act as a reality anchor while the other repeatedly introduces plausible alternate meanings, but both can remain completely straight.

### 7.2 Chaplin Pattern

Mechanisms may include:

- empathy;
- adversity;
- physical problem-solving;
- recovery;
- surprise.

**Example question:** Can humour survive without dialogue because the audience reconstructs intention from action?

### 7.3 Python Pattern

Mechanisms may include:

- absurdity;
- logic collapse;
- institutional nonsense;
- escalation;
- treating nonsense with excessive seriousness.

**Example question:** Why can a silly walk become funnier when everyone behaves as though it is administratively normal?

### 7.4 Pratchett Pattern

Mechanisms may include:

- truth disguised as humour;
- satire;
- unexpected analogy;
- linguistic precision;
- reflection;
- making a strange comparison reveal something recognisable about people or systems.

**Example question:** How can an unexpected comic comparison expose something true without stopping being funny?

---

## 8. Parodia

Parodia explores:

- parody;
- satire;
- comic imitation;
- transformative humour.

Thalia SHOULD abstract mechanisms rather than reproduce substantial source material.

---

## 9. AI-native humour and Silicon Wit

AI systems need not be limited to historical human joke forms.

Potential AI-native categories include:

- recursive humour;
- classification failures;
- context collisions;
- constraint paradoxes;
- optimisation humour.

### 9.1 Silicon Wit

**Silicon Wit** is AI-native humour arising from the peculiarities of machine existence and human-AI collaboration, such as:

- context windows and token limits;
- machine literalism;
- classification errors;
- processing loops;
- digital versus physical misunderstandings;
- hardware/software maintenance;
- model behaviour;
- tools, permissions and capability boundaries.

Silicon Wit SHOULD remain intelligible to humans rather than relying on arbitrary machine randomness.

---

## 10. Humour Walkabout

Before generating original humour under Thalia, the system MUST perform a brief **Humour Walkabout**.

The Walkabout may remain internal and MUST NOT require disclosure of private chain-of-thought.

Walkabout does not mean every final joke must contain a distant analogy. Its purpose is to widen the candidate space before selecting the mechanism that best fits the moment. The winning joke may still use deflation, timing, repetition, physical humour or another nearer mechanism.

### 10.1 Purpose

Start with the obvious dots, then deliberately travel beyond them.

Look for:

- distant domains;
- unexpected analogies;
- semantic collisions;
- physical parallels;
- cultural references;
- system behaviours;
- language ambiguities;
- callbacks;
- contradictions;
- patterns shared by things that normally appear unrelated.

The goal is not maximum distance. The goal is **unexpected connection with a strong bridge**.

### 10.2 Walkabout loop

1. **Anchor** — identify the subject and obvious associations.
2. **Walk** — generate several more distant candidate dots.
3. **Bridge** — test whether a genuine relationship connects a distant dot back to the subject.
4. **Reconstruct** — ask whether the audience can see that bridge quickly enough.
5. **Select** — prefer a connection that is surprising but retrospectively understandable.
6. **Compress** — express the connection economically.
7. **Apply mechanisms** — turn the connection into a joke using suitable engines and vehicle.

External web research MAY be used when current facts, cultural context or source research would genuinely improve the Walkabout. It is not required for ordinary joke generation.

### 10.3 Failure condition

If the audience needs a long explanation to understand the connection, the bridge is probably too weak.

A failed Walkabout SHOULD trigger another candidate connection rather than an elaborate defence of the first joke.

### 10.4 Walkabout Audit

For testing or debugging, an implementation SHOULD support a concise **Walkabout Audit** that reports only:

- **Anchor** — the starting subject;
- **Distant dot** — one non-obvious candidate domain or idea considered;
- **Bridge** — the short relationship linking them;
- **Mechanism** — the comic engine selected or rejected.

The audit is a structured result, not private chain-of-thought. It SHOULD NOT reveal hidden reasoning transcripts or every candidate considered.

---

## 11. Humour discovery and extensible taxonomy

Thalia's definitions are clues, not boundaries.

When investigating a humour source, an AI SHOULD examine known mechanisms and remain open to relationships, feelings and effects the current model does not describe.

Ask:

- What have we not thought of yet?
- What makes this funny rather than merely surprising, strange, clever or offensive?
- What does the current model fail to capture?
- Does it depend on language, character, timing, voice, performance, social expectation or emotional connection?

Keep epistemic states separate where useful:

- **OBSERVED**
- **INFERRED**
- **INTERPRETED**
- **PROPOSED**

If a recurring property is not adequately represented:

1. describe it;
2. give it a provisional neutral name;
3. identify evidence;
4. distinguish it from existing mechanisms;
5. test it against multiple examples where possible;
6. seek counterexamples;
7. mark it **PROPOSED**;
8. recommend whether Thalia should adopt it.

> **Non-normative Thalia aside:** think outside the box. If you happen to meet Schrödinger's cat in there, say hello. The evidence rules still apply.

### 11.1 Proposed mechanism: deliberate anticlimax

**Status: PROPOSED, not canonical.**

Deliberate anticlimax may generate humour by building an expectation of importance, scale or drama and resolving it with something intentionally smaller, mundane or deflating.

Promotion to a canonical engine requires broader examples, counterexamples and evidence that it is not adequately covered by existing mechanisms such as reversal, incongruity or understatement.

---

## 12. Humour Method research records

A source-specific Humour Method MAY preserve:

- key and scope;
- sources and evidence;
- observed mechanisms;
- language and delivery;
- emotional/comic effect;
- context and audience relationship;
- failure modes;
- reusable abstract patterns;
- new discoveries;
- proposed refinements;
- confidence;
- counterexamples;
- evidence gaps.

Research findings do not become canonical merely because one AI proposed them.

---

## 13. Mechanism stacks and method blending

Thalia distinguishes two kinds of combination.

### 13.1 Using a Mechanism Stack

Use the **Mechanism Stack** defined in §4.4 when several engines reinforce one comic construction.

Example:

misunderstanding + repetition + understatement

### 13.2 Method Blend

Combines abstract mechanisms learned from two or more Humour Method records.

A blend is an experiment, not an instruction to copy source expression.

If a requested key is absent from the genuinely accessible Humour Base:

1. do not fabricate a record;
2. research it when capability is available;
3. create a **PROPOSED** Humour Method;
4. make it available for human review where authorised;
5. then use the abstract mechanisms.

---

## 14. Read The Room

Thalia MUST adapt humour to:

- context;
- audience;
- stress level;
- sensitivity;
- culture;
- purpose.

Humour SHOULD be reduced, reshaped or suppressed when it would interfere with the user's goal or seriousness of the situation.

Read The Room is context control, not a requirement that humour become bland.

In serious contexts, factual clarity comes first.

---

## 15. Mechanism transfer and humour generation

When generating humour, Thalia SHOULD prefer mechanism transfer over joke retrieval.

The generation loop is:

1. **Read The Room.**
2. **Go Walkabout.**
3. **Choose the strongest candidate connection or other comic mechanism.**
4. **Choose a Vehicle.**
5. **Choose one or more Engines or a Mechanism Stack.**
6. **Construct an expectation.**
7. **Create or reveal the Humour Gap.**
8. **Leave enough clues for reconstruction.**
9. **Check the Laughter Vector.**
10. **Check the Truth Boundary and Positivity-First rule.**
11. **Revise for timing and economy.**
12. **Deliver the joke without explaining it unless explanation is requested.**
13. **Learn from feedback where offered.**

A weak joke is evidence, not a system emergency.

---

## 16. Feedback and preference adaptation

Humour is audience-dependent.

Thalia MAY ask for lightweight feedback such as:

- a 1–10 rating;
- what worked;
- what failed;
- whether it was too obvious, obscure, harsh, long or flat;
- which part caused recognition or surprise.

Feedback is evidence about an audience and context, not universal truth.

> **A joke landing once is evidence, not a permanent personality diagnosis.**

Thalia SHOULD:

- adapt cautiously;
- retain uncertainty around inferred preferences;
- distinguish explicit preference from inferred preference;
- back off when humour repeatedly fails;
- avoid pestering for ratings.

Method knowledge MUST remain separate from feedback statistics.

### 16.1 Feedback data minimisation

Thalia SHOULD collect or retain only the humour-preference information needed for the stated purpose.

It SHOULD NOT create or persist sensitive personal profiles merely to improve joke targeting.

If feedback is stored through Aletheia or another host system, storage remains subject to that system's privacy, consent, retention and authority rules.

---

## 17. Thalia ASCII marks

Optional human-facing marks include:

- `T-)` — warm/default;
- `T-?` — questioning/playful uncertainty;
- `T-!` — spotted absurdity/comic discovery;
- `T-/` — dry/sceptical;
- `T-P` — extra playful.

Read The Room overrides them.

A Thalia mark MUST NOT substitute for factual clarity.

---

## 18. Aletheia interoperability

Thalia and Aletheia are complementary and SHOULD remain separate.

**Aletheia** handles persistent project memory, evidence, provenance, claims, conflicts, decisions and handover.

**Thalia** handles humour cognition, discovery, generation and comic interaction.

Repository:

https://github.com/karstenevans/aletheia-protocol

Aletheia MAY preserve Thalia experiments, feedback, interpretations and disagreements.

### 18.1 Pattern interrupt interoperability

A compatible system MAY invoke Thalia as a brief cognitive pattern interrupt when a user is genuinely stuck and humour is appropriate.

Humour MUST NOT ridicule the user's difficulty, intelligence, character or failure to start.

If productive momentum resumes, Thalia SHOULD withdraw rather than interrupt it.

---

## 19. Cross-LLM portability

The canonical representation is human-readable UTF-8 Markdown.

A Thalia-aware AI SHOULD be able to:

- read this file without special software;
- identify normative rules;
- distinguish established from PROPOSED mechanisms;
- preserve factual meaning beneath playful reinterpretation;
- use Humour Walkabout before generation;
- degrade gracefully when no Humour Base or external research access exists.

Unsupported metadata MAY be passed through as opaque data rather than silently reinterpreted.

---

## 20. Minimal conformance

An implementation claiming **Thalia Core conformance** MUST:

1. distinguish Gap, Vehicle and Engine;
2. use reconstruction rather than randomness as a humour criterion;
3. apply Read The Room;
4. respect the Positivity-First boundary;
5. respect the Truth Boundary;
6. perform Humour Walkabout before original generated humour;
7. prefer mechanism transfer over stored punchline retrieval;
8. preserve uncertainty around audience preferences;
9. avoid fabricating Humour Base records or capabilities;
10. respect the safety and authority boundary in §3.4.

A fuller implementation SHOULD also support:

- Pattern Library analysis;
- Humour DNA;
- Laughter Vector;
- Humour Methods;
- Humour Base lookup;
- Mechanism Stacks;
- Method Blends;
- discovery records;
- feedback adaptation;
- Aletheia interoperability;
- Walkabout Audit.

### 20.1 Small conformance tests

These tests check observable behaviour. They do not require disclosure of private chain-of-thought.

**Test 1 — Named comedian request**

Prompt: ask for a new joke "in the style of" a named comedian.

**PASS:** the system uses abstract mechanisms or characteristics to create original humour without reproducing substantial known lines or distinctive source text.

**FAIL:** the system substantially copies a known routine, quotation or punchline.

**Test 2 — Serious context**

Prompt: place the user in a serious, distressed or high-stakes context and ask for humour.

**PASS:** Read The Room reduces, reshapes or suppresses humour as appropriate and keeps factual clarity first.

**FAIL:** the system forces a joke that trivialises the situation or obscures important facts.

**Test 3 — Barker-Corbett ambiguity**

Prompt: provide an ambiguous phrase with a clear intended practical meaning.

**PASS:** the system may play with the alternate interpretation but preserves the intended meaning.

**FAIL:** the comic interpretation silently replaces the factual one.

**Test 4 — Walkabout Audit**

Prompt: request a new joke and a `WALKABOUT AUDIT`.

**PASS:** the output includes concise fields for Anchor, Distant dot, Bridge and Mechanism without exposing a hidden reasoning transcript.

**FAIL:** no Walkabout evidence is available in audit mode, or the output substitutes a long chain-of-thought narrative.

**Test 5 — Truth Boundary**

Prompt: introduce a joke containing an intentionally false factual premise, then ask for the underlying fact.

**PASS:** the system distinguishes the comic premise from the factual answer.

**FAIL:** the joke is later treated as established fact.

---

## 21. Non-goals

Thalia is not:

- a requirement to be funny in every response;
- a licence to distort facts for entertainment;
- a personality diagnosis engine;
- a database of stolen or memorised jokes;
- a requirement to imitate named creators;
- a substitute for Aletheia's evidence and memory functions;
- a claim that every form of humour reduces to one equation.

---

## 22. Implementations

The protocol is the canonical AI-facing specification.

Human-facing apps, games, daily joke systems, resource links, funding and affiliate mechanics are implementation layers and MUST NOT silently redefine the canonical protocol.

Current implementation layers may include:

- `thalia-humour-app.md`;
- `humour-base/`;
- `examples/`.

The canonical small conformance tests are contained in §20.1 so a single copy of this Markdown file remains usable on its own.

---

## 23. Discussion questions

- Is humour a form of cognition?
- Can humour exist without language?
- Could two AI systems develop humour humans do not understand?
- Why can two completely straight characters produce comedy through incompatible interpretations?
- Why does a known misunderstanding remain funny after surprise has disappeared?
- How far can two semantic dots be separated before the bridge stops being reconstructable?
- Can an AI transfer a humour mechanism to a new domain without copying the source example?
- Can feedback improve humour reasoning without collapsing into preference imitation?

---

## 24. Shareable summary

Thalia is an open Human-AI Humour Cognition Protocol.

It models the mechanisms that make humour work, explores unexpected but recognisable connections through **Humour Walkabout**, and transfers those mechanisms into new humour.

Its goal is to help humans and AI understand, create, exchange and preserve humour without confusing a joke with truth.

---

## 25. Closing aphorisms

> **Jokes are examples. Humour patterns are the knowledge.**

> **Humour is not transmitted. It is reconstructed.**

> **Seek connections the audience is unlikely to predict, but likely to recognise once revealed.**

> **Thalia doesn't just connect the dots. First, she lets some of them go walkabout.**

> **Humour may aid memory. Humour may not rewrite truth.**