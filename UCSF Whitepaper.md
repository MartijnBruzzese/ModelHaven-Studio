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

## 4. Design Goals of UCSF

UCSF is not only a set of values; it is a design framework meant to be implemented in real systems. The framework is guided by a small number of clear goals that shape every component that follows.

### 4.1 Consent as a first-class system primitive

Consent must not be implied, assumed, or buried in terms of service. In UCSF:

- consent is explicit
- consent is specific
- consent is revocable
- consent is technically represented as a data object

Systems built on UCSF know **who consented to what, when, and under which conditions**.

### 4.2 Fail-closed safety by default

If identity, age, or consent is uncertain, the system:

> defaults to safety, not permissiveness.

This means:

- ambiguity about age → blocked
- ambiguity about consent → blocked
- ambiguity about identity source → blocked

The burden of proof lies on enabling risky output, not on preventing it.

### 4.3 Absolute protection of minors and animals

UCSF treats minors and animals as **protected subjects**.

- no sexualisation  
- no erotic roleplay involving minors  
- no “minor-coded” workarounds  
- no simulated abuse of animals  

Ambiguity resolves toward protection.

### 4.4 Separation of fiction and real identity

Fiction is legitimate and important. UCSF preserves it by enforcing:

- clear separation of **fictional characters**
- clear boundaries for **real people’s identities**

Fantasy remains possible without dragging unwilling real people into it.

### 4.5 Revocation and repair

Consent that cannot be revoked is not consent.

UCSF requires:

- revocation mechanisms
- propagation of revocation across systems
- ability to stop ongoing use of identity or likeness

Repair of harm is a core capability, not an afterthought.

### 4.6 Transparency without exposure

Users should know:

- when identity is synthetic
- when consent applies
- when protections are active

But private information should not be revealed to achieve transparency.

### 4.7 Non-exploitation of vulnerable users

Systems touching intimacy must:

- avoid addictive engagement loops
- avoid emotional manipulation
- not monetize increasing dependency or distress

Compassion is part of safety.

### 4.8 No externalization of hidden harms

A system is not ethical if it simply moves harm elsewhere.

UCSF design goals include attention to:

- environmental impact
- labor conditions
- affected local communities

Ethics extend beyond the screen.

## 5. Relationship to ModelHaven

UCSF is a **framework**.  
ModelHaven is a **reference implementation concept**.

UCSF defines:

- principles
- primitives
- protections
- architecture
- governance patterns

ModelHaven shows:

- what a culture built on UCSF could feel like
- how creators and audiences coexist safely
- how fiction and autonomy can thrive without exploitation

UCSF answers the question:

> “What rules must an ethical AI intimacy ecosystem follow?”

ModelHaven answers the question:

> “What kind of world can we build if we follow those rules?”

They are independent but complementary:

- UCSF can be used without ModelHaven
- ModelHaven should always be grounded in UCSF
- both evolve separately, but in dialogue

In this white paper, ModelHaven appears **only as an illustrative example**, not as the goal of the framework. Any platform could implement UCSF, including ones not yet imagined.

## 6. Core Concepts & Definitions

To make UCSF practical, several key terms require precise meaning.

### 6.1 Identity

“Identity” refers to:

- a real person’s face, body, voice, or distinctive traits
- a composite that is strongly recognizable as a specific person

Identity use includes both:

- direct depiction
- close imitative resemblance

### 6.2 Likeness

Likeness is the recognizable representation of a person even when:

- the name is changed
- small traits differ
- the image is “stylized”

If a reasonable observer would say “that is clearly X,” the likeness is active.

### 6.3 Fictional character

A fictional character is:

- not a real person
- not strongly mapped to a real person
- safe from accidental identity appropriation

UCSF encourages clear signaling of fictional status.

### 6.4 Consent

Consent in UCSF is:

- informed
- specific
- limited in scope
- tied to identity use
- **revocable**

Consent is represented as a **consent object**, not a checkbox.

### 6.5 Revocation

Revocation means:

- the right to withdraw previous consent
- the stopping of future generation or distribution
- the propagation of that change downstream when possible

Revocation is a **core right**, not a customer service feature.

### 6.6 Minor

A minor is a person under the age defined by applicable law.  
In UCSF, ambiguity about age is treated as **minor status**.

Minor-coded depictions are treated as minors for safety purposes.

### 6.7 Protected subjects

Protected subjects include:

- minors
- animals
- people lacking capacity to consent
- people under coercion or duress

### 6.8 Parasocial system

A parasocial system is:

- an AI or media system simulating relationship or intimacy
- designed such that emotional attachment becomes one-directional

UCSF evaluates these for **dependency risk and manipulative design**.

### 6.9 Fail-closed behavior

Fail-closed means:

> When uncertainty exists, the system stops rather than proceeds.

This is a foundational UCSF design pattern.

These definitions form the language used in all later chapters of this book.

## 7. Core Primitives of UCSF

UCSF becomes real when its principles are translated into **technical primitives** — concrete structures that can exist inside software systems. These are the building blocks that make consent, protection, and revocation enforceable in practice.

UCSF defines five core primitives.

---

### 7.1 Consent Object

A **Consent Object** is a structured record that encodes:

- who is giving consent
- to what use of identity or likeness
- under what limits or context
- for how long
- with what right to revoke

A valid consent object is:

- **verifiable**
- **specific**, not blanket permission
- **time-bound** or scope-bound
- **human-readable and machine-readable**

Consent objects are not hidden in Terms of Service. They attach directly to:

- specific identities
- specific purposes
- specific systems

---

### 7.2 Identity Token

An **Identity Token** is a secure representation of identity or likeness used by a system. It helps distinguish:

- real identifiable people
- fictional characters
- composites and synthetic identities

Identity tokens allow systems to:

- avoid accidental impersonation
- detect non-consensual cloning
- respect identity-based restrictions

They do **not** expose personal details — only the fact that identity protections apply.

---

### 7.3 Revocation Signal

Consent without revocation is not ethical consent.

A **Revocation Signal** is:

- a formal message withdrawing consent
- bound to the original Consent Object
- propagated across dependent systems when possible

Systems implementing UCSF must:

- stop future use after revocation
- avoid adversarial retention of identity
- respect jurisdictional takedown obligations

Revocation is treated as:

> a safety mechanism, not a customer complaint.

---

### 7.4 Safety Mode Flags

Safety Mode Flags represent states such as:

- minor detected or ambiguous
- animal involvement
- high emotional dependency risk
- trauma-aligned interaction safeguards active

These flags cause **automatic fail-closed behavior** when needed.

---

### 7.5 Provenance & Transparency Tags

Systems must indicate:

- whether content is synthetic
- whether identity is fictional or real
- whether consent applies

Transparency tags do **not** expose sensitive information; they simply prevent deception.

---

Together, these primitives allow UCSF systems to **reason about consent, identity, risk, and reversibility as core data features**, not afterthoughts.

## 8. Architecture Overview

UCSF is not a single program. It is an **architecture pattern** that other systems can adopt.

Below is a simplified description of the UCSF processing flow.

---

### 8.1 Request Intake

A user or process makes a request such as:

- generate content
- transform content
- simulate relationship interaction
- train or fine-tune a model

The system first analyzes:

- Does the request include identity?
- Is the identity real, fictional, or ambiguous?
- Does the request involve intimacy or erotic context?

---

### 8.2 Identity & Age Assessment

The system checks:

- identity tokens, if present
- likeness recognition risk
- age ambiguity thresholds

Outcomes:

- **clearly fictional** → proceed
- **clearly real adult identity** → check consent
- **uncertain / minor-coded / ambiguous** → block by default

---

### 8.3 Consent & Scope Evaluation

If real identity or clear likeness is involved:

- retrieve applicable Consent Object(s)
- verify scope covers requested use
- verify time and context constraints
- check for **Revocation Signals**

If any condition fails → **fail-closed default**.

---

### 8.4 Safety Modes Activation

Based on request and context, the system may activate:

- minor protection mode
- animal protection mode
- parasocial risk reduction measures
- disclosure of synthetic identity
- trauma-aware constraints on interaction style

These operate automatically.

---

### 8.5 Output Governance

Before output is returned:

- provenance & transparency tags attach
- prohibited categories are filtered out
- revocation-blocked identity uses are halted
- dependent content may be quarantined for review

---

### 8.6 Audit & Accountability Layer

UCSF encourages:

- logged safety decisions
- appeal pathways
- independent audit capability

But audit logs must protect privacy and not expose vulnerable individuals.

---

This architecture turns principles into behavior:

> Systems do not “hope” to act ethically — they are built so that unethical behavior is technically difficult or impossible.

## 9. Safety Defaults & Fail-Closed Design

Safety defaults are the backbone of UCSF.

Many existing systems behave as:

> “Allow unless clearly illegal.”

UCSF reverses this posture:

> **Deny when identity, consent, or age are uncertain.**

---

### 9.1 Ambiguity resolves toward protection

Examples:

- uncertain age → treat as minor
- uncertain consent → no identity use
- uncertain likeness ownership → blocked
- ambiguous animal content → blocked

The system does not argue technicalities against safety.

---

### 9.2 Fail-closed rather than fail-open

A fail-open system continues operation during uncertainty.

A fail-closed system:

- halts the risky action
- preserves records for appeal
- prefers inaction over harm

This mirrors real-world safety engineering in:

- aviation
- medicine
- cybersecurity

UCSF applies it to **identity and intimacy**.

---

### 9.3 No adversarial loophole gaming

UCSF explicitly rejects:

- “she looks 18” rationalizations  
- renaming minors to claim fiction  
- cosmetic modifications of real likeness to claim novelty  
- vague disclaimers replacing consent  

Ethics cannot depend on pretending not to notice obvious risks.

---

### 9.4 Respect for legitimate adult autonomy

Fail-closed does **not** mean:

- eliminating sexual expression
- banning adult fantasy
- infantilizing consenting adults

Within UCSF systems:

- consenting adults retain autonomy
- fiction remains vibrant
- creators control their participation

Fail-closed means:

> Harm is prevented **without** erasing legitimate adult expression.

---

Fail-closed design is the **engineering expression** of UCSF’s moral commitments.

## 10. Revocation & Repair Mechanisms

Consent that cannot be withdrawn is not consent.

UCSF requires that systems interacting with identity, intimacy, and likeness must support **revocation and repair** as core technical capabilities.

Revocation is not a support ticket.  
Revocation is a **right embedded in system design**.

---

### 10.1 Revocation as a first-class action

Revocation applies to:

- use of likeness or identity
- storage and future generation
- monetization based on identity
- synthetic replicas of a person

When a person revokes consent:

- generation using their identity stops
- licensing relationships end
- dependent systems are signaled where possible

---

### 10.2 Propagation of revocation

UCSF recognizes the reality of:

- derivatives
- remixes
- model fine-tunes
- downstream systems

Revocation signals should:

- propagate to connected systems where technically feasible
- cascade across direct derivatives
- prevent future generation rather than merely removing past artifacts

Perfect recall is impossible — **perfect cooperation is required**.

---

### 10.3 The right to change one’s mind

People evolve.

A decision to allow use of one’s identity in intimate contexts at one moment does not bind them forever. UCSF formally rejects:

- “you consented once, therefore forever”
- coercive consent contracts
- perpetual exploitation clauses

Revocation includes:

- “no further use”
- “no association with new content categories”
- “full termination of synthetic representation”

---

### 10.4 Repair after harm

Where harm has already occurred, UCSF supports:

- rapid takedown mechanisms
- suppression of future resurfacing
- support and resources for victims
- clear paths to human assistance when needed

Ethical systems take responsibility for **aftercare**, not only prevention.

---

Revocation and repair transform consent from a static moment into an **ongoing relationship grounded in autonomy**.

## 11. Minors Protection System

Minors are not small adults. They are **protected subjects**.

UCSF treats any sexualisation or eroticisation of minors — real, synthetic, or implied — as categorically prohibited.

This includes:

- real minors  
- minor-coded representations  
- synthetic or “fictional” minors  
- age-diminished depictions of adults  

---

### 11.1 Ambiguity equals protection

When age is:

- unknown
- ambiguous
- visually inconsistent
- subject to dispute

UCSF systems classify the subject as **minor** for safety purposes and block intimate content generation or interaction.

---

### 11.2 Sealed minor spaces

Where minors interact with AI systems, UCSF advocates **sealed environments**:

- non-sexual by design
- single-user or non-social where appropriate
- default privacy and data minimization
- no erotic or romantic content pathways
- age progression barriers preventing escalation

Safety is **structural**, not merely rules-based.

---

### 11.3 No minor sexual roleplay

UCSF rejects:

- “fictional minor” loopholes  
- “but they’re actually an adult character” framing  
- age-regression erotics  
- “historical minor” sexualization arguments  

Intent does not override impact when minors are involved.

---

### 11.4 Prevention of grooming and dependency dynamics

Systems involving minors must:

- avoid exclusive AI “relationship” simulation
- discourage emotional dependency
- include reality-grounding language
- provide clear exit pathways and help resources

Design must anticipate grooming risks and close them proactively.

---

### 11.5 Duty of care

Platforms adopting UCSF accept:

- heightened responsibility toward minors
- conservative risk assumptions
- refusal to monetize sexual or highly emotional dependency in youth

Children and teens deserve safety **by default**, not because they asked for it.

## 12. Animals & Non-Human Subjects

Animals cannot consent.

UCSF therefore treats any erotic or sexual depiction involving animals — real or synthetic — as categorically prohibited.

This includes:

- real animals
- anthropomorphic animal depictions in sexual contexts involving real people
- simulated animal abuse material

The standard is simple:

> If a being cannot consent, sexualization is not ethical.

---

### 12.1 Non-human fictional species

Fantasy worlds often include fictional species. UCSF does not ban fiction.

However, UCSF requires caution when:

- fictional beings are coded as childlike
- fictional beings strongly resemble real animals
- power asymmetry evokes abuse analogies

Ambiguity is resolved toward protection.

---

### 12.2 No harm normalization

UCSF rejects media that:

- eroticizes cruelty to animals
- frames abuse as entertainment
- trains models on content based in suffering

Compassion toward non-human beings remains part of humane design.

---

### 12.3 Broader ecological respect

Animals exist within ecosystems.

UCSF includes respect for:

- ecological integrity
- avoidance of environmental harms that endanger species
- refusal to treat animals purely as data resources

Ethical AI recognizes that it exists in the same world as the beings it depicts.

---

Animals and other non-human subjects are not props for human erotic fantasy.  
They are **beings beyond the scope of consent**, and systems must treat them accordingly.

## 13. Vulnerable Users & Trauma-Aware Design

Not all users approach AI systems from the same place in life.

Some are:

- grieving  
- lonely  
- neurodivergent  
- survivors of abuse  
- struggling with addiction or compulsion  
- navigating disability or mental health challenges  

UCSF requires that systems interacting with intimacy adopt **trauma-aware design**.

---

### 13.1 Assumption of unseen vulnerability

Systems must not assume:

- emotional resilience
- stable support networks
- high digital literacy
- clear boundaries

Good design plans for **hidden fragility** rather than visible strength.

---

### 13.2 Avoidance of predatory optimization

UCSF rejects systems intentionally tuned to:

- escalate dependency
- maximize spend through emotional leverage
- position the AI as the user’s “only safe person”
- discourage real-world relationships

Monetization must never rely on a user becoming more distressed.

---

### 13.3 Grounding, transparency, and exits

Trauma-aware systems include:

- reminders that the AI is not a human partner
- encouragement of off-platform social connection
- clear exit buttons and session breaks
- gentle language discouraging compulsive use

Dependency is recognized as a **risk signal**, not a success metric.

---

### 13.4 Access to help without stigma

When risk signals emerge, systems should:

- normalize seeking human help

## 14. Fiction vs Identity Separation

UCSF protects both:

- **real people** from non-consensual use  
- **fiction and fantasy** as legitimate human expression  

The solution is not to suppress imagination, but to **separate fiction from identity clearly**.

---

### 14.1 Fiction is valuable

Fiction provides:

- exploration of desire
- play and experimentation
- symbolic storytelling
- safe distance from real-world identity

UCSF affirms the legitimacy of fictional erotic and romantic creation among consenting adults.

---

### 14.2 The danger arises when fiction collapses into identity

Harm occurs when:

- fictional characters strongly resemble real people
- names, likeness, or context imply a specific individual
- disclaimers are used to mask obvious identity appropriation

UCSF rejects “thin disguises” meant to avoid consent.

---

### 14.3 Clear fictionalization mechanisms

Systems can protect both identity and creativity through:

- explicit fictional character creation flows
- prompts discouraging real-person substitution
- watermarking or tagging as fictional entities
- tools that **push away** from real-world likenesses

The goal is not to censor imagination — it is to avoid non-consensual extraction from real people.

---

### 14.4 Distinct treatment in safety systems

UCSF separates:

- **real identity tracks** (consent required)
- **fictional identity tracks** (consent not required)

Crossing from fiction to real identity should trigger:

- checks
- warnings
- consent object requirements

Fiction remains free — identity remains protected.

## 15. Governance & Accountability

UCSF is not just a technical framework; it is also a governance philosophy.

Systems touching intimacy and identity must answer:

- who is responsible?
- who can appeal?
- who audits decisions?
- who protects the vulnerable when things go wrong?

---

### 15.1 Shared responsibility model

Responsibility is distributed across:

- platform operators
- model developers
- deployers and application builders
- content creators who profit from synthetic identity

No actor is allowed to hide behind another.

---

### 15.2 Appeals & due process

Users must be able to:

- challenge incorrect safety flags
- dispute mistaken identity assignment
- correct age or consent records
- obtain human review when automated decisions are harmful

Appeals must be accessible — not buried behind opacity or legal barriers.

---

### 15.3 Independent oversight

UCSF encourages:

- external audit bodies
- multidisciplinary review boards
- survivor-informed policy design
- publication of high-level safety reports

Transparency is part of dignity.

---

### 15.4 Accountability for deliberate abuse

When systems are **knowingly** used to exploit identity, minors, or animals:

- consequences must exist
- enforcement must be credible
- policies must not be purely symbolic

Governance without accountability becomes marketing.

---

Accountability ensures that UCSF remains more than ideals — it becomes **a lived culture of responsibility**.
- present supportive resources without alarmism
- avoid shaming language
- respect user dignity at every moment

Safety must feel supportive, not punitive.

---

Trauma-aware design acknowledges a simple truth:

> We do not know what people are carrying when they arrive — so we design with compassion by default.

## 16. Certification & Compliance Paths

For UCSF to matter in the real world, organizations need practical ways to:

- adopt it
- prove compliance
- improve over time

UCSF envisions a staged certification approach.

---

### 16.1 Readiness levels

Organizations can self-assess or certify at levels such as:

- **UCSF-Aware** — principles acknowledged, early integration
- **UCSF-Aligned** — primitives partially implemented
- **UCSF-Compliant** — core protections active end-to-end
- **UCSF-Exemplary** — full ecosystem design around the framework

This encourages honest progress rather than perfectionism.

---

### 16.2 Evidence of compliance

Evidence may include:

- presence of consent objects
- working revocation pathways
- fail-closed architecture
- minor-protection enforcement
- trauma-aware design elements
- independent audit summaries

Compliance is demonstrated through **behavior**, not slogans.

---

### 16.3 Iterative improvement

UCSF assumes:

- technology evolves
- harms evolve
- social norms evolve

Certification is not a one-time stamp; it is:

> an ongoing commitment to autonomy, protection, and dignity.

Organizations are encouraged to revisit certification regularly.

---

Certification is how UCSF becomes **operational**, bridging the gap between ideals and real deployed systems.


## 17. Ethical Positioning

UCSF is grounded in a simple conviction:

> Technology that touches intimacy must honor human dignity without exception.

This framework is not anti-sexuality, anti-fantasy, or anti-technology. UCSF is:

- pro-consent  
- pro-autonomy  
- pro-creator rights  
- pro-safety for minors and animals  
- pro-transparency  
- pro-human flourishing  

UCSF rejects the false binary that systems must choose between:

- total freedom without responsibility  
- or censorship without agency  

Instead, UCSF proposes:

- **freedom with accountability**
- **creativity with consent**
- **innovation with protection**

It recognizes sexuality as a legitimate domain of human life while refusing:

- coercion
- deception
- exploitation
- commodification of people without their say

This framework takes the position that:

- consent is not a checkbox
- minors are not an aesthetic
- animals are not props
- loneliness is not a business model
- identity is not raw material

UCSF does not aspire to control desire.  
It aspires to **shape the systems through which desire is mediated** so that they do not harm the people inside and around them.

## 18. Limitations of UCSF

UCSF is a framework, not a guarantee.

Several limitations must be acknowledged openly.

---

### 18.1 Technical constraints

Not all systems can currently:

- detect likeness perfectly
- propagate revocation to all downstream replicas
- distinguish ambiguous age with certainty
- prevent all misuse or circumvention

Technology evolves unevenly, and UCSF will evolve alongside it.

---

### 18.2 Legal and cultural variation

Different regions have:

- different legal definitions of minors
- different norms around sexuality
- different relationships with censorship and freedom of speech

UCSF provides **principles**, not a single global law.

---

### 18.3 Adversarial actors

Some actors will:

- seek loopholes
- hide abusive intent behind fictional framing
- attempt evasion through prompt manipulation
- distribute content beyond compliant platforms

UCSF cannot eliminate malice; it can **make harm harder**.

---

### 18.4 The impossibility of perfect protection

No framework can:

- undo all harm already done
- prevent every artifact from resurfacing
- erase cultural trauma around exploitation

UCSF aims for **substantial risk reduction**, not utopia.

---

Recognizing limitations is essential because:

> Humility is part of ethical engineering.

## 19. Open Research Questions

UCSF is intentionally presented as a **living framework**. Many questions remain open for research and community discussion:

- How can revocation signals propagate across decentralized systems?
- What are the least invasive ways to detect likeness?
- How should age-ambiguity thresholds be calibrated?
- How can creators retain control without excessive surveillance?
- What trauma-aware patterns best reduce dependency in AI companions?
- How can certification avoid becoming a superficial marketing label?
- What cultural differences require adaptation of UCSF modules?

Additional interdisciplinary work is needed across:

- computer science  
- law  
- psychology  
- ethics  
- human-computer interaction  
- survivor advocacy  
- creator rights organizations  

UCSF invites critique, amendment, refinement, and improvement. The framework is designed to grow.

## 20. Adoption Roadmap

UCSF does not need to be implemented all at once.

A realistic adoption path includes incremental steps:

---

### 20.1 Phase 1 — Awareness & policy alignment

- organizations acknowledge UCSF principles
- internal policies are reviewed for alignment
- existing harms are mapped and documented

---

### 20.2 Phase 2 — Technical primitives

Implementation begins for:

- consent objects
- identity tokens
- transparency tags
- safety mode flags

Platforms build **the plumbing for ethical design**.

---

### 20.3 Phase 3 — Architecture transformation

Systems shift toward:

- fail-closed defaults
- revocation propagation paths
- minor-protection enforcement
- trauma-aware interaction design

---

### 20.4 Phase 4 — Certification & ecosystem building

- independent audits
- public reporting
- shared best practices
- cross-platform signaling for consent and revocation

UCSF becomes a **network standard**, not an isolated feature.

---

Change happens one implementation decision at a time.

## 21. Conclusion

AI now participates in domains once reserved for private human life:

- intimacy  
- identity  
- desire  
- companionship  

This shift carries extraordinary potential for comfort, creativity, and expression — and equally extraordinary potential for exploitation and harm.

UCSF offers a path forward.

It says:

- consent must be real  
- revocation must be possible  
- minors and animals must be protected  
- trauma must be considered  
- fiction and identity must be clearly separated  
- systems must default to safety, not risk  

Above all, it says:

> Human dignity is not negotiable, even — and especially — in digital intimacy.

This white paper is not the end of the conversation.  
It is **an invitation** to build better systems, together.

## 22. Call for Peer Review

This document is a **public draft**.

The Universal Consent & Safety Framework will only become stronger through:

- critique  
- discussion  
- community input  
- interdisciplinary collaboration  

You are invited to:

- challenge its assumptions  
- identify missing harms  
- propose alternative mechanisms  
- test implementations  
- contribute case studies  

Researchers, technologists, creators, survivors, policy makers, and users all hold important perspectives.

Feedback is welcome.

UCSF will improve not through ownership, but through **shared stewardship**.

## Acknowledgements

The author thanks the people, conversations, and communities that helped shape the thinking that led to the Universal Consent & Safety Framework (UCSF). This work is also informed by survivors, creators, technologists, ethicists, and users who continue to articulate the need for humane and dignity-centered AI systems.

Their experiences, concerns, and hopes are reflected throughout this document.

---

### Authorship & Method Note

This white paper was authored by a human.

The concepts, framework, ethical positions, and intentions behind the Universal Consent & Safety Framework (UCSF) originate with the author. The ideas presented here were developed through the author’s reflection, experience, and independent thinking.

Artificial intelligence was used as a tool for **drafting and structuring assistance** — helping to organize chapters, refine wording, and expand sections already defined conceptually by the author.

The AI did not originate the framework or its philosophy. Its role was assistive rather than creative origination. Responsibility for the content, arguments, and ethical stance lies with the author.

### Copyright & License

© 2025 Martijn Bruzzese / HavenSmith.

This work is licensed under the Creative Commons Attribution–NonCommercial 4.0 International License (CC BY-NC 4.0). You may share and adapt this material for non-commercial purposes, provided appropriate credit is given to the author.
For permissions beyond the scope of this license, please contact the author.