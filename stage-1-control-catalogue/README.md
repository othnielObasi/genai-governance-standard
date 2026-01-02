# Stage 1 — GenAI Security & Governance Control Catalogue

## Overview

This catalogue defines a **vendor-neutral baseline of security and governance controls for Generative AI systems** across their full lifecycle.

It answers a single question:

> What must be true for a GenAI system to be safe, reviewable, and suitable for production use?

This catalogue is **descriptive, not prescriptive**.  
It does not mandate specific tools, vendors, or architectures.

This control catalogue is derived from and aligned with the OWASP GenAI security landscape, translating ecosystem guidance into a vendor-neutral baseline of security controls.

OWASP explains the GenAI security landscape; this catalogue defines the baseline controls required to operate within it safely.

---

## Control Domains

### 1. Use-Case & Scope Definition
GenAI systems must have:
- a clearly documented purpose
- defined intended users
- explicitly prohibited uses

Unbounded systems inevitably drift into unsafe or unintended use.

---

### 2. Architecture Classification
Systems must declare whether they are:
- prompt-only
- retrieval-augmented (RAG)
- agentic
- tool-integrated
- composite

Risk and autonomy differ materially by architecture.

---

### 3. Data & Knowledge Governance
Systems must:
- document data sources
- classify sensitive data
- prohibit disallowed data flows

Most GenAI failures are data failures, not model failures.

---

### 4. Prompt & Behaviour Integrity
System behaviour must be:
- intentionally designed
- resistant to instruction drift
- aligned with declared scope

Prompting alone is not governance.

---

### 5. Testing & Evaluation
Systems must be tested for:
- misuse
- bias
- adversarial inputs
- edge cases

Untested autonomy is unmanaged risk.

---

### 6. Deployment & Release Controls
Production deployment must require:
- explicit approval
- version tracking
- rollback readiness

Uncontrolled releases amplify failure impact.

---

### 7. Monitoring & Governance
Systems must:
- be observable
- support investigation
- allow suspension or retirement

If behaviour cannot be reconstructed, it cannot be governed.

---

## Intended Use

- Internal AI standards
- Design and architecture reviews
- Audit preparation
- Reference baseline for implementation
