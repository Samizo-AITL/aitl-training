---
title: "aitl-training"
description: "AITL-based education and training documentation aligned with ISO 9001 competence requirements"
---

# AITL Training

This repository provides **education and training documentation** based on  
**AITL (Architecture for Integrated Technology Logic)**,  
organized with **ISO 9001–style competence management, training structure, and responsibility separation** in mind.

This repository does **not** contain technical implementations or source code.  
It defines **how AITL-related knowledge is trained, verified, and maintained** from an education and competence perspective.

---

## Purpose

The purpose of this repository is to:

- Define **training objectives and competence requirements** for AITL-based design activities
- Organize educational materials into a **traceable and auditable training structure**
- Support education and training aligned with **ISO 9001 Clause 7.2 (Competence)**
- Enable organizations to adopt AITL **without compromising design responsibility or accountability**

---

## Scope

This repository covers:

- Training policy and educational principles
- Training architecture and learning paths
- Role-based training plans
- Training records and verification criteria
- Concepts for continuous improvement and corrective actions

This repository does **not** replace or duplicate:

- Physical modeling
- Control system design
- Implementation repositories
- Proof-of-concept (PoC) or experimental systems

These remain the **Single Source of Truth** within the main Samizo-AITL repositories.

---

## Directory Overview

The directory structure itself reflects the **AITL education and competence framework**.

### 📁 Policy
- [`00_Policy/`](./00_Policy/)
- Defines **non-negotiable principles**, responsibility separation, and education policy  
- Top-level reference aligned with ISO 9001 Clause 7.2

---

### 📁 Training Architecture
- [`01_Training_Architecture/`](./01_Training_Architecture/)
- Defines the **ordered learning structure**  
  (Physical → Control → Intelligence → Boundary & Recovery)
- Ensures causal, responsibility-preserving education

---

### 📁 Training Plans (Role-based)
- [`02_Training_Plan/`](./02_Training_Plan/)
- Role-specific competence definitions and learning scope
  - Design Engineer
  - Control Engineer
  - AI System Architect
  - (Optional) Engineering Manager
- Specifies **what must be understood and explained**, not how to implement

---

### 📁 Training Records
- [`03_Training_Record/`](./03_Training_Record/)
- Templates for **objective evidence of training and competence**
- Supports audits, reviews, and traceability

---

### 📁 Verification
- [`04_Verification/`](./04_Verification/)
- Defines **competence verification criteria**
- Confirms understanding, judgment, and accountability
- Prevents unsafe delegation to AI or tools

---

### 📁 Improvement
- [`05_Improvement/`](./05_Improvement/)
- Concepts for **continuous improvement and corrective actions**
- Supports ISO 9001 Clause 10 (Improvement)

---

### 📁 Reference
- [`99_Reference/`](./99_Reference/)
- Links to **main Samizo-AITL repositories**
- Declares the **Single Source of Truth**
- No original technical content is created here

---

## Relation to Samizo-AITL

AITL is based on a strict separation of responsibilities:

- **Real-time control**: PID / FSM  
- **Adaptive assist**: NN / RL (bounded and supervised)  
- **Design-time intelligence**: LLM (non-real-time use only)

This repository documents **how these architectural principles are taught, understood, and verified**,  
not how they are technically implemented.

---

## Intended Audience

This repository is intended for:

- Control system designers
- Semiconductor and MEMS engineers
- AI-assisted system architects
- Engineering managers responsible for education, training, and competence management

This is **not an introductory tutorial**.  
It assumes prior engineering knowledge and focuses on **design responsibility and competence assurance**.

---

## License

Documentation in this repository is provided under a **hybrid license model** consistent with Samizo-AITL.  
Refer to the main Samizo-AITL project for detailed licensing terms.
