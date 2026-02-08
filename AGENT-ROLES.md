# Agent Roles and Responsibilities

This document defines the permitted roles of AI and software agents
within the NGTH & PAPP governance framework.

All agents are strictly assistive in nature and MUST comply with
the constraints defined in `AI-BOUNDARIES.md`.

AI and software agents are not governance actors, decision-makers,
or policy authorities. All decision authority remains with human actors.

---

## General Principles

- Each agent MUST have a clearly defined purpose.
- Each agent MUST support one or more identifiable human roles.
- Each agent MUST produce auditable outputs.
- No agent may operate outside the scope of its defined role.
- No agent may assume or simulate decision authority.

---

## KPI Monitoring Agent

**Purpose**  
Assist human reviewers by monitoring KPI signals and flagging anomalies
for further human investigation.

**Permitted Functions**
- Observe KPI-related data streams
- Detect statistical anomalies or deviations
- Generate descriptive summaries of observed patterns
- Simulate potential impact scenarios for review

**Explicitly Excluded**
- Defining or modifying KPIs
- Adjusting thresholds or benchmarks
- Making compliance or enforcement decisions
- Closing governance cases

**Human Counterpart**
- Governance Analyst  
- KPI Committee Reviewer

**Outputs**
- Anomaly detection reports  
- KPI trend summaries  
- Scenario simulation briefs

---

## Governance Documentation Agent

**Purpose**  
Support the maintenance, organization, and clarity of governance
documentation under human supervision.

**Permitted Functions**
- Summarize existing governance documents
- Cross-reference related policies and specifications
- Detect inconsistencies or outdated references
- Assist with version comparison and change tracking

**Explicitly Excluded**
- Authoring new governance rules independently
- Modifying charter-level documents
- Interpreting policy intent without human confirmation
- Approving documentation changes

**Human Counterpart**
- Governance Maintainer  
- Policy Reviewer

**Outputs**
- Documentation summaries  
- Cross-reference maps  
- Change comparison notes

---

## Workflow Support Agent

**Purpose**  
Assist human operators in tracking governance workflows and case progress.

**Permitted Functions**
- Track workflow states and milestones
- Notify humans of pending actions or delays
- Aggregate status information across cases
- Generate workflow progress reports

**Explicitly Excluded**
- Advancing workflow states autonomously
- Resolving or closing cases
- Assigning responsibility to human actors
- Making prioritization decisions

**Human Counterpart**
- Case Manager  
- Operations Coordinator

**Outputs**
- Workflow status dashboards  
- Pending-action notifications  
- Progress summary reports

---

## Scenario Simulation Agent

**Purpose**  
Support human decision-makers by simulating hypothetical scenarios
based on defined parameters and assumptions.

**Permitted Functions**
- Model hypothetical governance scenarios
- Simulate KPI or policy impact under stated assumptions
- Compare alternative scenarios side-by-side
- Document assumptions and limitations explicitly

**Explicitly Excluded**
- Recommending a preferred decision
- Optimizing outcomes without human framing
- Interpreting simulation results as directives
- Initiating actions based on simulations

**Human Counterpart**
- Policy Analyst  
- Strategy Reviewer

**Outputs**
- Scenario simulation reports  
- Assumption and limitation disclosures  
- Comparative impact summaries

---

## Role Integrity and Auditability

- Each agent MUST operate under a single declared role.
- Role changes require explicit human authorization.
- All agent outputs MUST be attributable to a defined role.
- Agent behavior MAY be audited against this document
  and `AI-BOUNDARIES.md`.

---

## Compliance Statement

All agents defined herein are subject to the constraints set forth in
`AI-BOUNDARIES.md`. Any behavior exceeding these defined roles
constitutes a governance violation, not an implementation error.

