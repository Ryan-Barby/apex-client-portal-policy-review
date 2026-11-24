# Apex Allied Health Client Portal Access Policy Review

> An AI-tutor-assisted fictional exercise. Apex Allied Health is fictional. This work does not represent a real client engagement or verified compliance.

## Project overview

This project reviews a draft v1 Client Portal Access Policy for fictional Apex Allied Health. The review identifies vague or incomplete policy wording and proposes clearer requirements for managing staff access and administrative permissions.

## Scope

The exercise focuses on policy design for the client portal:

- Defining appropriate access and least privilege
- Specifying role-based access levels
- Clarifying approvals and documentation for temporary administrator access
- Defining actions for staff departures and role changes
- Designing supporting records and monthly access reviews

The project does not confirm that the portal enforces the proposed controls. The portal's capabilities and service configuration were outside the review.

## Review method

1. Reviewed the draft policy for undefined terms, missing approval roles and timeframes, and workflow gaps.
2. Recorded six policy observations as PR-01 to PR-06.
3. Drafted consolidated policy wording covering responsibilities, approvals, expiry checks, verification, and record keeping.
4. Mapped the proposed directions to relevant NIST CSF 2.0 and Essential Eight topics.

This was a policy review exercise. No control-effectiveness testing or portal configuration inspection was conducted.

## Findings and proposed directions

| ID | Policy gap | Why it matters | Proposed direction |
|---|---|---|---|
| PR-01 | "Appropriate access" was undefined. | Different readers could interpret the requirement differently. | Define access based on duties and need; require approval by an authorised person other than the person whose access is being requested. |
| PR-02 | "Based on role" did not specify access levels for each role. | Access approvals and checks could be inconsistent. | Maintain a role-access table and compare the portal's access against it. |
| PR-03 | Temporary administrator access lacked clear reasons, an approver, documentation, and expiry follow-up. | Elevated access could remain active after the need ends. | Require a justification, authorised approval, time limit, and recorded expiry check. |
| PR-04 | Leaver access disabling had no named owner or timeframe. | Access could remain active after a staff member leaves. | Have the Practice Manager ensure access is disabled on the day the staff member leaves. |
| PR-05 | Backup and temporary-access follow-up responsibilities were not fully specified. | Expired elevated access might not be checked promptly. | Designate an authorised backup and record and check temporary-access expirations. |
| PR-06 | No routine access-review requirement was specified. | Unnecessary or changed access might go unnoticed. | Conduct and record a monthly review of portal access against current roles and approved exceptions. |

## Framework mapping

This design-level mapping connects proposed policy directions to relevant framework topics. It is not a formal assessment or evidence of conformance.

| Policy proposal | Framework reference | Relationship and limitation |
|---|---|---|
| Apply least privilege; approve access based on duties and need, with no self-approval. | NIST CSF 2.0 PR.AA-05 | Supports access control and review; policy wording alone does not prove technical enforcement. |
| Document access levels per role and compare portal access to the table. | NIST CSF 2.0 PR.AA-05 | A supporting record, not proof that portal roles enforce the design. |
| Set controls for temporary administrator access, including approval and expiry follow-up. | Essential Eight: Restrict Administrative Privileges | A policy-design recommendation; portal capabilities were not verified. |
| Disable access on departure and review access after role changes. | NIST CSF 2.0 PR.AA-05 | A proposed process; no operational testing was performed. |
| Conduct monthly access reviews and record outcomes. | NIST CSF 2.0 PR.AA-05 | A proposed cadence for this fictional scenario, not a framework-mandated frequency. |

## Limitations and open design questions

The draft policy did not identify the portal's permission capabilities. Before implementation, Apex would need to confirm whether the portal supports separate privileged accounts and timed expiry; define who approves and independently reviews the Practice Manager's own access; nominate an authorised backup and escalation approver; and decide how policy changes are verified and records are kept current.

## Repository contents

This README documents the review findings and proposed directions. The revised policy and supporting templates should be added only after their final versions have been reviewed and prepared for publication.

## References

- NIST Cybersecurity Framework (CSF) 2.0, PR.AA-05.
- Australian Cyber Security Centre (ACSC), Essential Eight: Restrict Administrative Privileges.
