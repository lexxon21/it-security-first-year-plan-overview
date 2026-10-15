# The year at a glance

> **Reference work.** Fictional scenario built for a public portfolio. Not deployed in, derived from, or describing any employer environment. Not professional advice.

**What this is.** How an incoming Director of IT and Security would run the first year of internal IT and security at Fabrikam, Inc. (fictional), a workforce software company of about 450 people on Microsoft 365. The role covers the company's own IT and security: employee technology, enterprise systems, the help desk, security, and the SOC 2 program. The product platform Fabrikam sells, and its security, availability, and recovery, are owned by Engineering and are out of scope here. The year runs from day 1 (Monday, 2026-11-02) to the first annual review in October 2027. Every date and target is a proposal, tuned after discovery.

## The situation on day 1

Corporate IT runs Microsoft 365 E3, lightly configured: sign-in mostly by push or text code, standing administrator rights, joiners and leavers handled by email, no after-hours alerting, no backup beyond retention, and no dedicated security hire. Two earlier acquisitions left duplicate systems, identities, and SaaS to consolidate. Fabrikam holds a SOC 2 Type II report that its customers rely on, and the current review period closes at the end of March 2027.

Three dates set the pace: Microsoft retires its own text and voice sign-in codes for most users on 2027-02-01; Fabrikam freezes risky changes from mid-December through January, when staffing is light over the holidays; and the SOC 2 review period closes at the end of March 2027.

## The five phases

| Phase | Name | When | The idea |
|---|---|---|---|
| 1 | Listen and learn | Days 1 to 30 (November 2026) | Map the environment, fix only the urgent, protect the audit in progress |
| 2 | Stabilize | Days 31 to 60 (December 2026) | Quick wins before the mid-December freeze; a first risk register |
| 3 | Commit | Days 61 to 90 (January 2027) | The executive team approves the 12-month plan, budget, and policies |
| 4 | Build | Months 4 to 6 (February to April 2027) | Stand up the controls the budget funds |
| 5 | Scale and sustain | Months 7 to 12 (May to October 2027) | Widen coverage, run the program, review the year |

## Milestones

| Milestone | When | What it marks |
|---|---|---|
| M1 | Day 30 | Listening report, inventories, baseline measures, draft top risks |
| M2 | Day 60 | Stabilization quick wins done; risk register with executive owners; SOC 2 on track |
| M3 | Day 90 (the executive team meets Thursday 2027-01-28) | Plan, budget, policies, risk appetite, and NIST CSF 2.0 Profiles approved |
| D120 | Friday 2027-02-26 | First results readout: what has measurably changed, and what is at risk |
| M4 | End of March 2027 | SOC 2 period closes with no new exceptions caused by the Director's changes; the next period continues without a gap |
| M5 | July 2027 | Acquisition systems consolidated: one identity per person, duplicate tools retired |
| M6 | July 2027 | Identity lifecycle automated; phishing-resistant sign-in for all admins and most users |
| M7 | October 2027 | First annual review: results against targets, re-baselined risks, next-year plan |

## The first 90 days and day 120

- **Day 30 (M1):** a listening report, inventories, baseline measures, and draft top risks. Phase 1 changes little beyond emergency access accounts, multifactor authentication on every administrator, after-hours alerting, and one restore check.
- **Day 60 (M2):** quick wins before the freeze, a risk register with named executive owners, and the SOC 2 period on track.
- **Day 90 (M3):** the executive team approves the 12-month plan, budget, policy set, risk appetite, and the NIST Cybersecurity Framework 2.0 Profiles, and no one relies only on text or voice codes.
- **Day 120 (D120):** first results measured against the day-30 baselines.

## The team

| Role | Day 1 | By month 12 |
|---|---|---|
| Director of IT and Security | Starts, reporting to the CTO | In post; plan, budget, execution, incident command |
| IT Operations Manager and three IT generalists | In post | In post; service desk, devices, identity, change, backups |
| Security Engineer | None | Hired from March 2027; detections, MDR liaison, simulations |
| GRC Analyst | A finance manager coordinates SOC 2 part time | Hired from March 2027; the SOC 2 program, risk register, vendor reviews, KPIs |

Until the two new roles start, the Director and the Systems Engineer (one of the three IT generalists) carry the build, with Microsoft FastTrack and contracted help from February. Partners: a managed detection and response provider, the SOC 2 audit firm, a penetration testing firm, and an IT hardware partner.

## How progress is shown

Twenty-four proposed measures (key performance indicators), baselined at day 30 and given targets at day 90, a one-page monthly scorecard from December, and a quarterly risk review. No single composite score.

## What could be built this year

- Phishing-resistant sign-in for every administrator by December 2026 and most employees by July 2027.
- Protection for the company's own staff and finance from phishing, business email compromise, and account takeover.
- Email authentication enforced on every sending domain.
- A managed detection and response service watching the corporate environment around the clock from the end of April 2027.
- The human resources record driving who gets access, so new hires work on day one and leavers lose access on time.
- Tested backups and recovery for corporate Microsoft 365 data.
- A clean SOC 2 close, with named control owners and continuous evidence in place of hand collection.
- The systems left by the two acquisitions consolidated: one identity per person, duplicate tools retired.
- An AI security standard and guardrails so staff use AI on approved tools.

## Full detail

The companion repository `it-security-first-year-plan` holds the full plan: the executive summary, the first 90 days, the twelve-month roadmap, and the operating model, team, and budget.

## Sources

Every fact here is drawn from and sourced in the companion repository `it-security-first-year-plan` (each document carries a Sources section with primary links and check dates). The two dated Microsoft facts repeated above:

- Passkeys by default and retirement of Microsoft-provided SMS and voice authentication. Microsoft Learn. https://learn.microsoft.com/en-us/entra/identity/authentication/concept-sms-voice-retirement . Checked 2026-10-13. Primary.
- Microsoft 365 Pricing and Packaging Updates (the July 2026 additions to Microsoft 365 E3). Microsoft. https://www.microsoft.com/en-us/licensing/news/2026-m365-packaging-pricing-updates . Checked 2026-10-13. Primary.
