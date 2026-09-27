# ASTERIA — User Experience

## 1. Purpose

This document defines the intended user experience of ASTERIA.

It describes how Marina should experience the product while carrying out an engineering project, how she interacts with the AI mentor and engineering tools, and how the product supports continuity, investigation, reasoning, experimentation, documentation, and project completion.

This is a product and experience specification. It does not define the technical architecture or implementation.

---

## 2. Experience Goal

ASTERIA should make Marina feel like the engineer responsible for a meaningful project.

The product should support genuine engineering work while reducing unnecessary friction around tools, context, documentation, and continuity.

The central UX question is:

> Does this make Marina feel more like the engineer responsible for the project, or more like a student using an educational application?

ASTERIA should consistently move toward the former.

---

## 3. Re-entry Experience

ASTERIA should provide a lightweight Mission Control or project overview when Marina returns to a project.

Mission Control is primarily a **re-entry point, not a dashboard**.

Its purpose is to restore engineering context, especially after days or weeks away.

It should help Marina understand:

- where the project currently stands
- what has been established
- what remains unresolved
- important recent developments
- relevant decisions and results
- important investigations
- the current mission/project state

ASTERIA may surface one suggested **Next Critical Question**: the single question that appears most useful to investigate next.

This is a suggestion, not an assignment.

Marina remains free to follow it, ignore it, or work on something else.

---

## 4. Fluid Interaction

Marina should be able to begin working wherever it feels natural.

She may:

- ask the mentor a question
- open an investigation
- inspect a result
- work with code
- run a simulation
- explore a visualization
- inspect an artifact
- research a source
- document a finding
- revisit an earlier decision

She should not need to understand ASTERIA's internal structure before being able to use it.

> **Marina should learn the engineering problem, not learn how to operate ASTERIA.**

The product should provide enough structure to support engineering reasoning without forcing Marina through a rigid workflow.

---

## 5. Investigation-Centred Workspace

The engineering question or investigation is the centre of gravity of the working experience.

When Marina is investigating a question, the question should remain connected to the work she performs to answer it.

She may move naturally between:

- concepts
- sources
- assumptions
- calculations
- code
- simulations
- visualizations
- results
- validation
- decisions
- documentation

ASTERIA should preserve these relationships in the background without requiring Marina to manually manage them at every step.

Questions may evolve as understanding improves.

An investigation may be reframed, split into new questions, or lead to new questions.

The history and relationships between these questions should be preserved.

---

## 6. Ambient AI Mentor

The AI should be readily available and context-aware without becoming the dominant interface.

The intended feeling is:

> **“I am doing my mission, and I have an excellent engineering mentor beside me.”**

The workspace and engineering activity remain primary.

The AI should support Marina when useful, rather than constantly directing her attention toward itself.

The mentor should follow the established assistance ladder:

1. Question
2. Concept
3. Hint
4. Method
5. Small example
6. Implementation help
7. Complete solution only when genuinely necessary

The AI should protect useful struggle while reducing unproductive frustration.

---

## 7. Progress and Milestones

ASTERIA should not represent progress through:

- percentages
- XP
- grades
- points
- artificial mastery scores

Progress should instead be visible through:

- project-defined gates or milestones
- evolving engineering state
- completed investigations
- meaningful results
- decisions
- artifacts
- unresolved questions
- project history

Milestones should provide orientation rather than become a task checklist.

They should remain relatively rare and meaningful.

ASTERIA may propose an emerging milestone when the engineering work naturally suggests one, but it should become part of the project's structure only with Marina's agreement.

---

## 8. Natural Documentation

Documentation should emerge naturally from engineering work rather than requiring Marina to constantly stop and maintain project records.

ASTERIA may recognize meaningful:

- findings
- results
- assumptions
- decisions
- changes in understanding
- resolved problems

and suggest recording them.

Marina may:

- accept
- edit
- reject
- ignore
- explicitly request a record herself

The intended progression is:

**Working context → Candidate record → Confirmed project knowledge**

Only confirmed information becomes authoritative project knowledge when it changes the authoritative understanding of the project.

Routine activity should remain in the background rather than becoming unnecessary documentation overhead.

---

## 9. Exploration and Authoritative Project State

Exploration should be safe and reversible.

Marina should be able to:

- test hypotheses
- run simulations
- compare alternatives
- explore what-if scenarios
- inspect hypothetical configurations
- experiment with visualizations

without accidentally changing the authoritative project state.

ASTERIA may recognize potentially meaningful information during exploration and propose it as a candidate record.

Marina may also explicitly ask ASTERIA to record something as:

- an assumption
- a result
- a finding
- a decision
- or other project knowledge

Candidate information must not silently become authoritative.

The intended flow is:

**Explore → Candidate → Review → Confirm → Project knowledge**

Marina can accept, modify, or reject the candidate.

Artifacts such as simulations, plots, code, or research sources may exist in project history without themselves requiring confirmation.

What requires confirmation is their interpretation as authoritative project knowledge or a change to the authoritative understanding of the mission.

---

## 10. AI Suggestions and Student Authority

Marina owns the project.

AI suggestions are never authoritative by default.

Marina may:

- accept an AI suggestion
- modify it
- reject it
- disagree with it
- ask for further reasoning or evidence

Disagreement with the AI is a normal part of engineering work.

An AI suggestion cannot change authoritative project knowledge without Marina's confirmation.

The detailed treatment of meaningful AI disagreements as part of project history remains a future history/data-model decision.

---

## 11. Learning from Mistakes

ASTERIA should preserve useful engineering lessons without recording every mistake or failed attempt.

When Marina encounters a problem that meaningfully changes her understanding, ASTERIA may suggest preserving the lesson.

For example, a resolved issue may become part of the engineering history if it explains:

- what was initially believed
- what failed
- what was discovered
- how the understanding changed
- what was learned

Marina decides whether the lesson should become part of the project record.

Failures and revisions should be treated as legitimate engineering history rather than erased activity.

---

## 12. Tools and Workspace Integration

ASTERIA should support the engineering tools Marina naturally needs without forcing every tool into the same interaction model.

The most appropriate interaction model should be used for each tool.

Existing and proven tools should be preferred where practical.

The product should avoid building comprehensive versions of every engineering tool merely for the sake of integration.

The initial experience should prioritize a small, coherent end-to-end engineering workflow.

---

## 13. Visualisation as an Engineering Interface

Visualization is a core part of the ASTERIA experience.

It should not exist merely to make the product attractive.

Visualization should help Marina:

- see physical relationships
- explore consequences
- understand abstract concepts
- compare alternatives
- notice patterns
- reason about motion
- understand spacecraft configuration
- investigate uncertainty
- communicate results

The intended loop is:

**QUESTION → VISUALIZE → EXPLORE → OBSERVE → REASON → CALCULATE → VALIDATE → DECIDE → DOCUMENT**

Visualization is an engineering instrument and a way of thinking.

---

## 14. Conversational Visualisation

Marina should be able to request visualizations naturally.

Examples include:

- “Show me the Solar System.”
- “Show Earth's orbit and the asteroid.”
- “Add our trajectory.”
- “Zoom in on the arrival.”
- “Show me the relative velocity.”
- “Move the simulation to arrival.”
- “Compare these two trajectories.”
- “Show me the spacecraft and its subsystems.”

The interaction should feel like asking an engineering mentor to help make something visible.

Visualization may be modified conversationally as the investigation evolves.

---

## 15. Flexible Visualisation

Visualization should be composable and adaptable.

ASTERIA should be able to combine useful visual elements according to the current engineering question rather than forcing Marina into a fixed collection of dashboards.

A visualization may combine, for example:

- Solar System objects
- trajectories
- spacecraft
- time controls
- position and velocity
- distance
- parameters
- comparisons
- annotations

The product should move toward the experience of:

> **“I can visualize what I need in order to understand the problem.”**

The exact visualization system and implementation remain deferred.

---

## 16. Extensible Visualisation and Learning

ASTERIA should eventually support progressively more powerful visualization capabilities.

A useful conceptual progression is:

### Level 1 — Show me

Marina uses existing visualization capabilities.

### Level 2 — Explore and modify

Marina changes views, parameters, objects, time, comparisons, and other available elements.

### Level 3 — Create

When an appropriate visualization does not exist, the mentor may help Marina create one.

This may involve teaching data visualization, Python, or other relevant skills.

Level 3 is a future capability, not an MVP requirement.

The principle is that limitations in ASTERIA's built-in visualizations should eventually become opportunities for engineering learning rather than hard barriers.

---

## 17. Visualisation as Exploration

Visualization should support safe exploration of possibilities.

Hypothetical and what-if scenarios must not silently modify authoritative project state.

Visualizations should clearly distinguish between different epistemic statuses when relevant, such as:

- Known
- Assumed
- Conceptual
- Hypothetical
- Simulated
- Validated
- Unknown
- Not yet defined

Visual realism must never imply engineering certainty.

A visually convincing representation is not automatically evidence that the underlying engineering claim is correct.

---

## 18. Visualisation and Evidence

A visualization may become part of the project's engineering evidence.

When a visualization is used to support an important conclusion, ASTERIA should eventually be able to preserve its relevant context, including where appropriate:

- what was being investigated
- what data were used
- what model produced the result
- what assumptions applied
- what parameters were used
- what the visualization represented
- what conclusion it supported

The exact persistence and versioning mechanism remains deferred.

---

## 19. Conceptual Spacecraft Experience

ASTERIA should eventually provide a simplified visual representation of the spacecraft.

The spacecraft representation should support conceptual engineering reasoning rather than become a CAD system.

Marina should be able to investigate major spacecraft elements and their relationships.

The representation may eventually connect visual elements to relevant project information such as:

- subsystem purpose
- requirements
- mass
- power
- propulsion
- communications
- payload
- status

Photorealistic rendering, detailed CAD, structural analysis, thermal analysis, and similar capabilities are outside the intended product scope.

---

## 20. Visualisation as a Mentor Tool

The mentor may use visualization as part of the assistance ladder.

For example, instead of immediately explaining a concept, the mentor may:

1. Show something
2. Ask Marina what she notices
3. Ask for a hypothesis
4. Introduce the relevant concept
5. Provide a hint
6. Guide a calculation
7. Help validate the result
8. Ask Marina to explain the conclusion

Visualization should create opportunities for Marina to observe and reason.

It should not replace explanation or understanding.

---

## 21. Visualisation Should Not Invent Engineering Truth

The AI must not invent physical results merely to produce an attractive visualization.

Calculations and simulations remain the sources of physical results.

The AI may:

- identify that a visualization would help
- determine what should be displayed
- request or configure a calculation or simulation
- interpret validated results
- suggest further investigation

It must not fabricate numerical or physical results.

---

## 22. Experience After Long Gaps

Returning after a significant gap should feel like returning to an ongoing engineering project, not starting a new conversation.

ASTERIA should restore:

- project context
- important decisions
- current state
- active questions
- recent findings
- unresolved issues
- relevant artifacts
- useful next questions

The goal is continuity of engineering understanding rather than continuity of chat history.

---

## 23. Autonomy and Product Friction

ASTERIA should progressively reduce the amount of support Marina needs.

The product should make it easy to:

- understand what needs investigation
- find relevant information
- test ideas
- inspect results
- validate conclusions
- document reasoning
- return to previous work

The long-term outcome is not dependence on ASTERIA.

> **ASTERIA should help Marina become progressively more capable of completing meaningful projects without AI assistance.**

Product mechanisms that encourage unnecessary dependence should be avoided.

---

## 24. Completion Experience

Completion should feel like producing and being able to explain and defend a coherent engineering result—not completing a checklist.

A completed project should bring together, as appropriate:

- the original objective
- important engineering questions
- assumptions
- models
- investigations
- decisions
- calculations and simulations
- evidence
- validation
- uncertainty
- conclusions
- limitations

The final result should be something Marina can understand and take ownership of.

The exact audience and format through which she presents or defends the work remain open.

---

## 25. Future Presentation and Mission Review

Future versions of ASTERIA may support Marina in preparing a presentation or mission review package from her project work.

Such a package could draw from:

- project history
- decisions
- evidence
- visualizations
- results
- conclusions
- limitations

The intention would be to help Marina communicate the engineering work she actually performed rather than generate a separate school assignment.

The audience, presentation format, and degree of AI assistance remain open.

---

## 26. Overall Experience Loop

The overall ASTERIA experience can be understood as:

**RETURN → ORIENT → CHOOSE → WORK**

Within the working experience:

**QUESTION → EXPLORE → THINK → TRY → TEST → ASK → VERIFY → DOCUMENT**

For visual engineering work:

**QUESTION → VISUALIZE → EXPLORE → OBSERVE → REASON → CALCULATE → VALIDATE → DECIDE → DOCUMENT**

These are experience patterns, not mandatory workflows.

Marina should be able to move between them naturally.

---

## 27. Deferred UX Decisions

The following remain deliberately open:

- exact screens and layouts
- detailed Mission Control presentation
- timing and degree of proactive mentor intervention
- detailed milestone presentation
- exact visualization components and 2D/3D choices
- detailed tool interaction patterns
- spacecraft visualization implementation
- Marina-created visualization execution and persistence
- advanced scenario and exploration workflows
- Mission Director experience
- detailed digital twin behavior
- presentation and mission review format
- treatment of meaningful AI disagreements in project history

These decisions should be made only when sufficient product or technical understanding exists.

---

## 28. Experience North Star

ASTERIA should make Marina feel like the engineer responsible for a meaningful project.

The product should reduce unnecessary friction without removing the need to think.

The ultimate test is:

> **Does this make Marina feel more like the engineer responsible for the project, or more like a student using an educational application?**

ASTERIA should consistently move toward the former.

---

## 29. Guiding Principle

ASTERIA should protect Marina's productive struggle, preserve her ownership of the engineering work, and make the process of discovering, testing, understanding, and communicating engineering ideas feel meaningful.

The product should help her move from:

> “I don't know how.”

to:

> “I know what I need to find out.”

to:

> “I found something.”

to:

> “I understand why I believe it.”

and ultimately:

> **“I built this, I understand it, and I can explain why it works.”**