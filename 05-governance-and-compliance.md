# Governance, risk, and compliance

> **Reference work.** Fictional scenario built for a public portfolio. Not deployed in, derived from, or describing any employer environment. Not professional advice.

**What this is.** How the program is governed, how risk is run, how the SOC 2 program is protected, how people are trained, and how results reach the executive team. On day 1 SOC 2 evidence is gathered by hand near audit time, there is no formal risk register, and policies are out of date.

## What could be built

- **A governance model and NIST CSF 2.0 Profiles.** Clear decision rights (the Director proposes and executes; the executive team approves and accepts risk), forums with set cadences, and a current and target NIST Cybersecurity Framework 2.0 Organizational Profile approved at day 90.
- **The SOC 2 program.** The Director runs the SOC 2 program and owns the company-wide controls that feed it: access management, HR security, change management, vendor risk, logging, and policy. The current review period is protected so it closes at the end of March 2027 with no new exceptions caused by the Director's changes and no gap before the next period. Evidence moves from hand-collected to a compliance automation platform. Engineering owns the product-specific technical controls in the report.
- **A risk register.** The top IT and security risks with a stated scoring method, a risk appetite statement, named executive owners, treatments, and an exception process, held in [`data/risk-register.csv`](data/risk-register.csv).
- **The policy set.** Fifteen policies (POL-01 to POL-15), refreshed and approved as a set at day 90, including an AI security standard under the Information Security Policy.
- **Third-party and privacy coordination.** Vendor reviews sized to the data a vendor can reach, and privacy questions (including state privacy and employee monitoring laws) routed to General Counsel.
- **Measures and reporting.** Twenty-four KPIs in [`data/kpi-catalog.csv`](data/kpi-catalog.csv), a one-page monthly scorecard, and a quarterly risk review.
- **A real training program.** A once-a-year video is replaced by onboarding, short recurring modules, role-based tracks (finance, support, engineers, administrators, executives), and phishing simulation with one Report button.
- **A framework crosswalk.** Every NIST CSF 2.0 category mapped to the related SOC 2 criteria, the plan documents, and the KPIs, in [`data/csf2-soc2-crosswalk.csv`](data/csf2-soc2-crosswalk.csv), with the author's own analysis where no official mapping exists.

## The key decision

A compliance automation platform for SOC 2 evidence and control monitoring (named by category, not vendor), evaluated by the Director and the outside readiness consultant and approved at day 90 (ADR-007).

## Full detail

Companion repository `it-security-first-year-plan`: document 10 (governance and compliance), document 11 (risk management), document 12 (metrics and executive reporting), document 09 (security awareness and training), the crosswalk, and ADR-007.

## Sources

Drawn from and sourced in the companion repository `it-security-first-year-plan` (documents 09 to 12, the crosswalk, and ADR-007 carry the primary sources: NIST CSF 2.0, the 2017 Trust Services Criteria cited by identifier, the NIST awareness guidance, and the state privacy laws, each with a check date). The KPI, risk, and crosswalk data files here are the same as in that repository, and their document references point to it.
