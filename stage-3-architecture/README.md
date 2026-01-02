# Stage 3 — GenAI Governance Reference Architecture

## Overview

Stage 3 describes a **conceptual reference architecture** for governing Generative AI (GenAI) systems at runtime.

It addresses the question:

> How should GenAI systems be structured so that approved constraints continue to apply during operation?

This stage is **architectural and principle-based**.  
It defines structural concerns and responsibilities without prescribing implementation details.

---

## Architectural Principle

GenAI systems should not be relied upon to self-govern.

Effective governance requires that:
- decision authority is external to the model
- constraints are evaluated prior to execution
- system behaviour is observable by default

These principles apply regardless of model, vendor, or deployment environment.

---

## Reference Architecture Domains

The following domains represent **common structural concerns** that must be addressed to support enforceable governance in GenAI systems.

They are not components, products, or services, but **conceptual responsibilities** that may be realised in different ways.

---

### 1. Identity & Accountability

System actions should be attributable to a known actor (human, service, or system role), with clearly defined accountability for behaviour and outcomes.

---

### 2. Policy Evaluation

System behaviour should be evaluated against predefined rules, constraints, or conditions prior to execution, with outcomes that are explicit and reviewable.

---

### 3. Execution Control

Models may propose actions, but execution should occur only through approved pathways that constrain side effects and respect declared autonomy levels.

---

### 4. Observability & Evidence

System decisions and actions should produce records sufficient to support review, investigation, and audit, including reconstruction of behaviour after the fact.

---

### 5. Governance & Operational Control

Systems should support restriction, suspension, or retirement in a controlled manner, including defined responses to abnormal or high-risk conditions.

---

## Scope Clarification

This stage defines a **reference architecture for GenAI governance**.

It does not specify:
- implementation mechanisms
- runtime enforcement logic
- policy languages or tooling
- operational procedures

These elements must be designed and validated in accordance with organisational context and risk profile.

---

## Intended Use

- Architectural design and review
- Governance model alignment
- Risk and assurance discussions
- Reference point for further system design
