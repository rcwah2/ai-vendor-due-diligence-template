# Frameworks Referenced

This document lists all standards, frameworks, and guidelines referenced in the AI Vendor Due Diligence Governance Pack, organized by domain.

## AI Governance

| Standard | Publisher | Description | URL |
|---|---|---|---|
| NIST AI RMF 1.0 | NIST | Voluntary framework for managing risks throughout the AI lifecycle. Organized around four functions: Govern, Map, Measure, Manage. | [nist.gov](https://www.nist.gov/itl/ai-risk-management-framework) |
| ISO/IEC 42001:2023 | ISO/IEC | First international standard for AI Management Systems (AIMS). Certifiable. Covers organizational governance of AI across the lifecycle. | [iso.org](https://www.iso.org/standard/81230.html) |
| EU AI Act | European Union | Legally binding regulation classifying AI systems by risk tier (minimal, limited, high, unacceptable). Requires conformity assessment for high-risk systems. | [eur-lex.europa.eu](https://eur-lex.europa.eu/eli/reg/2024/1689/oj) |

### NIST AI RMF to ISO 42001 Crosswalk

NIST publishes an official crosswalk mapping the NIST AI RMF functions to ISO/IEC 42001 clauses:
- GOVERN → ISO 42001 clauses 4, 5, 7 + Annex A.2/A.3
- MAP → clause 4.3 and 6.1.4 + Annex A.4/A.5
- MEASURE → clause 6.1.2 and clause 9 + Annex A.6.2.4/A.6.2.6
- MANAGE → clause 6.1.3, clauses 8 and 10 + Annex A.6.2.5, A.8, A.10

Source: [NIST AIRC Crosswalks](https://airc.nist.gov/airmf-resources/crosswalks/)

## Cybersecurity & Supply Chain

| Standard | Publisher | Description | URL |
|---|---|---|---|
| NIST SP 800-161 Rev. 1 | NIST | Cybersecurity Supply Chain Risk Management (C-SCRM) Practices for Systems and Organizations. Includes supplier assessments and reviews. | [csrc.nist.gov](https://csrc.nist.gov/pubs/sp/800/161/r1/final) |
| NIST SP 1326 | NIST | Cybersecurity Supply Chain Risk Management: Due Diligence Assessment Quick-Start Guide. Five assessment components: foreign ownership/control/influence, provenance, resilience, foundational cyber practices, supply-chain tiers. | [csrc.nist.gov](https://csrc.nist.gov/pubs/sp/1326/final) |
| ISO/IEC 27001 | ISO/IEC | Information security management system (ISMS) standard. Certifiable. | [iso.org](https://www.iso.org/standard/27001) |
| CSA Framework | Cloud Security Alliance | Cloud security controls and best practices. Includes AI-specific guidance. | [cloudsecurityalliance.org](https://cloudsecurityalliance.org/) |

## Data Privacy

| Standard | Publisher | Description | URL |
|---|---|---|---|
| GDPR | European Union | General Data Protection Regulation. Governs processing of personal data of EU residents. | [gdpr.eu](https://gdpr.eu/) |
| CCPA/CPRA | California | California Consumer Privacy Act / California Privacy Rights Act. Governs processing of personal data of California residents. | [oag.ca.gov](https://oag.ca.gov/privacy/ccpa) |
| HIPAA | U.S. HHS | Health Insurance Portability and Accountability Act. Governs protected health information (PHI). | [hhs.gov](https://www.hhs.gov/hipaa/index.html) |

## Incident Response & Forensics

| Standard | Publisher | Description | URL |
|---|---|---|---|
| NIST SP 800-61 Rev. 2 | NIST | Computer Security Incident Handling Guide. Four-phase lifecycle: preparation, detection/analysis, containment/eradication/recovery, post-incident activity. Requires chain of custody records. | [nist.gov](https://nvlpubs.nist.gov/nistpubs/specialpublications/nist.sp.800-61r2.pdf) |
| NIST SP 800-86 | NIST | Guide to Integrating Forensic Techniques into Incident Response. Four-phase forensic process: collection, examination, analysis, reporting. | [csrc.nist.gov](https://csrc.nist.gov/pubs/sp/800/86/final) |
| NIST IR 8387 | NIST | Digital Evidence Preservation: Considerations for Evidence Handlers. Updates definitions to include AI systems and cloud service metadata. | [nist.gov](https://nvlpubs.nist.gov/nistpubs/ir/2022/NIST.IR.8387.pdf) |
| ISO/IEC 27037:2012 | ISO/IEC | Guidelines for identification, collection, acquisition, and preservation of digital evidence. | [iso.org](https://www.iso.org/standard/44407.html) |
| ISO/IEC 27042:2015 | ISO/IEC | Guidelines for the analysis and interpretation of digital evidence. Addresses continuity, validity, reproducibility, repeatability. | [standards.iteh.ai](https://standards.iteh.ai/catalog/standards/iso/10c47499-2a7b-40ae-bf3e-795909b33f27/iso-iec-27042-2015) |
| ISO/IEC 27043:2015 | ISO/IEC | Incident investigation principles and processes. | [iso.org](https://www.iso.org/standard/44407.html) |
| ISO 42001 Annex A.8.4 | ISO/IEC | AI incident communication plan requirements. Requires documented plan defining what constitutes an AI incident, notification timelines, and reporting details. | [watchdogsecurity.io](https://watchdogsecurity.io/iso-42001/communication-of-incidents) |
| CoSAI AI Incident Response Framework V1 | Coalition for Secure AI | AI-specific incident response framework. Includes evidence collection for AI systems: interaction logs, model versions, system configurations, vector database queries, API calls. | [coalitionforsecureai.org](https://www.coalitionforsecureai.org/) |

## Agentic AI

| Standard | Publisher | Description | URL |
|---|---|---|---|
| NIST AI 100-4 | NIST | Reducing Risks of AI in Agentic Systems. Addresses autonomous goal pursuit, tool misuse, multi-agent coordination failures, and cascading failures. | [cltc.berkeley.edu](https://cltc.berkeley.edu/publication/agentic-ai-risk-profile/) |
| NIST AI 100-5 | NIST | Agentic AI guidance. Covers multi-step reasoning failures, unintended goal pursuit, tool-use risks, and challenges in maintaining human control. | [aisecurityandsafety.org](https://aisecurityandsafety.org/en/frameworks/nist-ai-100-5-agentic/) |
| CSA Agentic AI Governance Profile | Cloud Security Alliance | Extends NIST AI RMF with four capabilities: autonomy tier classification, tool-use risk modeling, runtime behavioral metrics, delegation chain monitoring. | [labs.cloudsecurityalliance.org](https://labs.cloudsecurityalliance.org/agentic/agentic-nist-ai-rmf-profile-v1/) |
| OWASP Top 10 for Agentic Applications | OWASP | Security risks specific to agentic AI: goal hijack, tool misuse, privilege abuse, agent access control violations, cascading failures. | [aivss.owasp.org](https://aivss.owasp.org/) |
| NIST CAISI AI Agent Standards Initiative | NIST | Launched February 2026. First U.S. government program dedicated to security and interoperability standards for agentic AI systems. | [labs.cloudsecurityalliance.org](https://labs.cloudsecurityalliance.org/research/csa-research-note-nist-ai-agent-standards-initiative-2026040/) |

## Vendor Financial Viability

| Standard | Publisher | Description | URL |
|---|---|---|---|
| NIST SP 1326 | NIST | Due Diligence Assessment Quick-Start Guide. Includes resilience assessment component covering financial viability. | [csrc.nist.gov](https://csrc.nist.gov/pubs/sp/1326/final) |
| ISO 42001 Annex A.10 | ISO/IEC | Third-party and customer relationships. Requires identification of AI suppliers, allocation of responsibilities, and AI-specific supplier management. | [isms.online](https://www.isms.online/iso-42001/ai-vendor-risk/) |

---

*All framework references are based on publicly available standards as of August 2026. Verify currency before relying on specific clause numbers or requirements.*
