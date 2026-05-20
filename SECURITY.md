# Security and Safety Policy

## Purpose

This project deals with AI, agents, governance, safety infrastructure, and human rights. Some contributions may be dual-use: useful for defense, but also useful for harm if published without care.

This policy explains how to report security issues, safety concerns, and dual-use risks.

## Reporting security or safety issues

If you discover a vulnerability, unsafe prototype, dangerous disclosure, or serious misuse risk, do not publish operational details in a public issue.

Use the private reporting channel below:

```text
Security contact: harrisonzhaowork@gmail.com
```

Until a private channel is established, open a public issue with only a high-level description and request maintainer contact. Do not include exploit steps, sensitive code, credentials, or instructions for abuse.

## What to report

Please report:

- vulnerabilities in project code;
- unsafe autonomous agent behavior;
- prompt or tool designs that enable misuse;
- harmful automation risks;
- governance capture risks;
- privacy or identity risks;
- data exposure;
- instructions that could enable cyber abuse, fraud, manipulation, coercion, or surveillance abuse;
- unsafe disclosure in issues, pull requests, or discussions;
- dual-use research that needs restricted handling.

## What not to publish publicly

Do not publicly post:

- exploit code or step-by-step exploitation instructions;
- credentials, tokens, private keys, or private data;
- operational guidance for cyber abuse;
- instructions for fraud, phishing, or mass manipulation;
- weaponization guidance;
- bypasses for safety systems;
- details that make harmful autonomous deployment easier;
- private information about individuals.

## Safety expectations for prototypes

Technical prototypes should include:

- purpose and scope;
- setup instructions;
- expected behavior;
- limitations;
- dependencies;
- safety boundaries;
- known failure modes;
- external systems they can access;
- whether they use autonomous agents;
- whether they call external APIs;
- whether they can write files, send messages, execute code, or take actions outside a sandbox.

Autonomous agents should be constrained by default.

They should not be granted broad external permissions without explicit review.

## Dual-use review

A contribution may require dual-use review if it involves:

- autonomous agents;
- security testing;
- vulnerability discovery;
- surveillance or monitoring systems;
- persuasion or influence systems;
- identity, reputation, or arbitration infrastructure;
- safety bypass analysis;
- high-scale automation;
- models or tools that can be adapted for harm.

Reviewers may request:

- redaction;
- delayed publication;
- safer framing;
- sandboxing;
- narrower scope;
- additional documentation;
- external expert review.

## Coordinated disclosure

When a report concerns a real vulnerability or misuse pathway, maintainers should:

1. acknowledge receipt;
2. assess severity;
3. reduce immediate risk;
4. coordinate with affected parties when relevant;
5. prepare a fix or mitigation;
6. publish a summary when safe to do so.

The public summary should explain the issue and mitigation without enabling abuse.

## Safe harbor for good-faith research

Good-faith security and safety research is welcome when it is conducted responsibly.

Good-faith researchers should:

- avoid harming people or systems;
- avoid accessing private data;
- avoid persistence or stealth;
- avoid public disclosure before mitigation;
- report issues promptly;
- follow maintainer guidance.

## Out-of-scope requests

The project will not assist with:

- cyber abuse;
- fraud;
- coercion;
- surveillance abuse;
- unsafe deployment of autonomous agents;
- weapons development;
- evasion of safety systems;
- real-world harm.

## Emergency actions

Maintainers may temporarily remove, redact, lock, or pause content that creates a credible safety risk.

Such action should be documented when possible, but documentation may be limited if details would increase harm.

## Principle

Safety is not a side constraint on this project.

Safety is part of the project’s foundation.
