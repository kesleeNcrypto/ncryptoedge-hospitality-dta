# Scoring model

This model is a prioritization aid, not a certification or universal measure of compliance. Tailor thresholds and risk appetite with the assessment sponsor before work begins.

## Control status

| Status | Meaning |
|---|---|
| Implemented | Evidence supports that the control is designed and operating for the assessed scope. |
| Partially implemented | Some elements operate, but material gaps or inconsistent coverage remain. |
| Not implemented | Reliable evidence indicates the control is absent or not operating. |
| Not evidenced | Evidence available is insufficient to determine implementation. |
| Not applicable | A documented scope-based rationale supports exclusion. |
| Not assessed | The control was outside the assessment procedures or could not be assessed. |

Do not treat “not evidenced” or “not assessed” as equivalent to “not implemented.”

## Risk rating

Rate each finding using **impact** and **likelihood**. Consider guest privacy, financial loss, service availability, physical safety, legal exposure, reputation, and recovery effort. Explain material judgment calls.

### Impact

1. **Low:** limited, readily reversible effect; no material sensitive-data, safety, or service impact expected.
2. **Moderate:** bounded disruption, exposure, or financial/reputational harm requiring managed response.
3. **High:** significant guest or business impact, sensitive-data exposure, extended disruption, or substantial legal/financial consequences.
4. **Critical:** credible risk of severe or widespread harm, major safety consequences, systemic compromise, or prolonged loss of essential operations.

### Likelihood

1. **Unlikely:** requires unusual conditions and multiple safeguards are evidenced.
2. **Possible:** plausible under foreseeable circumstances; some relevant weaknesses or uncertainty exist.
3. **Likely:** straightforward or recurring conditions make realization probable.
4. **Very likely:** active exposure, repeated occurrence, or readily exploitable conditions are evidenced.

### Inherent priority matrix

| Likelihood \\ Impact | 1 Low | 2 Moderate | 3 High | 4 Critical |
|---|---:|---:|---:|---:|
| 1 Unlikely | Low | Low | Moderate | High |
| 2 Possible | Low | Moderate | High | Critical |
| 3 Likely | Moderate | High | Critical | Critical |
| 4 Very likely | High | Critical | Critical | Critical |

Use professional judgment to adjust for exposure, compensating controls, uncertainty, and business context. Record both impact and likelihood, rationale, and any residual-risk decision.

## Remediation urgency (default guidance)

- **Critical:** contain or mitigate immediately; executive notification and a tracked response plan.
- **High:** assign an accountable owner promptly and target near-term remediation.
- **Moderate:** schedule remediation within an agreed planning cycle.
- **Low:** address through routine improvement or document an accepted risk.

The organization should set actual response deadlines and escalation thresholds. A risk owner—not the assessor—accepts residual risk.

## Reporting

For each finding record: unique ID, domain, condition, criteria, evidence IDs, impact, likelihood, rating, recommendation, owner, due date, status, and residual-risk decision. Avoid false precision; ratings are reasoned prioritization, not actuarial predictions.
