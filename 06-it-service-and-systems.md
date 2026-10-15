# IT service, devices, and systems

> **Reference work.** Fictional scenario built for a public portfolio. Not deployed in, derived from, or describing any employer environment. Not professional advice.

**What this is.** How IT runs as a service for about 450 remote-first employees, how devices are managed, and how the applications and systems left by two acquisitions are consolidated. On day 1 there are duplicate tools, no application inventory, inconsistent device management, and two still-separate acquisition estates.

## What could be built

- **A service desk that works.** Priorities and service levels, a request catalog, a self-service portal, Teams and email routed into tickets, and a satisfaction survey, measured by KPI-20 to KPI-24.
- **Help desk identity verification.** No password or multifactor reset on the caller's word: a call-back to the number on file, or a live video check with the manager, with a recently changed number never counting. This is one of the controls open to no exception.
- **A device standard.** Windows and Mac enrolled and compliant, disk encryption, local administrator rights removed with a just-in-time elevation path, update rings, and any remaining Windows 10 devices bridged or replaced before April 2027.
- **Change and problem management.** A weekly change board from week 2, flagging any change that touches a SOC 2 control, and monthly problem reviews.
- **Environment discovery (Phase 1).** A read-only mapping of people, processes, technology, data, and vendors that produces the facts the rest of the plan depends on, without disturbing the SOC 2 period.
- **Acquisition consolidation.** One identity per person, duplicate tools retired at their contract notice dates, file stores cleaned and consolidated, and sensitive applications moved behind single sign-on.
- **Value from licenses already owned.** Switch on what Microsoft 365 E3 already includes (including the July 2026 additions) before buying more.

## The key decisions

- One endpoint management standard for Windows and macOS (ADR-008).
- How to license the security capabilities for about 450 users: configure what E3 already includes, then add Microsoft Defender Suite and Microsoft Entra ID Governance, rather than jumping to a top-tier bundle (ADR-001).
- How to consolidate the acquired companies' identities, devices, files, and applications (ADR-005).

## Full detail

Companion repository `it-security-first-year-plan`: document 13 (IT service management), document 05 (environment discovery), document 15 (enterprise systems and SaaS), ADR-001, ADR-005, and ADR-008.

## Sources

Drawn from and sourced in the companion repository `it-security-first-year-plan` (documents 05, 13, and 15 and ADRs 001, 005, and 008 carry the primary Microsoft sources for licensing, Intune, Windows, and migration, each with a check date).
