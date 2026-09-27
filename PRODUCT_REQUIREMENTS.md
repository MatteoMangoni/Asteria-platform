# ASTERIA — Product Requirements

## 1. Purpose

This document defines the product requirements for ASTERIA.

The requirements describe what ASTERIA should provide as an educational engineering project environment. They do not prescribe a particular technical architecture, implementation technology, AI model, database, hosting environment, or development framework.

The first concrete application of these requirements is the ASTERIA asteroid rendezvous and exploration mission.

---

## 2. Project Definition

R1 — Structured Project Definition

Every ASTERIA project must have a lightweight common structure while allowing project-specific content.

A project definition should establish, as appropriate:

- objectives;
- success criteria / definition of done;
- expectations;
- scope;
- mission and performance requirements;
- constraints;
- initial assumptions and simplifications.

Mission and performance requirements define conditions the engineering solution is expected to satisfy. They should describe the engineering problem and its boundaries without prescribing the solution path.

Exceeding a requirement should not automatically constitute project failure. The project should allow Marina to investigate, understand and document the consequences of exceeding a requirement and, where appropriate, justify the deviation or revise the engineering approach. Any material change to the project definition remains subject to the existing approval rules below.

For the current version, the project definition is provided by the project creator or supervisor.

The student may propose changes to objectives, scope, constraints or success criteria when new information or engineering reasoning justifies them. Such changes require Mission Director approval and become part of the project's engineering history.

Future versions may support projects whose definitions are created collaboratively with the student and/or AI.

---

## 3. Student Agency

### R2 — Student-Controlled Work

Marina should remain free to decide what to investigate or work on next.

ASTERIA should not require her to follow a predetermined sequence of tasks.

When she is uncertain about what to do next, the AI mentor should help her reason toward the next useful step rather than simply assigning one.

ASTERIA should encourage the habit of thinking about the next move and discussing it with the mentor when useful.

---

## 4. Question-Centred Engineering

### R3 — Engineering Questions and Investigations

ASTERIA should organise engineering work primarily around questions and investigations rather than task completion.

The product should distinguish between:

- requirements;
- engineering questions;
- investigations;
- supporting tasks;
- artifacts and evidence;
- results and conclusions;
- decisions.

A typical relationship is:

**Requirement → Question → Investigation → Evidence / Artifact → Result / Decision**

Tasks may organise practical work within an investigation, but task completion should not itself define project progress or success.

Marina should be able to create new engineering questions at any point during the project. The AI may suggest questions, but Marina decides whether a suggested question becomes part of the project's active work.

---

## 5. Project State and History

### R4 — Visible Project State

Marina must be able to understand the current state of the project, including relevant:

- objectives;
- questions;
- investigations;
- established knowledge;
- decisions;
- results;
- uncertainties;
- remaining work.

The current engineering focus should be visible without becoming a mandatory task sequence.

### R5 — Meaningful Project History

ASTERIA must preserve a meaningful history of important:

- investigations;
- discoveries;
- unsuccessful approaches;
- decisions;
- results;
- changes in direction;
- changes to the project definition.

The history should not be a transcript of every conversation.

Marina should be able to understand both **where the project is now** and **how it got there**.

---

## 6. Engineering Artifacts and Evidence

### R6 — First-Class Artifacts

Significant work produced or collected during a project should be representable as project artifacts.

Examples include:

- code;
- calculations;
- models;
- simulations;
- plots;
- datasets;
- sources;
- assumptions;
- validation results;
- decisions;
- mission documents;
- scientific findings.

Temporary or incidental work does not need to become a formal artifact.

### R7 — Traceability and Provenance

Significant artifacts should be associable with the questions, investigations, decisions, results or conclusions they support.

Important engineering claims, decisions and conclusions should be supportable by relevant evidence.

Significant artifacts should retain information about their origin, including whether they were:

- created by Marina;
- generated or assisted by AI;
- obtained externally;
- derived from another artifact;
- produced collaboratively.

Artifact provenance should remain distinct from Marina's understanding and engineering ownership.

AI assistance does not by itself determine whether Marina owns the resulting engineering work.

---

## 7. Validation, Uncertainty and Revision

### R8 — Engineering Validation

Important engineering results should be capable of being validated through appropriate checks, comparisons, tests or independent reasoning.

Important results should retain sufficient context to understand what they represent, including relevant:

- inputs;
- assumptions;
- models or methods;
- uncertainty;
- limitations.

ASTERIA should help Marina distinguish between evidence types and understand their limitations, including external data, assumptions, estimates, calculations, simulations and validation results.

### R9 — Revision and Engineering History

Important results and decisions should be revisable when new evidence, improved models or changed assumptions justify reconsideration.

ASTERIA should preserve the previous state and make the relationship between earlier and revised results or decisions visible.

Being wrong earlier should remain part of the engineering history rather than being silently erased.

---

## 8. AI Engineering Mentor

### R10 — Mentor Role and Assistance

The AI must act as an engineering mentor and partner, not as the owner of the project, its decisions or its conclusions.

The AI should adapt its assistance to Marina's demonstrated needs, following a progressive pattern such as:

1. Question
2. Concept
3. Hint
4. Method
5. Small example
6. Implementation help
7. Complete solution when genuinely necessary

Complete solutions should not be the default when they would bypass an important learning opportunity.

### R11 — Adaptive and Proactive Mentoring

The AI should be able to assess Marina's understanding of relevant concepts through interaction and questioning and use that understanding to guide her toward knowledge required for the current engineering problem.

The AI should be able to identify and gently surface:

- knowledge gaps;
- missing prerequisites;
- inconsistencies;
- weakly supported reasoning;
- skipped reasoning steps;
- useful validation opportunities;
- potentially useful engineering questions.

Proactive mentoring should remain lightweight and should preserve Marina's control over what she chooses to investigate or do next.

The system should not require numerical mastery or capability scores.

### R12 — AI Transparency and Project Context

The AI should clearly distinguish between:

- established information;
- assumptions;
- estimates;
- calculations;
- simulation results;
- external information;
- uncertainty.

When information is unavailable, ambiguous, uncertain or insufficiently supported, the AI must make that clear rather than presenting an unsupported answer as fact.

The AI should receive relevant project context when assisting Marina rather than depending on the complete historical conversation.

---

## 9. Shared and Specialised AI Contexts

### R13 — Shared Mission Context

ASTERIA should support specialised AI contexts focused on particular engineering domains or project activities.

Specialised contexts may provide domain-specific:

- knowledge;
- reasoning patterns;
- tools;
- guidance;
- relevant project context.

All specialised contexts must operate against the same authoritative project state.

Specialisation must not fragment the project or create independent versions of mission state.

---

## 10. Authoritative Project State

### R14 — AI-Assisted Project Updates

The application must maintain the authoritative project state independently of the AI conversation.

When the AI identifies information that should become part of that state, it should propose the appropriate update to Marina and request confirmation before changing it.

Once Marina confirms an appropriate update, ASTERIA should apply it seamlessly without requiring her to maintain duplicate records manually.

The AI may maintain the project administratively, but Marina authorises what becomes part of the authoritative project state.

---

## 11. Mission Director

### R15 — Human Supervision

ASTERIA should support a Mission Director role that can:

- review the project;
- provide guidance;
- approve important project changes;
- intervene when appropriate.

The core student experience should not depend on the Mission Director being continuously available or actively managing Marina's day-to-day work.

ASTERIA should be able to identify situations that may deserve Mission Director attention, particularly material changes to project definition or other decisions requiring human approval.

---

## 12. Knowledge and Sources

### R16 — Research and Source Traceability

External sources and important knowledge inputs should be representable as project artifacts, with their provenance preserved and their relevance to the project visible.

For important external information, ASTERIA should preserve enough context to understand what the information represents and how it was used.

Where applicable, this may include:

- units;
- reference frames;
- epochs;
- time systems;
- uncertainty;
- source limitations.

---

## 13. Project Lifecycle

### R17 — Project Lifecycle

ASTERIA should represent meaningful project lifecycle states, including:

- not started;
- active;
- paused;
- completed;
- archived.

Lifecycle state should provide status and continuity without unnecessarily restricting Marina's ability to investigate, revisit or revise previous work.

Mission-specific structures such as the current ASTERIA Gates are separate from the generic project lifecycle.

---

## 14. Tools and Integrations

### R18 — Integrated Engineering Tools

ASTERIA should provide convenient access to tools required by the current project, including where relevant:

- programming;
- calculations;
- simulations;
- data analysis;
- visualisation;
- documentation.

ASTERIA should prefer integrating or embedding suitable existing tools where they can provide the required capability reliably and with lower implementation complexity and cost than building equivalent functionality itself.

Where feasible, integrated tools should feel like part of the ASTERIA environment and remain connected to relevant project context, artifacts and AI mentoring.

Specific technologies and integration mechanisms are intentionally not defined here.

---

## 15. Final Outcome and Review

### R19 — Coherent Project Outcome

Every project should have a defined final outcome that brings together relevant results, decisions, evidence, artifacts and conclusions into a coherent whole.

Project completion should be determined primarily by the project's defined success criteria and intended outcome rather than by completion of an arbitrary list of tasks.

### R20 — Final Engineering Review

ASTERIA should support a final project review in which Marina can explain:

- what she did;
- why she made important decisions;
- what the evidence shows;
- what remains uncertain;
- what assumptions and limitations apply.

---

## 16. Engineering Experience

### R21 — Engineering-Oriented Experience

ASTERIA should reinforce Marina's sense of responsibility for a meaningful engineering project rather than the experience of completing a conventional educational course.

### R22 — Meaningful Visualisation and Feedback

ASTERIA should use visualisations and project feedback where they materially improve Marina's understanding of the system, results, project state or engineering decisions.

### R23 — Authentic Engagement

ASTERIA should not rely on points, badges, artificial rewards or similar mechanisms as the primary means of motivation.

Engagement should primarily come from the project itself and the experience of doing meaningful engineering work.

---

## 17. Boundaries and Deferred Decisions

The following are deliberately not specified by this document:

- application architecture;
- database technology;
- programming frameworks;
- AI models or providers;
- hosting and deployment;
- specific external tools;
- exact user-interface design;
- exact implementation of proactive AI;
- exact implementation of knowledge assessment;
- future project-creation workflows;
- numerical student mastery or capability scores;
- detailed Mission Director tooling.

These decisions should be made only when they become necessary for subsequent product or technical design.

---

## 18. Guiding Principle

ASTERIA should continuously favour the simplest product that can deliver the intended engineering and learning experience.

The purpose of these requirements is not to automate every aspect of engineering work.

The purpose is to create an environment in which Marina can:

**QUESTION → THINK → TRY → TEST → ASK → VERIFY → DOCUMENT**

and progressively become capable of carrying out meaningful engineering projects with increasing independence.