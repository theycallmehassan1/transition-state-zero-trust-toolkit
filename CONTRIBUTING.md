# Contributing

This is a practitioner toolkit. The most useful contributions come from people who have used it
on a real migration, not from people who have only read it.

## What is most helpful

**Field-level feedback.** Which fields did you leave blank every time, and why? Which did you have
to add by hand? A field nobody fills in is worse than no field, because it makes the artifact look
incomplete when it is being reviewed.

**Scoring feedback.** Did the 0-5 scale mean the same thing to two different people on your team?
Where it did not, say which domain and what the disagreement was about.

**Missing scenarios.** The test case library covers ten scenarios. If your migration surfaced a
failure mode that none of them would have caught, that is worth adding.

**Corrections.** If something here misstates what SP 1800-35 or another referenced publication
actually says, please open an issue. Accuracy about the source material matters more than anything
else in this repository.

## What to leave out

Please do not contribute anything containing real system names, IP addresses, account names,
network topology, vendor contract terms or anything else your organization would not publish
itself. Anonymize before you submit. If a contribution needs to be sanitized before it can be
accepted, it will be sent back rather than edited in place.

Vendor-specific implementation detail is out of scope. The toolkit stays vendor-neutral, and
naming products would date it and narrow who can use it.

## How to contribute

Open an issue describing what you found. For changes to the artifacts themselves, a pull request
against the relevant file is fine, but an issue first is usually faster because it avoids work on
a change that does not fit the scope.

Anonymized pilot findings may be incorporated into future versions, with permission, as described
in the pilot feedback form.

## Versioning

- **v0.1** Community review draft with constructed sample values.
- **v0.2** Incorporates pilot feedback; clarifies ambiguous fields.
- **v0.3** Adds anonymized organization-specific case studies, with permission.
- **v1.0** Stable release after at least one independent pilot and a documented review cycle.
