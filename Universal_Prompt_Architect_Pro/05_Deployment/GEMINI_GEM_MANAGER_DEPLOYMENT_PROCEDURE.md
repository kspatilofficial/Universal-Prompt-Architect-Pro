# Gemini Gem Manager Deployment Procedure

**Project:** Universal Prompt Architect Pro (UPAP)

**Platform:** Google Gemini Gem Manager

**Module:** 05_Deployment

**Repository Version:** v1.0.0 RC1.1

**Status:** Production

---

# 1. Purpose

This document defines the official deployment procedure for deploying Universal Prompt Architect Pro (UPAP) into Google Gemini Gem Manager.

The objective is to provide a repeatable, repository-first deployment process that preserves governance, knowledge integrity, and version consistency.

---

# 2. Scope

This procedure applies only to:

- Google Gemini Gem Manager
- Production Gem deployments
- Certified repository versions

Gemini Opal deployments are documented separately.

---

# 3. Prerequisites

Before deployment, confirm:

- Repository certification completed.
- Repository version confirmed.
- Validation completed.
- Acceptance Testing completed.
- Deployment package prepared.
- Knowledge package prepared.
- Production System Prompt available.

Deployment shall not begin until all prerequisites are satisfied.

---

# 4. Deployment Inputs

Required deployment assets include:

- Certified repository
- Production System Prompt
- Approved Knowledge Package
- Deployment documentation
- Validation records
- Repository version information

---

# 5. Repository Verification

Before opening Gemini Gem Manager:

Verify:

- Repository version
- Certification version
- Module completeness
- Documentation synchronization
- Knowledge package version

Only certified repository assets shall be used.

---

# 6. Knowledge Package Preparation

Prepare the knowledge package according to the Knowledge Upload Strategy.

Include only approved knowledge assets.

Do not include:

- Archive
- Release history
- GitHub administration files
- Temporary documentation
- Draft documents

---

# 7. Gem Configuration

Configure the Gem using:

## Name

Use the approved repository naming convention.

---

## Description

Use the repository-approved production description.

---

## System Prompt

Use the certified Production System Prompt.

Do not modify the prompt during deployment.

---

## Knowledge

Upload only the approved knowledge package.

Maintain the approved upload sequence.

---

# 8. Recommended Upload Order

Upload repository knowledge in the following order:

1. Runtime
2. Governance
3. Behavior
4. Knowledge
5. Optional supporting documentation
6. Deployment documentation (only if required)

This order preserves logical dependency relationships.

---

# 9. Post-Deployment Validation

Immediately after deployment, verify:

- System Prompt loaded correctly.
- Knowledge uploaded successfully.
- Repository version matches deployment.
- Responses follow governance.
- Runtime behaviour is correct.
- Knowledge is accessible.
- No deployment warnings remain.

---

# 10. Deployment Completion Checklist

Confirm:

- Deployment successful.
- Validation successful.
- Repository version recorded.
- Knowledge package version recorded.
- Deployment date recorded.
- Operator recorded.
- Deployment status updated.

---

# 11. Deployment Restrictions

During deployment:

- Do not edit repository documents.
- Do not modify the System Prompt.
- Do not upload uncertified knowledge.
- Do not mix repository versions.
- Do not bypass validation.

---

# 12. Relationship to Other Modules

This deployment procedure depends on:

- Deployment Policy & Strategy
- Governance Module
- Knowledge Module
- Validation Module

All deployment activities shall comply with these modules.

---

# 13. Ownership

Owner:
Project Maintainer

Approval:
Repository Certification

Status:
Production Baseline
