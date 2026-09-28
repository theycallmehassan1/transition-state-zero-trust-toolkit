# Four-Week Pilot Plan

A bounded way to test the toolkit with one organization before wider use.

The pilot is deliberately small. It produces planning artifacts, not configuration changes, and
it should leave the organization with something useful whether or not they continue.

## Boundaries

The pilot does not require, and should not be given:

- Production passwords, private keys or credentials of any kind.
- Unrestricted or administrative access to live systems.
- Classified information or proprietary source code.
- Copies of sensitive, personal or regulated data.

System names and diagrams may be anonymized throughout. Nothing leaves the organization's
environment without their written agreement. The pilot changes nothing in the environment.

## What the organization needs to provide

- Time with the people who actually run the systems, roughly two hours a week.
- Existing inventory, architecture or network documentation, however incomplete.
- A named point of contact, and a sponsor who can make decisions.

Incomplete documentation is normal and is not a reason to delay. Finding out how incomplete it is
forms part of the baseline.

## Week 1: discovery and baseline

**Focus.** Establish scope and a factual baseline.

Confirm scope and owners. Run the environment intake first, using the call guide, before scoring
anything. Complete the workload register and capture every temporary condition the organization
can name. Use the applicability map to decide which of the twelve scorecard domains actually
apply here, then complete the readiness scorecard for those domains. Review whatever asset,
identity, network, logging and DR evidence exists. Identify legacy dependencies that are known
informally but not written down.

**Outputs.** Completed environment intake, workload register, temporary conditions list,
applicability map, scope statement, baseline scores with evidence references, list of evidence
gaps.

## Week 2: transition risks and integration

**Focus.** Make temporary conditions visible.

Create the transition-state risk register and carry over every entry from the week 1 temporary
conditions list, plus anything else that surfaces now. Assign business, technical and security
owners. Complete the integration readiness checklist for the pilot scope. Identify policy and
telemetry gaps.

**Outputs.** Populated risk register with owners and expiry dates, integration actions, exception
ownership matrix.

## Week 3: sequencing, tests and handover planning

**Focus.** Decide order, and define what proves it worked.

Work through the migration sequencing worksheet for the candidate workloads. Select five to ten
test cases from the library and adapt them. Draft the handover checklist against the current
state. Identify training needs.

**Outputs.** Proposed migration waves with rationale, adapted test suite, handover gap list.

## Week 4: review and roadmap

**Focus.** Hand over and set the follow-up.

Re-score the priority domains. Review residual risks. Run any authorized tests. Deliver a
workshop walking the internal team through each artifact so they can maintain them. Gather
feedback.

**Outputs.** Pilot findings, 30/60/90-day roadmap, completed feedback form, proposed changes for
v0.2.

## What the organization keeps

All artifacts, completed and populated with their own data, plus the blank templates. There is no
dependency on the facilitator afterwards. That is the point.

## Minimum success criterion

The pilot should identify at least one transition risk that was not previously being managed,
assign it a named owner, define an evidence-based retirement condition, and leave the
organization with a repeatable operating artifact.

If it does not achieve that, the pilot did not succeed, and the feedback explaining why is more
valuable than a polite write-up.
