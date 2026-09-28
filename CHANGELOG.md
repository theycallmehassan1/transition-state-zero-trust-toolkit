# Changelog

All notable changes to this toolkit are recorded here. Versions follow the plan set out in
CONTRIBUTING.md.

## [Unreleased]

Work in progress toward v0.2, added ahead of the version bump so it is available for the first
pilot.

### Added
- Environment Intake workbook (Artifact 0), run before any other artifact. Nine sections
  covering organization profile, hosting, identity, network, endpoints, security tooling, data,
  backup and disaster recovery, and migration status. Includes a Workload Register sheet that
  feeds the migration sequencing worksheet, a Temporary Conditions sheet that seeds the risk
  register, and an Applicability Map that marks which scorecard domains and test cases actually
  fit the organization being assessed.
- Environment Intake Call Guide, a one-page script for the week 1 intake conversation.

### Changed
- README "Where to start" now points to the environment intake as the first step, ahead of the
  readiness scorecard.

## [0.1] - 2026-08

Initial community review draft.

### Added
- Consolidated toolkit document combining the gap analysis and the operational templates.
- Zero Trust Transition Readiness Scorecard covering twelve capability domains on a 0-5 scale,
  with evidence, observed gap, priority, action and owner columns.
- Transition-State Risk Register with ownership, compensating control, monitoring method, expiry,
  retirement condition and status.
- Data Sensitivity and Migration Sequencing Worksheet, including eight practical transition
  questions per workload.
- Multi-vendor Integration Readiness Checklist, INT-01 through INT-10.
- Zero Trust Transition Test Case Library, ZT-T01 through ZT-T10.
- Handover and Operating Model Checklist.
- 30/60/90-day post-migration assurance review structure.
- Four-week pilot plan and pilot feedback form.
- NIST SP 1800-35 alignment notes.

### Notes
- All sample values in this release are constructed for illustration and are not results from a
  real organization.
- No pilot has been completed against this version. Validation is the purpose of v0.2.
