# Knowledge Refresh & Synchronization Procedure

**Project:** Universal Prompt Architect Pro (UPAP)

**Version:** v1.0.0 RC1.1

**Status:** Production

---

# 1. Purpose

This document defines the official procedure for synchronizing Gemini knowledge with the certified GitHub repository.

Its objectives are to:

- Maintain consistency between the repository and deployed Gemini Gems.
- Prevent outdated knowledge from remaining active.
- Ensure reproducible deployments.
- Support repository certification and release management.

---

# 2. Synchronization Principle

The GitHub repository is the canonical source of truth.

Gemini knowledge is a deployed copy of selected repository content.

Repository changes must always occur before Gemini knowledge updates.

---

# 3. When Synchronization Is Required

Perform a knowledge synchronization whenever one of the following occurs:

- A new certified repository release.
- A Runtime document is modified.
- A Governance document is modified.
- A Behavior document is modified.
- A Core Knowledge document is modified.
- A deployment package is updated.
- A validation process identifies outdated knowledge.

---

# 4. Standard Synchronization Workflow

Follow this sequence:

1. Confirm the certified repository version.
2. Review the release notes and repository changes.
3. Identify affected knowledge assets.
4. Remove outdated knowledge from Gemini.
5. Upload the latest approved files.
6. Validate Gemini behaviour.
7. Record the deployed repository version.
8. Archive deployment records if required.

---

# 5. Version Consistency Rule

A Gemini deployment shall reference only one certified repository version.

Mixing files from different repository releases is prohibited.

---

# 6. Knowledge Replacement Rule

Whenever a knowledge file is updated:

- Replace the previous version.
- Do not retain duplicate copies.
- Do not upload multiple revisions of the same document.

Only the latest certified version shall remain active.

---

# 7. Validation After Synchronization

After every synchronization, verify that Gemini:

- follows the current runtime rules,
- applies the latest governance policies,
- follows updated behaviour specifications,
- references the correct repository version,
- produces consistent responses.

---

# 8. Rollback Procedure

If synchronization introduces unexpected behaviour:

1. Stop using the updated deployment.
2. Restore the previous certified knowledge package.
3. Revalidate Gemini behaviour.
4. Investigate repository changes.
5. Repeat synchronization after corrective action.

---

# 9. Synchronization Log

Each synchronization should record:

- Repository version
- Synchronization date
- Operator
- Knowledge package used
- Validation outcome
- Deployment status

This log provides traceability for future maintenance.

---

# 10. Periodic Review

Review Gemini knowledge periodically even if no repository release has occurred.

Recommended review events include:

- Before major deployments.
- After certification updates.
- During scheduled repository audits.

---

# 11. Ownership

Owner:
Project Maintainer

Approval:
Repository Certification

Status:
Production Baseline
