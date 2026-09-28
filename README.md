# Transition-State Zero Trust Adoption Toolkit

Open, vendor-neutral operational templates for governing the transition state between legacy
infrastructure and zero trust, aligned with NIST SP 1800-35.

**Version 0.1 (community review draft), August 2026.**

## The problem this addresses

NIST SP 1800-35 establishes that zero trust adoption is incremental rather than a single
deployment. What it does not cover in depth is the period in between: the months or years when
legacy identity paths, temporary firewall exceptions, hybrid dependencies, partial telemetry and
new enforcement points all operate at the same time.

That period is where temporary conditions quietly become permanent ones. A rule opened "just for
the migration" outlives the migration. An exception granted to one team is never reviewed because
nobody owns it. The organization reaches its target architecture with a layer of undocumented
risk underneath it.

The toolkit exists to make that middle state explicit: which dependency is blocking segmentation,
which exception is temporary, who owns it, when it expires, what has to be true before it can be
retired, and whether the internal team can operate the result once the implementers leave.

## What is in here

| Artifact | Format | Use |
|---|---|---|
| [Environment intake](assessment-tool/environment_intake.xlsx) | XLSX | Baseline the actual environment before scoring anything, including a workload register and an applicability map |
| [Readiness scorecard](assessment-tool/zero_trust_transition_readiness_scorecard.xlsx) | XLSX | Baseline twelve capability domains, 0-5, with evidence |
| [Transition-state risk register](templates/transition_state_risk_register.xlsx) | XLSX | Ownership, compensating control, expiry, retirement condition |
| [Data sensitivity and migration sequencing](templates/data_sensitivity_migration_sequencing.xlsx) | XLSX | Order workloads using approved sensitivity and readiness |
| [Integration readiness checklist](templates/integration_readiness_checklist.csv) | CSV | Validate multi-vendor policy chains before you depend on them |
| [Transition test cases](test-cases/zero_trust_transition_test_cases.csv) | CSV | Ten reusable validation scenarios |
| [Handover and operating model checklist](templates/handover_operating_model_checklist.md) | Markdown | Confirm the internal team can actually run it |
| [Four-week pilot plan](pilot/4_week_pilot_plan.md) | Markdown | Bounded way to try the toolkit |
| [Environment intake call guide](pilot/environment_intake_call_guide.md) | Markdown | One page to run the week 1 intake conversation |
| [Pilot feedback form](pilot/pilot_feedback_form.md) | Markdown | Structured input for the next version |
| [SP 1800-35 alignment notes](docs/nist_sp1800_35_alignment.md) | Markdown | Traceability and scope boundaries |

Each spreadsheet opens on a Read Me sheet explaining what it is for, followed by a working sheet
with shaded cells to complete and a worked sample.

## Where to start

Start with the environment intake, regardless of where you are in a migration. It establishes
what actually exists before anything gets scored, and it decides which scorecard domains and
test cases apply to your organization at all. Running the scorecard before the intake usually
produces a score for something that does not describe the environment in front of you.

Once the intake is done, move to the readiness scorecard. It takes an afternoon with the right
people in the room and it will tell you which domains are going to cause you trouble.

If you are already mid-migration and know you have accumulated temporary exceptions, start with
the risk register instead. Getting them into one place with names and dates against them is
usually the single highest-value hour available to you.

If you are choosing products, start with the integration readiness checklist, before procurement
rather than after.

## Who this is for

Organizations with real constraints: small teams, legacy systems that cannot simply be switched
off, uneven documentation, and obligations they have to meet anyway. State and local government,
community colleges, healthcare and financial SMEs, credit unions, nonprofits handling sensitive
data, and the service providers supporting them.

It assumes no specialist tooling and no consultant to interpret it.

## Scope and honest limits

This is independent practitioner work. It is informed by NIST SP 1800-35, NIST SP 800-207, NIST
CSF 2.0 and NIST SP 800-53 Rev. 5, and it uses the language "aligned with" and "complements"
deliberately.

It is **not** endorsed, approved, certified or validated by NIST, the NCCoE, CISA or any other
government entity. It is not a compliance determination, an audit opinion, a FedRAMP authorization
package, or a guarantee against breach. It does not replace formal data classification, privacy
review, legal review or enterprise risk management.

Sample values throughout are constructed for illustration. They are not results from a real
organization, and should not be presented as such.

## Contributing

Feedback from practitioners who have actually run a migration is the most useful thing this
project can receive, particularly on whether the fields are sufficient, which are missing and
which are noise. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

Released under [CC BY 4.0](LICENSE). Use it, adapt it, publish your changes. Attribution is
appreciated and required.
