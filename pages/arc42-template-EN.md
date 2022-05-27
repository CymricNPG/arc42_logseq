- ![Logo](images/arc42-logo.png)
- **About arc42**
  
  arc42, the Template for documentation of software and system architecture.
  
  Created and maintained by Dr. Peter Hruschka, Dr. Gernot Starke and contributors.
  
  Template Revision: 8.0 EN (based on asciidoc), February 2022
  
  © We acknowledge that this document uses material from the arc 42 architecture template,<https://arc42.org>.
  
  ```note
  This version of the template contains some help and explanations. It is
  used for familiarization with arc42 and the understanding of the
  concepts. For documentation of your own system you use better the
  *plain* version.
  ```
- # [[Introduction and Goals]]
- # [[Architecture Constraints]]
- # [[System Scope and Context]]
- # [[Solution Strategy]]
- # [[Building Block View]]
  collapsed:: true
- # [[Runtime View]]
- # [[Deployment View]]
- # [[Cross-cutting Concepts]]
- Architecture Decisions
	- ::: formalpara-title
	  **Contents**
	  :::
	  
	  Important, expensive, large scale or risky architecture decisions
	  including rationals. With \"decisions\" we mean selecting one
	  alternative based on given criteria.
	  
	  Please use your judgement to decide whether an architectural decision
	  should be documented here in this central section or whether you better
	  document it locally (e.g. within the white box template of one building
	  block).
	  
	  Avoid redundancy. Refer to section 4, where you already captured the
	  most important decisions of your architecture.
	  
	  ::: formalpara-title
	  **Motivation**
	  :::
	  
	  Stakeholders of your system should be able to comprehend and retrace
	  your decisions.
	  
	  ::: formalpara-title
	  **Form**
	  :::
	  
	  Various options:
- ADR []{.indexterm
    primary="Architecture Decision Record"}[Architecture Decision
    Record](https://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions)
    for every important decision
- List or table, ordered by importance and consequences or:
- more detailed in form of separate sections per decision
  
  See [Architecture Decisions](https://docs.arc42.org/section-9/) in the
  arc42 documentation. There you will find links and examples about ADR.
# Quality Requirements {#section-quality-scenarios}

::: formalpara-title
**Content**
:::

This section contains all quality requirements as quality tree with
scenarios. The most important ones have already been described in
section 1.2. (quality goals)

Here you can also capture quality requirements with lesser priority,
which will not create high risks when they are not fully achieved.

::: formalpara-title
**Motivation**
:::

Since quality requirements will have a lot of influence on architectural
decisions you should know for every stakeholder what is really important
to them, concrete and measurable.

See [Quality Requirements](https://docs.arc42.org/section-10/) in the
arc42 documentation.
## Quality Tree {#_quality_tree}

::: formalpara-title
**Content**
:::

The quality tree (as defined in ATAM -- Architecture Tradeoff Analysis
Method) with quality/evaluation scenarios as leafs.

::: formalpara-title
**Motivation**
:::

The tree structure with priorities provides an overview for a sometimes
large number of quality requirements.

::: formalpara-title
**Form**
:::

The quality tree is a high-level overview of the quality goals and
requirements:
- tree-like refinement of the term \"quality\". Use \"quality\" or
    \"usefulness\" as a root
- a mind map with quality categories as main branches
  
  In any case the tree should include links to the scenarios of the
  following section.
## Quality Scenarios {#_quality_scenarios}

::: formalpara-title
**Contents**
:::

Concretization of (sometimes vague or implicit) quality requirements
using (quality) scenarios.

These scenarios describe what should happen when a stimulus arrives at
the system.

For architects, two kinds of scenarios are important:
- Usage scenarios (also called application scenarios or use case
    scenarios) describe the system's runtime reaction to a certain
    stimulus. This also includes scenarios that describe the system's
    efficiency or performance. Example: The system reacts to a user's
    request within one second.
- Change scenarios describe a modification of the system or of its
    immediate environment. Example: Additional functionality is
    implemented or requirements for a quality attribute change.
  
  ::: formalpara-title
  **Motivation**
  :::
  
  Scenarios make quality requirements concrete and allow to more easily
  measure or decide whether they are fulfilled.
  
  Especially when you want to assess your architecture using methods like
  ATAM you need to describe your quality goals (from section 1.2) more
  precisely down to a level of scenarios that can be discussed and
  evaluated.
  
  ::: formalpara-title
  **Form**
  :::
  
  Tabular or free form text.
# Risks and Technical Debts {#section-technical-risks}

::: formalpara-title
**Contents**
:::

A list of identified technical risks or technical debts, ordered by
priority

::: formalpara-title
**Motivation**
:::

"Risk management is project management for grown-ups" (Tim Lister,
Atlantic Systems Guild.)

This should be your motto for systematic detection and evaluation of
risks and technical debts in the architecture, which will be needed by
management stakeholders (e.g. project managers, product owners) as part
of the overall risk analysis and measurement planning.

::: formalpara-title
**Form**
:::

List of risks and/or technical debts, probably including suggested
measures to minimize, mitigate or avoid risks or reduce technical debts.

See [Risks and Technical Debt](https://docs.arc42.org/section-11/) in
the arc42 documentation.
# Glossary {#section-glossary}

::: formalpara-title
**Contents**
:::

The most important domain and technical terms that your stakeholders use
when discussing the system.

You can also see the glossary as source for translations if you work in
multi-language teams.

::: formalpara-title
**Motivation**
:::

You should clearly define your terms, so that all stakeholders
- have an identical understanding of these terms
- do not use synonyms and homonyms
  
  ```{=html}
  <!-- -->
  ```
- A table with columns \<Term> and \<Definition>.
- Potentially more columns in case you need translations.
  
  See [Glossary](https://docs.arc42.org/section-12/) in the arc42
  documentation.
  
  +-----------------------+-----------------------------------------------+
  | Term                  | Definition                                    |
  +=======================+===============================================+
  | *\<Term-1>*           | *\<definition-1>*                             |
  +-----------------------+-----------------------------------------------+
  | *\<Term-2>*           | *\<definition-2>*                             |
  +-----------------------+-----------------------------------------------+