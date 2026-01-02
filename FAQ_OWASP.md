# FAQ — “Why not just use OWASP?”

## Isn’t OWASP enough?
OWASP is an excellent foundation for understanding the GenAI security landscape. However, OWASP is intentionally broad and descriptive. Most organisations also need:
- an operational baseline (“what must be true before production”)
- practical artefacts for teams (“what we produce and verify”)
- a system model for runtime governance (“how we prevent bypasses”)

This repository complements OWASP by translating ecosystem guidance into a lifecycle-based baseline and a conceptual governance architecture.

## Are you replacing OWASP?
No. This work is designed to align with and build on OWASP GenAI guidance. It fills a different gap: operational consistency and production readiness.

## What’s the main difference in one sentence?
OWASP explains the GenAI security landscape; this repository defines the baseline controls required to operate within it safely.

## Does this include implementation?
No. This public repository avoids publishing enforcement implementations, policy engines, or runbooks. It focuses on vendor-neutral baseline expectations and a conceptual governance model.

## Why define a “production readiness” standard?
Because many GenAI failures occur after deployment, when behaviour is difficult to reconstruct or stop. A go/no-go standard supports executive decision-making and reduces ambiguity at release time.
