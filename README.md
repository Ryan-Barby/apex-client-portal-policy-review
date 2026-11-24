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

## Findings summary

| ID | Policy gap | Why it matters | Proposed direction |
|---|---|---|---|
| PR-01 | "Appropriate access" was undefined. | Different readers could interpret the requirement differently. | Define access based on duties and need; require approval by an authorised person other than the person whose access is being requested. |
| PR-02 | "Based on role" did not specify access levels for each role. | Access approvals and checks could be inconsistent. | Maintain a role-access table and compare the portal's access against it. |
| PR-03 | Temporary administrator access lacked clear reasons, an approver, documentation, and expiry follow-up. | Elevated access could remain active after the need ends. | Require a justification, authorised approval, time limit, and recorded expiry check. |
| PR-04 | Leaver access disabling had no named owner or timeframe. | Access could remain active after a staff member leaves. | Have the Practice Manager ensure access is disabled on the day the staff member leaves. |
| PR-05 | Backup and temporary-access follow-up responsibilities were not fully specified. | Expired elevated access might not be checked promptly. | Designate an authorised backup and record and check temporary-access expirations. |
| PR-06 | No routine access-review requirement was specified. | Unnecessary or changed access might go unnoticed. | Conduct and record a monthly review of portal access against current roles and approved exceptions. |

The full review table, with the reasoning behind each finding, is in [policy-review-findings](policy-review-findings).

## Repository contents

- [policy-review-findings.md](policy-review-findings.md) — the full review table (PR-01 to PR-06): the gaps identified in the draft policy, why each matters, and the proposed direction for each.
- [revised-client-portal-access-policy.md](revised-client-portal-access-policy.md) — the consolidated revised policy drafted in response to the findings, including its open implementation items.
- [framework-mapping.md](framework-mapping.md) — design-level mapping of the recommendations to NIST CSF 2.0 and the Essential Eight.

## Limitations and open design questions

The draft policy did not identify the portal's permission capabilities. Before implementation, Apex would need to confirm whether the portal supports separate privileged accounts and timed expiry; define who approves and independently reviews the Practice Manager's own access; nominate an authorised backup and escalation approver; and decide how policy changes are verified and records are kept current.

## Related project

- [mock-user-access-review](https://github.com/Ryan-Barby/mock-user-access-review) — a companion exercise using the same fictional scenario: a simulated review of Client Portal accounts against role and leaver rules.

## References

- NIST Cybersecurity Framework (CSF) 2.0, PR.AA-05.
- Australian Cyber Security Centre (ACSC), Essential Eight: Restrict Administrative Privileges.
