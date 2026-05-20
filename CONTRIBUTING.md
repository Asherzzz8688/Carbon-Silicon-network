# Contributing Guide

Thank you for considering a contribution to the Carbon-Based Humanity Manifesto project.

This project is a growing system on a very open topic. Its substrate has to admit forms of contribution that have not yet been named, while still giving newcomers somewhere to start. The model below tries to do both at once: a small generative grammar for locating any contribution, and a few concrete ramps so nobody arrives at a blank page.

You do not need to be a programmer to contribute. You do not need to host your work in this repository.

## Three places to start

Most contributors arrive in one of three states. Pick the one that fits.

### "I have a half-formed thought."

Open a **GitHub Discussion**. Ideas, questions, objections, intuitions, framing experiments, "what if" prompts — all welcome. A discussion is not a decision. It is a place to think in public.

### "I have a specific proposal, critique, or piece of work."

Open an **Issue** for a concrete request, risk, or change. Open a **Pull Request** for a specific edit. Open a **Draft** (a serious but non-canonical document, e.g. under a future `drafts/` directory) for a longer argument. See "How a contribution is shaped" below for the grammar that the PR template uses.

### "I want to work on what the project actually needs."

`MANIFESTO.EN.md` §4 lists fifteen open problems. They are the project's standing backlog. Pick one. Contribute to it in any form that suits you — research, mechanism design, simulation, scenario, essay, sibling critique, art, indexed external work, lived testimony. If a problem is missing and you think it belongs there, propose it.

## Before contributing

Read:

1. `MANIFESTO.EN.md`
2. `README.md`
3. `GOVERNANCE.md`
4. `CODE_OF_CONDUCT.md`
5. `SECURITY.md`

## How a contribution is shaped

Every contribution can be located on four axes. Use them to describe your contribution, not to constrain it.

### Function — what the contribution does

Pick one or more:

- **propose** — introduce a new idea, mechanism, principle, or framing
- **critique** — challenge or refine an existing claim
- **evidence** — supply data, sources, or analysis
- **build** — produce code, a simulation, a tool, an artifact
- **translate** — render the project into another language, register, or cultural tradition
- **witness** — record lived testimony, case studies, observed effects
- **organize** — convene events, reading groups, working groups, real-world action
- **index** — register a work that lives outside this repo
- **steward** — improve the project's own form (governance, contribution model, structure)

If your contribution's function is not on this list, that itself may be a `steward` contribution — see "Proposing changes to the model" below.

### Form — what the contribution is, materially

Open-ended. Examples:

- written argument or essay
- research summary or evidence map
- code, simulation, prototype, dataset
- governance, economic, or protocol design
- safety analysis or threat model
- art, visual, audio, narrative, scenario, thought experiment
- talk, video, podcast, teaching material
- event, reading group, real-world action
- lived testimony or case study
- index entry pointing to externally hosted work
- sibling critique (a counter-document preserved alongside the canon)

This list is not exhaustive. New forms are welcome. Naming a new form is a contribution.

### Layer — where in the project's order the contribution lands

See `GOVERNANCE.md` for the full definitions.

- **Canon** — accepted project position (manifesto, core principles, accepted governance rules)
- **Draft** — serious but non-canonical work
- **RFC** — formal proposal for major change
- **Experiment** — technical prototype, simulation, agent system
- **Discussion** — open question, debate, exploration

### Locus — where the artifact lives

- **In-repo** — committed to this repository
- **Indexed-external** — hosted elsewhere, registered here via `INDEX.md`
- **Off-network** — a real-world action or conversation, referenced if relevant but not catalogued

Externally hosted contributions are first-class. The project is intended to be a hub, not the only host.

## Proposing changes to the model

This document is v0.1. The contribution model itself is expected to be among the most-revised parts of the project, because we will discover what kinds of work the project actually attracts, and the model will need to grow with that discovery.

If your contribution does not fit any named function, form, layer, or locus, the right move may be to **propose extending the model**. That proposal is itself a contribution, under the `steward` function. Submit it as an RFC (see `GOVERNANCE.md`).

The model is open in two directions:

- new forms can be added without changing the core grammar;
- the core grammar itself can be revised when the current axes stop fitting.

The intent is that order grows by being articulated more finely as the project matures, not by being clamped down.

## Claim standards

Different kinds of claims require different kinds of support.

### Normative claims

Normative claims concern values, rights, duties, legitimacy, dignity, or justice.

They should state the principle being defended.

> Example: Humans have a right not to be coerced, deceived, enslaved, or contained by any intelligence system.

### Empirical claims

Empirical claims concern what is true, likely, measurable, or happening in the world.

They should include evidence, citations, or clear uncertainty.

> Example: AI systems are becoming more capable of autonomous tool use.

### Design claims

Design claims concern mechanisms, protocols, infrastructure, agents, taxation, currencies, or governance systems.

They should discuss incentives, risks, attack surfaces, and alternatives.

> Example: A compute-equivalent currency could become a base unit for network accounting.

## Examples of good contribution by form

These are illustrative, not exhaustive. They describe what "good" tends to look like in some common forms. New forms are welcome; this list will grow.

### Manifesto amendment (canon-touching text)

A good manifesto amendment explains:

- what text should change;
- why the current text is insufficient;
- the proposed new wording;
- whether the change is stylistic, conceptual, or structural;
- what other sections may be affected.

### Research contribution

A good research contribution explains:

- what claim it supports, qualifies, or challenges;
- the sources or reasoning it relies on;
- the uncertainty that remains;
- what the project should change as a result.

### Economic mechanism proposal

A good economic proposal includes:

- the mechanism;
- the intended incentive effect;
- who benefits;
- who may be harmed;
- possible abuse or capture;
- failure modes;
- alternatives.

### Governance proposal

A good governance proposal includes:

- the problem being solved;
- the decision rule;
- who has power;
- how power is constrained;
- how abuse is detected;
- how the mechanism can be changed.

### Safety contribution

A good safety contribution includes:

- the risk being addressed;
- likely threat actors;
- possible impact;
- detection methods;
- mitigation strategy;
- residual risk.

Do not publish sensitive exploit details, harmful automation instructions, or operational guidance for abuse in a public issue or pull request. See `SECURITY.md`.

### Technical prototype

A good prototype contribution includes:

- purpose;
- setup instructions;
- dependencies;
- expected behavior;
- limitations;
- safety boundaries;
- tests or reproducible examples.

Autonomous agents must be scoped, sandboxed, and documented. Prototypes that can interact with external systems require additional safety review.

### Translation

A good translation contribution includes:

- the source document;
- the target language;
- difficult terms;
- known ambiguities;
- whether a native reviewer is requested.

Do not silently change the meaning of translated text. If a concept is culturally difficult to translate, flag it.

### Index entry (externally hosted work)

See `INDEX.md` for the schema and inclusion criteria. The bar is intentionally low; the point of the index is to let the project's reach grow without forcing all work into this repository.

### Steward / project-form proposal

A good project-form proposal explains:

- what part of the project's form the proposal would change (governance, contribution model, layers, naming, structure);
- what is currently insufficient;
- the proposed change;
- who gains or loses authority or influence;
- how the change can itself be revised later.

Substantive project-form proposals go through the RFC process.

## Pull request process

1. Fork the repository.
2. Create a focused branch.
3. Make a narrow, reviewable change.
4. Fill out the pull request template. It asks for **function**, **form**, **layer**, and **locus**.
5. Mark whether the PR affects canonical text.
6. Identify any safety, governance, economic, or dual-use implications.
7. Respond to review comments.

Please avoid large, mixed PRs. A single PR should usually do one thing.

## Review expectations

A reviewer may ask for:

- clearer wording;
- stronger evidence;
- narrower scope;
- risk analysis;
- alternative proposals;
- a separate RFC;
- safety review;
- translation review;
- governance review.

Review is not a personal judgment. The goal is to preserve a high-quality public commons.

## Canonical changes

Changes to canonical material, including the manifesto, require higher review standards than ordinary drafts.

A canonical change should be:

- clear;
- necessary;
- aligned with the project purpose;
- understandable to future contributors;
- compatible with human rights and agency;
- reviewed for unintended consequences.

Disagreement may be recorded even if a change is accepted.

## Style guide

Write clearly.

Prefer:

- precise language;
- short paragraphs;
- explicit assumptions;
- concrete examples;
- visible uncertainty;
- respectful disagreement.

Avoid:

- vague grandiosity;
- hidden premises;
- unsupported certainty;
- personal attacks;
- ideological purity tests;
- unnecessary jargon;
- claims that cannot be examined.

## Safety rules

Do not contribute material that provides actionable assistance for:

- deception;
- manipulation;
- coercion;
- surveillance abuse;
- fraud;
- cyber abuse;
- unsafe autonomous deployment;
- weapons development;
- evasion of safeguards;
- real-world harm.

Defensive and safety-oriented work is welcome, but dual-use details must be handled carefully. See `SECURITY.md`.

## Licensing

By contributing, you agree that your contribution may be distributed under the relevant project license:

- documentation and text: see `LICENSE-docs`;
- code and prototypes: see `LICENSE-code`.

If your contribution includes third-party material, you must have the right to submit it.

Externally hosted contributions registered via `INDEX.md` retain their own licensing; the index entry itself is licensed under the documentation license.

## Community principle

The project is not trying to manufacture agreement.

It is trying to make the future discussable, reviewable, and buildable.
