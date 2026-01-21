---
title: "aitl-training"
description: "Education & Training Needs Matrix (AITL – Public Repositories)"
---

# 📊 Education & Training Needs Matrix  
**Rows:** Training Items (Public Repositories)  
**Columns:** Required Job Competencies / Skills  

This matrix defines **which competencies are covered by which public AITL repositories**.

It is intended for:

- 🧑‍💼 **AITL adoption decision making**  
- 🔍 **Training gap analysis**  
- 📘 **Management and ISO audit explanation**  

This document provides a **competence coverage view**, not a training procedure.

---

## 🔖 Legend

- ◎ **Mandatory** — Can take full responsibility independently  
- ○ **Important** — Can perform tasks autonomously  
- △ **Basic** — Conceptual / explanatory understanding  
- — **Not applicable**

---

## 🧠 Competency Definitions (Columns)

| ID | Competency / Skill | Business-Level Definition |
|---|---|---|
| S1 | Physical Principles | Can explain phenomena causally (including V–I characteristics) |
| S2 | Modeling | Can build models using equations or block diagrams with explicit assumptions |
| S3 | Control Theory (PID) | Can design gains with stability and performance justification |
| S4 | State Control (FSM) | Can define states, transitions, and fault states explicitly |
| S5 | AI Control (NN / RL) | Can define objectives, metrics, and deviation handling |
| S6 | LLM Utilization | Can restrict LLM usage to design support with validation rules |
| S7 | System Integration | Can specify responsibility separation (Control × AI × Safety) |
| S8 | Implementation | Can build reproducible implementations (Python / Git / EDA) |
| S9 | Verification | Can define pass/fail criteria, tests, and logs |
| S10 | Documentation | Can maintain traceability (Requirements → Design → Verification) |

---

## 🧱 Training Item × Competency Matrix  
*(Public Repositories Only)*

### 🧪 Physics / Semiconductor & EDA

| Training Item (Repository) | S1 | S2 | S3 | S4 | S5 | S6 | S7 | S8 | S9 | S10 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| **Edusemi-v4x** | ◎ | ◎ | △ | — | — | — | ○ | △ | ○ | ○ |
| **SemiDevKit** | ○ | ◎ | ○ | — | — | — | ○ | ◎ | ○ | △ |
| **openlane2-sram** | ○ | ◎ | — | — | — | — | △ | ◎ | ○ | △ |
| **Edusemi-Plus** | ○ | ○ | ○ | △ | ○ | ○ | ◎ | △ | ○ | ○ |

---

### 🎛 Control / Safety

| Training Item (Repository) | S1 | S2 | S3 | S4 | S5 | S6 | S7 | S8 | S9 | S10 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| **EduController** | △ | ○ | ◎ | ◎ | △ | — | ◎ | ○ | ◎ | ○ |
| **Control Playground** | △ | ○ | ○ | ○ | △ | — | ○ | ◎ | ○ | △ |
| **AITL Controller A-Type** | △ | ○ | ◎ | ◎ | ○ | — | ◎ | ○ | ◎ | ○ |
| **Envelope Control** | △ | ○ | ◎ | ○ | — | — | ◎ | ○ | ○ | △ |
| **Design Recovery Control** | ○ | ◎ | ◎ | ◎ | △ | — | ◎ | ○ | ◎ | ○ |
| **AI Control Safety Package** | — | ○ | ○ | ◎ | ○ | — | ◎ | △ | ◎ | ◎ |
| **V–I Control ASIC** | ◎ | ◎ | ◎ | △ | — | — | ◎ | ○ | ○ | ○ |

---

### 🧩 MEMS / Mechanical / Inkjet

| Training Item (Repository) | S1 | S2 | S3 | S4 | S5 | S6 | S7 | S8 | S9 | S10 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| **MEMS pre-FEM Analysis** | ◎ | ◎ | — | — | — | — | ○ | △ | ○ | △ |
| **Inkjet DTS** | ◎ | ◎ | ○ | △ | — | — | ◎ | △ | ○ | ○ |
| **Inkjet Timing** | ◎ | ◎ | ◎ | △ | — | — | ◎ | △ | ○ | ○ |
| **GF180 Inkjet Driver IC** | ◎ | ◎ | ◎ | △ | — | — | ◎ | ○ | ○ | ○ |
| **Full Code Mechanical Design** | ◎ | ◎ | — | — | — | — | ○ | ○ | △ | △ |

---

### 🏛 Architecture / Governance

| Training Item (Repository) | S1 | S2 | S3 | S4 | S5 | S6 | S7 | S8 | S9 | S10 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| **Samizo-AITL.github.io/portal** | ○ | ○ | ○ | ○ | ○ | ○ | ◎ | — | △ | ○ |
| **AITL Animation Demos** | △ | △ | △ | △ | △ | △ | ○ | — | — | △ |
| **aitl-training** | — | — | — | — | — | — | △ | — | △ | ◎ |

---

## 🧭 How to Use This Matrix (For Companies)

- 🎛 **Control & Safety deployment**  
  Focus on `EduController`, `AITL Controller A-Type`, `AI Control Safety Package`  
  → **S3, S4, S7 must be ◎**

- 🧪 **Physics / device-driven development**  
  Focus on `Edusemi-v4x`, `V–I Control ASIC`  
  → **S1, S2 must be ◎**

- 🧰 **Implementation & EDA flow**  
  Focus on `SemiDevKit`, `openlane2-sram`  
  → **S8 and S9 must be satisfied**

- 🏛 **AITL governance & explanation responsibility**  
  Use `portal` and `aitl-training`  
  → **S7 and S10 must be satisfied**

---

## ⚠️ Explicit Notes (Business Use)

- This matrix is built **exclusively from public repositories**.  
- “Completed reading” is **not sufficient**.  
  ➜ **Competence must be confirmed via S9 (Verification).**  
- If mandatory (◎) competencies are not met,  
  🚫 **deployment to production work is not permitted.**

---

> 🛡 **Note**  
> This document defines **competency coverage and responsibility boundaries**.  
> It does **not** replace role-specific training plans or verification records.

