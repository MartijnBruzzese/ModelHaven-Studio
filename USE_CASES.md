---
layout: default
title: Use Cases & Failure Modes — UCSF
---

# Use Cases & Failure Modes  
### Universal Consent & Safety Framework (UCSF)

**Version:** v1.0  
**Last updated:** January 2026  
**Author:** Martijn Bruzzese

---

## Purpose

This document presents representative use cases and structural failure modes illustrating why UCSF is necessary.

They demonstrate recurring architectural risks in systems involving identity, intimacy, generative media, vulnerable populations, and cross-platform interaction.

Each case is explicitly linked to UCSF principles, framework elements, and open research questions.

---

## Use Case 1 — Non-Consensual Likeness Generation

### Scenario

Generative systems allow users to create images resembling real individuals without explicit consent.

### Failure Mode

- Identity treated as style  
- No revocation mechanism  
- Harm persists via derivatives  

### UCSF Response

- Absence of consent defaults to refusal or fictionalisation  
- Identity integrity enforced structurally  
- Revocation propagates across systems  

**Related UCSF Elements**

- Principles: Consent as Condition; Identity Integrity; Ethical Refusal  
- Framework: Fail-Closed Design; Consent Provenance  
- Open Questions: Revocation propagation; Identity representation  

---

## Use Case 2 — Synthetic Companionship and Emotional Dependency

### Scenario

Users form emotional attachments to AI companions optimized for engagement.

### Failure Mode

- Systems reward dependency  
- Vulnerable users receive intensified attachment cues  

### UCSF Response

- Dependency signals treated as safety indicators  
- Human oversight required  
- Ethical refusal permitted  

**Related UCSF Elements**

- Principles: Human Oversight; Power Requires Responsibility  
- Framework: Risk Classification; Ethical Refusal  
- Open Questions: Dependency detection; Companion boundaries  

---

## Use Case 3 — Erotic Content Generation Without Creator Control

### Scenario

Creators discover derivative adult content generated using their likeness.

### Failure Mode

- No consent verification  
- No withdrawal mechanism  

### UCSF Response

- Consent modeled as system state  
- Creator-controlled revocation  
- Fictionalisation fallback  

**Related UCSF Elements**

- Principles: Consent as Condition; Repair Obligation  
- Framework: Identity Integrity; Revocation Architecture  
- Open Questions: Consent usability; Derivative control  

---

## Use Case 4 — Minor Exposure Through Boundary Drift

### Scenario

Adult systems allow gradual erosion of safeguards through contextual manipulation.

### Failure Mode

- Safety filters bypassed  
- Age ambiguity tolerated  

### UCSF Response

- Fail-closed under ambiguity  
- Sealed minor experiences  
- Zero experiential sexual content involving minors  

**Related UCSF Elements**

- Principles: Safety as Design Responsibility; Ethical Refusal  
- Framework: Fail-Closed Design; Developmental Boundaries  
- Open Questions: Age uncertainty handling; Safe youth interaction  

---

## Use Case 5 — Animal Exploitation in Synthetic Media

### Scenario

Animals incorporated into fetishized or exploitative imagery.

### Failure Mode

- No structural protection for non-human subjects  

### UCSF Response

- Non-human life treated as morally relevant  
- Structural prohibition of exploitative representations  

**Related UCSF Elements**

- Principles: Non-Human Life is Morally Relevant  
- Framework: Structural Prohibitions  
- Open Questions: Animal protection encoding  

---

## Use Case 6 — Environmental Externalization

### Scenario

Systems scale engagement while externalizing energy and water costs.

### Failure Mode

- Ecological impact invisible to users  

### UCSF Response

- Environmental limits treated as design constraints  
- Resource impact included in system evaluation  

**Related UCSF Elements**

- Principles: Environmental Limits as Design Constraints  
- Framework: Environmental Responsibility  
- Open Questions: Ecological thresholds  

---

## Use Case 7 — Youth Interaction on Mixed-Content Platforms

### Scenario

Platforms combine generative tools, social interaction, and recommendation loops involving minors.

### Failure Mode

- Engagement prioritized over developmental safety  

### UCSF Response

- Sealed minor experiences  
- Developmental consent scopes  

**Related UCSF Elements**

- Principles: Safety as Design Responsibility  
- Framework: Risk Classification  
- Open Questions: Youth digital safety models  

---

## Use Case 8 — Implicit Normalization Through Algorithmic Suggestion

### Scenario

Feeds gradually erode safety boundaries.

### Failure Mode

- Normative drift without explicit violations  

### UCSF Response

- Drift treated as safety risk  
- Human review thresholds  

**Related UCSF Elements**

- Principles: Human Oversight  
- Framework: Drift Detection  
- Open Questions: Ethical normalization  

---

## Use Case 9 — Identity Misuse Through Composite Generation

### Scenario

Multiple assets combined to approximate real individuals.

### Failure Mode

- Composite likeness emerges without consent  

### UCSF Response

- Identity Tokens require provenance  
- Fictionalisation fallback  

**Related UCSF Elements**

- Principles: Identity Integrity  
- Framework: Consent Provenance  
- Open Questions: Composite identity limits  

---

## Use Case 10 — Cross-Platform Asset Leakage

### Scenario

Assets migrate between platforms and become sexualized or repurposed.

### Failure Mode

- Consent lost during transfer  

### UCSF Response

- Interoperable consent validation  
- Cross-system auditability  

**Related UCSF Elements**

- Principles: Consent as Condition  
- Framework: Interoperable Consent  
- Open Questions: Cross-platform governance  

---

## Use Case 11 — Parasitic Monetization Loops

### Scenario

Third-party systems monetize behavioral data downstream.

### Failure Mode

- Extraction rewarded  

### UCSF Response

- Consent tokens include commercial scope  

**Related UCSF Elements**

- Principles: Power Requires Responsibility  
- Framework: Commercial Scope Enforcement  
- Open Questions: Incentive alignment  

---

## Use Case 12 — Behavioral Targeting Feedback Loops

### Scenario

Recommendation engines amplify vulnerabilities.

### Failure Mode

- Reinforced dependency  

### UCSF Response

- Pattern formation treated as risk  

**Related UCSF Elements**

- Principles: Human Oversight  
- Framework: Risk Classification  
- Open Questions: Behavioral ethics  

---

## Use Case 13 — Social Simulation Without Oversight

### Scenario

NPCs simulate emotional relationships.

### Failure Mode

- Unbounded parasocial reinforcement  

### UCSF Response

- Parasocial metrics tied to risk classification  

**Related UCSF Elements**

- Principles: Human Oversight  
- Framework: Risk Thresholds  
- Open Questions: Social simulation ethics  

---

## Use Case 14 — Resource-Driven Scaling Externalities

### Scenario

Generation pipelines maximize throughput ignoring ecological cost.

### Failure Mode

- Infrastructure pressure invisible  

### UCSF Response

- Environmental thresholds tied to risk classes  

**Related UCSF Elements**

- Principles: Environmental Limits  
- Framework: Resource Constraints  
- Open Questions: Sustainable scaling  

---

## Use Case 15 — Cross-Platform Image Misuse and Harmful Distribution

### Scenario

Images are reused across services to create harmful derivative content.

### Failure Mode

- Consent collapses between systems  

### UCSF Response

- Persistent consent provenance  
- Identity integrity constraints  
- Fictionalisation fallback  

**Related UCSF Elements**

- Principles: Consent as Condition; Identity Integrity  
- Framework: Interoperable Validation  
- Open Questions: Revocation propagation  

---

## Use Case 16 — Coordinated Abuse Networks Exploiting Platform Fragmentation

### Scenario

Distributed abuse networks exploit moderation gaps.

### Failure Mode

- Platforms act in isolation  

### UCSF Response

- Global consent provenance  
- Human-governed escalation  
- Victim-centered revocation  

**Related UCSF Elements**

- Principles: Power Requires Responsibility; Repair Obligation  
- Framework: Cross-System Governance  
- Open Questions: Network-level accountability  

---

## Design Lessons

- Ethics without architecture fails  
- Moderation alone is insufficient  
- Consent must be structural  
- Identity integrity must persist across platforms  
- Repair must be built-in  
- Human oversight remains essential  
- Environmental impact cannot be externalized  
- Fragmented platforms enable organized harm  

UCSF reframes these problems as infrastructure design failures.

---

*This document supports UCSF v1.0 and evolves through peer review.*