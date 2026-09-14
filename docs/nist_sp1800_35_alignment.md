# Alignment with NIST SP 1800-35

This note records what the toolkit takes from NIST SP 1800-35, *Implementing a Zero Trust
Architecture* (Final, June 2025), where it adds something, and where it deliberately stops.

## Language used here

The toolkit uses "aligned with", "complements" and "operationalizes". It does not use
"NIST-approved", "NIST-certified", "NIST-validated" or any similar construction. No endorsement by
NIST, the NCCoE, CISA or any other government entity exists or should be inferred.

## Theme-by-theme

### Scope and audience

SP 1800-35 assumes an existing cybersecurity capability and focuses on conventional enterprise IT.
The toolkit adds lightweight worksheets for teams with uneven documentation or limited staff, who
need a structured baseline before they can act on the guide's recommendations.

### Implementation challenges

Section 2.2 identifies resource constraints, training needs, incomplete asset inventory, limited
communication-flow visibility, fragmented policy and technology integration difficulties. The
readiness scorecard, risk register and integration checklist turn each of those into something a
team can record and track.

### Integration findings

Sections 5.1 to 5.3 document out-of-the-box integration limitations, incomplete policy context,
multiple policy decision points, and the value of SIEM, SOAR and data-security signals. The
integration readiness checklist converts those observations into questions to answer before
procurement, rather than after deployment.

### Incremental implementation

Section 8 recommends discovery, policy formulation, use of existing capabilities, risk-based gap
closure, incremental implementation, verification and continuous improvement. The sequencing
worksheet, test case library and 30/60/90-day review follow that order.

### Verification and periodic testing

Section 8.6 recommends repeatable testing across on-premises and cloud resources, managed and
unmanaged endpoints, authorized and unauthorized subjects, and service-to-service requests. The
test case library turns those scenarios into reusable records with expected results and evidence
requirements.

### Training and continuous improvement

Section 2.2 raises skills and training challenges; Section 8.7 covers continuous improvement. The
handover checklist treats internal operating capability as part of security readiness rather than
as project closeout, and the assurance review gives residual risk a scheduled follow-up.

## The gap this toolkit addresses

SP 1800-35 establishes that zero trust adoption is incremental. The toolkit addresses what
incremental adoption produces in practice: a transition state in which legacy identity paths,
temporary exceptions, hybrid dependencies, partial telemetry and mixed operational ownership
coexist for an extended period.

That state is not a separate target architecture. It is the operating condition that has to be
governed while the target architecture is being reached. The central principle is that temporary
risk should be visible, owned, monitored and retired, rather than allowed to become a permanent
operating condition by default.

## Where the toolkit deliberately stops

- **Data classification.** SP 1800-35 places the risk and policy requirements of discovering and
  classifying data outside its project scope. The sequencing worksheet does not attempt to fill
  that gap. It takes an organization's already-approved sensitivity label as an input and uses it
  to inform sequencing only.
- **OT and IoT.** Not addressed. The referenced material focuses on conventional enterprise IT and
  the toolkit stays within that boundary.
- **Vendor selection.** The integration checklist asks whether capabilities can be demonstrated.
  It does not recommend products.
- **Compliance and audit.** Nothing here constitutes a compliance determination, an audit opinion
  or a FedRAMP authorization package.

## References

1. NIST Special Publication 1800-35, *Implementing a Zero Trust Architecture*, Final, June 2025.
   DOI: 10.6028/NIST.SP.1800-35
2. NIST Special Publication 800-207, *Zero Trust Architecture*, August 2020.
3. NIST Cybersecurity Framework (CSF) 2.0, February 2024.
4. NIST Special Publication 800-53 Revision 5, *Security and Privacy Controls for Information
   Systems and Organizations*.

Comments on SP 1800-35 itself may be submitted to the NCCoE zero trust architecture project
address identified in that publication. Any such outreach should be framed as a request for
technical feedback, not as a request for endorsement.
