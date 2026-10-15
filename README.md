# Fabrikam, Inc. (fictional): first-year IT and security plan, in brief

> **Reference work.** Fictional scenario built for a public portfolio. Not deployed in, derived from, or describing any employer environment. Not professional advice.

**AI-assisted.** (see [AI assistance](#ai-assistance)).

A short, clickable overview of how an incoming Director of IT and Security would run the first year of internal IT and security at Fabrikam, Inc. (fictional), a workforce software company of about 450 people on Microsoft 365. The role covers the company's own IT and security: employee technology, enterprise systems, the help desk, security, and the SOC 2 program. The product platform Fabrikam sells, and its security, availability, and recovery, are owned by Engineering and are out of scope here. The plan runs in five phases from November 2026 to October 2027, with dated milestones and a one-page monthly scorecard the executive team can hold it to. For the full plan, see [the detailed version](#the-detailed-version).

**The top priorities:** phishing-resistant identity and protecting the company's own staff and finance from business email compromise, detect and contain incidents at any hour, run the SOC 2 program and keep the report without a gap, let the human resources record drive who has access, make corporate data recoverable, and consolidate the systems left by two acquisitions.

## Start here

Read [the year at a glance](01-the-year.md) first. It gives the situation, the five phases, the milestones, the team, and what could be built. Then the seven areas, each a one-page summary of what it is, what gets built, and the key decision:

| # | Area | What it covers |
|---|---|---|
| 1 | [The year at a glance](01-the-year.md) | Situation, phases, milestones, team, first 90 days and day 120 |
| 2 | [Identity and access](02-identity.md) | Phishing-resistant sign-in, least privilege, HR-driven joiners and leavers |
| 3 | [Email authentication and data protection](03-email-and-data.md) | DMARC to enforcement, less oversharing of company data |
| 4 | [Detection and response](04-detection-and-response.md) | Managed detection, incident response, the business email compromise playbook, hunting queries |
| 5 | [Governance, risk, and compliance](05-governance-and-compliance.md) | The SOC 2 program, NIST CSF 2.0, the risk register, KPIs, training |
| 6 | [IT service, devices, and systems](06-it-service-and-systems.md) | Service desk, device standard, change control, acquisition consolidation |
| 7 | [Resilience: backup and continuity](07-resilience.md) | Recovery classes, Microsoft 365 backup, restore testing |
| 8 | [AI security](08-ai-security.md) | AI policy, guardrails, and controls, and safe Copilot adoption |

## What is here

- The eight summaries above.
- Concrete artifacts, the same files as in the detailed version:
  - [`data/kpi-catalog.csv`](data/kpi-catalog.csv), the 24 key performance indicators;
  - [`data/risk-register.csv`](data/risk-register.csv), the top IT and security risks;
  - [`data/csf2-soc2-crosswalk.csv`](data/csf2-soc2-crosswalk.csv), NIST CSF 2.0 mapped to SOC 2 and to the plan;
  - [`queries/`](queries/), eight Microsoft Defender advanced-hunting queries (untested reference templates).

The document references inside the data files point to the detailed version's numbered documents.

## The detailed version

This repository is a shortened overview. The companion repository `it-security-first-year-plan` holds the full plan: 18 numbered documents, 8 architecture decision records, a playbook, templates, and the full Sources sections with primary links and check dates. Everything here is drawn from and sourced there.

## Limitations

- **Fictional and untested.** This is reference work for a fictional company. Nothing has been deployed, and the numbers in the data files are illustrative.
- **Dates and targets are proposals,** to be tuned after discovery.
- **Internal IT and security only.** This plan is the Director's scope: the company's own IT, security, and SOC 2 program. The product platform and its security, availability, and recovery are Engineering's and are described only where the two connect.
- **A summary, not the source.** Where this overview states an external fact (for example a Microsoft date or a framework version), the companion repository holds the citation with its check date. Time-sensitive facts were checked in October 2026 and can change: Microsoft's packaging, preview features, and dates; the monthly MITRE ATLAS release; and the OWASP list.
- **The queries are untested templates,** written against Microsoft's published schemas, with no tenant used.

## License

- **Code: [MIT License](LICENSE).** Covers the Microsoft Defender queries (`.kql`).
- **Documentation and data: [CC BY 4.0](LICENSE-docs).** Covers the Markdown summaries and the CSV data files.

Copyright 2026 Jacob Welch. Both licenses allow reuse and adaptation with credit, and both cover original content only. Third-party names, identifiers, and quoted material stay under their owners' terms, as [NOTICE.md](NOTICE.md) records.

## Author

**Jacob Welch.** 17+ years in IT and systems administration, including regulated healthcare and financial services. Current role: Associate Director of Security and Compliance. [LinkedIn](https://www.linkedin.com/in/jacobwelch21)

The parts of this plan closest to his own experience are Conditional Access and Privileged Identity Management in Microsoft Entra, SOC 2 Type II audits, customer security reviews, email authentication (SPF, DKIM, and DMARC), disaster recovery testing, and security awareness training. Like the rest of the repository, those parts were written for the fictional scenario from public sources and contain no employer information.

The plan deliberately reaches beyond his hands-on experience into areas such as managed detection and response, identity lifecycle automation with Microsoft Entra ID Governance, and NIST CSF 2.0 Organizational Profiles; those parts are design and analysis work.

Certifications:

- Certified Information Security Manager (CISM), ISACA
- Microsoft Certified: Cybersecurity Architect Expert (SC-100)
- Microsoft Certified: Security Operations Analyst Associate (SC-200)
- Microsoft Certified: Identity and Access Administrator Associate (SC-300)
- Microsoft Certified: Azure Security Engineer Associate (AZ-500)
- Microsoft 365 Certified: Administrator Expert
- CompTIA Security+ ce
- ITIL 4 Foundation in IT Service Management
