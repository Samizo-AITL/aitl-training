---
title: "aitl-training"
description: "Education & Training Needs Matrix (AITL – Public Repositories)"
---

# Education & Training Needs Matrix  
**Rows: Training Items (Public Repositories)**  
**Columns: Required Job Competencies / Skills**

**Legend**  
◎ = Mandatory (can take full responsibility independently)  
○ = Important (can perform tasks autonomously)  
△ = Basic understanding  
— = Not applicable  

---

## Competency Definitions (Columns)

| ID | Competency / Skill | Practical Definition (Business Level) |
|---|---|---|
| S1 | Physical Principles | Can explain phenomena causally (incl. V–I characteristics) |
| S2 | Modeling | Can build models with equations / block diagrams and assumptions |
| S3 | Control Theory (PID) | Can design gains with stability & performance justification |
| S4 | State Control (FSM) | Can define states, transitions, and fault states |
| S5 | AI Control (NN/RL) | Can define objectives, metrics, and deviation handling |
| S6 | LLM Utilization | Can restrict LLMs to design support with validation rules |
| S7 | System Integration | Can specify responsibility separation (Control × AI × Safety) |
| S8 | Implementation | Can build reproducible implementations (Python / Git / EDA) |
| S9 | Verification | Can define pass/fail criteria, tests, and logs |
| S10 | Documentation | Can maintain traceability (Req → Design → Verification) |

---

## Training Item × Competency Matrix (Public Repos Only

### Physics / Semiconductor & EDA

| Training Item (Repository) | S1 | S2 | S3 | S4 | S5 | S6 | S7 | S8 | S9 | S10 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| **Edusemi-v4x** | ◎ | ◎ | △ | — | — | — | ○ | △ | ○ | ○ |
| **SemiDevKit** | ○ | ◎ | ○ | — | — | — | ○ | ◎ | ○ | △ |
| **openlane2-sram** | ○ | ◎ | — | — | — | — | △ | ◎ | ○ | △ |
| **Edusemi-Plus** | ○ | ○ | ○ | △ | ○ | ○ | ◎ | △ | ○ | ○ |

### Control / Safety

| Training Item (Repository) | S1 | S2 | S3 | S4 | S5 | S6 | S7 | S8 | S9 | S10 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| **EduController** | △ | ○ | ◎ | ◎ | △ | — | ◎ | ○ | ◎ | ○ |
| **Control Playground** | △ | ○ | ○ | ○ | △ | — | ○ | ◎ | ○ | △ |
| **AITL Controller A-Type** | △ | ○ | ◎ | ◎ | ○ | — | ◎ | ○ | ◎ | ○ |
| **Envelope Control** | △ | ○ | ◎ | ○ | — | — | ◎ | ○ | ○ | △ |
| **Design Recovery Control** | ○ | ◎ | ◎ | ◎ | △ | — | ◎ | ○ | ◎ | ○ |
| **AI Control Safety Package** | — | ○ | ○ | ◎ | ○ | — | ◎ | △ | ◎ | ◎ |
| **V–I Control ASIC** | ◎ | ◎ | ◎ | △ | — | — | ◎ | ○ | ○ | ○ |

### MEMS / Mechanical / Inkjet

| Training Item (Repository) | S1 | S2 | S3 | S4 | S5 | S6 | S7 | S8 | S9 | S10 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| **MEMS pre-FEM Analysis** | ◎ | ◎ | — | — | — | — | ○ | △ | ○ | △ |
| **Inkjet DTS** | ◎ | ◎ | ○ | △ | — | — | ◎ | △ | ○ | ○ |
| **Inkjet Timing** | ◎ | ◎ | ◎ | △ | — | — | ◎ | △ | ○ | ○ |
| **GF180 Inkjet Driver IC** | ◎ | ◎ | ◎ | △ | — | — | ◎ | ○ | ○ | ○ |
| **Full Code Mechanical Design** | ◎ | ◎ | — | — | — | — | ○ | ○ | △ | △ |

### Architecture / Governance

| Training Item (Repository) | S1 | S2 | S3 | S4 | S5 | S6 | S7 | S8 | S9 | S10 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| **Samizo-AITL.github.io/portal** | ○ | ○ | ○ | ○ | ○ | ○ | ◎ | — | △ | ○ |
| **AITL Animation Demos** | △ | △ | △ | △ | △ | △ | ○ | — | — | △ |
| **aitl-training** | — | — | — | — | — | — | △ | — | △ | ◎ |

---

## How to Use This Matrix (For Companies)

- **Control & Safety deployment**  
  → Focus on `EduController`, `AITL Controller A-Type`, `AI Control Safety Package`  
  → Ensure **S3, S4, S7 = ◎**

- **Physics / Device-driven development**  
  → Focus on `Edusemi-v4x`, `V–I Control ASIC`  
  → Ensure **S1, S2 = ◎**

- **Implementation & EDA flow**  
  → Focus on `SemiDevKit`, `openlane2-sram`  
  → Ensure **S8, S9**

- **AITL governance & explanation responsibility**  
  → `portal` + `aitl-training`  
  → Ensure **S7, S10**

---

## Explicit Notes (Business Use)

- This matrix is built **only from public repositories**.
- “Completed reading” is not sufficient.  
  **Competency must be confirmed via S9 (Verification).**
- If mandatory (◎) competencies are not met,  
  **deployment to production work is not allowed.**

---
