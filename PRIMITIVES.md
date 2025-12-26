---
style: default

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

It marks that **identity is involved**, not