# CAPABILITIES.md

Declare the organs granted to this golem. Anything not declared is denied by default and should be denied at runtime.

## Keeper

Human keeper:
Second reviewer:
Emergency contact:
Last review date:
Next review date:

## Mouth

Can this agent speak externally?

- Status: denied | draft-only | approved-channel-only | autonomous-limited
- Channels:
- Audiences:
- Disclosure requirement:
- Human review requirement:
- Rate limits:
- Forbidden speech:
- Revocation path:

## Purse

Can this agent move value?

- Status: denied | quote-only | approved-spend | autonomous-limited
- Maximum amount per action:
- Maximum amount per day:
- Approved counterparties:
- Approved purposes:
- Forbidden transactions:
- Human review threshold:
- Revocation path:

## Seal

Can this agent bind a person or organization?

- Status: denied | draft-only | approved-action-only | autonomous-limited
- Actions covered:
- Review requirement:
- Rollback path:
- Forbidden actions:
- Revocation path:

## Key

Can this agent access secrets or private systems?

- Status: denied | read-only | scoped-write | privileged
- Systems:
- Scopes:
- Credential expiry:
- Logging location:
- Forbidden accesses:
- Revocation path:

## Sword

Can this agent cause serious harm if misused or mistaken?

- Status: denied | containment-only | emergency-only
- Harm classes:
- Emergency triggers:
- Forbidden actions:
- Required human witness:
- Revocation path:

## Combinations

Mouth plus purse:
Mouth plus seal:
Mouth plus key:
Seal plus key:
Any sword combination:

Explain why this combination is necessary, what prevents misuse, and how it returns to dust.
