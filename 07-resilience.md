# Resilience: backup and continuity

> **Reference work.** Fictional scenario built for a public portfolio. Not deployed in, derived from, or describing any employer environment. Not professional advice.

**What this is.** How Fabrikam (fictional) keeps its corporate IT working through an outage and gets its data back after a loss. On day 1 Microsoft 365 data has no backup beyond retention settings and the continuity plan is out of date. (Disaster recovery for the product platform is owned by Engineering and is out of scope here.)

## What could be built

- **A business impact analysis and recovery classes.** Corporate systems and data sorted into three recovery classes with proposed recovery-time and recovery-point objectives, confirmed by the owning executives, so the backup design follows the agreed numbers rather than the other way round.
- **Microsoft 365 backup.** Backup for mail, files, and sites, with the most critical (class A) data protected before mid-December and a first restore test run before year-end.
- **Copies that survive ransomware.** An isolated copy of the most critical data, if funded.
- **A restore testing program.** Scheduled restore tests measured by KPI-19, a continuity drill, and a mass restore exercise, so recovery is proven rather than assumed.
- **Corporate continuity.** An up-to-date plan for the company's own operations during an outage, with out-of-band communication and named coverage over the year-end season.

## The key decision

Backup for Microsoft 365 data, including whether to fund an isolated, ransomware-resistant copy of the most critical data (ADR-006). If it is not funded, the CEO accepts the residual risk for a set period.

## Full detail

Companion repository `it-security-first-year-plan`: document 14 (business continuity and backup) and ADR-006.

## Sources

Drawn from and sourced in the companion repository `it-security-first-year-plan`, document 14 and ADR-006, which carry the primary Microsoft 365 Backup sources and the recovery-objective reasoning, each with a check date.
