---
layout: page
title: "Swartzism: Principles"
permalink: /principles/
description: "The analytical machine: axioms, PII doctrine, guardrails, canon, taxonomy, open questions. Every claim carries a source."
---


The analytical companion to the Manifesto. Axioms, the PII doctrine, guardrails, the canon, taxonomy, and open questions. **v0.0.2 · Request for Comments** — every claim about the record carries a source; nothing here is invented.

---

## 1. Definition

**Swartzism** is a doctrine of information power derived from the record of Aaron Swartz: a claim about the moral status of knowledge (a commons), a claim about obligation (access creates duty), a claim about method (build and open), a claim about practice (analyze, then act), and a claim about politics (participation over purity) — all bounded by a single inviolable rule separating knowledge from persons (the PII boundary).

It is not a claim about what Swartz himself would have endorsed. It is a construction *from* his record — usable, testable, and open to revision.

## 2. The Five Axioms

| \# | Axiom | One-line meaning | Derivation from the record |
| --- | --- | --- | --- |
| I | **Knowledge is a Commons** | What is collectively produced belongs to everyone; enclosure is theft | Co-founded Creative Commons; RSS; Reddit's open-source kernel; `infojustice.org` essays on why information wants to be (and is) shared |
| II | **Access Creates Duty** | Holding a key is an obligation, not a privilege | "Guerrilla Open Access Manifesto": *"Those with access to these resources — students, librarians, scientists — you have been given a privilege. You get to feed at this banquet of knowledge while the rest of the world is locked out."* |
| III | **Build and Open** | Construction and openness are one praxis | Built the open web's core protocols (RSS, Creative Commons, Markdown, web.py, Open Library) *and* broke the PACER paywall *and* mass-downloaded JSTOR — two hands, one body of work |
| IV | **Analyze, Then Act** | Understand the machine before striking it | the SOPA strategy was data-driven politics (Demand Progress built influence from measured email campaigns); his essays dissect how closed systems resist evidence ("Look at yourself objectively", the Semmelweis essay) |
| V | **Participation Over Purity** | The goal is a changed world, not a pure movement | Demand Progress/Stop SOPA: a broad, impure coalition — librarians, tech giants, volunteers, senators — beat a powerful lobby; the coalition's breadth is documented in the Stop SOPA record |

### 2.1 Elaborations

**I — Knowledge is a Commons.** The public funds the research (taxes → grants → journals), writes the reviews, supplies the data; the journals sell it back. Same logic applies to court records (publicly funded justice, priced per page), government registries, and model weights trained on the public's corpus. Copying is non-destructive and non-rivalrous — so the *lock*, not the copy, is the harm. Note: this axiom is about knowledge **of the world**, not data **about persons** (see §4).

**II — Access Creates Duty.** The doctrine's most personally demanding axiom: privilege is a load, not a prize. It converts insider status into moral liability. Its institutional corollary: gatekeepers who will not open are accomplices to enclosure. Its limit: the duty is to *share*, not to *expose persons* — the PII boundary (§4) constrains how the duty may be discharged. Its mode (v0.2): service — opening, publishing, documenting, building. The duty never requires what could cost a keyholder their keys; the doctrine needs keyholders and must not tax them out of existence.

**III — Build and Open.** The praxis is a *couple*: opening without building leaves speeches — a demand with nothing behind it; building without opening becomes administration of the enclosure. The record suggests the order matters — build the open thing first, so the opening has a destination.

**IV — Analyze, Then Act.** Institutions are machines with seams: dockets, registries, procurement lists, minutes, APIs. Analysis is targeting. The strongest Swartzist artifacts are therefore *databases* (maps) that end in *strikes* (acts). Aggression without analysis is noise; analysis without action is a seminar.

**V — Participation Over Purity.** Purity is a luxury of those who can afford not to win. Coalitions that win are ugly and broad. Corollary: do not let the perfect analysis delay the necessary act, and do not let the beautiful act delay the winning coalition. Its hard lines (2026-10-14): participation forgives impurity; it does not suspend the doctrine. The distinction is **compromise vs. violation** — forgiveness covers what the allies are, never what the coalition's shared act does; judge the shared act, not the ally. Four lines bind every coalition: (1) **the boundary is not coalition-negotiable** — no ally, price, or trade touches person-data; (2) **no person-harm as method** — pressure the office, never the home; (3) **no new locks** — the shared act's output must be commons, not relocated enclosure; (4) **take help, not direction** — allies may be ugly; the agenda may not be bought. An ally's unrelated conduct is not a line — the 2012 coalition ran on corporate money and was legitimate — because the shared act itself must pass the tests (§5). This closes the Pass 1 stress-test on 'forgive the allies'; Q2 (who may act) remains open — these lines bind what coalitions do, not who gets to act.

## 3. The Ethics of Scale

Because information is non-rival, **scale compounds liberation and does not compound harm** — for knowledge.

- One copy dies with its server; a thousand mirrors cannot be deleted. Distribution is defense.
- Mass distribution is therefore mass liberation: the PACER stunt cost $0 in damage to the courts and freed a federal docket; JSTOR suffered no harm — only its business model did.
- The state, however, scales its response. The doctrine therefore includes a duty of care toward its own: anonymity for those who need it, voluntary martyrdom only, standing defense funds, institutional memory that outlives individuals.

The ethics of scale **inverts at the PII boundary** (§4): copying multiplies harm when the copied thing is a person's data. There, small is beautiful; there, deletion is mercy.

The **concealment answer.** The ethics of scale governs *distribution*, not *taking*: the single discreet copy is the same act as the mass mirror, just at lower scale. What makes scale liberation is that mirrors defeat deletion — so the quiet insider copy is the seed of scale, and the doctrine honors it as such. Secrecy is a tactical state, not a moral one. (Resolves Q1, Pass 1.)

## 4. The PII Doctrine

**"Liberate the world's knowledge. Defend each person's life."**

| Question | Knowledge (of the world) | PII (about a person) |
| --- | --- | --- |
| Ownership | A commons — belongs to everyone | Belongs to the person |
| Copying | Multiplies value | Multiplies harm |
| Hoarding | Enclosure — the sin | Privacy — often a right |
| Leaking | Liberation — the act | Harm — the crime |
| Doctrine | Liberate at scale | Protect absolutely |

### 4.1 The ownership test

The first question about any contested dataset is not *"should this be public?"* but *"who does this data describe?"*

- **Data about the world** (dockets, gazettes, registries, judgments, scientific literature, mapping data) → commons → liberate.
- **Data about a person** (health records, biometrics, private communications, browsing, location) → the person's own → protect.
- **Data about the powerful acting in their official capacity** → the power exercised is public business → the *act* is commons; the *person* (home, family, private life) is PII. Expose the contract, redact the life.

### 4.2 The asymmetry

The doctrine is deliberately asymmetric: the powerful's secrets are ours to expose, the weak's data is theirs to keep. This asymmetry is the point. Hoarded knowledge by institutions → liberate. Leaked PII of ordinary people → defend the people, strike the system that took their data. The custodian who hoards knowledge is the enemy; the liberator who leaks lives is worse.

### 4.3 The triage (decision procedure)

Given a contested dataset, apply in order:

1. **Does it describe persons?**
   - No → **Liberate** (axiom I; the ethics of scale applies).
   - Yes → go to 2.
2. **Who are those persons?**
   - Private individuals (weak) → **Protect absolutely.** Do not redistribute. Strike the system that collected/exposed it. If it is a breach dump, work for takedown and remediation, not propagation.
   - Officials acting in official capacity → go to 3.
3. **Does it expose the power or the person?**
   - The power (corruption, misconduct, decisions, contracts) → **Liberate the act**, redact the private life.
   - The person (home address, family, private communications) → **Protect.**

### 4.4 The hard case: power PII as an instrument of accountability

When official misconduct is *only provable through personal data* (e.g., a minister's demonstrable abuse documented via records that include personal details), the doctrine requires all four conditions before release:

1. **Imminence + gravity** — the harm being exposed is ongoing or severe;
2. **Minimality** — the least personal data that proves the act;
3. **Asymmetry** — the subject holds power over the people affected;
4. **Process** — a documented proportionality decision by more than one person, reviewable later.

The purpose of the four conditions is not to block release; it is to make the release *defensible* — because an accountability act that harms the innocent discredits the doctrine, not just the act.

### 4.5 Why the boundary is absolute

The doctrine has no chance without trust. Institutions will always argue that openness is a slippery slope to surveillance. Every time a "liberator" leaks ordinary people's data, they prove the institutions right. The boundary is not a policy choice within Swartzism; it is the load-bearing wall of the entire doctrine. It does not move. (Stress-test note: the doctrine should assume this will be attacked exactly there, by enemies and by the careless alike.)

## 5. The Guardrails

Any Swartzist act — before it is done — must pass three tests; any Swartzist text — before it is published — must pass a fourth:

1. **Intent test** — Does this liberate a commons, or harm a person? (→ §4 triage)
2. **Method test** — Is the transgression minimal, precise, and non-destructive to the system's *function* (only to its enclosure)? PACER: yes. Taking down a hospital's IT: no.
3. **Target test** — Is the strike aimed at the machine (institution, gatekeeper, business model), not at people? Institutions may be inconvenienced; persons may not be harmed. (Switching off a *gatekeeping service* — e.g., disabling a paywall, not a hospital — is legitimate; the former hurts a business model, the latter hurts lives.)
4. **Profession test** (doctrine texts) — Could someone safely say this aloud at work? A text that marks its professor as a leak risk fails the doctrine's own growth condition. The record may be described in full; the program may only command bounded-cost acts: build, open, publish, mirror, archive, map, organize, collect, keep. A doctrine that taxes its professors shrinks to martyrs.

Acts that fail any test are not Swartzist acts. They are merely illegal.

## 6. Taxonomy: Swartzism vs. Adjacent Doctrines

| Doctrine | Overlap | Difference |
| --- | --- | --- |
| **Stallmanism / free software** | The commons, the license | Stallmanism is a rule of *authorship* (what you write must be free); Swartzism is a rule of *access* (what the world makes must be open). Swartzism extends the commons from code to *all knowledge*, and permits transgression where Stallmanism asks for conversion |
| **Hacktivism** | Direct action | Hacktivism is spectacle; Swartzism is *redistribution* — the act's meaning is that knowledge changes hands, not that attention is captured. PII is a bright line hacktivism historically blurs |
| **Free culture** | Creative Commons | Free culture is about *permission regimes* for art; Swartzism is about *access regimes* for the public record. Swartzism treats access as owed, not licensed |
| **Effective Altruism** | Counterfactual thinking | EA optimizes *consequences* (and has, in its worst form, rationalized surveillance); Swartzism is a *rights* doctrine: the commons is owed, the boundary is absolute, regardless of marginal utility |
| **Pirate politics** | Copyright skepticism | Pirate parties are a *legislative* program; Swartzism is a *praxis* that includes legislation (Work 4) but does not stop there |
| **Open data / FOI** | Transparency | FOI asks; Swartzism takes. The request-framed world is the polite forecourt of the enclosure; Swartzism's patience for politeness is not infinite |

## 7. The Canon (acts that define the doctrine)

| Act | What happened | Why it's canon |
| --- | --- | --- |
| **PACER break-in (2008)** | Downloaded \~2.7M documents from the federal docket — public records sold at 8¢/page — and shared them | The pure case of Work 1: public data, artificial paywall, non-destructive, scaled liberation. No PII beyond what the courts themselves publish |
| **Guerrilla Open Access Manifesto (2008)** | The explicit statement: "those with access... you have been given a privilege... you have a duty to share" | The doctrine's founding text — axiom II in the author's own words |
| **Creative Commons / RSS / Markdown / web.py** | The open building blocks of the modern web | Axiom III's builder hand; the alternative exists because he built it |
| **Demand Progress / Stop SOPA (2011-12)** | Data-driven organizing that turned public outrage into a coordinated strike that killed the bill | Axiom V: participation over purity — the coalition included everyone from libraries to Google |
| **JSTOR mass download (2010-11)** | 4.8M articles — the act that killed him | The martyrdom: the state demanded 35 years for a non-destructive act of copying, then drove him to suicide. The wall's defenders had won every argument except the one that mattered, and everyone saw it. The doctrine keeps the whole arc — including the January 2011 escalation that ended in the charges — as a warning about state power, not a glory |
| **Bad Apple (2021)** | Aaron Swartz Day's suite of law-enforcement accountability tools, built in Swartz's name | Work 5's founding artifact — the institutional continuation of his policing critique, and the model for any Work 5 practice. *(Corrigendum: an earlier draft cited a 2010 essay "Bad Apples"; no such essay exists in the archived record — the project is ASD's, not a lost text.)* |

Sources: [Guerrilla Open Access Manifesto](https://archive.org/stream/GuerillaOpenAccessManifesto/Goamjuly2008_djvu.txt) · [PACER (law) — Wikipedia](https://en.wikipedia.org/wiki/PACER_\(law\)) · [JSTOR case — Wikipedia](https://en.wikipedia.org/wiki/United_States_v._Swartz) · [SOPA — Wikipedia](https://en.wikipedia.org/wiki/Stop_Online_Piracy_Act) · [Bad Apple announcement — Aaron Swartz Day](https://www.aaronswartzday.org/bad-apple-announcement) · [Semmelweis essay — Raw Thought](http://www.aaronsw.com/weblog/semmelweis) · [Career timeline — Wikipedia](https://en.wikipedia.org/wiki/Aaron_Swartz)

## 8. Open Questions (stress-test agenda)

1. **~~The concealment problem.~~** **Answered (Pass 1).** Axiom II says access creates duty — but the doctrine must protect the *quiet* leaker (the insider who copies one record out of loyalty to the commons). Answer: the ethics of scale governs *distribution*, not *taking* — one act, mirrored later by many, is still scale; secrecy is tactical, not moral. (Moved to §3.)
2. **The elite entry-point.** Does the doctrine hold if the liberation is performed *by the powerful* (a minister leaking her own government's docket) or *for profit* (a shadow library run as a business)? Participation over purity suggests yes, uncomfortably.
3. **Martyrdom logistics.** The state will punish Swartzist acts. Does the doctrine's duty of care (anonymity, defense funds) imply that *unattributable* acts are preferable to credited ones? (Swartz died famous; the anonymous leaker survives.)
4. **The AI-era extension.** Is a model trained on enclosed corpora a Swartzist act (Work 1 at scale) or a PII violation (if the corpus contains personal data)? The doctrine's answer is: it depends entirely on the corpus — the boundary, not the technology, decides. The triage (§4.3) must be run on the *training data*, and the burden is on whoever trained the model.
5. **The boundary under pressure.** What counts as "private life" of an official — and who decides? The four conditions (§4.4) handle the hard case, but the doctrine should admit this is the most contestable seam.
6. **Institutional capture.** When Work 4 (organize) succeeds — when open-access advocates sit inside the institutions — does the doctrine's breaking hand atrophy? The record suggests Swartz himself worried about this; the axiom III couple is the intended answer.
7. **The professing movement.** The v0.2 reframe made profession cheap by moving the program from breaking to opening. Does the cheapened profession blunt the doctrine's leverage — or was the leverage always in the claim ("the theft is the lock") rather than the verb? Working answer: the energy relocates from the verb to the claim; re-examine after first public deployment.

---

*Draft. The canon, the guardrails, and the open questions are maintained here so the manifesto can stay short and the doctrine can stay honest.*