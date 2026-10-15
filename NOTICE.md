# Notices and attribution

> **Reference work.** Fictional scenario built for a public portfolio. Not deployed in, derived from, or describing any employer environment. Not professional advice.

This file lists the third-party frameworks, identifier sets, names, and quoted material used in this repository, and the terms each comes with. Each source's terms were checked at the source on 2026-10-14 (table at the end). This repository is a shortened overview of the companion repository `it-security-first-year-plan`, which carries the same data files and queries and the full Sources sections.

The repository's own licenses cover original content only: the [MIT License](LICENSE) for the KQL queries, and [CC BY 4.0](LICENSE-docs) for the summaries and data. Third-party material stays under its owner's terms. Naming an organization, product, or framework here does not imply affiliation with, sponsorship by, or endorsement by its owner.

## MITRE ATT&CK

- **Used:** technique and tactic IDs and names from MITRE ATT&CK Enterprise v20, in the headers of seven of the eight queries (q07 cites none; q01 and q06 map none and name T1078.004 only as the exposure they size) and named as the version the threat mapping uses in the detection and response summary. No technique descriptions are quoted.
- **Terms:** MITRE's Terms of Use license ATT&CK for research, development, and commercial use, on condition that copies reproduce MITRE's copyright designation and the license. Both follow, as published on MITRE's Terms of Use page:

  The MITRE Corporation (MITRE) hereby grants you a non-exclusive, royalty-free license to use ATT&CK® for research, development, and commercial purposes. Any copy you make for such purposes is authorized provided that you reproduce MITRE's copyright designation and this license in any such copy.

  "© 2026 The MITRE Corporation. This work is reproduced and distributed with the permission of The MITRE Corporation."

- **Trademarks:** MITRE ATT&CK and ATT&CK are registered trademarks of The MITRE Corporation.

## MITRE ATLAS

- **Used:** MITRE ATLAS is named by content release only. The AI security summary names MITRE ATLAS content release 2026.09 (released 2026-09-15) as one of the public sources behind the AI controls. No ATLAS identifier, technique description, data file, or other ATLAS content is reproduced. ATLAS publishes content releases monthly; 2026.09 was the newest release in the ATLAS data manifest on 2026-10-14.
- **Terms:** the LICENSE file in The MITRE Corporation's atlas-data repository names MITRE as the copyright holder for 2021 to 2026 and licenses the repository under the Apache License, Version 2.0. The release statement in its README instead carries a copyright line followed by "ALL RIGHTS RESERVED." This repository records both, names only the content release, and reproduces no ATLAS content.
- **Trademarks:** MITRE ATLAS™ is a trademark of The MITRE Corporation.

## OWASP Top 10 for LLM Applications

- **Used:** the OWASP Top 10 for Large Language Model Applications 2026 (released August 2026) is named in the AI security summary as the basis for testing product AI features before launch. No identifier or entry text is reproduced.
- **Terms:** the 2026 edition's License and Usage page states that it is licensed under Creative Commons CC BY-SA 4.0, and the OWASP GenAI Security Project website states that its content is CC BY-SA 4.0 unless otherwise specified, provided without warranty.
- **Attribution:** "OWASP Top 10 for LLM Applications 2026" by the OWASP GenAI Security Project, https://genai.owasp.org/resource/owasp-genai-llm-top-10-2026/ , licensed under CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0/). This repository's CC BY 4.0 license does not cover it.

## NIST publications

- **Used:** NIST Cybersecurity Framework (CSF) 2.0 Function, Category, and Subcategory identifiers in the summaries and in the crosswalk (`data/csf2-soc2-crosswalk.csv`), with Category descriptions paraphrased in the crosswalk; and the names of NIST publications the summaries reference, including SP 800-61 (incident handling), SP 800-50 (security awareness), the AI Risk Management Framework (AI RMF 1.0, NIST AI 100-1), and NIST AI 600-1. No NIST text is reproduced verbatim.
- **Terms:** NIST states that works authored by NIST employees are not subject to copyright protection within the United States, that foreign rights are reserved, and that to the extent NIST may assert rights outside the United States, the public is granted a royalty-free, worldwide right to reprint them. NIST asks reprints to carry its recommended citation.
- **Credit:** the CSF 2.0 identifiers and the Category descriptions paraphrased in the crosswalk come from National Institute of Standards and Technology (2024), The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, National Institute of Standards and Technology, https://doi.org/10.6028/NIST.CSWP.29 (accessed 2026-10-13).

## AICPA Trust Services Criteria

- **Used:** identifiers from the 2017 Trust Services Criteria (with the 2022 revised points of focus), such as CC1.1 to CC9.2, A1.1 to A1.3, and C1.1 to C1.2, in the crosswalk (`data/csf2-soc2-crosswalk.csv`), each with an original paraphrase. No criteria text or point of focus is reproduced.
- **Terms:** AICPA & CIMA's Terms and Conditions state that the website's content is protected by copyright and may not be reproduced, modified, or used to create derivative works without written permission. The criteria appear here only by identifier, with paraphrases written for this plan.

## US government works

- **Used:** publications of NIST (above), and the joint government AI security guidance named in the AI security summary, issued by CISA, the NSA, or the FBI with partner agencies, including AI Data Security (May 2025) and Deploying AI Systems Securely (April 2024).
- **Terms:** under 17 U.S.C. 105, "Copyright protection under this title is not available for any work of the United States Government." Publications issued jointly with non-federal partners are not treated here as U.S. government works; they are named and paraphrased only. No seal or logo of any agency is used.

## State laws

The governance and AI security summaries refer in general terms to state biometric and employee monitoring laws. No statute text is reproduced; the companion repository `it-security-first-year-plan` cites the specific sections, which are read as questions for counsel, not as legal advice.

## Microsoft

- **Products:** the plan uses Microsoft products as Fabrikam's platform. Microsoft and the names of the Microsoft products and services referred to in this repository are trademarks of the Microsoft group of companies. Microsoft's trademark guidelines ask third parties to refer to its products truthfully and not to imply affiliation or endorsement; this repository implies neither.
- **Cited material:** the query headers and the summaries cite Microsoft Learn and other Microsoft pages for product facts, licensing, and dates. That content is Microsoft's and is not covered by this repository's licenses. Microsoft Learn's Terms of Use (updated 2025-05-12) note that certain documentation may carry explicit license terms, which control; Microsoft publishes the source of many Learn pages in public MicrosoftDocs repositories under their own licenses.
- **Fabrikam:** Fabrikam is one of the fictional company names used in Microsoft's documentation and learning material; an archived Microsoft TechNet Wiki page lists it as "Fabrikam, Inc.". Fabrikam, Inc. (fictional) is a fictional organization used for this plan. It is not affiliated with Microsoft and does not describe any real organization.

## Other sources and names

- Every summary points to the companion repository `it-security-first-year-plan`, where each document lists its sources with publisher, URL, date checked, and a quality label.
- All other product names, company names, and marks belong to their respective owners and are used only to identify them.
- This repository is not affiliated with, sponsored by, or endorsed by any organization it names, and Fabrikam, Inc. (fictional) does not describe any real organization.

## Terms checked for this notice

| Title | Publisher | URL | Date checked | Quality |
|---|---|---|---|---|
| Terms of Use (ATT&CK license, copyright designation, and trademark notice) | MITRE | https://attack.mitre.org/resources/legal-and-branding/terms-of-use/ | 2026-10-14 | Primary |
| atlas-data LICENSE (Apache License, Version 2.0, and copyright line) | The MITRE Corporation, on GitHub | https://raw.githubusercontent.com/mitre-atlas/atlas-data/main/LICENSE | 2026-10-14 | Primary |
| atlas-data README (release statement with "ALL RIGHTS RESERVED"; monthly content releases) | The MITRE Corporation, on GitHub | https://raw.githubusercontent.com/mitre-atlas/atlas-data/main/README.md | 2026-10-14 | Primary |
| ATLAS data manifest (content release 2026.09, release date 2026-09-15) | The MITRE Corporation, on GitHub | https://raw.githubusercontent.com/mitre-atlas/atlas-data/main/dist/manifest.yaml | 2026-10-14 | Primary |
| D3FEND Terms of Use (MITRE ATLAS trademark statement) | The MITRE Corporation | https://next.d3fend.mitre.org/tou | 2026-10-14 | Primary |
| OWASP GenAI LLM Top 10 2026 (resource page and site footer license notice) | OWASP GenAI Security Project | https://genai.owasp.org/resource/owasp-genai-llm-top-10-2026/ | 2026-10-14 | Primary |
| Attribution-ShareAlike 4.0 International legal code | Creative Commons | https://creativecommons.org/licenses/by-sa/4.0/legalcode.en | 2026-10-14 | Primary |
| Copyright, Fair Use, and Licensing Statements for SRD, Data, Software, and Technical Series Publications (updated June 24, 2025) | NIST | https://www.nist.gov/open/copyright-fair-use-and-licensing-statements-srd-data-software-and-technical-series-publications | 2026-10-14 | Primary |
| Copyright Law of the United States, Chapter 1, section 105 (United States Government works) | U.S. Copyright Office | https://www.copyright.gov/title17/92chap1.html | 2026-10-14 | Primary |
| Terms & Conditions (Version 4), section 2 | AICPA & CIMA | https://www.aicpa-cima.com/help/terms-and-conditions | 2026-10-14 | Primary |
| Trademark and Brand Guidelines | Microsoft | https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks | 2026-10-14 | Primary |
| Terms of Use, Microsoft Learn (updated 2025-05-12) | Microsoft | https://learn.microsoft.com/en-us/legal/termsofuse | 2026-10-14 | Primary |
| List of fictional companies used in Microsoft material (archived community wiki page) | Microsoft Learn archive | https://learn.microsoft.com/en-us/archive/technet-wiki/1117.list-of-fictional-companies-used-in-microsoft-material | 2026-10-14 | Secondary |
| Attribution 4.0 International legal code (the text in LICENSE-docs) | Creative Commons | https://creativecommons.org/licenses/by/4.0/legalcode.txt | 2026-10-14 | Primary |
| MIT License template (the text in LICENSE) | GitHub, choosealicense.com | https://github.com/github/choosealicense.com/blob/gh-pages/_licenses/mit.txt | 2026-10-14 | Primary |
