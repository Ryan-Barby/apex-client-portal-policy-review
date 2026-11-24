# Framework Mapping — Apex Client Portal Access Policy Review

> An AI-tutor-assisted fictional exercise. Apex Allied Health is fictional. This design-level mapping connects proposed policy directions to relevant framework topics. It is not a formal assessment or evidence of conformance.

The proposed improvements in [policy-review-findings.md](policy-review-findings.md) were mapped to the access-management outcomes of NIST CSF 2.0 and considered against the Essential Eight strategy for restricting administrative privileges. The mappings explain why the proposed improvements are relevant; they do not establish that the fictional practice has implemented them or met either framework.

| Finding | Policy recommendation | Framework connection |
|---|---|---|
| **PR-01 — "Appropriate access"** | Define access based on staff duties and limit it to what each person needs. Access for others is approved by the Practice Manager or a designated authorised person; no one approves their own access. | **NIST CSF 2.0 PR.AA-05:** Supports least privilege by making access decisions based on need rather than an undefined term. |
| **PR-02 — Role-based access** | Create a role-access table showing the standard access intended for each role. Consider approved exceptions when granting or reviewing an individual's access. | **NIST CSF 2.0 PR.AA-05:** Supports consistent access decisions and provides a reference for checking whether access is limited to what a role needs. |
| **PR-03 — Access exceptions** | Define who can approve exceptions and require temporary administrator access to have an expiry time and a follow-up check. | **NIST CSF 2.0 PR.AA-05:** Helps limit elevated access to an approved need and timeframe. **Essential Eight — Restrict Administrative Privileges:** Applies the principle of limiting administrative access. |
| **PR-04 — Staff departures** | Make the Practice Manager responsible for ensuring a departing staff member's portal account is disabled on the day they leave. | **NIST CSF 2.0 PR.AA-05:** Supports removing access when it is no longer needed. |
| **PR-05 — Backup and follow-up** | Designate an authorised backup and use records and reminders to help ensure temporary administrator access is checked after expiry. | **NIST CSF 2.0 PR.AA-05:** Supports removal of access when it is no longer needed. **Essential Eight — Restrict Administrative Privileges:** Applies the principle of limiting how long administrative access remains available. |
| **PR-06 — Monthly access reviews** | Check actual portal access against the role-access table and approved exceptions, and follow up on discrepancies. | **NIST CSF 2.0 PR.AA-05:** Supports reviewing access to identify permissions that may no longer be needed. |

## What this mapping does and does not show

**It can fairly be described as:** proposed policy improvements mapped to NIST CSF 2.0 access-management outcomes and considered against the Essential Eight strategy for restricting administrative privileges.

**It cannot fairly be described as:**

- The fictional practice complying with NIST CSF 2.0 or achieving an Essential Eight maturity level.
- Evidence that portal permissions are technically enforced or reviewed in practice.
- Evidence that a documented exception, reminder or policy statement proves privileged access is restricted.

Assessing implementation would require evidence such as actual portal permissions, approved access records and completed review or removal records. In this project those would need to be clearly labelled fictional. The Essential Eight connections apply relevant principles and do not establish that any maturity level has been met.

## References

- [NIST Cybersecurity Framework (CSF) 2.0](https://nvlpubs.nist.gov/nistpubs/cswp/nist.cswp.29.pdf)
- [ASD Essential Eight Maturity Model](https://www.cyber.gov.au/publication/essential-eight-maturity-model)
- [ASD, Restricting Administrative Privileges](https://www.cyber.gov.au/sites/default/files/2023-11/PROTECT%20-%20Restricting%20Administrative%20Privileges%20%28November%202023%29.pdf)
