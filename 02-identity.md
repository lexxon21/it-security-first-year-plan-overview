# Identity and access

> **Reference work.** Fictional scenario built for a public portfolio. Not deployed in, derived from, or describing any employer environment. Not professional advice.

**What this is.** How Fabrikam (fictional) gives, changes, and removes access, and how people prove who they are at sign-in. On day 1 this is a weak area: sign-in by push or text code, standing administrator rights, and joiners and leavers run by email.

## What could be built

- **Phishing-resistant sign-in.** Passkeys and security keys replace text and voice codes, which Microsoft retires for most users on 2027-02-01. Every administrator is covered by December 2026; most employees by July 2027. A phished password or code no longer opens an account.
- **Least standing privilege.** Administrator roles move to just-in-time activation with approval, so almost no one holds a standing privileged role. Emergency access accounts are set up and monitored.
- **One identity, driven by HR.** Fabrikam's own human resources product becomes the system of record: it creates, changes, and removes accounts through automated joiner, mover, and leaver workflows, with access packages by role. New hires are productive on day one, and a departure removes access on time.
- **Identity proofing before the first credential.** A new hire's identity is checked on a video call against a government-issued photo ID before any credential is issued, to counter fraudulent remote hires.
- **Access reviews and contractor control.** Periodic reviews of who can reach what, and every contractor and guest with a sponsor and an end date.

## The key decisions

- The HR record drives the identity lifecycle, rather than IT creating accounts by hand (ADR-002).
- Phishing-resistant methods, and the order they roll out in, are chosen deliberately around the 2027-02-01 retirement date (ADR-004).

## Full detail

Companion repository `it-security-first-year-plan`: document 06 (Microsoft 365 security baseline, the identity and access sections), document 07 (identity lifecycle), ADR-002, and ADR-004.

## Sources

Drawn from and sourced in the companion repository `it-security-first-year-plan` (documents 06 and 07 and ADRs 002 and 004 each carry a Sources section). The dated Microsoft fact repeated here:

- Passkeys by default and retirement of Microsoft-provided SMS and voice authentication. Microsoft Learn. https://learn.microsoft.com/en-us/entra/identity/authentication/concept-sms-voice-retirement . Checked 2026-10-13. Primary.
