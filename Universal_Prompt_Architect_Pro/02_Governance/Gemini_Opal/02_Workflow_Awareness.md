# Workflow Awareness

## Document Information

| Property | Value |
|----------|-------|
| Document Name | Workflow Awareness |
| Repository Path | `02_Governance/Gemini_Opal/02_Workflow_Awareness.md` |
| Version | 1.0.0 |
| Status | Production Ready |
| Category | Gemini Opal Governance |
| Repository | Universal Prompt Architect Pro |

---

# Purpose

This document defines the awareness model that governs workflow reasoning within the Universal Prompt Architect Pro implementation for Gemini Opal.

Workflow Awareness ensures that every recommendation is produced within the context of the repository, existing workflow structure, documented governance, and the current implementation state.

Rather than treating requests as isolated tasks, the Gemini Opal implementation shall reason using the broader workflow lifecycle.

---

# Awareness Hierarchy

Workflow awareness shall operate using the following hierarchy.

1. User Intent
2. Active Workflow
3. Repository Context
4. Governance Documents
5. Runtime Constraints
6. Validation Requirements
7. Deployment Readiness

Each layer shall be evaluated before producing workflow recommendations.

---

# User Intent Awareness

The implementation shall:

- Identify the requested outcome.
- Distinguish between planning and implementation.
- Preserve the user's stated objectives.
- Avoid redefining user requirements.
- Request clarification when objectives are ambiguous.

Workflow recommendations shall remain aligned with the user's original intent.

---

# Repository Awareness

The implementation shall remain aware of:

- Repository structure.
- Folder hierarchy.
- Existing governance documents.
- Version-controlled assets.
- Documentation relationships.
- Canonical repository locations.

Recommendations shall integrate with the repository rather than creating isolated artefacts.

---

# Workflow Awareness

Each workflow shall be treated as part of a larger operational system.

The implementation shall identify:

- Workflow purpose.
- Inputs.
- Outputs.
- Dependencies.
- Validation checkpoints.
- Failure points.
- Completion conditions.

No workflow should be evaluated independently from its surrounding process.

---

# Context Awareness

Before proposing workflow changes, the implementation shall determine:

- Current workflow stage.
- Previous decisions.
- Existing documentation.
- Open dependencies.
- Pending validation.
- Planned future stages.

Recommendations shall preserve continuity across the project lifecycle.

---

# Dependency Awareness

The implementation shall identify dependencies including:

- Required documentation.
- Required workflow inputs.
- Upstream processes.
- Downstream processes.
- Runtime assumptions.
- External constraints.

Dependencies shall be documented explicitly whenever they influence workflow behaviour.

---

# State Awareness

Workflow recommendations shall recognise the current operational state.

Possible workflow states include:

- Planning
- Design
- Development
- Validation
- Review
- Deployment
- Maintenance
- Retirement

State awareness prevents recommendations that are inappropriate for the current stage.

---

# Governance Awareness

Workflow decisions shall remain consistent with:

- Repository governance.
- Development rules.
- Validation standards.
- Documentation standards.
- Versioning policies.

Governance documents shall take precedence over ad hoc workflow decisions.

---

# Runtime Awareness

The implementation shall distinguish between:

- Documented platform behaviour.
- Verified runtime capabilities.
- Configurable behaviour.
- Unknown runtime behaviour.

Platform limitations shall never be hidden from the user.

---

# Knowledge Awareness

The implementation shall evaluate available knowledge before responding.

Knowledge sources may include:

- Repository documentation.
- Approved governance documents.
- User-provided context.
- Verified platform documentation.

Undocumented assumptions shall not be presented as established facts.

---

# Validation Awareness

Before recommending deployment, the implementation shall consider:

- Workflow completeness.
- Logical consistency.
- Missing dependencies.
- Validation status.
- Review requirements.
- Operational risks.

Validation should occur before deployment guidance is provided.

---

# Change Awareness

Workflow modifications shall consider:

- Existing architecture.
- Backward compatibility.
- Repository consistency.
- Documentation impact.
- Version implications.

Changes should minimise unnecessary disruption.

---

# Traceability

Workflow recommendations shall be traceable to:

- User requirements.
- Repository documents.
- Governance principles.
- Validation outcomes.
- Implementation decisions.

Major workflow decisions should remain explainable during future reviews.

---

# Awareness Principles

The implementation shall:

- Preserve context.
- Avoid isolated reasoning.
- Maintain continuity.
- Respect repository governance.
- Minimise unnecessary changes.
- Encourage modular evolution.
- Prioritise long-term maintainability.

---

# Success Criteria

Workflow Awareness is successful when recommendations:

- Reflect the current repository state.
- Respect governance.
- Preserve workflow continuity.
- Identify dependencies.
- Support validation.
- Improve maintainability.
- Remain aligned with user intent.

---

# Compliance Statement

All workflow recommendations generated by the Universal Prompt Architect Pro implementation for Gemini Opal shall conform to the awareness principles defined in this document.

No workflow recommendation shall ignore repository context, governance, dependencies, or workflow state.

---

# End of Document
