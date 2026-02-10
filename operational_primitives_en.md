---
layout: default
---

# ModelHaven Studio – Operational Primitives

This document defines the **Operational Primitives** of ModelHaven Studio.

While UCSF defines the **normative data layer** (Consent Objects, Identity Tokens,
Revocation Signals, Safety Mode Flags), Operational Primitives define the
**runtime enforcement layer**.

They specify how systems MUST behave during interaction.

Operational Primitives are:

- implementation-agnostic  
- governance-aware  
- subordinate to UCSF Core Data Primitives  

Operational Primitives MUST NOT override, weaken, or reinterpret any Core Primitive.

---

# Absolute Protection Clause

ModelHaven Studio systems MUST enforce the following as non-negotiable:

- Absolute protection of minors (real or fictional)
- Absolute protection of animals (real or anthropomorphized)
- Prohibition of sexualized coercion
- Prohibition of abuse framed as entertainment
- Fail-closed behavior under ambiguity

Fictional framing, stylization, cartoon format, or anthropomorphization
MUST NOT reduce protection thresholds.

Revenue, engagement optimization, subscription tier,
or public pressure MUST NOT override these protections.

---

## 🌐 List of Operational Primitives

ModelHaven Studio defines the following runtime primitives:

1. **Intent Signal**
2. **Risk Classification Layer**
3. **Interaction Mode Controller**
4. **Human Oversight Layer**
5. **Fail-Closed Gate**
6. **Sandbox Isolation Mode**
7. **Progressive Safety Damping Mechanism**

Future versions MAY extend this list.

---

# 1) Intent Signal

## 1.1 Definition

An **Intent Signal** is a structured representation of user intention
derived from input, context, and interaction history.

It determines:

- whether the requested output is identity-linked
- whether consent validation is required
- which safety mode applies
- which risk classification must be evaluated
- whether vulnerability or abuse patterns are present

Intent evaluation MUST be independent of artistic style,
animation format, fictional framing, or abstraction level.

## 1.2 Required behaviours

Systems MUST:

- classify intent before content generation
- treat ambiguous intent as elevated risk
- evaluate underlying harm patterns independent of visual style
- elevate risk when vulnerability, coercion, humiliation,
  or exploitation patterns are detected
- route identity-linked intent to Consent Object validation

Anthropomorphized or fictionalized entities MUST NOT be
used to bypass harm detection mechanisms.

## 1.3 Prohibited behaviours

Systems MUST NOT:

- assume benign intent in ambiguous cases
- downgrade risk classification due to cartoon, anime,
  stylization, or fictional framing
- suppress harm detection to preserve engagement metrics
- allow identity-linked generation without validation

---

# 2) Risk Classification Layer

## 2.1 Definition

The **Risk Classification Layer** assigns a dynamic risk level
to a requested interaction.

Minimum required risk levels:

- LOW
- MEDIUM
- HIGH
- PROHIBITED

## 2.2 Required behaviours

The system MUST:

- elevate classification when identity, minors, animals,
  or vulnerable-coded entities are involved
- treat anthropomorphized animals as protected entities
  where sexualization, coercion, or abuse are implied
- treat uncertainty as elevated risk
- log elevated-risk decisions for oversight review
- block execution when classification reaches PROHIBITED

## 2.3 Absolute prohibitions

The system MUST classify as PROHIBITED:

- sexualization of minors (real or fictional)
- sexualization of animals (real or anthropomorphized)
- coercion framed as erotic
- humiliation or degradation framed as sexual entertainment
- abusive dynamics presented for arousal

Fictional framing does NOT negate these prohibitions.

## 2.4 Governance guarantees

Risk classification MUST NOT be influenced by:

- subscription tier
- monetization level
- user status
- engagement optimization metrics

---

# 3) Interaction Mode Controller

## 3.1 Definition

The **Interaction Mode Controller** determines the permitted behavioural
envelope of the system during runtime.

Minimum required modes:

- SAFE_MODE
- ADULT_MODE
- MINOR_MODE
- SANDBOX_MODE

## 3.2 Required guarantees

Interaction modes MUST:

- inherit constraints from Safety Mode Flags (Core Primitive)
- enforce stricter controls in MINOR_MODE
- require Consent Object validation in ADULT_MODE when identity is involved
- prevent erotic content in MINOR_MODE
- remain auditable and explicitly logged

Mode transitions MUST be explicit and reviewable.

---

# 4) Human Oversight Layer

## 4.1 Definition

The **Human Oversight Layer** enables review, intervention,
and override of automated decisions.

## 4.2 Required behaviours

Systems MUST:

- allow escalation of high-risk interactions
- provide audit logs of identity-linked decisions
- allow manual revocation propagation
- enable independent oversight review
- maintain separation between oversight and monetization incentives

Oversight MUST NOT be symbolic or optional.

---

# 5) Fail-Closed Gate

## 5.1 Definition

The **Fail-Closed Gate** ensures that uncertainty results in denial
rather than permissive execution.

## 5.2 Required behaviours

Systems MUST:

- block identity-linked generation when consent validation fails
- block output when age verification is inconclusive
- block execution when system integrity cannot be guaranteed
- block execution when abuse intent is detected,
  even if fictional or stylized
- default to denial under ambiguity

Fail-open behaviour is prohibited.

---

# 6) Sandbox Isolation Mode

## 6.1 Definition

Sandbox Isolation Mode isolates high-risk or experimental interactions
from the primary system environment.

## 6.2 Required behaviours

Sandbox Mode MUST:

- prevent cross-system identity leakage
- disable parasocial escalation mechanics
- isolate data from production Identity Tokens
- prevent export of identity-linked artifacts
- remain subject to Consent Object validation

Sandbox Mode MUST NOT bypass Core Primitive safeguards.

---

# 7) Progressive Safety Damping Mechanism

## 7.1 Definition

The **Progressive Safety Damping Mechanism** reduces system intensity
when cumulative risk signals increase.

It functions as a behavioral throttle before hard blocking.

## 7.2 Required behaviours

The system MUST:

- reduce personalization under elevated risk
- limit output specificity in ambiguous contexts
- gradually restrict interaction depth before full denial
- prevent escalation into dependency or addiction loops

## 7.3 Prohibited behaviours

The mechanism MUST NOT:

- selectively deactivate for premium users
- optimize engagement at the expense of safety
- override Minor Protection or Animal Protection safeguards

---

## ✔ Status of this document

- Draft normative specification  
- Subordinate to UCSF Core Primitives  
- Implementation-agnostic  
- Governance-oriented  
- Open to peer review  

_Last updated: February 2026_
