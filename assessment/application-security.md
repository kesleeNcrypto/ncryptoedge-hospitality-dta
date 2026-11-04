# Application security assessment

## Scope

Identify in-scope websites, mobile applications, APIs, integrations, development pipelines, and vendors. Include booking, guest account, loyalty, property-management, channel-manager, payment, and customer-support components as applicable.

## Review objectives

- Confirm ownership, architecture, data flows, trust boundaries, and threat-model coverage.
- Review authentication, authorization, session security, account recovery, and administrative functions.
- Evaluate input validation, error handling, cryptographic practices, and security configuration.
- Review API inventory, access controls, rate limits, integration credentials, and webhook validation.
- Assess dependency management, code review, build/release protections, secrets handling, and remediation tracking.
- Review logging and monitoring while avoiding unnecessary collection of guest or payment information.
- Consider accessibility and secure alternatives for guest-facing critical functions.

## Evidence to request

Architecture and data-flow diagrams; secure-development policy; threat models; code-review and release records; dependency and vulnerability management reports; API specifications; security testing summaries; defect remediation evidence; and vendor assurance.

## Safe assessment boundary

This guide does not authorize penetration testing, exploitation, credential attacks, or production scanning. Any technical validation requires separate written authorization defining systems, methods, dates, limits, contacts, and stop conditions. Use non-production systems and synthetic data where possible.
