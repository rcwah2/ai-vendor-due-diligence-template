# Part 3: Contract Clause Checklist

**Purpose:** Topics for legal counsel to convert into binding contract terms. Answers: "What are the vendor's legal obligations, and what happens if they fail?"

**How to use:** This is a clause checklist, not drafted legal language. Review with legal counsel to convert these topics into binding terms within the Master Services Agreement (MSA), Data Processing Agreement (DPA), or AI-specific addendum.

**Important:** A governance practitioner identifies what needs to be in the contract. Legal counsel drafts the binding terms. Do not use this checklist as a substitute for qualified legal review.

---

## 1. AI Governance Obligations

- [ ] AI system documentation requirements (model cards, datasheets, impact assessments)
- [ ] Risk classification and ongoing re-assessment obligations
- [ ] Human oversight requirements (who, when, escalation thresholds)
- [ ] Bias testing and fairness audit obligations
- [ ] Transparency and explainability documentation
- [ ] Compliance with applicable AI regulations (EU AI Act, sector-specific requirements)
- [ ] ISO/IEC 42001 alignment or certification maintenance

## 2. Security Obligations

- [ ] Security addendum referencing SOC 2, ISO 27001, CSA framework controls
- [ ] Encryption requirements (at rest, in transit, in use)
- [ ] Key management and rotation obligations
- [ ] Vulnerability management and remediation timelines
- [ ] Access control requirements (least privilege, role-based)
- [ ] Security monitoring and incident detection obligations
- [ ] Sub-processor security requirements and flow-down obligations

## 3. Data Protection Obligations

- [ ] Data Processing Agreement (DPA) per GDPR/CCPA/HIPAA as applicable
- [ ] Data residency and cross-border transfer restrictions
- [ ] Data retention and deletion obligations (including post-termination)
- [ ] Sub-processor disclosure and change notification
- [ ] Data subject rights handling procedures
- [ ] Data return and destruction at engagement end
- [ ] Data breach notification obligations (timeline, content, recipients)

## 4. Vendor Financial and Operational Obligations

- [ ] Financial stability reporting requirements (annual or upon material change)
- [ ] Insurance requirements (cyber liability, E&O, general liability — minimum coverage amounts)
- [ ] Business continuity and disaster recovery obligations
- [ ] Transition assistance obligations (upon termination)
- [ ] Source code or data escrow requirements
- [ ] Sub-contractor approval and notification requirements
- [ ] Exit and data return procedures

## 5. Incident Response Obligations

### 5.1 Notification and Cooperation

- [ ] Incident notification timeline (e.g., within 24-72 hours of detection)
- [ ] Required notification content (nature, scope, affected data, remedial actions)
- [ ] Cooperation with client's incident investigation
- [ ] Evidence preservation obligations (non-spoliation, legal hold cooperation)
- [ ] Audit and investigation rights (access to logs, records, systems)
- [ ] Regulatory notification support (if client is required to notify regulators)

### 5.2 Forensic Evidence

- [ ] Retention and chain of custody requirements for AI-specific evidence
- [ ] Availability of evidence for investigation, regulatory inquiry, dispute, or audit
- [ ] Log retention period (minimum)
- [ ] Confidentiality of forensic evidence
- [ ] Cooperation with third-party forensic investigators (access conditions)

## 6. Agentic AI Obligations

### 6.1 Agent Authority and Revocation

- [ ] Agent revocation rights and procedures (who can revoke, how, timeline)
- [ ] Kill switch authority (client's right to invoke)
- [ ] Credential revocation obligations upon agent decommissioning
- [ ] Evidence preservation during agent decommissioning

### 6.2 Agent Audit and Liability

- [ ] Audit rights specific to agent behavior and access
- [ ] Logging and audit trail requirements (immutable, exportable)
- [ ] Liability for autonomous actions taken by the agent
- [ ] Indemnification for agent-caused harm or unauthorized actions
- [ ] Red teaming and security testing obligations (cadence, results sharing)

### 6.3 Multi-Agent and Third-Party

- [ ] Disclosure of multi-agent system architecture
- [ ] Liability for cascading failures across multi-agent systems
- [ ] Flow-down of AI governance obligations to sub-processors providing agent capabilities
- [ ] Transition assistance for replacing or upgrading agents

## 7. General Contractual Terms

- [ ] Audit rights (frequency, scope, cost allocation)
- [ ] Breach and cure obligations (cure period, remedies)
- [ ] Termination rights (for cause, for convenience, transition period)
- [ ] Data rights and IP ownership (training data, model outputs, derivatives)
- [ ] Survival obligations (which obligations survive termination)
- [ ] Limitation of liability (carve-outs for data breach, IP infringement, gross negligence)
- [ ] Indemnification (IP infringement, data breach, third-party claims)
- [ ] Force majeure (exclusions for cyber incidents, AI system failures)
- [ ] Compliance with laws (ongoing obligation, change-in-law provisions)
- [ ] Subcontracting restrictions and approval requirements

---

## Clause Priority Matrix

| Priority | Clause Category | Rationale |
|---|---|---|
| Critical | Incident notification, data breach, evidence preservation, audit rights | Non-negotiable for regulated industries |
| Critical | Agent revocation, kill switch, logging requirements | Non-negotiable for agentic AI systems |
| High | Data protection, DPA, data residency | Required for GDPR/HIPAA compliance |
| High | Financial stability, insurance, transition assistance | Required for critical vendor relationships |
| Medium | Security addendum, sub-processor flow-down | Standard for AI vendor agreements |
| Medium | Red teaming, behavioral monitoring | Important but can be phased |
| Standard | General MSA terms | Standard contract provisions |

---

*This checklist is a governance framework, not legal advice. All clauses must be reviewed and finalized by qualified legal counsel before inclusion in any contract.*
