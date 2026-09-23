# AI Vendor Due Diligence Template

**A three-part governance pack for assessing, contracting, and operating third-party AI systems.**

Most AI risk an organization carries today arrives through vendors. The organization remains accountable for outcomes it does not directly control: how a model was trained, how it is secured, how incidents are handled, and what an autonomous agent is permitted to do. This template gives procurement, risk, security, and legal teams a consistent way to assess those risks before contract signature and to carry the resulting requirements into the Statement of Work and the contract itself.

## What's Included

| Part | File | Purpose | When to Use |
|---|---|---|---|
| 1 | [Due Diligence Questionnaire](01-due-diligence-questionnaire.md) | Pre-contract assessment across seven risk domains, with response, evidence, and risk-rating fields | During vendor selection and procurement |
| 2 | [SOW / Operational Requirements Exhibit](02-sow-operational-requirements.md) | Defines how the vendor must operate during the engagement | When drafting the Statement of Work or operational exhibit |
| 3 | [Contract Clause Checklist](03-contract-clause-checklist.md) | Contractual obligations to negotiate, with a clause priority matrix | During contract negotiation with legal counsel |
| — | [Frameworks Referenced](frameworks-referenced.md) | Standards and regulations behind each section, with links | As a reference throughout |

The three parts are designed to work in sequence. What the questionnaire surfaces as a risk becomes an operational requirement in the SOW and an enforceable obligation in the contract.

## Assessment Domains

The questionnaire covers seven domains:

1. **AI Governance & Risk** — intended use, training data provenance, risk classification, human oversight, bias and fairness, explainability, and impact assessment
2. **Cybersecurity & Security** — supply chain risk and security control alignment
3. **Data Privacy & Compliance** — personal data handling, residency, and regulatory obligations
4. **Vendor Operational Risk** — service delivery, dependencies, and continuity
5. **Vendor Financial Viability** — stability, resilience, and exposure if the vendor fails
6. **Incident Response & Forensics** — incident process, evidence preservation and chain of custody, AI-specific evidence, a client-vendor RACI matrix, and ISO 42001 incident communication
7. **Agentic AI Controls** — autonomy classification, tool and API access, identity and credentials, kill switch and containment, behavioral monitoring and drift detection, multi-agent risk, security testing, and logging

## How to Use

1. **Scope the assessment.** Decide which sections apply based on the AI system type and risk classification. Section 7 applies only to systems with autonomous or agentic capabilities.
2. **Send Part 1 to the vendor.** Score responses against your organization's risk tolerance. Treat "unable to provide" and "not applicable" responses as follow-up items, not passes.
3. **Translate findings into Part 2.** Carry material risks into specific operational requirements, service levels, and escalation procedures in the SOW.
4. **Negotiate with Part 3.** Use the clause checklist and priority matrix to decide what is non-negotiable, what is required, and what can be phased.
5. **Revisit after deployment.** Reassess at renewal, after material model changes, and after significant incidents.

## Framework Alignment

| Area | Frameworks |
|---|---|
| AI governance | NIST AI RMF 1.0, ISO/IEC 42001:2023, EU AI Act |
| Cybersecurity & supply chain | NIST SP 800-161r1, NIST SP 1326, ISO/IEC 27001, CSA |
| Data privacy | GDPR, CCPA/CPRA, HIPAA |
| Incident response & forensics | NIST SP 800-61r3, NIST SP 800-86, NIST IR 8387, ISO/IEC 27037, 27042, 27043, ISO 42001 Annex A.8.4, CoSAI AI Incident Response Framework |
| Agentic AI | CSA Agentic AI Governance Profile, OWASP Top 10 for Agentic Applications, NIST CAISI AI Agent Standards Initiative |
| Third-party relationships | ISO 42001 Annex A.10, NIST SP 1326 |

See [frameworks-referenced.md](frameworks-referenced.md) for descriptions and links.

## Important Note

This template is a governance framework, not legal advice. Contract clauses must be reviewed and finalized by qualified legal counsel before inclusion in any agreement. Adapt the questions, thresholds, and priorities to your organization's industry, risk profile, and regulatory obligations.

## Related Repositories

- [AI Implementation Reference Model](https://github.com/rcwah2/ai-implementation-reference-model) — the phased model showing where vendor due diligence fits in the path from pilot to production
- [AI System Inventory Template](https://github.com/rcwah2/ai-system-inventory-template) — documents each AI system, including vendor and agentic AI fields that align with this template
- [AI Governance Crosswalk](https://github.com/rcwah2/ai-governance-crosswalk) — shared artifacts and evidence mapping across NIST AI RMF and ISO 42001
- [AI Governance Portfolio](https://github.com/rcwah2/ai-governance-portfolio) — applied governance case studies

## Author

Raymond Wah — Enterprise AI Governance & Implementation Program Leader, Lissome Technology Consulting

- LinkedIn: [linkedin.com/in/raymondwah](https://www.linkedin.com/in/raymondwah/)
- Substack: [rwahai.substack.com](https://rwahai.substack.com/)
- GitHub: [github.com/rcwah2](https://github.com/rcwah2)

## License

Copyright (c) 2026 Lissome Technology Consulting.

This work is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may share and adapt it, including for commercial purposes, provided you give appropriate credit to Lissome Technology Consulting, link to the license, and indicate if changes were made. See [LICENSE](LICENSE) for the full terms.
