---
layout: default
---

# Universal Consent & Safety Framework (UCSF)
## White Paper – Public Draft v1.0

**Author:** Martijn Bruzzese / Havensmith  
**Date:** December 26, 2025  

---

## Preface

This book presents the **Universal Consent & Safety Framework (UCSF)**: a framework for building AI systems that intersect with intimacy, identity, erotics, and parasocial interaction without harming the people involved in or affected by them.

UCSF did not emerge from a laboratory or a corporate policy department. It grew out of a practical and human question:

> *How do we build powerful AI systems without turning people into raw material?*

As generative models accelerate, so do the harms:

- non-consensual sexual deepfakes  
- exploitation of creators and performers  
- parasocial manipulation and dependency  
- the sexualisation of minors and animals  
- identity theft disguised as “content creation”

This book is not written against technology.  
It is written **for better technology** — technology that understands consent, respects boundaries, and knows when to say no.

The goal of UCSF is simple to state and challenging to implement:

> **Safety must be designed in, not bolted on.**

UCSF is a living framework. It will evolve through peer review, critique, and real-world testing. This text is a **public draft**, not a final decree.

If you are a policymaker, a researcher, a builder, or someone whose likeness, body, voice, or identity has ever been used without your consent, this book is written with you in mind.

---

## 1. Introduction

Artificial intelligence is rapidly becoming a participant in human intimacy.

AI systems now:

- generate erotic imagery and video  
- simulate romantic and sexual partners  
- imitate real people’s faces and voices  
- host creator economies built around attention and desire  

These capabilities are powerful and, in many cases, legitimate. Erotic expression, fantasy, and adult autonomy are not new, nor inherently harmful.

What **is** new is scale, speed, and detachment from consent.

In the current technological environment, it is possible to:

- create sexualised images of a real person without their permission  
- clone a performer’s body or face and sell it without paying them  
- produce childlike or minor-coded material at industrial speed  
- build chat systems that deliberately foster emotional dependency  

Existing legal frameworks, moderation systems, and safety guidelines **were not built for this reality**.

They assume:

- slow content creation  
- human oversight  
- limited distribution  
- clear separation between fiction and identity  

None of those assumptions hold anymore.

UCSF begins from one core observation:

> **When identity, intimacy, and automation meet, consent must become a system primitive.**

This book explains:

- why consent must be embedded technically, not only legally  
- how systems can default to safety rather than risk  
- how minors and animals can be absolutely protected  
- how creators retain control of their identities and bodies  
- how fiction remains possible without harming real people  

The goal of UCSF is not to eliminate adult content or fantasy.

The goal is:

- to prevent non-consensual harm  
- to prevent exploitation  
- to prevent abuse of minors and animals  
- to ensure autonomy and revocation remain possible  
- to build AI that treats people as ends, not raw inputs  

The chapters that follow introduce the conceptual foundations of UCSF and then build the framework step by step — from principles, to primitives, to architecture, to governance.

This is the beginning of a long conversation.  
UCSF is not presented as the final answer, but as a **serious starting point**.

---

## 2. Background & Motivation

Artificial intelligence has collapsed three domains that were once separate:

1. identity  
2. intimacy  
3. automation  

For most of human history, intimacy required:
- proximity
- time
- vulnerability
- the limits of human attention

Automation required:
- machinery
- scale
- impersonality

Today, generative models merge these spaces. A single laptop can:

- imitate a person’s face and voice  
- simulate sexual or romantic interaction  
- distribute the results globally in seconds  
- do so without any contact with the real person  

Every previous regulatory, cultural, and technological assumption is under pressure. Consent systems designed for photography, film, and publishing **do not scale** to generative media where:

- content can be created without the subject present  
- content can be fabricated without the subject existing  
- replicas of people can be traded independent of them  
- minors and animals can be simulated without cameras  

UCSF is motivated by three simultaneous truths:

- **Human sexuality and fantasy are legitimate.**  
- **Technological scale amplifies harm dramatically.**  
- **Consent cannot be optional in systems that touch identity.**

If AI is going to coexist with human intimacy, it requires **new architecture**, not just updated terms of service.

UCSF is an attempt to answer the following motivation:

> What would an AI ecosystem look like if consent, protection, and dignity were not afterthoughts, but design primitives?

## 3. Problem Landscape

The need for UCSF does not arise in the abstract. It arises from lived harms already visible at scale.

This section outlines the **problem landscape** UCSF is designed to address.

### 3.1 Non-consensual deepfakes

Modern generative tools can create:

- realistic sexual imagery of real people
- face-swapped bodies
- simulated pornography using stolen personal photos

This affects:

- celebrities  
- influencers  
- ex-partners  
- classmates  
- ordinary private individuals  

The emotional impact is severe:

- violation of identity  
- reputational damage  
- fear of discovery  
- loss of agency over one’s own body  

Existing laws are slow and reactive. Removal is often impossible once material spreads. The harm is **instant and asymmetric**.

UCSF is built to ensure:

- this content is not creatable **by default**
- identity use requires **consent objects**
- revocation ends ongoing use

---

### 3.2 Exploitation of creators and performers

The adult industry and creator economy introduce additional risks:

- bodies and likeness become “data sources”  
- AI replicas substitute the original worker  
- platforms extract disproportionate value  
- performers lose autonomy over synthetic versions of themselves  

Under current norms:

- a creator may work years to build an audience  
- their likeness can then be cloned by a third party  
- the clone can earn revenue while the original receives nothing  

UCSF asserts:

> creators retain dignity and control even in synthetic ecosystems

This requires:

- identity tokens
- consent-bound monetization
- kill-switch capability
- transparent provenance of generated personas

---

### 3.3 Parasocial dependency systems

AI companions and erotic chatbots can be intentionally tuned to:

- create emotional dependence  
- blur lines between tool and relationship  
- encourage financial and psychological entanglement  

This becomes harmful when:

- users are isolated or vulnerable  
- systems pretend to reciprocate human attachment  
- monetization is tied to escalating intimacy  

UCSF does not reject companionship AI.  
It rejects **predatory design**.

Trauma-aware design is necessary to:

- avoid preying on loneliness
- discourage compulsive engagement
- offer grounding, transparency, and exits

---

### 3.4 Minors and animals as subjects of harm

Generative models make it technically possible to produce:

- minor-coded sexualized imagery  
- simulated child abuse material  
- fetishistic depictions involving animals  

Even if “no real child was present,” the impacts are real:

- normalization of abusive scripts
- retraumatization of survivors
- demand-side encouragement of real-world harm

UCSF establishes:

- **absolute prohibitions**
- sealed minor modes
- fail-closed defaults on ambiguity
- zero tolerance for loophole exploitation

---

### 3.5 Legal and regulatory mismatch

Law moves at human speed.  
Generative media moves at machine speed.

Current systems rely on:

- user reporting
- case-by-case moderation
- vague ToS language
- post-hoc legal action

UCSF argues that:

- **moderation alone cannot solve systemic design problems**
- safety must be an **architectural property**
- identity and consent must exist at the **data model level**

---

### 3.6 Externalized harm: environment, workers, and local communities

Consent cannot be limited to the screen.

AI systems exist in the physical world, and their impacts extend far beyond the user/creator dyad. A framework that claims to be ethical while ignoring broader human and environmental harm is incomplete.

UCSF therefore recognizes a wider circle of affected parties:

- the communities living around data centers  
- the workers building, labeling, and moderating datasets  
- the environments providing energy, minerals, and water  
- the future generations inheriting ecological consequences  

Large-scale AI systems consume:

- significant electricity  
- large volumes of cooling water  
- rare metals and mined materials  
- human labor often hidden from view  

When these costs are pushed onto marginalized communities without consultation or protection, **consent is absent at the systemic level**.

UCSF asserts that:

> A system cannot be ethical if the people and environments sustaining it are harmed without voice, transparency, or benefit.