# Assessment methodology

## 1. Objective

Evaluate the design and operation of in-scope digital services and supporting controls, identify material risks, and produce evidence-linked, actionable recommendations. The assessment is not a certification or guarantee that all risks have been identified.

## 2. Planning and scope

Document the following before assessment work begins:

- Sponsor, accountable owners, contacts, and escalation route.
- Legal entities, countries, properties, business units, and service providers included.
- Systems, environments, interfaces, data types, and critical dependencies in scope.
- Assessment period, working hours, permitted methods, and operational constraints.
- Explicit exclusions, assumptions, and limitations.
- Required outputs, classification, audience, delivery date, and approval process.

Create a system and data-flow inventory. Include guest booking and property-management systems, channel managers, payment services, loyalty platforms, identity providers, networks, cloud services, backups, connected devices, and AI services as applicable.

## 3. Work stages

1. **Authorize:** execute written authorization, confidentiality terms, and rules of engagement. Confirm emergency contacts and stop conditions.
2. **Discover:** review scope, architecture, inventories, policies, risk registers, and prior findings.
3. **Assess:** conduct interviews, configuration and process reviews, and other specifically approved validation. Do not exceed authorized access or testing limits.
4. **Corroborate:** map each conclusion to evidence, identify gaps and contradictions, and request factual validation from owners.
5. **Rate:** assign an evidence-based control status and risk rating using `scoring-model.md`.
6. **Report:** document scope, limitations, findings, business impact, evidence references, recommendations, owners, and target dates.
7. **Close:** agree corrective actions, evidence retention/disposal, and any follow-up validation.

## 4. Assessment domains

Use the working matrix and domain guides to tailor coverage across infrastructure, application security, data protection, and AI governance. Add operational resilience, physical security, payment-card obligations, safety, accessibility, vendor risk, or other domains where scope requires.

## 5. Evidence and findings

Assign evidence IDs in `evidence/evidence-register.csv`. Keep evidence in an approved restricted repository; the register should contain metadata and references, not secrets or unnecessary personal data. Each finding should state the condition, criteria, evidence, cause where known, impact, recommendation, accountable owner, and planned completion date.

Label statements as verified, interview-based, self-reported, inferred, or not assessed. A missing artifact is an evidence gap; it is not automatically proof that a control does not exist.

## 6. Validation and quality review

Provide responsible owners an opportunity to correct factual errors and supply additional evidence. Preserve the assessor’s independent risk judgment. Review consistency of scope, scoring, evidence references, recommendations, and report handling before issuance.

## 7. Safety and stop conditions

No intrusive testing, production changes, social engineering, credential collection, or access to personal data is permitted unless expressly authorized in writing with specific safeguards. Stop activity and notify the designated contact if service degradation, unexpected sensitive-data exposure, scope ambiguity, or a safety concern occurs.

## 8. Limitations

Assessment conclusions apply only to the stated scope, period, and evidence available. Sampling, access restrictions, third-party dependencies, and point-in-time changes may limit assurance. Record these limitations in the final report.
