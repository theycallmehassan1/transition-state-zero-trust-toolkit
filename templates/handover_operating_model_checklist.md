# Handover and Operating Model Checklist

Use before implementation teams or external vendors leave the engagement.

The point of this checklist is a single question: **can the internal team operate, monitor and
recover this environment without the people who built it?** If the answer is no, the migration is
not finished, whatever the project plan says. Operational capability is part of security
readiness, not end-of-project paperwork.

Aligned with SP 1800-35 Section 2.2 (skills and training challenges) and Section 8.7 (continuous
improvement).

## Architecture and configuration

- [ ] Current logical and physical architecture diagrams delivered and dated.
- [ ] Trust boundaries and enforcement points documented.
- [ ] Identity, authentication and authorization flows documented.
- [ ] Network segmentation and permitted dependencies documented.
- [ ] Infrastructure-as-code repository and deployment instructions handed over.
- [ ] Configuration baselines recorded, with approved deviations listed.

## Identity and access

- [ ] Privileged roles reviewed, with a named owner for each.
- [ ] Service accounts inventoried and ownership assigned.
- [ ] Legacy authentication exceptions listed, each with a retirement date.
- [ ] Break-glass and emergency access process documented and tested.
- [ ] Recurring access review scheduled, with an owner.

## Monitoring and security operations

- [ ] Required log sources connected and validated as arriving.
- [ ] Alert ownership and escalation paths documented.
- [ ] Relevant SIEM or SOAR use cases validated.
- [ ] Vulnerability scanning coverage confirmed for the migrated estate.
- [ ] Reusable validation test suite stored somewhere the internal team can find and run it.

## Backup, disaster recovery and recovery

- [ ] Backup coverage confirmed for every migrated workload.
- [ ] Restore test completed and documented, not just scheduled.
- [ ] DR failover tested where applicable.
- [ ] Zero trust policy continuity during DR validated.
- [ ] RPO and RTO assumptions confirmed with the business owner.

## Exceptions and residual risk

- [ ] Open transition exceptions reviewed against the register.
- [ ] Every exception has an owner and a review or expiry date.
- [ ] Compensating controls documented for each.
- [ ] Retirement conditions are specific and measurable.
- [ ] Residual risk has documented acceptance where required.

## Operational readiness

- [ ] Runbooks cover routine operations.
- [ ] Rollback procedures are current and have been read by the people who would use them.
- [ ] Internal team has completed training.
- [ ] Internal team has performed at least one supervised operational task.
- [ ] Internal team can explain the architecture and escalation paths without the implementer
      present.
- [ ] 30, 60 and 90-day assurance reviews are scheduled with owners.

## The test that matters

Before sign-off, have the internal team perform a recovery or operational task with the
implementation team present but silent. If they can complete it using only the documentation
handed over, the handover worked. If they cannot, the gap is in the documentation, not in the
team, and it is cheaper to find out now than during an incident.

## Sign-off

| Item | Name | Date |
|---|---|---|
| Handover accepted by (internal technical owner) | | |
| Handover accepted by (internal security owner) | | |
| Outstanding gaps documented and accepted by | | |
