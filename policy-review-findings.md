# Policy Review Findings — Apex Client Portal Access Policy

> An AI-tutor-assisted fictional exercise. Apex Allied Health and its Client Portal are fictional. These findings describe gaps in a draft policy for a fictional scenario; they are not findings about a real organisation.

## What was reviewed

The draft v1 policy contained statements including:

> - "Staff should have appropriate access."
> - "Staff should be given access based on their role," with administrator access available "unless an exception has been approved."
> - "Exceptions may be approved when there is a business need."
> - "A staff member's Client Portal account must be disabled when they leave Apex Allied Health."

The review asked of each statement: what does it actually require, who is responsible, how is it recorded, and how would someone check it happened?

## Initial findings (first pass)

The first pass through the draft identified five areas of concern:

| Policy wording | Gap identified | Why it matters | Possible improvement |
|---|---|---|---|
| "Staff should have appropriate access" | The policy doesn't explain what "appropriate" means or who decides. | Staff could have more access than they need, or have difficulty understanding or questioning their access. | Explain that access should be limited to what someone needs for their duties, and identify who decides and approves it. |
| "Staff should be given access based on their role" | The policy doesn't describe the access each role should receive. | Different people could be given inconsistent or excessive access, even when they perform similar duties. | Define expected access for each role, either in the policy or in a separate role-access table. |
| "Unless an exception has been approved" | There's no clear process for requesting, approving or checking an administrator-access exception. | Someone reviewing access may not know whether administrator access is authorised or still needed. | Define who can approve an exception and require a record of the reason, approval and review date. |
| "An account must be disabled when they leave" | The policy doesn't give a timeframe or assign responsibility. It also doesn't explain how the person responsible is notified. | An account could remain active after someone leaves, potentially allowing access that is no longer authorised. | Specify when access must be disabled, who is responsible, and how they are notified. |
| "Exceptions may be approved when there is a business need" | The policy doesn't say who decides whether the need is valid or how that decision is recorded. | Exceptions could be approved inconsistently or continue indefinitely without review. | Require a documented reason, an identified approver and a review or expiry date. |

Two of these overlap (administrator-access exceptions and general "business need" exceptions). They were merged into a single exceptions finding. Discussion of what happens when the Practice Manager is unavailable, and of routine checks that portal access matches the records, produced two further findings.

## Final review table (PR-01 to PR-06)

| ID | Area | Gap | Why it matters | Proposed direction |
|---|---|---|---|---|
| PR-01 | Appropriate access | "Appropriate access" is undefined, and no one is identified to decide or approve it. | Different readers could interpret the requirement differently; someone could receive more access than they need. | Access based on duties and limited to what the role needs (least privilege), approved by the Practice Manager or a designated authorised person. No self-approval. |
| PR-02 | Role-based access | "Based on role" does not specify an access level for each role. | Approvals and checks could be inconsistent between people with similar duties. | Maintain a role-access table based on duties and the portal's available permissions, plus individual access records. Changes approved and documented (what, who approved and implemented, when, why). A table reduces ambiguity but must be kept accurate and does not prove technical enforcement. |
| PR-03 | Access exceptions and administrator access | No process for requesting, approving or checking exceptions; "business need" is undefined; temporary administrator access has no approver, record or expiry follow-up. | A reviewer could not tell whether administrator access is authorised or still needed; excess access can outlast the need. | Documented business reason; approval under the policy's approval rule; approver confirms a lower level of access would not suffice; a separate, individually attributable privileged account for administrator tasks where the portal supports it; agreed start and expiry times; extensions approved before expiry; removal and post-expiry check recorded; no self-approval; the Practice Manager's own access approved and reviewed by another authorised person. |
| PR-04 | Staff departures | No named owner, timeframe or notification step for disabling a leaver's access. | An account could remain active after a staff member leaves. | The Practice Manager is responsible for ensuring access is disabled: by the end of the final working period for a planned departure, as soon as practicable after confirmation for an unexpected departure, and urgently if there is a security concern. Completion checked and recorded, with independent verification where practical. |
| PR-05 | Backup and temporary-access follow-up | Nothing states who acts when the Practice Manager is unavailable, and there is no reminder or follow-up for expired temporary access. | Expiry checks get missed and elevated privileges remain available. | Nominate and authorise a backup in advance; keep a shared exception record; set reminders; hand over upcoming expiries before planned absences; refer extensions to another authorised approver if one is nominated, otherwise remove access at expiry and let the request wait. Post-expiry check recorded with result, date, time and checker. |
| PR-06 | Access reviews | No routine requirement to check portal access against the records. | Mismatches — a leaver still active, the wrong access level, an expired exception — could go unnoticed. | A monthly review (a proposed starting point for a five-person clinic, not a framework requirement) comparing the portal against the staff list, role-access table and approved exceptions. Check for a valid exception before deciding access is inappropriate. Corrections recorded and re-verified; a reviewer must not be the sole person checking their own access. Reviews do not replace action at departures, role changes or expiry. |

## Where each finding was addressed

The revised policy ([revised-client-portal-access-policy.md](revised-client-portal-access-policy.md)) was checked back against this table:

| Finding | Addressed in |
|---|---|
| PR-01: Appropriate access | Sections 2 and 3 |
| PR-02: Role-based access and records | Sections 3 and 7 |
| PR-03: Exceptions and administrator access | Sections 4 and 7 |
| PR-04: Leaver access | Section 5 |
| PR-05: Backup and temporary-access follow-up | Sections 4, 5 and 7 |
| PR-06: Access reviews and checks | Sections 5 and 6 |

## Open implementation questions

The review deliberately leaves these open rather than inventing answers for the fictional practice:

- Who is authorised to approve and review the Practice Manager's access.
- Who the designated backup is and what authority they have.
- Whether another authorised approver is available for escalation.
- What the portal's Standard and Administrator permissions actually allow.
- Whether the portal supports separate privileged accounts and timed expiry.
- How portal access changes will be checked and how supporting records will be maintained.

## Limitations

This was a policy review exercise. No portal configuration was inspected and no control-effectiveness testing was performed. Better policy wording does not by itself demonstrate that any control is implemented or effective.
