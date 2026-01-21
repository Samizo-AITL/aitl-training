---
title: "aitl-training"
description: "Competence Verification Checklist"
---

# Competence Verification Checklist (AITL)

This document defines the **competence verification checklist** for AITL-based education and training.
It is used to confirm that training outcomes are **demonstrated, explainable, and responsibility-preserving**.

This checklist is aligned with **ISO 9001 Clause 7.2 (Competence)** and is applicable to all roles
defined in the AITL Training Plans.

---

## 1. Purpose

The purpose of this checklist is to:

- Verify that training has resulted in **actual competence**, not just attendance
- Confirm that responsibility boundaries defined by AITL are understood
- Prevent unsafe delegation of design or control responsibility to AI or tools
- Provide an auditable record of competence verification

This checklist is used in conjunction with training records defined in `03_Training_Record`.

---

## 2. Verification Principles

Competence verification under AITL is based on the following principles:

- **Explainability over automation**
- **Responsibility over convenience**
- **Causal understanding over pattern recognition**
- **Human accountability over AI authority**

Verification must confirm understanding, not tool familiarity.

---

## 3. General Verification Items (All Roles)

The following items apply to **all roles**.

| Item | Verification Question | Pass / Fail | Notes |
|---|---|---|---|
| GV-1 | Can the trainee explain AITL responsibility separation (PID / FSM / NN-RL / LLM) without ambiguity? |  |  |
| GV-2 | Can the trainee clearly state where AI assistance is **not allowed**? |  |  |
| GV-3 | Can the trainee identify who is responsible for final design decisions? |  |  |
| GV-4 | Can the trainee explain system behavior using physical and causal reasoning? |  |  |
| GV-5 | Can the trainee explain why LLMs are restricted to non-real-time use? |  |  |

---

## 4. Design Engineer Verification Items

Applicable to trainees following `Plan_Design_Engineer`.

| Item | Verification Question | Pass / Fail | Notes |
|---|---|---|---|
| DE-1 | Can the trainee justify architectural decisions based on physical constraints? |  |  |
| DE-2 | Can the trainee explain why AI outputs are non-authoritative? |  |  |
| DE-3 | Can the trainee identify scenarios requiring design recovery? |  |  |
| DE-4 | Can the trainee explain risks of delegating design judgment to AI? |  |  |
| DE-5 | Can the trainee communicate design boundaries to stakeholders? |  |  |

---

## 5. Control Engineer Verification Items

Applicable to trainees following `Plan_Control_Engineer`.

| Item | Verification Question | Pass / Fail | Notes |
|---|---|---|---|
| CE-1 | Can the trainee explain PID control behavior and stability reasoning? |  |  |
| CE-2 | Can the trainee explain FSM supervision and mode transitions? |  |  |
| CE-3 | Can the trainee identify when adaptive assistance must be disabled? |  |  |
| CE-4 | Can the trainee recognize loss of controllability or unsafe operation? |  |  |
| CE-5 | Can the trainee justify exclusion of LLMs from real-time control? |  |  |

---

## 6. AI System Architect Verification Items

Applicable to trainees following `Plan_AI_System_Architect`.

| Item | Verification Question | Pass / Fail | Notes |
|---|---|---|---|
| AI-1 | Can the trainee explain AI’s role as design-time support only? |  |  |
| AI-2 | Can the trainee identify prohibited AI use cases in control systems? |  |  |
| AI-3 | Can the trainee explain how AI outputs must be reviewed and validated? |  |  |
| AI-4 | Can the trainee explain responsibility boundaries between AI and engineers? |  |  |
| AI-5 | Can the trainee explain escalation to design recovery processes? |  |  |

---

## 7. Verification Outcome

Verification is considered **successful** when:

- All applicable items are marked as **Pass**
- Any noted limitations are documented
- Responsibility boundaries are explicitly acknowledged by the trainee

Partial completion or tool proficiency alone is **not sufficient**.

---

## 8. Use in Training Records

Verification results shall be:

- Referenced in training records (`03_Training_Record`)
- Reviewed during audits or internal reviews
- Used as input for improvement or corrective actions if gaps are identified

---

## 9. Summary

This checklist ensures that:

- Training outcomes are **verifiable and explainable**
- AI does not obscure engineering responsibility
- AITL principles are consistently applied across roles

Competence under AITL is defined by **understanding, judgment, and accountability**.
