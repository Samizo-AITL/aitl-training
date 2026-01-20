# Training Plan: Design Engineer (AITL)

This document defines the **role-based training plan** for **Design Engineers**
working with systems based on **AITL (Architecture for Integrated Technology Logic)**.

This plan is aligned with **ISO 9001 Clause 7.2 (Competence)** and specifies
required knowledge, learning scope, and verification criteria to ensure
that design responsibility is preserved when applying control and AI technologies.

---

## 1. Role Definition

A **Design Engineer** under AITL is responsible for:

- Defining system architecture and design intent
- Making final design decisions based on physical and control constraints
- Determining where automation or AI assistance is acceptable
- Retaining accountability for safety, performance, and limitations

This role **cannot delegate responsibility** to tools, algorithms, or AI systems.

---

## 2. Training Objectives

After completing this training, a Design Engineer shall be able to:

- Explain system behavior from **physical causes to control responses**
- Justify architectural choices using AITL responsibility separation
- Identify conditions where adaptive or AI-based methods must be restricted or stopped
- Clearly explain **why LLMs are limited to non-real-time, design-time use**
- Communicate design assumptions, risks, and boundaries to stakeholders

---

## 3. Required Training Layers

Design Engineers must complete training in the following AITL layers.

### Layer 1: Physical and System Constraints

Required competence:
- Explain dominant physical laws and constraints
- Identify non-negotiable system limits
- Describe failure modes caused by physical assumptions

Typical references:
- Semiconductor / MEMS physics
- Electrical, thermal, mechanical boundaries

---

### Layer 2: Models and Control Foundations

Required competence:
- Explain modeling assumptions and limitations
- Understand PID-based real-time control principles
- Explain stability, response, and performance trade-offs

Key rule:
- Real-time control responsibility remains with **PID and FSM**

---

### Layer 3: Supervisory Control and State Management

Required competence:
- Understand FSM-based mode management
- Explain state transitions and supervision logic
- Identify conditions triggering recovery or shutdown

Key rule:
- Supervisory logic governs **permission for adaptation**

---

### Layer 4: Adaptive Assistance (Bounded)

Required competence:
- Understand the role of NN / RL as adaptive assist
- Identify safe bounds for adaptation
- Recognize unsafe or responsibility-breaking use cases

Key rule:
- Adaptive methods must not replace deterministic control

---

### Layer 5: Design-Time Intelligence (LLM)

Required competence:
- Use LLMs for analysis, review, and design support only
- Explain why LLMs are excluded from real-time control
- Treat AI outputs as **non-authoritative input**

Key rule:
- Final design judgment remains human-responsible

---

### Layer 6: Boundary Confirmation and Design Recovery

Required competence:
- Detect breakdown of assumptions
- Decide when to stop operation and return to design
- Participate in design recovery and corrective action

---

## 4. Learning Materials

Training materials shall be selected from the **Samizo-AITL main repositories**,
including but not limited to:

- Physical and device documentation
- Control architecture explanations
- AITL Controller PoC and demonstrations
- Design recovery and legacy case studies

This training plan does **not** duplicate technical documentation.

---

## 5. Verification Criteria

Competence verification for Design Engineers shall confirm that the trainee can:

- Explain AITL responsibility separation **without ambiguity**
- Describe system behavior using causal reasoning
- Justify the exclusion of AI from real-time control
- Identify unsafe delegation of responsibility

Verification methods may include:
- Oral explanation
- Written justification
- Design review discussion
- Checklist-based assessment

---

## 6. Training Records

Completion of this training shall be recorded using the templates defined in:

- `03_Training_Record`

Records must show:
- Training scope completed
- Verification method used
- Verifier identity

Attendance alone is **not sufficient**.

---

## 7. Completion Criteria

A Design Engineer is considered trained under AITL when:

- All required layers are completed
- Verification criteria are satisfied
- Design responsibility boundaries are clearly understood and accepted

---

## 8. Summary

This training plan ensures that Design Engineers:

- Use AI and automation **without losing accountability**
- Maintain clear responsibility boundaries
- Make design decisions grounded in physical and control reality

AITL-based design relies on **competent engineers, not autonomous tools**.

