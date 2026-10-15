# Email authentication and data protection

> **Reference work.** Fictional scenario built for a public portfolio. Not deployed in, derived from, or describing any employer environment. Not professional advice.

**What this is.** How Fabrikam (fictional) stops attackers from spoofing its email and stops sensitive company data from leaking through oversharing in Microsoft 365. A convincing fake "change my bank details" or invoice email is the classic business email compromise attack against any company's own finance team.

## What could be built

- **Email authentication (DMARC), the safe, staged way.** On day 1 the main domain publishes DMARC at p=none and its reports go to a mailbox nobody reads, so it gives neither protection nor visibility. The plan first makes reporting work on every sending domain, then confirms every sender signs with a Fabrikam domain, then moves the policy to quarantine and finally to reject, domain by domain, after the year-end freeze. A parked brand domain gets protective records early. The finish line: every sending domain at reject, with no unknown sender in the monthly report.
- **Email protection before the freeze.** Impersonation protection for executives and payment approvers, an external-sender tag, and automatic external forwarding turned off.
- **Less oversharing.** "Anyone" sharing links are limited and then removed, sensitive files are moved out of mail and personal storage, and sensitivity labels mark the most sensitive content. This also makes it safe to introduce Microsoft Copilot later, because an assistant can only surface what a person can already open.

## The key decision

Enforcement is explained for executives as well as administrators: why p=none with unread reports is common but weak, and why the company needs to reach reject so that no one can spoof its name. The enforcement calendar is approved by the business owner of each sending service, and each service has a named owner who aligns it.

## Full detail

Companion repository `it-security-first-year-plan`: document 06 (Microsoft 365 security baseline), especially the email authentication subsection, and the collaboration and data protection sections.

## Sources

Drawn from and sourced in the companion repository `it-security-first-year-plan`, document 06, which carries the primary sources for DMARC, the mailbox-provider sender rules, and the Microsoft 365 protections, each with a check date.
