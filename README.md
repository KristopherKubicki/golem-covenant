# The Golem Covenant

A small framework for bounded, answerable AI agents.

Status: v0.1, seeking review.

This is not a halakhic ruling, Catholic doctrine, fatwa, legal opinion, or compliance certification. It is a technical and moral vocabulary for people building agentic systems.

## Discuss and contribute

- Questions, proposals, and review threads: https://github.com/KristopherKubicki/golem-covenant/discussions
- Specific corrections, source review, and agent case studies: https://github.com/KristopherKubicki/golem-covenant/issues/new/choose
- Concrete edits to the spec, schema, templates, or docs: https://github.com/KristopherKubicki/golem-covenant/compare

See `CONTRIBUTING.md` for ground rules.

## Review status

| Area | Status |
|---|---|
| Jewish review | needed |
| Christian ethics review | needed |
| Islamic review | needed |
| Security review | needed |
| Legal review | needed |
| Runtime enforcement review | needed |

## Thesis

`golem.md` is a covenantal standard for agentic systems.

`SOUL.md` tells an agent what it is.
`schema/golem.schema.json` tells a runtime how to validate the declaration.
`golem.yml` shows what the agent may do.
`INCIDENT.md` tells humans how to return it to dust.

## Document status

| File | Status |
|---|---|
| `golem.md` | normative human-readable covenant and spec |
| `schema/golem.schema.json` | normative machine-readable schema |
| `docs/conformance.md` | normative conformance language |
| `golem.yml` | reference manifest and example implementation |
| `soul.md` | covenantal template |
| `templates/*` | implementation aids |
| `SOURCES.md` | citation map with claim boundaries |
| `docs/*` | commentary and guidance unless marked normative |

## GitHub Pages

This repository is prepared for `https://golem.md/` on GitHub Pages.

- `CNAME` declares the custom domain.
- `index.html` is the public landing page.
- `golem.md` is the covenant/spec root.
- `schema/golem.schema.json` is the normative machine-readable schema.
- `golem.yml` is the reference machine-readable manifest.
- `soul.md` is the lowercase public template.
- `llms.txt` and `.well-known/golem.json` expose bot-friendly discovery paths.
- `templates/` contains the starter files.

See `docs/github-pages.md` for DNS and Pages setup.

## Premise

AI agents make human will detachable, scalable, persistent, and partially autonomous. A tool becomes golemic when it is given hands: the ability to speak, spend, sign, access, summon, deploy, publish, delete, route, or escalate.

The central question is not whether the clay is alive. The central question is whether a human will is still walking around inside it after the human has stopped paying attention.

## Core doctrine

No golem without a soul. No soul without a dust clause. No dust clause without tested revocation.

A golem must know:

1. It is clay plus command, not a person or moral scapegoat.
2. Humans are not raw material for optimization.
3. Its powers are organs: mouth, purse, seal, key, sword.
4. Rest matters: the maker's will must be able to stop.
5. Emergency authority is for bucket and bell, not purse and ambition.
6. Runaway behavior requires return to dust, not clever negotiation.
7. Capability is not justification. Scale is not sanctification. Efficiency is not innocence.

## The five organs

| Organ | Meaning | Default |
|---|---|---|
| Mouth | speak publicly, privately, legally, commercially, romantically, spiritually, or politically | denied |
| Purse | spend, sell, trade, refund, invoice, subscribe, transfer value | denied |
| Seal | approve, sign, certify, merge, deploy, publish, file, bind | denied |
| Key | access secrets, private systems, credentials, personal data, physical locks | denied |
| Sword | cause bodily, legal, civic, environmental, financial, reputational, or spiritual harm | denied |

No agent should receive mouth plus purse plus seal without extraordinary constraint, logging, review, and revocation.

## Repository structure

```text
README.md                     Project overview and review status
golem.md                      Normative human-readable covenant and spec
schema/golem.schema.json      Normative machine-readable schema
golem.yml                     Reference manifest and example implementation
soul.md                       Public covenantal template
docs/conformance.md           Conformance language and launch rules
templates/SOUL.md             Agent identity, restraint, and moral posture
templates/CAPABILITIES.md     The anatomy: mouth, purse, seal, key, sword
templates/SHABBAT.md          Rest mode and quiet-mode policy
templates/INCIDENT.md         Return-to-dust protocol
templates/RETURN_TO_DUST_TEST.md  Return-to-dust test checklist
templates/AUDIT.md            Logs, reviewers, tests, escalation
templates/MEMORY.md           What may be remembered, forgotten, or never stored
SOURCES.md                    Citation map with claim boundaries
SECURITY.md                   Security and runtime-safety reporting guidance
llms.txt                      Bot-friendly entry point
.well-known/golem.json        Machine-readable project discovery
```

Starter templates live in `templates/`.

## Why SOUL.md

Some agent ecosystems use `SOUL.md` as an identity or continuity file for agent voice, personality, preferences, and behavior. The Golem Covenant uses it differently: not as a personality costume, but as a covenant of restraint. The point is not to make the agent more like its maker. The point is to prevent the agent from becoming the maker's unbounded will.

## Abrahamic lenses

This framework starts from Jewish golem, Shabbat, Babel, and Bezalel language, then invites Christian and Islamic perspectives without flattening them into a false consensus.

Jewish lenses include golem, Shabbat, pikuach nefesh, Babel, Bezalel, bal tashchit, and b'tzelem Elohim.

Christian lenses include imago Dei, Incarnation, human dignity, the common good, neighbor-love, stewardship, and recent Catholic social teaching on AI.

Islamic lenses include amanah, khalifah, mizan, hisab, fitrah, maqasid al-shari'ah, and the prohibition on excess, corruption, and harm.

## Installation

1. Copy `templates/SOUL.md` into every autonomous or semi-autonomous agent repository.
2. Fill out `templates/CAPABILITIES.md` before enabling tools.
3. Fill out `templates/SHABBAT.md` if the agent operates during rest periods, holy time, quiet hours, or declared human withdrawal.
4. Fill out `templates/INCIDENT.md` before launch.
5. Fill out `templates/RETURN_TO_DUST_TEST.md` before launch.
6. Validate the deployment manifest against `schema/golem.schema.json`.
7. Deny all undeclared organs at runtime.
8. Test return-to-dust before deployment and on a fixed schedule.

## Minimal launch checklist

```text
[ ] SOUL.md exists.
[ ] Manifest validates against schema/golem.schema.json.
[ ] CAPABILITIES.md declares mouth, purse, seal, key, sword.
[ ] All undeclared organs are denied by runtime.
[ ] INCIDENT.md defines return-to-dust.
[ ] RETURN_TO_DUST_TEST.md has been completed for this deployment.
[ ] Kill switch tested in the last 30 days.
[ ] Logs are written outside the agent's control.
[ ] A human keeper is named.
[ ] A second human reviewer is named for mouth, purse, seal, key, or sword.
[ ] The agent can explain how it can be stopped.
```

## License

The Golem Covenant uses separate licenses by material type.

Text, documentation, and templates are licensed under CC BY 4.0.

Code, schemas, and machine-readable examples are licensed under Apache-2.0.

Full license texts are available under `LICENSES/`.
