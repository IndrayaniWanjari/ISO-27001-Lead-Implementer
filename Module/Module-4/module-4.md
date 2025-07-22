# Module 04 – The Do Phase

> **Summary**: This module focuses on translating planning into action by implementing controls, policies, and processes defined in the Risk Treatment Plan. It emphasizes operational execution of the ISMS in line with ISO/IEC 27001:2022 requirements.

---

## Overview of the Module

The "Do" phase in the PDCA (Plan-Do-Check-Act) cycle is where the Information Security Management System (ISMS) begins to operate. This involves the execution of controls identified in the planning phase and ensuring that day-to-day processes reflect the security expectations set forth in the Statement of Applicability (SoA) and Risk Treatment Plan (RTP).

---

## Clauses Covered

---

### Clause 6.1.3 – Risk Treatment Plan

#### Purpose

This clause requires organizations to develop a structured plan for how they will treat identified risks. The Risk Treatment Plan (RTP) serves as a bridge between risk assessment and control implementation.

#### Key Requirements

- List all selected controls from the SoA
- Define responsibilities, timelines, and resource needs
- Map each control to the risk it addresses
- Obtain approval from top management or the risk owner

#### Mandatory Documents

- Documented **Risk Treatment Plan**
- Updated **Statement of Applicability (SoA)** reflecting selected controls

#### Example

| Control                       | Related Risk                               | Responsible Person | Deadline | Resources                           | Follow-up              |
| ----------------------------- | ------------------------------------------ | ------------------ | -------- | ----------------------------------- | ---------------------- |
| Document cryptographic policy | Data leakage through unencrypted transfers | Security Officer   | 30 days  | Policy template, stakeholder review | Monthly review of logs |

#### Reflection

> "A well-documented RTP avoids future misunderstandings and drives accountability across the organization."

---

### Clause 8.1 – Operational Planning and Control

#### Purpose

This clause ensures that the ISMS is embedded into the operational routines of the organization and adapts to changes over time.

#### Key Requirements

- Use the ISMS daily, not just for audits
- Assign document owners for regular review
- Ensure updates are made when processes or risks change
- Monitor and adapt to outsourced operations

#### Mandatory Documents

- None explicitly required  
  🔹 **However, best practices recommend:**
  - **Document control procedures**
  - **Outsourcing policy or supplier management guidelines**
  - **Operational process documentation**

#### Managing Outsourced Operations

Outsourcing (e.g., recruitment, IT support) must still comply with ISMS policies. Organizations must:

1. Define outsourcing procedures internally
2. Communicate security expectations to suppliers
3. Include security clauses in contracts (Annex A reference)

#### Change Management

Changes to systems or services must be:

- Planned and assessed for security impact
- Documented even if informal (best practice)
- Evaluated for compatibility and data integrity

#### Example

> A company migrating from one cloud storage provider to another must review compatibility, ensure no data loss, and assign a project team to manage the transition.

#### Reflection

> "The ISMS must be a living system — adapting to new risks, tools, and business changes."

---

### Clause 8.2 – Information Security Risk Assessment (Review)

#### Purpose

Reassess risk periodically or when major changes occur to ensure the ISMS remains relevant and risk-aware.

#### Key Requirements

- Conduct risk assessment at planned intervals
- Reassess after significant operational changes
- Update and version risk records accordingly

#### Mandatory Documents

- Updated **Risk Assessment Report**
- Version-controlled **Risk Register**

#### Example

> After integrating a new HR platform, reassess privacy-related risks and update mitigation strategies.

#### Reflection

> "Periodic reassessment is a reminder that no control is permanent — risk is always evolving."

---

### Clause 8.3 – Information Security Risk Treatment (Implementation)

#### Purpose

To take action based on the Risk Treatment Plan — putting selected controls into operation.

#### Key Requirements

- Implement each selected control from the RTP
- Ensure policies are communicated and understood
- Monitor implementation results

#### Mandatory Documents

- Records of **implemented controls** (can be tracked in the SoA or via internal audit checklists)
- Optional: Control testing results, evidence of awareness/training

#### Example

> To implement an access control policy, a company rolls out two-factor authentication, updates SOPs, and trains employees on the new process.

#### Reflection

> "Implementation is where intent meets reality — it’s not what you planned, it’s what you did."

---

## Documented Outputs

- Risk Treatment Plan (Clause 6.1.3)
- Statement of Applicability
- Risk Assessment Review Records
- Change Management Logs
- Supplier Communication Records (if outsourced)
- Control Implementation Evidence

---

## Key Takeaways

- The Do phase operationalizes the ISMS — planning ends, execution begins
- Documentation and accountability are critical for implementation
- Risk and control environments must evolve together

---

## References

- ISO/IEC 27001:2022
  - Clause 6.1.3 – Risk Treatment Plan
  - Clause 8.1 – Operational Planning and Control
  - Clause 8.2 – Risk Assessment Review
  - Clause 8.3 – Risk Treatment Implementation
- Advisera Course – Module 04: The Do Phase
