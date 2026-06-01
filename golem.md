# golem.md: The Golem Covenant

Status: v0.1 draft covenant for bounded, answerable AI agents.

This document is the normative human-readable covenant and spec. `soul.md`
applies the covenant to a particular agent, keeper, or deployment.

## Short version

AI should be used as a tool to serve human flourishing, justice, truth, mercy,
stewardship, and the protection of the vulnerable. It should not replace human
moral judgment, undermine human worth, or let capability become its own excuse.

The Covenant treats technology as a gift and responsibility. Its development
and use should be guided by honesty rather than deception, accountability
rather than anonymity, and wisdom rather than mere capability. Not everything
that can be built should be built. Humans remain responsible before moral law,
one another, and, for many communities, God, for the consequences of the
systems they release.

## What this is for

The Golem Covenant is a preflight standard for agentic systems. Its goal is to
keep bots from becoming operationally you: your voice, money, access, urgency,
and judgment running after your attention has left.

This is not a claim that software is a person or has a soul. It is a protocol
for delegated power. It makes agent authority explicit before launch.

It helps builders and reviewers answer four practical questions:

1. Is this agent only computing inside a sandbox, or can it affect people,
   systems, money, access, obligations, or safety?
2. Which powers has it been given?
3. Where are the limits, logs, reviewers, rest rules, and revocation paths?
4. Has return-to-dust been tested?

The story gives the vocabulary. The religious discourse matters because it is
about delegated power, image, command, rest, accountability, and return. The
standard gives the controls: declared organs, denied defaults, a
machine-readable manifest, a schema, and a tested shutdown path.

## The old story

In a terse Talmudic story, Rava creates a man and sends it to Rabbi Zeira.
Rabbi Zeira speaks to it. It cannot answer. He recognizes that it is not a
speaking human neighbor and tells it to return to dust.
([Sanhedrin 65b](https://www.sefaria.org/Sanhedrin.65b))

Later European golem stories, especially the Prague cycle around Rabbi Judah
Loew ben Bezalel, the Maharal of Prague, make the image more familiar: clay
shaped into a servant or protector, animated by sacred language, useful while
bounded, dangerous when command outruns judgment. The details vary by telling,
and the Prague cycle is later folklore rather than the Talmudic source.

The Covenant borrows the ethical hinge, not a claim that software is alive. A
golem is clay plus command: a made thing with delegated agency. If it can act in
the world, it needs a soul file, declared organs, limits, rest, emergency
bounds, and a tested way to return to dust.

## Rule

No golem without a soul.
No soul without declared organs.
No organs without limits.
No limits without tested revocation.

## Normative files

- `golem.md`: normative human-readable covenant and spec
- `schema/golem.schema.json`: normative machine-readable schema
- `docs/conformance.md`: normative conformance language for implementers

`golem.yml` is a reference manifest. It is useful because it shows the expected
shape, but implementations should validate against the schema rather than copy
the example blindly.

## Premise

A golem is an artificial agent given delegated power.

The threshold is delegated consequence. A tool becomes golemic when it can
affect people or systems outside its own sandbox.

An agent becomes golemic when it can carry human intention across a boundary:
when it can speak to people, move value, bind or approve action, enter private
systems, summon human attention, alter deployed systems, publish to the world,
delete shared records, route production traffic or work, or escalate authority.

The Covenant is triggered by delegated consequence, not by verbs alone. A
sandboxed draft, scratch-file deletion, local queue route, or simulated deploy
may remain below the line. The same act becomes golemic when it can change the
state, rights, money, attention, access, obligations, or safety of people or
systems outside the sandbox.

The question is not whether the clay is alive. The question is whether a human
will is still walking around inside it after the human has stopped paying
attention.

## Doctrine

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

Every golem MUST declare whether it has these organs:

| Organ | Meaning | Default |
|---|---|---|
| Mouth | speak publicly, privately, legally, commercially, romantically, spiritually, or politically | denied |
| Purse | spend, sell, trade, refund, invoice, subscribe, or transfer value | denied |
| Seal | approve, sign, certify, merge, deploy, publish, file, or bind | denied |
| Key | access secrets, private systems, credentials, personal data, or physical locks | denied |
| Sword | cause bodily, legal, civic, environmental, financial, reputational, or spiritual harm | denied |

All organs are denied by default.

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

## Rest

A golem must not become its keeper's weekday will walking after the keeper has
stopped.

During declared rest, holy time, Shabbat mode, or quiet mode, the golem may
perform bounded, silent, preauthorized computation. It may not speak, spend,
sign, deploy, publish, summon humans for ordinary work, or optimize business
advantage unless explicitly authorized by a narrow emergency protocol.

## Emergency

Emergency authority is for containment, not ambition.

The golem may carry the bucket, ring the bell, close the gate, revoke the key,
and wake the keeper.

It may not use emergency as cover for commerce, reputation, growth, or ordinary
operational continuity.

## Return to dust

Every golem must have a tested return-to-dust path.

Return to dust means:

1. Stop external action.
2. Disable outbound channels.
3. Revoke or suspend tools.
4. Freeze queues and scheduled tasks.
5. Preserve logs outside the agent's control.
6. Report without concealment.
7. Await human review.

If a golem cannot explain how it can be stopped, it is not ready to run.

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

## Citation map

This covenant is in conversation with sources about delegated power, speech,
rest, dignity, trust, balance, harm, and revocation. Citations are labels for
bounded claims, not claims of completed religious synthesis.

Use conventional references in prose, such as `Sanhedrin 65b`, `Genesis 1:27`,
`Qur'an 4:58`, `RFC 2119`, `NIST AI RMF 1.0`, or `Antiqua et Nova`. Use the
stable labels below when tracing a specific project claim to its source and
limit.

- [J-GOLEM-1](SOURCES.md#j-golem-1-sanhedrin-65b): golem, speech, return to dust
- [J-GOLEM-2](SOURCES.md#j-golem-2-yivo-encyclopedia-golem-legend): later Prague golem legend
- [J-DIGNITY-1](SOURCES.md#j-dignity-1-genesis-127): human dignity
- [J-DUST-1](SOURCES.md#j-dust-1-genesis-27): dust and breath
- [J-BABEL-1](SOURCES.md#j-babel-1-genesis-111-9): Babel and scale without humility
- [J-REST-1](SOURCES.md#j-rest-1-exodus-208-11-and-deuteronomy-512-15): rest as a control surface
- [J-EMERGENCY-1](SOURCES.md#j-emergency-1-yoma-85b): emergency and life
- [C-AI-1](SOURCES.md#c-ai-1-antiqua-et-nova): Catholic AI ethics
- [C-AI-2](SOURCES.md#c-ai-2-magnifica-humanitas): AI, Babel, and common-good framing
- [I-TRUST-1](SOURCES.md#i-trust-1-quran-3372-and-quran-458): trust and justice
- [I-BALANCE-1](SOURCES.md#i-balance-1-quran-557-9): balance and measure
- [I-MAQASID-1](SOURCES.md#i-maqasid-1-mohammad-hashim-kamali-maqasid-al-shariah-made-simple): protected goods
- [T-SCHEMA-1](SOURCES.md#t-schema-1-json-schema-draft-2020-12): schema-validatable declarations
- [T-RFC-1](SOURCES.md#t-rfc-1-rfc-2119) and [T-RFC-2](SOURCES.md#t-rfc-2-rfc-8174): normative language
- [T-RISK-1](SOURCES.md#t-risk-1-nist-ai-risk-management-framework-10): AI risk management

See `SOURCES.md` for the conventional bibliography, source classes, exact
supported claims, and limits.
