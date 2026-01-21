---
title: "aitl-training"
description: "Training Plans"
---

# 🧩 Training Plans

This directory contains **role-based training plans** for **AITL-based systems**.

Each training plan defines **what a role is responsible for knowing, explaining, and judging**,  
from an **education and competence assurance perspective**.

---

## 🎯 Purpose of Training Plans

Each training plan clearly defines:

- 👤 **Role responsibility and authority**  
- 🧱 **Required training layers** based on the AITL training architecture  
- 🎯 **Competence objectives** (knowledge, judgment, explanation capability)  
- ✅ **Verification expectations** for competence confirmation  

These plans exist to ensure that **design responsibility remains explicit, auditable, and human-owned**.

---

## 🚫 Scope Limitation

The training plans in this directory:

- ❌ **Do not duplicate technical documentation**  
- ❌ **Do not provide implementation guidance or code**  

They define:

> **What must be understood and explained**  
> — **not** how to implement it.

Technical implementation remains the responsibility of the appropriate  
design and implementation repositories.

---

## 🔖 Alignment and Constraints

All training plans are aligned with:

- 🧭 **AITL responsibility separation**  
  *(Control / Adaptive Assist / Design-time Intelligence)*  
- 📘 **ISO 9001 Clause 7.2 (Competence)**  
- 🧱 The **AITL Training Architecture**  

No training plan may override or reinterpret these higher-level constraints.

---

## 📌 Core Reference (Adoption Decision)

### 🗂 Education & Training Needs Matrix (Public Repositories)

- 📄 [`Education_Training_Needs_Matrix_AITL_Public.md`](./Education_Training_Needs_Matrix_AITL_Public.md)  
- Defines the **competency coverage of AITL** using **public repositories only**  
- Used for:
  - 📊 AITL adoption decision  
  - 🔍 Training gap analysis  
  - 🧑‍💼 Management and auditor explanation  

🔑 This matrix serves as the **single entry point** for organizational adoption and review.

---

## 👥 Available Training Plans

### 🤖 AI System Architect
- 📄 [`Plan_AI_System_Architect.md`](./Plan_AI_System_Architect.md)  
- Defines:
  - System-level architectural responsibility  
  - Required competence boundaries  
  - Explanation scope for AI-assisted and design-time intelligence layers  

---

### 🎛 Control Engineer
- 📄 [`Plan_Control_Engineer.md`](./Plan_Control_Engineer.md)  
- Defines:
  - Control-layer responsibility and authority  
  - Required competence for real-time behavior and verification  
  - Explanation scope tied to physical causality and control logic  

---

## 📝 Notes for Operation and Audit

- 🧭 The **Education & Training Needs Matrix** is the **entry point for management and auditors**  
- 📐 Role-based training plans **must reference the matrix**, not redefine competencies  
- ✅ Training completion and competence confirmation are validated in:
  - `03_Training_Record`  
  - `04_Verification`  

---

> 🛡 **Note**  
> Training plans define *competence expectations*, not performance guarantees.  
> Final design responsibility always remains with qualified human engineers.
