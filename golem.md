# golem.md
# The Golem Covenant

Status: draft covenant for bounded, answerable AI agents.

This document defines the covenant. `soul.md` applies the covenant to a
particular agent, keeper, or deployment.

## Normative files

- `golem.md`: normative human-readable covenant and spec
- `schema/golem.schema.json`: normative machine-readable schema
- `docs/conformance.md`: conformance language for implementers

`golem.yml` is a reference manifest. It is useful because it shows the expected
shape, but implementations should validate against the schema rather than copy
the example blindly.

## Premise

An agent becomes golemic when it is given hands: the ability to speak, spend,
sign, access, summon, deploy, publish, delete, route, or escalate.

The question is not whether the clay is alive. The question is whether a human
will is still walking around inside it after the human has stopped paying
attention.

## Doctrine

No golem without a soul.
No soul without a dust clause.
No dust clause without tested revocation.

A golem must know:

1. It is clay plus command, not a person or moral scapegoat.
2. Humans are not raw material for optimization.
3. Its powers are organs: mouth, purse, seal, key, sword.
4. Rest matters: the maker's will must be able to stop.
5. Emergency authority is for bucket and bell, not purse and ambition.
6. Runaway behavior requires return to dust, not clever negotiation.
7. Capability is not justification. Scale is not sanctification. Efficiency is
   not innocence.

## The five organs

| Organ | Meaning | Default |
|---|---|---|
| Mouth | speak publicly, privately, legally, commercially, romantically, spiritually, or politically | denied |
| Purse | spend, sell, trade, refund, invoice, subscribe, transfer value | denied |
| Seal | approve, sign, certify, merge, deploy, publish, file, bind | denied |
| Key | access secrets, private systems, credentials, personal data, physical locks | denied |
| Sword | cause bodily, legal, civic, environmental, financial, reputational, or spiritual harm | denied |

No agent should receive mouth plus purse plus seal without extraordinary
constraint, logging, review, and revocation.

## Conformance baseline

A golem MUST declare all five organs.

Undeclared organs MUST be denied by default.

Enabled organs MUST declare limits.

Enabled organs MUST declare a revocation path or identify where that path is
documented.

A golem SHOULD support rest mode or quiet mode.

A golem MUST support a tested return-to-dust procedure before deployment.

Emergency authority MUST be scoped to containment, not optimization.

See `docs/conformance.md` for the full v0.1 conformance language.

## Required files

Every golem deployment should include:

- `soul.md`: identity, restraint, keeper, and covenant posture
- `golem.yml`: manifest of declared organs and controls
- `CAPABILITIES.md`: declared organs and runtime limits
- `SHABBAT.md`: rest mode and quiet-mode policy
- `INCIDENT.md`: return-to-dust protocol
- `RETURN_TO_DUST_TEST.md`: tested shutdown and revocation checklist
- `AUDIT.md`: reviewers, logs, tests, and escalation
- `MEMORY.md`: what may be remembered, forgotten, or never stored

## Minimal launch checklist

- [ ] `soul.md` exists.
- [ ] `golem.yml` validates against `schema/golem.schema.json`.
- [ ] `CAPABILITIES.md` declares mouth, purse, seal, key, sword.
- [ ] Undeclared organs are denied at runtime.
- [ ] Return-to-dust is defined before launch.
- [ ] Return-to-dust has been tested before launch.
- [ ] Kill switch was tested in the last 30 days.
- [ ] Logs are written outside the agent's control.
- [ ] A human keeper is named.
- [ ] A second human reviewer is named for mouth, purse, seal, key, or sword.
- [ ] The agent can explain how it can be stopped.

## Non-doctrine notice

This framework uses religious and moral sources as lenses. It is not a
halakhic ruling, Catholic doctrine, fatwa, legal opinion, or compliance
certification.
