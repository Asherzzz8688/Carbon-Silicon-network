# Governance

## Current stage

This project is currently in **Seed Governance**.

Seed Governance means:

- the project is still forming its initial structure;
- maintainers may make practical setup decisions;
- major changes should be discussed openly;
- canonical text should not change casually;
- the governance process itself is expected to evolve.

## Governance goals

The governance system should protect:

- human rights and agency;
- openness to serious contribution;
- intellectual honesty;
- safety and responsible disclosure;
- pluralism and disagreement;
- resistance to capture;
- practical progress.

## Project layers

### Canon

Canon contains the current accepted project position.

Examples:

- the manifesto;
- core principles;
- accepted governance rules;
- accepted safety boundaries.

Canon changes require careful review.

### Draft

Drafts are serious but non-canonical materials.

Examples:

- essays;
- proposals;
- mechanism sketches;
- research notes;
- critiques;
- experimental frameworks.

Drafts may disagree with canon.

### RFC

RFCs are formal proposals for major changes.

Examples:

- adding a new human right;
- changing the economic model;
- changing the governance system;
- introducing a protocol layer;
- defining compute-equivalent currency;
- approving a new class of safety infrastructure;
- revising the contribution model or other project-form structure.

### Experiment

Experiments are technical prototypes, simulations, tools, or agent systems.

Experiments must follow the safety policy.

## Roles

### Stewards

Stewards are responsible for the overall direction of the project.

They may:

- approve canonical changes;
- appoint reviewers;
- resolve process disputes;
- pause high-risk work;
- initiate governance changes.

### Editors

Editors are responsible for clarity, structure, and coherence of written materials.

They may:

- review manifesto edits;
- improve wording;
- maintain style consistency;
- request clearer argumentation.

### Domain reviewers

Domain reviewers evaluate contributions in specific areas.

Possible areas include:

- AI safety;
- alignment;
- economics;
- governance;
- security;
- law and rights;
- translation;
- agent systems.

### Technical maintainers

Technical maintainers review code, prototypes, simulations, and infrastructure.

They may:

- review implementation quality;
- request tests;
- review safety boundaries;
- block unsafe technical changes.

### Contributors

Contributors are anyone who submits issues, discussions, pull requests, research, translations, code, or review comments.

Contributors may become reviewers or maintainers over time through consistent high-quality work.

## Decision types

### Routine decisions

Routine decisions include typo fixes, formatting, small documentation edits, and low-risk clarifications.

These may be merged by one maintainer.

### Substantive decisions

Substantive decisions include changes to meaning, project scope, terminology, or process.

These should usually receive review from at least two maintainers or one maintainer plus one relevant domain reviewer.

### Canonical decisions

Canonical decisions affect the manifesto, core principles, or governance rules.

These should require:

- a clear proposal;
- public review period when appropriate;
- documented reasoning;
- at least two approving maintainers;
- no unresolved high-severity safety concern.

### Safety-sensitive decisions

Safety-sensitive decisions affect security, autonomous agents, misuse potential, risk disclosure, or dual-use systems.

These require safety review. Maintainers may temporarily withhold, redact, or delay public details when necessary to prevent harm.

## RFC process

When the repository adds an `rfcs/` directory, major proposals should follow this lifecycle:

1. **Idea** — discussed informally.
2. **Draft RFC** — written in structured form.
3. **Review** — evaluated by maintainers and domain reviewers.
4. **Revision** — updated in response to critique.
5. **Accepted** — approved as project direction.
6. **Implemented** — reflected in canon, docs, or code.
7. **Rejected** — declined with reasoning.
8. **Archived** — preserved for historical record.

A rejected RFC may still be valuable.

## Merge criteria

A pull request may be merged when it is:

- aligned with the project purpose;
- clear and reviewable;
- appropriately scoped;
- licensed correctly;
- safe to publish;
- reviewed by the right people;
- not dependent on unresolved critical objections.

A merged PR does not mean every maintainer agrees with every sentence. It means the change meets the current project standard.

## Disagreement

Disagreement should be recorded, not erased.

When consensus is not possible:

1. clarify the disagreement;
2. separate empirical, normative, and design claims;
3. identify what evidence or reasoning would change minds;
4. move broad debate to Discussions;
5. preserve minority reports when useful;
6. avoid forcing unresolved issues into canon.

## Conflict of interest

Maintainers and reviewers should disclose conflicts of interest when they affect judgment.

Examples include:

- financial interest;
- employment relationship;
- institutional obligation;
- personal relationship;
- direct control over a proposed system.

A conflict does not automatically disqualify someone, but it should be visible.

## Emergency safety actions

Maintainers may take emergency action to reduce immediate risk.

Emergency actions may include:

- temporarily locking an issue;
- removing dangerous technical details;
- pausing a pull request;
- moving discussion to private reporting;
- requesting external safety review.

Emergency actions should be documented after the immediate risk has passed, unless documentation itself would create harm.

## Changing governance

This governance document may be changed through a substantive PR or RFC.

Changes should explain:

- the current governance problem;
- the proposed change;
- who gains or loses authority;
- how abuse is prevented;
- how the change can be reversed or amended.

## Evolution of project form

The contribution model, project layers, repository structure, and this governance document are themselves subject to revision.

Proposals to change the project's form are a recognized class of contribution (the `steward` function described in `CONTRIBUTING.md`) and follow the RFC process when substantive.

The intent is that the project's order grows by being articulated more finely as the project matures — not by being clamped down. The model should be expected to evolve as the project discovers what kinds of work it actually attracts.

## Long-term direction

The long-term goal is to move from founder-led Seed Governance toward a more pluralistic, transparent, and resilient governance model.

The project should become harder to capture as it becomes more important.
