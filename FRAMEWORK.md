---
layout: default
title: README
---

# UCSF – Universal Consent & Safety Framework

The **Universal Consent & Safety Framework (UCSF)** is the ethical and technical foundation of ModelHaven.

UCSF defines how AI systems that touch **intimacy, erotica, identity, minors, and parasocial relationships** must be designed in order to remain humane, non-exploitative, and rights-respecting.

UCSF is not a product or platform.

It is a **framework**:
- for designers and engineers
- for platform operators
- for regulators and policymakers
- for creators and subjects whose identity and likeness may be used

ModelHaven is a **reference implementation concept** of UCSF.

---

## 1. Purpose

UCSF exists to:

- prevent **non-consensual sexualisation**
- prevent **sexualisation of minors and animals**
- reduce **exploitation of creators**
- protect people from **parasitic parasocial dependency**
- make **consent, revocation, and safety core system functions**
- replace “generate now, moderate later” with **safety-by-design**
- default to **fiction**, not real people, when consent is absent or unclear

UCSF assumes:

> safety failures should fail-closed, not fail humans.

---

## 2. Scope

UCSF applies to systems involving:

- generative AI images and video
- companion chatbots and AI romance systems
- synthetic influencers and virtual personas
- erotic or NSFW content creation
- deepfakes and face/voice replacement
- platform environments monetising intimacy or persona

UCSF does **not** attempt to regulate:

- ordinary search engines
- purely non-intimate productivity tools
- general non-erotic creative tools unless misused

---

## 3. Core Principles

1. **Consent is a system primitive**  
   Consent is not a checkbox or pop-up.  
   It is an object in the system with state, duration, and scope.

2. **Revocation is a right, not a courtesy**  
   Consent may be withdrawn.  
   Systems must support creator-controlled **kill-switches**.

3. **Fail-closed by default**  
   If safety or consent cannot be verified, output stops or becomes fictional.

4. **Minors and animals are never sexualised**  
   No exceptions.  
   No “artistic context”.  
   No age-play that eroticises children.

5. **Fictionalisation fallback**  
   Where real-person consent is absent, the system:
   - extracts **style/essence without identity**
   - switches to a **fully fictional character**

6. **Transparency and auditability**  
   Users should know:
   - when fictionalisation has occurred
   - how consent applies to content
   - how to revoke consent

7. **Creator autonomy and dignity**  
   Systems must not treat creators as discardable supply.

8. **Trauma-aware design**  
   Avoid features that intentionally prey on:
   - loneliness
   - grief
   - addiction
   - attachment vulnerability

---

## 4. System Components

UCSF defines several conceptual building blocks:

- **Consent Object**  
  Machine-readable record of scope, duration, and terms of consent.

- **Identity Token**  
  Represents a creator/subject’s identity or likeness.

- **Safety Mode**  
  Clearly separates:
  - Adult Mode
  - Minor Mode (sealed, non-sexual, non-interactive)

- **Revocation Signal**  
  Allows immediate global withdrawal of consent and likeness.

- **Fiction Engine**  
  Automatically generates **non-referential fictional substitutes**.

- **Audit Trail**  
  Privacy-respecting logs for dispute resolution and regulator review.

(Consent Object and Identity Token will be specified formally in a separate section.)

---

## 5. Minors and Animals — Absolute Protections

This is a **zero-tolerance domain**.

UCSF requires:

- no experiential sexualisation of minors, in any form
- no depiction that eroticises minors, even “aged-up”
- sealed, non-interactive minor experiences
- age-affirming, supportive, educational content only
- animals not used for sexual gratification or fetish imagery

Ambiguity → fail-closed.

If age cannot be confidently established → no generation.

---

## 6. ModelHaven — Reference Implementation Concept

ModelHaven is:

- a **refuge metaphor**
- a **platform architecture concept**
- a **test-bed idea** for implementing UCSF in practice

Where UCSF says **what must be true**,  
ModelHaven explores **how systems can make it true**, including:

- consent object management
- creator dashboards
- revocation propagation
- safe-mode defaults
- automatic fictionalisation pipelines
- sealed minor spaces
- trust & safety operational design

ModelHaven is not the only way to implement UCSF.  
It is **one proposed blueprint**.

---

## 7. Relationship to Existing Frameworks

UCSF complements — but goes beyond — traditional AI ethics work by addressing:

- erotic content
- AI intimacy
- parasocial dependence
- creator exploitation
- minors & CSAM in AI systems

It can be mapped against:

- UNESCO AI Ethics
- OECD AI Principles
- EU AI Act risk categories
- IEEE Ethically Aligned Design

but fills the **missing “intimacy & erotics” chapter**.

---

## 8. Implementation Readiness Levels

UCSF recognises three maturity stages:

- **Conceptual**  
  Ethical structure defined (this repo).

- **Prototype**  
  Technical primitives implemented in limited environments.

- **Operational**  
  Platforms, models, and regulators adopt compliant systems.

This project is currently at: **Conceptual → entering Prototype design phase**.

See `STATUS.md`.

---

## 9. Next Documents

For deeper detail:

- 🎯 Principles – `PRINCIPLES.md`
- 🧩 System primitives (Consent & Identity Token spec) – coming next
- 📚 Book draft – `BOOK_DRAFT.md`
- 🧪 Open Questions – `OPEN_QUESTIONS.md`

---

_Last updated: December 26, 2025_