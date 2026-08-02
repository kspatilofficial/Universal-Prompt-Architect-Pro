# Knowledge Upload Policy

**Project:** Universal Prompt Architect Pro (UPAP)

**Version:** v1.0.0 RC1.1

**Status:** Production

---

# 1. Purpose

This document defines the official policy governing which repository assets may be uploaded into Google Gemini Gems and which assets must remain within the GitHub repository.

The objectives are to:

- Preserve repository integrity.
- Prevent unnecessary context consumption.
- Reduce token usage.
- Improve Gemini response quality.
- Keep deployment modular and maintainable.

---

# 2. Scope

This policy applies to:

- Gemini Gem Manager
- Gemini Opal
- Future Gemini runtime variants
- Repository maintainers
- Contributors
- Deployment operators

---

# 3. Repository First Principle

The GitHub repository is the canonical source of truth.

Knowledge uploaded into Gemini is a curated subset of the repository and must never replace the repository itself.

Repository updates must always occur before any Gemini knowledge refresh.

---

# 4. Knowledge Categories

Repository content is divided into the following categories:

1. Runtime Knowledge
2. Governance
3. Behaviour
4. Prompt Assets
5. Documentation
6. Validation
7. Deployment
8. Release Assets
9. Archive

Each category has different upload requirements.

---

# 5. Upload Principles

Only upload files that improve Gemini reasoning or runtime behaviour.

Do not upload files that are intended only for:

- GitHub management
- release history
- repository administration
- archival purposes
- contributor workflows

---

# 6. Context Efficiency

Gemini has finite knowledge capacity.

Only high-value documents should be uploaded.

Avoid duplicate information.

Avoid redundant versions of the same document.

Prefer canonical documents over derivative documents.

---

# 7. Version Synchronization

Knowledge uploads must always match the certified repository release.

Mixing files from different repository versions is prohibited.

---

# 8. Change Management

Whenever a repository release modifies uploaded knowledge:

1. Update the repository.
2. Review upload eligibility.
3. Replace outdated knowledge.
4. Validate Gemini behaviour.
5. Record deployment version.

---

# 9. Compliance

All deployments must comply with this policy.

Exceptions should be documented within the deployment records.

---

# 10. Document Ownership

Owner:
Project Maintainer

Approval:
Repository Certification

Status:
Production Baseline
