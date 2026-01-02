# Relationship to OWASP

This repository is **derived from and aligned with the OWASP GenAI Security landscape**.

OWASP documents the GenAI security landscape by describing common risk classes, failure modes, and recommended mitigations across the ecosystem. This repository complements that work by translating ecosystem guidance into a **vendor-neutral operational baseline** and a **conceptual system model** for governing GenAI in production environments.

## What OWASP provides
OWASP helps organisations understand:
- what can go wrong (risk taxonomy)
- where failures commonly occur (threat and failure patterns)
- what mitigations should be considered (recommended practices)

## What this repository adds
This repository focuses on operationalisation:
- **Baseline controls** (“what must be true” across the lifecycle)
- **Practical artefacts** (“what teams produce and verify” during build and review)
- **A conceptual Chain-of-Trust architecture** (“how governance becomes a system property”)

## Key distinction
OWASP explains the GenAI security landscape; this repository defines the baseline controls required to operate within it safely.

## Non-goals
This repository does not attempt to replace OWASP, and it does not publish:
- tool- or vendor-specific implementations
- runtime enforcement code or policy engines
- organisation-specific thresholds or incident runbooks

## Attribution and intent
Where OWASP provides ecosystem guidance, this repository provides a structured, lifecycle-oriented baseline intended to improve consistency, reviewability, and production readiness for GenAI deployments.
