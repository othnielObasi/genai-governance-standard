# Stage 2 — Practical GenAI Control Toolbox (Open Core)

## Overview

Stage 2 translates the Stage 1 control baseline into **practical artefacts that teams can use during design, build, and review**.

It answers:

> How do teams implement the baseline controls in practice?

This toolbox is intentionally **implementation-agnostic** and safe to share publicly.

---

## What This Stage Provides

For each control area, this stage includes:
- intent
- applicability
- example artefacts
- validation checklists
- common failure patterns

---

## Example Control Pack

### Control Pack: Use-Case Definition

**Intent**  
Ensure GenAI systems are deployed only for approved, understood purposes.

**Applicability**  
All GenAI systems.

**Example Artefacts**
- Use-case description
- Intended users
- Prohibited uses
- Risk classification

**Validation Checklist**
- Is the use-case documented?
- Are prohibited uses explicit?
- Is scope aligned with architecture?

**Common Failures**
- “General assistant” with no boundaries
- Scope expanding post-deployment

---

## What Is Deliberately Excluded

- Runtime enforcement mechanisms  
- Execution logic  
- Policy engines  
- Incident runbooks  

These belong to internal implementation and consulting work.

---

## Intended Use

- Engineering onboarding
- Product design
- Security reviews
- Consistent internal documentation
