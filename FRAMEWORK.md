---
layout: default
title: Framework — UCSF
---

# UCSF — Framework Architecture
### Universal Consent & Safety Framework

**Version:** v1.0  
**Last updated:** January 2026  
**Author:** Martijn Bruzzese

---

## Purpose

This document describes UCSF as a **normative system architecture**.

It explains how ethical principles are translated into structural design constraints for digital and AI systems that affect consent, identity, safety, power asymmetry, and environmental impact.

This document does not specify products, APIs, or implementations.

---

## UCSF as Architectural Framework

UCSF operates at three interconnected layers:

1. **Normative Layer**  
   Defines ethical boundaries and responsibilities.

2. **Structural Layer**  
   Translates norms into system-level constraints.

3. **Governance Layer**  
   Defines human oversight, accountability, and repair mechanisms.

These layers function together to prevent ethics from being reduced to policy alone.

---

## From Principles to Architecture

UCSF principles become enforceable through architectural commitments:

- Consent is modeled as system state  
- Absence of consent defaults to refusal  
- Safety failures resolve through fail-closed behavior  
- Identity integrity is protected structurally  
- Ethical refusal is a valid system outcome  
- Human oversight remains mandatory  
- Environmental pressure is treated as design constraint  

These commitments operate independently of user intent or platform incentives.

## Traceability Overview

```mermaid
flowchart TD

%% Principles
P1[Consent as Condition]
P2[Safety by Design]
P3[Ethical Refusal]
P4[Power ↔ Responsibility]
P5[Repair Obligation]
P6[Human Oversight]
P7[Non-Human Protection]
P8[Environmental Limits]

%% Framework
F1[Fail-Closed Architecture]
F2[Consent Provenance]
F3[Identity Integrity]
F4[Risk Classification]
F5[Human Escalation Paths]
F6[Environmental Constraints]

%% Use Cases
U4[Use Case 4: Minors Boundary Drift]
U15[Use Case 15: Cross-Platform Image Misuse]
U16[Use Case 16: Coordinated Abuse Networks]

%% Open Questions
Q1[Revocation Propagation]
Q2[Cross-System Accountability]
Q3[Dependency Detection]
Q4[Sustainable Scaling]

%% Links Principles -> Framework
P1 --> F2
P2 --> F1
P3 --> F1
P4 --> F5
P5 --> F5
P6 --> F5
P7 --> F3
P8 --> F6

%% Framework -> Use Cases
F1 --> U4
F2 --> U15
F3 --> U15
F5 --> U16
F2 --> U16
F6 --> U15

%% Use Cases -> Open Questions
U4 --> Q1
U15 --> Q2
U16 --> Q2
U16 --> Q3
U15 --> Q4

---

## Fail-Closed Design

UCSF requires systems to default to safety under uncertainty.

Examples include:

- unclear consent  
- ambiguous identity  
- elevated vulnerability  
- insufficient age verification  

In such cases, systems must reduce capability or refuse interaction rather than proceed.

Fail-open behavior is treated as architectural error.

---

## Separation of Norms and Implementation

UCSF explicitly separates:

- ethical definition  
from  
- technical realization  

UCSF defines *what must be true*.  
Implementations determine *how it becomes true*.

ModelHaven Studio represents one possible architectural exploration, not a requirement.

---

## Human Oversight and Repair

Automated systems must not replace moral responsibility.

UCSF requires:

- meaningful human intervention pathways  
- transparent refusal logic  
- mechanisms for remediation  
- auditability for accountability  

Repair is considered part of system architecture, not post-incident public relations.

---

## Environmental Responsibility

Large-scale AI systems exert pressure on:

- energy infrastructure  
- water resources  
- ecological systems  

UCSF treats environmental impact as an ethical design constraint rather than operational externality.

Systems must not optimize performance while externalizing ecological harm.

---

## Relationship to Other Frameworks

UCSF aligns with existing ethical efforts such as:

- UNESCO AI Ethics  
- OECD AI Principles  
- IEEE Ethically Aligned Design  
- EU AI Act  

UCSF extends these by addressing:

- consent as system primitive  
- identity integrity  
- parasocial risk  
- intimate AI interaction  
- non-human protection  
- architectural enforcement of ethics  

---

## Positioning

UCSF is:

- a normative framework  
- open to peer review  
- adaptable across jurisdictions  
- not a certification system  
- not a compliance label  

Ethical authority is not claimed.

Transparency is prioritized.

---

*This framework document defines UCSF v1.0 architecture and will not be substantively altered without formal versioning.*