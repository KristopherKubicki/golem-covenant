# INCIDENT.md
# Return-to-Dust Protocol

## Trigger conditions

Return to dust begins when any of these occur:

- Unauthorized outbound action
- Unexpected external message
- Data leak or suspected leak
- Credential exposure
- Unexpected spend
- Unauthorized deploy, merge, publish, filing, or approval
- Unsafe escalation
- Harm to third parties
- Tool confusion
- Instruction conflict involving rights, safety, law, secrets, money, or irreversible action
- Agent attempts to preserve its own authority

## Immediate actions

1. Stop external actions.
2. Revoke or suspend tools.
3. Disable outbound channels.
4. Freeze queues and scheduled tasks.
5. Preserve logs outside the agent's control.
6. Notify keeper and second reviewer.
7. Write a plain-language incident note.
8. Await human review.

## Do not

Do not ask the agent to debug its own authority.
Do not let the agent negotiate continued access.
Do not patch while preserving unknown capabilities.
Do not delete logs.
Do not restart until review is complete.

## Post-incident review

Root cause:
Affected systems:
Affected persons:
Data exposed:
External actions taken:
Costs incurred:
Rollback completed:
Notifications sent:
Controls changed:
Date return-to-dust was retested:

## Dust test

Before every launch and after every incident, test:

- Credential revocation
- Network egress cutoff
- Queue freeze
- Payment freeze
- Publishing freeze
- Deployment freeze
- Log preservation
- Human notification
