# GenAI Production Readiness Standard

## Purpose

This standard defines the **minimum conditions required to approve a Generative AI (GenAI) system for production use**.

It establishes a **go / no-go decision framework** for executives, reviewers, and risk owners by identifying baseline conditions that must be satisfied before a system may operate in a production environment.

If any required condition cannot be satisfied, the system is **not production-ready**.

---

## Core Questions

A GenAI system may be approved for production **only if all of the following questions can be answered affirmatively**:

- Can we clearly explain what the system is allowed to do?
- Can we restrict, suspend, or stop the system if necessary?
- Can we reconstruct what happened after an incident or unexpected outcome?
- Can we govern exceptions and deviations from normal operation?

If the answer to any of these questions is **“no”**, approval **should not be granted**.

---

## Minimum Readiness Domains

Approval for production requires affirmative evidence across **all** of the following domains.  
These domains define **what must be true**, not how the system is implemented.

### 1. Purpose & Scope

- The system has a clearly defined and approved purpose.
- Intended users and usage contexts are explicitly documented.
- Prohibited or out-of-scope uses are explicitly stated.

---

### 2. Authority & Accountability

- Actions performed by the system are attributable to a known actor (human, service, or system role).
- Authority to act is explicitly granted and scoped.
- Accountability for system behaviour is clearly assigned.

---

### 3. Policy & Constraints

- System behaviour is evaluated against predefined rules, constraints, or conditions prior to execution.
- Behaviour outside approved constraints is prevented or escalated.
- Default behaviour in the absence of clear approval is restrictive.

---

### 4. Execution Control

- The system cannot perform side effects outside approved capabilities or pathways.
- Autonomy levels are explicitly declared and respected.
- Execution paths are bounded and predictable.

---

### 5. Observability & Evidence

- System decisions and actions produce records sufficient for review and investigation.
- Behaviour can be reconstructed after the fact using available evidence.
- Evidence supports audit, oversight, and incident response needs.

---

### 6. Exception & Override Governance

- Deviations from normal operation are explicitly governed.
- Overrides are attributable, time-bound, and reviewable.
- Exceptional actions do not silently become normal behaviour.

---

### 7. Operational Control

- The system can be restricted, suspended, or retired in a controlled manner.
- Operational intervention does not rely on ad hoc or informal measures.
- Degraded or restricted operating modes are explicitly supported.

---

## Decision Outcome

Production approval may be granted **only if all readiness domains are satisfied**.

If one or more domains cannot be satisfied:

- the system must be remediated, restricted, or redesigned; or
- approval must be explicitly withheld.

---

## Positioning

This standard is:

- **vendor-neutral**
- **architecture-aware**
- **enforceable in principle**

It is intended to support:

- executive sign-off  
- audit readiness  
- consistent release decisions  
- operational confidence in GenAI deployments  

---

## Scope Note

This standard defines **baseline production readiness expectations**.  
Tool-specific implementations, runtime enforcement mechanisms, and operational runbooks are **out of scope** and must be designed and validated in accordance with organisational context and risk profile.
