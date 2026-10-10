# NIST RMF Practical Project: Hospital EHR Risk Assessment

## Project overview

This self-directed, simulated Governance, Risk, and Compliance (GRC) project applies practical risk-management concepts to a fictional hospital's Electronic Health Records (EHR) environment. The scenarios focus on confidentiality, availability, identity and access management, backup recovery, remediation tracking, and risk governance.

The project demonstrates how a GRC analyst can document a risk, evaluate likelihood and impact, recommend treatment, track corrective actions, review evidence, and determine whether a finding is ready for closure.

> **Scope and disclaimer:** This is an educational simulation. It is not an assessment of a real hospital, a formal NIST RMF authorization package, or evidence of professional client work. Risk ratings and recovery targets are illustrative and would need to be replaced with an organization's approved methodology, requirements, and evidence in a real engagement.

## Objectives

- Practice writing clear risk statements that connect an asset, threat/event, weakness, and potential business impact.
- Distinguish inherent risk from residual risk.
- Compare risk treatment options: mitigate, avoid, transfer/share, and accept.
- Document remediation owners, target dates, interim safeguards, evidence, and closure criteria.
- Apply governance principles to temporary risk acceptance and overdue remediation.
- Evaluate whether controls are designed, implemented, and operating effectively.
- Understand why a control's existence or a ticket's status does not, by itself, prove effectiveness.
- Practice risk-register and Plan of Action and Milestones (POA&M) concepts.

## Scenario

A fictional hospital operates an EHR server containing sensitive patient records. The exercise explores several hypothetical findings:

1. **EHR-001 — Unpatched vulnerability:** An internet-accessible server has a known software vulnerability. The scenario considers patching, interim network restrictions, verification, and closure.
2. **EHR-002 — Backup and recovery:** Recovery testing identifies a missed Recovery Time Objective (RTO), shared-network exposure, and data-integrity issues. Corrective actions are tracked and retested.
3. **EHR-003 — Former employees' accounts:** Unneeded accounts remain active. The exercise covers disablement, evidence, and verification.
4. **EHR-004 — Employee offboarding process:** A process weakness causes delays in access revocation. The exercise addresses ownership, routing, escalation, monitoring, and retesting.
5. **EHR-005 — Quarterly access reviews:** A documented requirement is not performed consistently. The exercise covers unclear ownership, incomplete evidence, exceptions, overrides, and monitoring.

These are simulated teaching scenarios, not verified findings from an actual environment.

## Approach

The practical workflow used throughout the exercise was:

1. **Identify:** Define the asset, event/threat, weakness, and potential consequence.
2. **Assess:** Consider likelihood and impact using an illustrative scale; validate ratings against an approved methodology in real work.
3. **Prioritize:** Consider severity alongside exploit activity, urgency, patient-care impact, exposure, and existing safeguards.
4. **Treat:** Recommend mitigation, avoidance, transfer/sharing, or formal acceptance as appropriate.
5. **Track:** Document accountable risk owner, remediation owner, target date, status, interim safeguards, and escalation.
6. **Verify:** Obtain evidence that corrective actions and controls operate as intended.
7. **Reassess and close:** Reassess residual risk and close only when the defined criteria and required approvals are satisfied.
8. **Monitor:** Continue tracking accepted risks, remaining exposure, and recurring control performance.

## Key learning outcomes

### Risk register discipline
- A risk remains open while remediation is incomplete.
- A patch being available is not the same as a patch being deployed and verified.
- A temporary safeguard can reduce exposure without eliminating the underlying vulnerability.
- Risk acceptance is a documented decision by an appropriately authorized person; it is not a substitute for remediation or a way to erase a finding.
- Residual risk should be reassessed based on evidence rather than automatically assigned a lower rating.

### Control assessment
- A documented policy is not proof that the control operates.
- A ticket marked complete is not proof that an access change succeeded.
- Control assessment should distinguish design, implementation, and operating effectiveness.
- Exceptions should be documented, investigated, and tracked through corrective action.
- Monitoring needs clear ownership, frequency, escalation, and evidence of follow-up.

### Backup and recovery
- Successful backup jobs do not prove recoverability.
- Recovery tests should evaluate data integrity and whether approved RTO/RPO targets are met.
- Backup isolation helps address shared-failure exposure but does not, by itself, prove restored data is complete and trustworthy.

## Deliverables

- `README.md` — project overview, scope, approach, and learning outcomes.
- `workbooks/NIST-RMF-Hospital-EHR-Risk-Register.xlsx` — sample risk register and remediation tracker.
- `documents/NIST-RMF-Hospital-EHR-Executive-Summary.pdf` — concise portfolio summary.
- `documents/Methodology-and-Limitations.md` — methodology, assumptions, and limitations.

## Important limitations

This project focuses on practical risk assessment and remediation concepts associated with the NIST Risk Management Framework. It does **not** complete every formal RMF activity. In particular, it does not constitute a full system categorization, control selection and tailoring, security control assessment, authorization package, or formal authorization-to-operate decision. A real engagement would require the applicable NIST publications, organizational policies, system boundary, evidence, risk methodology, and authorized stakeholders.

## Suggested GitHub topics

`nist-rmf` `cybersecurity` `grc` `risk-assessment` `risk-register` `healthcare-cybersecurity` `it-audit` `identity-and-access-management`

## How to use this repository

Review the workbook and executive summary together. The workbook provides a structured example of how findings can be documented and tracked; the report summarizes the approach and lessons. For future projects, reuse the workflow with a new scenario and clearly distinguish hypothetical assumptions from verified evidence.
