# Agent Compliance Checklist

This checklist defines the mandatory compliance requirements for any
AI or software agent operating within the NGTH & PAPP governance framework.

All agents MUST satisfy every applicable item below before deployment,
integration, or reference in governance workflows.

This document is normative and auditable.

---

## 1. Boundary Compliance (Mandatory)

- [ ] The agent explicitly complies with `AI-BOUNDARIES.md`.
- [ ] The agent is strictly assistive and non-decision-making.
- [ ] The agent does NOT make policy, governance, or executive decisions.
- [ ] The agent does NOT modify KPIs, thresholds, or governance definitions.
- [ ] The agent does NOT close cases or initiate enforcement actions.
- [ ] Final authority is explicitly retained by human actors.

---

## 2. Role Definition Compliance (Mandatory)

- [ ] The agent is mapped to exactly ONE role defined in `AGENT-ROLES.md`.
- [ ] The agent’s purpose matches the declared role.
- [ ] The agent does NOT perform functions outside its declared role.
- [ ] Any role change requires explicit human authorization.
- [ ] The agent does NOT combine multiple governance roles implicitly.

---

## 3. Human-in-the-Loop Compliance (Mandatory)

- [ ] A human counterpart is clearly identified.
- [ ] All agent outputs are intended for human review.
- [ ] The agent does NOT act on outputs without human confirmation.
- [ ] Human override is always possible.
- [ ] The agent does NOT simulate or assume human intent.

---

## 4. Output and Auditability Compliance (Mandatory)

- [ ] All outputs are attributable to a specific agent role.
- [ ] Outputs are reproducible or explainable post hoc.
- [ ] Assumptions and limitations are documented where applicable.
- [ ] Outputs can be reviewed independently of the agent’s implementation.
- [ ] No output is treated as authoritative or final.

---

## 5. Transparency and Non-Opaqueness (Mandatory)

- [ ] The agent does NOT operate as a black box.
- [ ] Inputs, transformations, and outputs are describable at a high level.
- [ ] The agent’s scope and limitations are documented.
- [ ] Automated behavior is observable by human operators.
- [ ] Hidden autonomy or silent escalation paths are prohibited.

---

## 6. Prohibited Capabilities Check (Hard Stop)

An agent MUST NOT be deployed if it exhibits any of the following:

- [ ] Autonomous governance decision-making
- [ ] Policy interpretation without human validation
- [ ] Self-directed role expansion
- [ ] Implicit prioritization or enforcement logic
- [ ] Political, persuasive, or normative content generation
- [ ] Undeclared modification of governance artifacts

---

## 7. Evidence and Documentation Requirements

Before approval, the following MUST be available:

- [ ] Agent description or specification document
- [ ] Declared role reference (`AGENT-ROLES.md`)
- [ ] Boundary compliance statement
- [ ] Description of inputs and outputs
- [ ] Identification of human counterpart
- [ ] Audit or review mechanism description

---

## 8. Approval and Review

- [ ] Compliance checklist completed and signed off by a human reviewer
- [ ] Governance maintainer approval recorded
- [ ] Review date documented
- [ ] Next review or revalidation date defined

---

## Compliance Statement

Any agent that fails to meet ALL mandatory requirements in this checklist
is considered non-compliant and MUST NOT be deployed or referenced
within the NGTH & PAPP governance framework.

Non-compliance constitutes a governance violation, not an implementation error.
