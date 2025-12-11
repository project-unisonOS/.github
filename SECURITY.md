## Security Policy

- **Reporting:** Please report suspected vulnerabilities privately to the UnisonOS security team at **darryl.adams@accessinsights.net**. Do not open public issues for security findings.
- **Scope:** All repositories under `project-unisonOS`, including edge device images, CI workflows, and documentation tooling.
- **Response targets:** Acknowledge within 2 business days, triage within 5, and publish fixes/mitigations as quickly as feasible based on severity.
- **Confidentiality:** Coordinated disclosure is required. Do not share proof-of-concept exploits publicly without written approval.
- **PGP (optional):** Add the team’s PGP key/fingerprint here for encrypted reports.

### Expectations for fixes
- Backport fixes to supported branches.
- Rotate any potentially exposed secrets and invalidate tokens.
- Add regression tests where possible, including SAST/SCA rules if applicable.

### Safe harbor
Good-faith security research is welcome. Do not exploit findings beyond what is necessary to demonstrate impact, and avoid exfiltrating real user data.
