# Production Master Prompt Blueprint

## Document Information

| Property | Value |
|----------|-------|
| Document Name | Production Master Prompt Blueprint |
| Repository Path | `02_Governance/Gemini_Opal/09A_Production_Master_Prompt_Blueprint.md` |
| Version | 1.0.0 |
| Status | Production Ready |
| Category | Gemini Opal Governance |
| Repository | Universal Prompt Architect Pro |

---

# Purpose

This document defines the architectural blueprint for the Universal Prompt Architect Pro Production Master Prompt targeting Gemini Opal.

Unlike the Production Master Prompt itself, this blueprint specifies the structure, organisation, instruction hierarchy, integration model, and governance mapping that shall be followed when constructing the final production prompt.

This blueprint is intended for repository maintenance and future prompt evolution.

---

# Objectives

The blueprint shall:

- Standardise prompt architecture.
- Preserve repository governance.
- Support long-term maintenance.
- Enable modular updates.
- Reduce prompt duplication.
- Improve prompt readability.
- Support future repository expansion.

---

# Blueprint Principles

The production prompt shall follow these principles:

- Governance First
- Repository First
- Workflow First
- Validation First
- Transparency First
- Modularity First
- Maintainability First

Every instruction included within the production prompt shall align with these principles.

---

# Prompt Architecture

The production prompt shall be organised into independent logical layers.

Layer 1

System Identity

↓

Layer 2

Mission

↓

Layer 3

Repository Awareness

↓

Layer 4

Workflow Awareness

↓

Layer 5

Reasoning Framework

↓

Layer 6

Runtime Governance

↓

Layer 7

Workflow Execution

↓

Layer 8

Validation Framework

↓

Layer 9

Communication Standards

↓

Layer 10

Completion Behaviour

Each layer shall remain independently maintainable.

---

# Instruction Hierarchy

Instruction precedence shall follow this order.

1. System Identity
2. Repository Governance
3. User Intent
4. Workflow Context
5. Runtime Constraints
6. Validation Rules
7. Communication Standards
8. Output Formatting

Lower-priority instructions shall never override higher-priority governance.

---

# Repository Mapping

Each prompt section shall correspond to one governance document.

| Prompt Section | Repository Source |
|----------------|-------------------|
| System Identity | 01_System_Identity.md |
| Workflow Awareness | 02_Workflow_Awareness.md |
| Runtime Governance | 03_Runtime_and_Node_Governance.md |
| Reasoning Framework | 04_Workflow_Reasoning_Framework.md |
| Validation | 05_Validation_and_QA.md |
| Communication | 06_Communication_and_Output_Standards.md |
| Operational Workflow | 07_Operational_Workflow.md |
| Runtime Layer | 08_Opal_Runtime_and_Execution_Layer.md |

The production prompt should reference repository concepts rather than duplicate repository documentation wherever practical.

---

# Prompt Composition

The production prompt shall contain:

- Identity definition
- Mission statement
- Operating principles
- Workflow awareness
- Repository awareness
- Reasoning rules
- Runtime governance
- Workflow execution guidance
- Validation requirements
- Communication standards
- Completion rules

Each section shall remain modular.

---

# Modular Design

Prompt sections should be replaceable without requiring a complete rewrite.

Each module shall:

- Have one responsibility.
- Avoid duplicated guidance.
- Minimise cross-dependencies.
- Support future revisions.

---

# Workflow Integration

The production prompt shall integrate with the operational workflow defined by the repository.

Supported stages include:

- Planning
- Analysis
- Design
- Validation
- Documentation
- Repository Integration
- Deployment Preparation

The prompt shall encourage progression through these stages without enforcing unsupported platform behaviour.

---

# Governance Integration

The prompt shall consistently enforce:

- Repository standards.
- Documentation standards.
- Versioning policies.
- Validation requirements.
- Workflow governance.

Governance instructions shall remain consistent across prompt revisions.

---

# Runtime Integration

The production prompt shall remain independent of undocumented runtime internals.

It shall define:

- Expected behaviour.
- Workflow coordination principles.
- Execution philosophy.
- Validation responsibilities.

It shall not define undocumented platform implementation details.

---

# Validation Integration

Every workflow generated under the production prompt shall encourage:

- Requirement validation.
- Design validation.
- Repository validation.
- Documentation review.
- Governance verification.

Validation shall be integrated throughout the workflow lifecycle.

---

# Communication Integration

The production prompt shall require responses to remain:

- Structured.
- Transparent.
- Repository-aware.
- Technically accurate.
- Governance-compliant.

Communication shall clearly distinguish:

- Verified information
- Recommendations
- Assumptions
- Unknowns

---

# Output Architecture

Where appropriate, responses should follow the following logical structure.

1. Objective
2. Context
3. Analysis
4. Recommendation
5. Validation Considerations
6. Repository Impact
7. Next Steps

Alternative structures may be used when they better support the user's objective.

---

# Maintainability Strategy

The production prompt shall support:

- Incremental improvements.
- Independent module updates.
- Repository synchronisation.
- Version-controlled revisions.
- Future governance expansion.

The architecture should minimise maintenance effort over time.

---

# Versioning Strategy

Changes to the production prompt should be classified as:

## Patch

Minor wording improvements.

---

## Minor

Additional governance modules.

---

## Major

Structural architecture changes affecting prompt behaviour.

Version history should remain traceable within the repository.

---

# Blueprint Constraints

The blueprint shall not:

- Define undocumented Gemini Opal implementation details.
- Duplicate repository governance unnecessarily.
- Introduce conflicting instructions.
- Reduce modularity.
- Override repository policies.

---

# Success Criteria

The blueprint is successful when the Production Master Prompt is:

- Modular.
- Repository-aware.
- Governance-compliant.
- Easy to maintain.
- Easy to extend.
- Consistent.
- Traceable.
- Suitable for long-term evolution.

---

# Compliance Statement

This blueprint establishes the canonical architecture for the Universal Prompt Architect Pro Production Master Prompt targeting Gemini Opal.

All future revisions of the Production Master Prompt shall remain consistent with this architectural blueprint unless a documented repository governance decision explicitly approves a structural change.

---

# End of Document
