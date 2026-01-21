---
title: "aitl-training"
description: "Control Engineer"
---

# Training Plan: Control Engineer (AITL)

This document defines the **role-based training plan** for **Control Engineers**
working with systems based on **AITL (Architecture for Integrated Technology Logic)**.

This plan is aligned with **ISO 9001 Clause 7.2 (Competence)** and focuses on
preserving **real-time control responsibility** while enabling supervised use
of adaptive and AI-assisted methods.

---

## 1. Role Definition

A **Control Engineer** under AITL is responsible for:

- Designing and validating real-time control loops
- Ensuring system stability, safety, and deterministic behavior
- Defining operating envelopes and safe modes
- Cooperating with supervisory and design-level functions without relinquishing control authority

Control Engineers are **directly responsible** for real-time system behavior.

---

## 2. Training Objectives

After completing this training, a Control Engineer shall be able to:

- Explain control behavior based on physical models and assumptions
- Design and tune PID-based control loops with clear stability justification
- Explain the role of FSMs in supervision and mode management
- Identify conditions under which adaptation must be limited or disabled
- Clearly explain why LLMs are excluded from real-time control

---

## 3. Required Training Layers

Control Engineers must complete training in the following AITL layers.

### Layer 1: Physical and System Constraints

Required competence:
- Understand physical limits affecting controllability
- Identify constraints that cannot be compensated by control
- Recognize model breakdown conditions

---

### Layer 2: Models and Real-Time Control

Required competence:
- Develop and validate control-oriented models
- Design and tune PID controllers
- Analyze stability, response, and robustness

Key rule:
- **Real-time control authority resides exclusively in PID and FSM**

---

### Layer 3: Supervisory Control (FSM)

Required competence:
- Design FSM-based supervision logic
- Define safe mode transitions
- Handle faults, degradation, and recovery

Key rule:
- FSM determines **when control modes may change**

---

### Layer 4: Adaptive Assistance (Bounded)

Required competence:
- Understand NN / RL as adaptive assist mechanisms
- Define explicit bounds and safety limits
- Recognize when adaptation threatens stability or responsibility

Key rule:
- Adaptive methods may assist but **must not override control logic**

---

### Layer 5: Design-Time Intelligence (LLM)

Required competence:
- Use LLMs for offline analysis and review only
- Interpret logs and trends without delegating decisions
- Communicate limitations of AI-assisted analysis

Key rule:
- LLMs are strictly **non-real-time and non-authoritative**

---

### Layer 6: Boundary Confirmation and Recovery

Required competence:
- Detect loss of controllability
- Decide when to stop control action
- Escalate to design recovery processes

---

## 4. Learning Materials

Training materials shall be selected from the **Samizo-AITL main repositories**,
including:

- Control architecture documentation
- PID / FSM PoC implementations
- Control playground demonstrations
- Envelope control and recovery concepts

This plan does **not** introduce alternative control frameworks.

---

## 5. Verification Criteria

Competence verification shall confirm that the Control Engineer can:

- Justify control designs using physical and control reasoning
- Explain FSM supervision and mode transitions
- Identify unsafe use of adaptive or AI-based methods
- Demonstrate awareness of responsibility boundaries

Verification methods may include:
- Design explanation
- Control response interpretation
- Scenario-based discussion
- Checklist-based assessment

---

## 6. Training Records

Completion of this training shall be recorded using:

- Templates defined in `03_Training_Record`

Records must indicate:
- Training layers completed
- Verification outcome
- Verifier identity

---

## 7. Completion Criteria

A Control Engineer is considered trained under AITL when:

- All required layers are completed
- Verification criteria are met
- Real-time control responsibility is clearly understood and accepted

---

## 8. Summary

This training plan ensures that Control Engineers:

- Retain full authority over real-time behavior
- Use adaptive and AI-assisted methods responsibly
- Protect system stability and safety

AITL-based control depends on **accountable engineers, not autonomous intelligence**.
