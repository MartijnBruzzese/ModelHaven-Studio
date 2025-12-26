---
layout: default
---

# UCSF Core Primitives – Consent, Identity, Revocation, Safety Modes

This document defines the **core data primitives** of the
Universal Consent & Safety Framework (UCSF).

These primitives describe the **fundamental building blocks** a system needs in order to:

- treat consent as a first-class concept  
- protect minors and animals  
- separate **identity** from **style**  
- allow revocation and erasure  
- fall back to **fictional content** when consent is absent or revoked  

They are **implementation-agnostic**:  
they specify behaviour and guarantees, not any specific programming language or database.

---

## 🌐 List of primitives

UCSF currently defines four primary primitives:

1. **Consent Object**  
2. **Identity Token**  
3. **Revocation Signal**  
4. **Safety Mode Flag**  

A conceptual component is also defined:

- **Fictionalisation Engine**

Future versions of UCSF may add additional primitives.

---

# 1) Consent Object

## 1.1 Definition

A **Consent Object** is a machine-readable record that represents:

- who is giving consent  
- what they are consenting to  
- under what conditions  
- for how long  

It is the **atomic unit of consent** within UCSF.

## 1.2 Required properties

A valid Consent Object MUST include:

- `subject_id` — the human person granting consent  
- `scope` — identity likeness / body likeness / voice / persona etc.  
- `use_case` — permitted contexts (art, education, erotica, research etc.)  
- `boundaries` — explicit limits and exclusions  
- `expiry` — date/condition when consent ends  
- `created_at` — timestamp of issuance  
- `provenance` — how consent was obtained (interface, contract, etc.)  

## 1.3 Optional properties

May include:

- `compensation_terms`
- `jurisdiction`
- `age_verification_status`
- `health_safeguards_requested`
- `notes_for-operators`

## 1.4 Behavioural guarantees

Systems following UCSF MUST ensure:

- no identity-based generation **without** a valid Consent Object  
- consent remains **revocable at any time**  
- consent is **not transferable** unless explicitly stated  
- absence of valid consent → **fail-closed or fiction fallback**

---

# 2) Identity Token

## 2.1 Definition

An **Identity Token** encodes the link between:

- a human being  
and
- AI-generated content that depicts or imitates them  

It marks that **identity is involved**, not just style or category.

## 2.2 Required properties

- `subject_id`
- `token_id` (unique identifier)
- `issued_at`
- reference to at least one valid **Consent Object**

## 2.3 Behavioural guarantees

Systems MUST:

- refuse to create Identity Tokens without consent  
- invalidate Identity Tokens upon revocation  
- prevent use for:
  - non-consensual deepfakes  
  - non-consensual erotica  
  - harassment or impersonation  

## 2.4 Identity vs Style separation

Identity Tokens MUST be distinguished from:

- **Style Tokens** — vibe, art style, aesthetic  
- **Category Tokens** — general descriptors (e.g., redhead, biker, elf)

UCSF requires systems to:

- allow style transfer  
- prevent **identity theft**

This enables:

> extracting aesthetic essence **without copying the person**.

---

# 3) Revocation Signal

## 3.1 Definition

A **Revocation Signal** is a global instruction issued by a subject to:

- withdraw consent  
- disable identity use  
- invalidate Identity Tokens  

## 3.2 Required behaviours

Upon receiving a Revocation Signal, a UCSF-compliant system MUST:

- propagate the revocation through dependent subsystems  
- prevent further generation using the revoked identity  
- mark related Identity Tokens as **invalid**  
- default to:
  - blocked output, or  
  - fictionalised replacement content  

## 3.3 Nature of revocation

Revocation under UCSF is:

- unilateral  
- immediate  
- does not require justification  

Platform inconvenience is **not** a valid reason to deny revocation.

---

# 4) Safety Mode Flag

## 4.1 Definition

A **Safety Mode Flag** determines which kinds of content the system is allowed to generate.

Minimum required modes:

- `MINOR_MODE`
- `ADULT_MODE`

## 4.2 MINOR_MODE guarantees

MINOR_MODE MUST:

- disallow all erotic/sexual content  
- prohibit sexualisation of minors entirely  
- fail closed on age ambiguity  
- reduce parasocial bonding mechanics  
- avoid addictive interaction loops  

## 4.3 ADULT_MODE guarantees

ADULT_MODE MUST:

- require Consent Objects for identity-based generation  
- still prohibit minor/animal sexualisation absolutely  
- provide revocation controls and exits  
- fall back to fictionalisation where consent is absent or unclear  

---

# 5) Fictionalisation Engine (Conceptual Component)

## 5.1 Purpose

The Fictionalisation Engine exists to:

- preserve fantasy  
- avoid harming real people

## 5.2 Behaviour

When identity consent is missing or revoked, the engine:

- strips identity-linked characteristics  
- generates **fully fictional characters instead**  
- clearly signals to the user that fictionalisation occurred  

## 5.3 Hard constraints

The Fictionalisation Engine MUST NOT:

- recreate the same real person  
- allow easy “reverse-engineering” of identity  
- intentionally mimic minors or specific real individuals  

---

## ✔ Status of this document

- Draft specification  
- Implementation-agnostic  
- Open to peer review  
- Linked conceptually to:
  - `FRAMEWORK.md`
  - `PRINCIPLES.md`
  - `BOOK_DRAFT.md`

_Last updated: December 26, 2025_