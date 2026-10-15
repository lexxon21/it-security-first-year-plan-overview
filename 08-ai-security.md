# AI security

> **Reference work.** Fictional scenario built for a public portfolio. Not deployed in, derived from, or describing any employer environment. Not professional advice.

**What this is.** How Fabrikam (fictional) adopts AI safely: the policy that governs it, the guardrails for what people may do, and the controls that enforce and detect. On day 1 employees already use public AI tools without guidance, leadership wants Microsoft Copilot, and product teams are building AI features, so the plan offers a safe path before closing the unsafe ones. It draws only on public sources.

## Three layers

- **Policy: what governs AI.** An AI section in the Acceptable Use Policy for people, and a new AI security standard under the Information Security Policy for AI systems, connections, and product AI features. No new policy number is added; the standard is approved with the policy set at day 90.
- **Guardrails: what people and teams may do.** An approved tool (work-account Copilot Chat) offered early; data rules tied to the classification set, so customer and employee personal data never goes into an unapproved tool; a named person accountable for any AI output that reaches a customer, and no AI-only decisions about people; an intake review before any AI tool connects to Fabrikam data; a review before any product AI feature launches; and AI agents (software that acts, not just answers) held to intake approval and treated as non-human identities, with a fuller agent standard left to year two.
- **Controls: what enforces and detects.** A controls register (AIC-01 to AIC-12), each control with an owner, the license it needs, the phase it lands in, and its framework references.

## What the controls cover

Unapproved AI use; data leaking through prompts or uploads; Copilot surfacing overshared files (fixed by the oversharing work before any pilot); over-permissioned AI apps and consent phishing; prompt injection hidden in email, files, or web content an assistant reads; AI-enabled fraud such as cloned voices asking for a bank change (answered by the same call-back rule that governs payroll changes); AI vendor and model supply-chain risk; confident but false AI output reaching customers; AI in decisions about people; product AI features (tested before launch, with a kill switch and incident routing); and AI incidents, handled under the existing incident process.

## Copilot, done in order

Microsoft Copilot grounds answers in the data a user can already open, so readiness starts with permissions, not licenses: fix oversharing first, then a readiness gate, then a short pilot on cleaned-up sites, then a measured expansion decided on evidence.

## The key decision

AI is treated as an opportunity to capture safely, built on public guidance (the NIST AI Risk Management Framework and generative AI profile, the OWASP Top 10 for Large Language Model Applications, MITRE ATLAS, joint government AI guidance, and Microsoft's published Copilot guidance). AI agents stay at policy level in year one.

## Full detail

Companion repository `it-security-first-year-plan`: document 16 (AI security and adoption guardrails), which holds the AI security overview, the full controls register, the AI security standard, and the product AI feature review.

## Sources

Drawn from and sourced in the companion repository `it-security-first-year-plan`, document 16, which carries the primary sources, each with a check date: the NIST AI RMF 1.0 and NIST AI 600-1, the OWASP Top 10 for Large Language Model Applications 2026, MITRE ATLAS content release 2026.09, the joint government AI data-security guidance, and Microsoft's published guidance on Copilot data protection, prompt-injection defense, and data loss prevention.
