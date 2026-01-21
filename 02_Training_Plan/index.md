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
  - [`../01_Training_Architecture/`](../01_Training_Architecture/)  

No training plan may override or reinterpret these higher-level constraints.

---

## 📌 Core References (Mandatory)

### 🗂 Education & Training Needs Matrix  
*(Adoption & Competency Definition)*

- 📄 [`Education_Training_Needs_Matrix_AITL_Public.md`](./Education_Training_Needs_Matrix_AITL_Public.md)  
- Defines **which competencies are required** and **where they are covered**  
- Used for:
  - 📊 AITL adoption decision  
  - 🔍 Training gap analysis  
  - 🧑‍💼 Management and ISO audit explanation  

🔑 This matrix is the **single entry point for adoption decisions**.

---

### 📘 Education & Training Program Plan  
*(Training Execution Plan)*

- 📄 [`Education_Training_Program_Plan_AITL.md`](./Education_Training_Program_Plan_AITL.md)  
- Defines:
  - Concrete education programs  
  - Training materials (repositories)  
  - Instructors and required training time  
  - Execution rules for education delivery  

This document is the **mandatory execution plan** that translates  
the Needs Matrix into **actual training activities**.

---

## 👥 Available Role-Based Training Plans

### 🤖 AI System Architect
- 📄 [`Plan_AI_System_Architect.md`](./Plan_AI_System_Architect.md)  
- Defines:
  - System-level architectural responsibility  
  - Required competence boundaries  
  - Explanation scope for AI-assisted and design-time intelligence  

---

### 🎛 Control Engineer
- 📄 [`Plan_Control_Engineer.md`](./Plan_Control_Engineer.md)  
- Defines:
  - Real-time control responsibility and authority  
  - Required competence for stability, safety, and verification  
  - Explanation scope tied to physical causality and control logic  

---

## 🔗 Related Directories (Evidence)

- 📝 **Training Records**  
  - [`../03_Training_Record/`](../03_Training_Record/)  

- ✅ **Competence Verification**  
  - [`../04_Verification/`](../04_Verification/)  

Training plans are considered **complete only when**
records and verification results are properly linked.

---

## 📝 Notes for Operation and Audit

- 🧭 **Needs Matrix → Program Plan → Role Plans** is the required flow  
- 📐 Role-based plans **must reference the matrix and program plan**  
- ✅ Training completion is confirmed only through:
  - Training Records  
  - Competence Verification  

---

> 🛡 **Note**  
> Training plans define *competence expectations*, not performance guarantees.  
> Final design responsibility always remains with qualified human engineers.

