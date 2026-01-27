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