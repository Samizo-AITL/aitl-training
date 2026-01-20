# AITL Training Policy

This document defines the **education and training policy** for the AITL Training repository.  
It establishes the non-negotiable principles, responsibility boundaries, and competence objectives
for education based on **AITL (Architecture for Integrated Technology Logic)**.

This policy is written with **ISO 9001 Clause 7.2 (Competence)** in mind and is intended to support
traceable, auditable, and responsibility-preserving engineering education.

---

## 1. Purpose of This Policy

The purpose of this policy is to:

- Define a clear **education and training philosophy** for AITL-based design
- Ensure that training supports **design responsibility and accountability**
- Prevent misuse of AI technologies in safety- or responsibility-critical design decisions
- Provide a stable reference for all training plans, records, and verification activities

This policy applies to all documents contained in the `aitl-training` repository.

---

## 2. Core Principle: Responsibility Separation

AITL is based on a strict and explicit separation of responsibilities.
This separation is a **non-negotiable design and education principle**.

### Responsibility Layers

- **Real-time control**
  - Implemented using PID and FSM
  - Responsible for stability, safety, and deterministic behavior

- **Adaptive assist**
  - Implemented using NN / RL
  - Allowed only when explicitly bounded and supervised
  - Must never replace or override real-time control logic

- **Design-time intelligence**
  - Implemented using LLMs
  - Used exclusively in **non-real-time** contexts
  - Supports analysis, review, and redesign decisions only

Education and training under AITL must reinforce this separation at all times.

---

## 3. Policy on the Use of AI and LLMs

Within AITL-based education:

- LLMs **shall not** be used for real-time control
- LLMs **shall not** make autonomous design decisions without human accountability
- LLM outputs are treated as **design support material**, not authoritative results

Training must ensure that engineers can clearly explain:

- Where AI is allowed to assist
- Where AI must not intervene
- Who remains responsible for final design decisions

---

## 4. Competence-Oriented Education

AITL training is **competence-oriented**, not tool-oriented.

Education focuses on ensuring that trained engineers can:

- Explain physical and control constraints that govern system behavior
- Justify architectural decisions based on responsibility boundaries
- Identify situations where adaptive or AI-based methods must be stopped
- Communicate design intent and limitations to third parties

Completion of training is based on **demonstrable understanding**, not attendance.

---

## 5. Alignment with ISO 9001

This policy supports alignment with **ISO 9001 Clause 7.2 (Competence)** by:

- Defining required competence domains
- Separating training, verification, and improvement activities
- Enabling traceable links between education objectives and verification results

This repository does **not** claim ISO 9001 certification or compliance.
It provides a structured framework that organizations may adapt to their own quality systems.

---

## 6. Relationship to Other Training Documents

This policy serves as the **top-level reference** for:

- Training architecture (`01_Training_Architecture`)
- Role-based training plans (`02_Training_Plan`)
- Training records (`03_Training_Record`)
- Competence verification (`04_Verification`)
- Continuous improvement (`05_Improvement`)

All subordinate documents must be consistent with this policy.

---

## 7. Change and Stability

This policy is intentionally **stable**.

Changes are permitted only when:

- The core AITL responsibility separation remains intact
- The change improves clarity, traceability, or educational effectiveness
- The rationale for the change is documented

---

## 8. Summary

AITL Training exists to ensure that:

- Advanced control and AI technologies are used **responsibly**
- Design accountability is preserved
- Education strengthens, rather than obscures, engineering judgment

This policy defines the foundation upon which all AITL education and training activities are built.

