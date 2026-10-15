# Detection and response

> **Reference work.** Fictional scenario built for a public portfolio. Not deployed in, derived from, or describing any employer environment. Not professional advice.

**What this is.** How a small team finds, contains, and recovers from security incidents around the clock, and the threats it plans against. On day 1 there is no after-hours coverage, and customer contracts set notification clocks that a slow response would miss.

## What could be built

- **A managed detection and response (MDR) service.** A provider watches Microsoft Defender around the clock and takes pre-approved containment actions inside limits the executive team sets in advance, live by the end of April 2027. An internal on-call rotation and a named incident commander handle what needs Fabrikam's own judgment. Before the service is live, an incident response retainer covers the year-end season.
- **An incident response plan.** Severity levels tied to business impact, an escalation and response-authority matrix, customer-notification readiness against contract clocks, and a plan aligned to the current NIST incident-handling guidance.
- **A payroll-diversion and email-compromise playbook.** Step-by-step handling for a request to change payroll or bank details and for a compromised mailbox, with out-of-band call-back verification and holding statements approved by General Counsel.
- **Hunting queries.** Eight Microsoft Defender advanced-hunting queries for discovery and measurement, covering sign-ins without strong authentication, legacy authentication, privileged role changes, external mail forwarding rules, app consent grants, stale accounts, remaining Windows 10 devices, and anonymous sharing links. They are in [`queries/`](queries/) as untested reference templates.
- **A threat profile and exercises.** The threats that matter most to a payroll platform, mapped to MITRE ATT&CK v20, plus an executive tabletop, notification drills, and one external penetration test in the summer of 2027.

## The key decision

A managed detection and response provider, rather than an in-house round-the-clock security operations center or business-hours-only coverage, because a lean team cannot staff nights and customer clocks are unforgiving (ADR-003).

## Full detail

Companion repository `it-security-first-year-plan`: document 08 (detection and incident response), document 17 (threat profile), ADR-003, and the payroll-diversion playbook. The queries here are the same files as in that repository.

## Sources

Drawn from and sourced in the companion repository `it-security-first-year-plan` (documents 08 and 17 and ADR-003 carry the primary sources, including the NIST incident-handling guidance and the MITRE ATT&CK version, with check dates). Each query file names its own data sources and licensing assumptions in its header.
