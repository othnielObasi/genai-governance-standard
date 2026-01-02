# Standards Alignment (High-Level)

This repository is designed to be compatible with established security and risk-management approaches. The mappings below are intentionally high-level and vendor-neutral.

## OWASP ASVS (Application Security Verification Standard)
While ASVS is not GenAI-specific, many requirements translate directly to GenAI systems, especially where GenAI is integrated into applications and workflows.

**Strong alignment areas**
- Authentication and session integrity (Identity & Authority)
- Access control and least privilege (Authority Grants)
- Input validation and output handling (Prompt/Tool boundaries)
- Logging, monitoring, and audit trails (Evidence & Observability)
- Secure configuration and deployment controls (Release gating, environment separation)

**Where this repository extends ASVS**
- Autonomy declaration and agent behaviour constraints
- Pre-execution policy evaluation for GenAI actions
- Evidence requirements tied to model+tool decisions, not only app logs

## NIST AI RMF (AI Risk Management Framework)
NIST AI RMF focuses on organisational risk management and trustworthy AI outcomes. This repository supports operationalisation of those goals in production environments.

**Strong alignment areas**
- GOVERN: roles, accountability, oversight mechanisms
- MAP: use-case definition, context, and impact scoping
- MEASURE: evaluation, testing, and monitoring expectations
- MANAGE: controls, incident response, and risk treatment

**Where this repository adds specificity**
- A production readiness bar (go/no-go criteria)
- A conceptual architecture for enforceable governance at runtime

## Notes
- This is not a certification claim.
- Organisations should interpret and tailor controls based on sector, jurisdiction, and risk profile.
