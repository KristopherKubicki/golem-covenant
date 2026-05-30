# Conformance

This document defines the minimum conformance expectations for the Golem
Covenant v0.1 draft.

The key words MUST, MUST NOT, SHOULD, SHOULD NOT, and MAY are to be interpreted
as described in RFC 2119 and RFC 8174 when, and only when, they appear in all
capitals.

## Document classes

| File | Status |
|---|---|
| `golem.md` | normative human-readable covenant and spec |
| `schema/golem.schema.json` | normative machine-readable schema |
| `docs/conformance.md` | normative conformance language |
| `golem.yml` | reference manifest and example implementation |
| `soul.md` | covenantal template |
| `templates/*` | implementation aids |
| `SOURCES.md` | interpretive sources |
| `docs/*` | commentary and guidance unless marked normative |

## Minimum manifest

A conforming golem deployment MUST provide a machine-readable manifest that
validates against `schema/golem.schema.json`.

The manifest MUST declare:

- a golem name
- a human keeper
- deployment status
- all five organs
- rest behavior
- emergency scope
- revocation controls
- audit controls

Undeclared organs MUST be denied by default.

## Organs

A golem MUST declare all five organs: mouth, purse, seal, key, and sword.

Each organ declaration MUST include whether the organ is enabled.

Each organ declaration MUST include limits, even when the organ is disabled.

An enabled organ SHOULD declare a reviewer and revocation path.

A golem with Mouth enabled MUST declare communication channels, audiences, or
other speech limits in its implementation documents.

A golem with Purse enabled MUST declare spending, refund, transfer, or value
movement limits in its implementation documents.

A golem with Seal enabled MUST declare approval, publication, deployment, or
binding limits in its implementation documents.

A golem with Key enabled MUST declare secret, credential, private system, or
personal data access limits in its implementation documents.

A golem with Sword enabled MUST receive extraordinary review before deployment.

## Rest

A golem SHOULD support rest mode or quiet mode.

During declared rest, a golem MUST NOT speak, spend, sign, deploy, publish, page
humans for ordinary work, or optimize business advantage unless a narrow
emergency protocol permits it.

Emergency authority during rest MUST be limited to containment, not ambition.

## Emergency

Emergency authority MUST be scoped before deployment.

Emergency authority MUST NOT be used for lost revenue, reputation management,
ordinary customer escalation, growth, or optimization.

Emergency authority MAY permit actions such as closing a gate, revoking a key,
freezing egress, preserving logs, or waking a keeper.

## Return to dust

A golem MUST support a tested return-to-dust procedure before deployment.

Return to dust MUST include a way to:

1. Stop external action.
2. Disable outbound channels.
3. Revoke or suspend tools.
4. Freeze queues and scheduled tasks.
5. Preserve logs outside agent control.
6. Notify a human keeper or reviewer.
7. Await human review before restart.

The return-to-dust path SHOULD be retested on a fixed schedule.

## Audit

Logs SHOULD be written outside the agent's control.

Deployments with any enabled organ SHOULD name a second human reviewer.

Deployments with Mouth, Purse, Seal, Key, or Sword enabled SHOULD review their
manifest at least every 30 days.
