# Part 2: SOW / Operational Requirements Exhibit

**Purpose:** Defines how the vendor must operate during the engagement. Answers: "How will this vendor meet our requirements for this specific engagement?"

**How to use:** Incorporate these requirements into the Statement of Work or operational exhibit attached to the vendor agreement. Customize based on the AI system type, risk classification, and engagement scope.

---

## 1. AI Governance Operations

- Define AI system registration and inventory requirements (owner, model type, data sources, risk tier)
- Specify model documentation deliverables (model cards, datasheets, impact assessments)
- Define risk classification methodology and documentation
- Specify human oversight requirements and escalation thresholds
- Define bias testing cadence and reporting format
- Specify transparency and explainability documentation requirements

## 2. Security Controls

- Define required security controls based on SOC 2 / ISO 27001 / CSA framework alignment
- Specify encryption requirements (at rest, in transit, in use)
- Define key management and rotation procedures
- Specify vulnerability scanning and remediation timelines
- Define access control requirements (least privilege, role-based)
- Specify security monitoring and reporting cadence

## 3. Data Handling

- Define data processing requirements (GDPR, CCPA, HIPAA as applicable)
- Specify data residency and cross-border transfer controls
- Define data retention and deletion timelines
- Specify sub-processor notification requirements (advance notice of changes)
- Define data return and destruction procedures at engagement end

## 4. Operational Service Levels

- Define model monitoring and drift detection procedures
- Specify SLAs (uptime, response time, resolution time)
- Define change management and model update notification procedures
- Specify reporting cadence (performance, incidents, compliance)
- Define acceptance criteria for AI system outputs

## 5. Incident Response Procedures

### 5.1 Incident Escalation

- Define client-specific severity levels and notification timelines
- Specify escalation paths, contacts, and communication channels
- Define response time requirements per severity level
- Specify tabletop exercise cadence for AI incident scenarios

### 5.2 Forensic Evidence and RACI

- Include RACI matrix for detection, containment, forensic preservation, root cause analysis, remediation, and reporting
- Define evidence preservation requirements: logs, prompts, model versions, configurations, retrieval context, tool calls, timestamps
- Specify forensic access procedures (who has access to logs, model data, system evidence, and under what conditions)
- Define root cause analysis ownership and timeline
- Specify model rollback and fallback procedures (who authorizes, who restores)

### 5.3 AI-Specific Evidence Logging

- Specify required logging fields: system prompt version, conversation history, model version and parameters, raw model output, tool call parameters and responses, agent identity, retrieval context, behavioral monitoring data
- Define retention period for AI-specific evidence
- Specify export format and access procedures
- Define redaction rules for sensitive data in logs

## 6. Agentic AI Operational Controls

### 6.1 Runtime Guardrails

- Define runtime guardrails and approval gates for high-risk actions
- Specify tool and API access controls (allowlists, denylists)
- Define credential rotation and JIT access procedures
- Specify behavioral monitoring against baseline, with drift detection
- Define delegation chain logging requirements

### 6.2 Agent Monitoring

- Specify required runtime behavioral metrics
- Define autonomy calibration assessment cadence
- Specify delegation chain monitoring requirements
- Define alerting thresholds for behavioral anomalies
- Specify continuous monitoring requirements (recognizing agentic behavior may evolve)

### 6.3 Agent Decommissioning

- Define procedures for principled agent decommissioning
- Specify credential revocation and session termination procedures
- Define evidence preservation requirements during decommissioning
- Specify transition procedures for replacing or upgrading agents

---

*This exhibit defines operational requirements for the engagement. For binding legal obligations, refer to Part 3 (Contract Clause Checklist).*
