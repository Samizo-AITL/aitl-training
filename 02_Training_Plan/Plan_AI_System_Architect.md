# Training Plan: AI System Architect (AITL)

This document defines the **role-based training plan** for **AI System Architects**
working with systems based on **AITL (Architecture for Integrated Technology Logic)**.

This plan is aligned with **ISO 9001 Clause 7.2 (Competence)** and is specifically designed
to ensure that AI technologies are applied **without violating control authority,
design responsibility, or accountability**.

---

## 1. Role Definition

An **AI System Architect** under AITL is responsible for:

- Designing how AI technologies are integrated into engineering systems
- Defining **where AI may assist and where it is explicitly prohibited**
- Ensuring AI usage does not obscure responsibility or decision ownership
- Supporting engineers through analysis, review, and design-time assistance

This role **does not own real-time behavior** and **does not make final design decisions**.

---

## 2. Training Objectives

After completing this training, an AI System Architect shall be able to:

- Explain AITL responsibility separation without ambiguity
- Clearly distinguish **design-time intelligence** from real-time control
- Identify prohibited AI use cases in control and safety-critical systems
- Design AI workflows that preserve human accountability
- Communicate AI limitations to engineers and management

---

## 3. Required Training Layers

AI System Architects must complete training in the following AITL layers.

### Layer 1: Physical and System Constraints

Required competence:
- Understand physical constraints that AI cannot override
- Recognize where abstraction hides critical physical assumptions
- Explain why AI cannot compensate for missing physics

---

### Layer 2: Models and Control Foundations

Required competence:
- Understand the role of control models and PID-based control
- Explain why AI is not a replacement for real-time control
- Recognize risks of AI-driven control substitution

Key rule:
- AI **shall not** replace control models or control logic

---

### Layer 3: Supervisory Control and State Management

Required competence:
- Understand FSM-based supervision
- Explain how supervision governs permission for adaptation
- Recognize escalation paths when assumptions break

Key rule:
- AI operates **under supervision**, never as a supervisor of control authority

---

### Layer 4: Adaptive Assistance (Bounded)

Required competence:
- Understand NN / RL as bounded adaptive assist mechanisms
- Identify explicit safety and responsibility bounds
- Recognize failure modes caused by uncontrolled adaptation

Key rule:
- AI adaptation is **conditional, bounded, and revocable**

---

### Layer 5: Design-Time Intelligence (LLM)

Required competence:
- Design workflows where LLMs support analysis and review
- Ensure LLM usage is strictly **non-real-time**
- Treat LLM outputs as **non-authoritative reference material**

Key rule:
- LLMs assist engineers; they do not decide for them

---

### Layer 6: Boundary Confirmation and Design Recovery

Required competence:
- Identify when AI-assisted assumptions are invalid
- Support escalation to design recovery processes
- Participate in corrective action and improvement activities

---

## 4. Prohibited AI Use Cases

AI System Architects must be able to clearly identify and prevent:

- Use of LLMs in real-time control loops
- Autonomous AI decision-making without human accountability
- Replacement of PID or FSM logic with AI models
- AI systems that obscure responsibility attribution
- AI-generated outputs used without verification

---

## 5. Learning Materials

Training materials shall be selected from the **Samizo-AITL main repositories**,
including:

- AITL architecture documentation
- Control and supervisory architecture explanations
- Design recovery and legacy case studies
- AI safety and responsibility discussions

This training plan does **not** promote AI-first or tool-driven design.

---

## 6. Verification Criteria

Competence verification shall confirm that the AI System Architect can:

- Explain AI’s permitted and prohibited roles under AITL
- Design AI workflows that preserve responsibility boundaries
- Identify unsafe or misleading AI integration patterns
- Communicate AI limitations clearly to non-AI engineers

Verification methods may include:
- Scenario analysis
- Architecture explanation
- Checklist-based assessment
- Design review discussion

---

## 7. Training Records

Completion of this training shall be recorded using:

- Templates defined in `03_Training_Record`

Records must indicate:
- Training layers completed
- Verification outcome
- Verifier identity

---

## 8. Completion Criteria

An AI System Architect is considered trained under AITL when:

- All required layers are completed
- Verification criteria are satisfied
- Responsibility boundaries are explicitly acknowledged

---

## 9. Summary

This training plan ensures that AI System Architects:

- Integrate AI **without displacing engineering judgment**
- Preserve accountability and safety
- Support, rather than replace, human decision-making

Under AITL, AI is a **design-time assistant**, not a decision authority.
