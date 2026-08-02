# Knowledge Upload Strategy & File Selection Matrix

**Project:** Universal Prompt Architect Pro (UPAP)

**Version:** v1.0.0 RC1.1

**Status:** Production

---

# 1. Purpose

This document defines which repository assets should be uploaded into Google Gemini Gems and under what conditions.

It converts the repository structure into a standardized operational upload strategy.

---

# 2. Upload Decision Legend

| Status | Meaning |
|----------|---------|
| ✅ Always Upload | Essential for normal Gemini operation |
| 🟡 Upload When Required | Upload only for specific tasks or workflows |
| 🔵 Deployment Only | Upload temporarily during deployment, migration, or validation |
| ❌ Never Upload | Repository-only assets |

---

# 3. Repository Upload Matrix

| Repository Location | Classification | Upload Status | Reason |
|---------------------|---------------|---------------|--------|
| `Universal_Prompt_Architect_Pro/01_Runtime/` | Class A | ✅ Always Upload | Defines runtime behaviour and execution rules. |
| `Universal_Prompt_Architect_Pro/02_Governance/` | Class A | ✅ Always Upload | Provides governance, operational constraints, and engineering policies. |
| `Universal_Prompt_Architect_Pro/03_Behavior/` | Class A | ✅ Always Upload | Controls AI behaviour, response standards, and operational consistency. |
| `Universal_Prompt_Architect_Pro/04_Knowledge/` | Class A | ✅ Always Upload | Contains canonical knowledge used directly by Gemini. |
| `Universal_Prompt_Architect_Pro/05_Deployment/` | Class C | 🔵 Deployment Only | Required only during deployment or migration activities. |
| `Universal_Prompt_Architect_Pro/07_Validation/` | Class B | 🟡 Upload When Required | Used for testing, verification, and acceptance activities. |
| `Universal_Prompt_Architect_Pro/00_Project_Documentation/` | Class B | 🟡 Upload When Required | Reference documentation for contributors and maintainers. |
| `Universal_Prompt_Architect_Pro/06_Release/` | Class E | ❌ Never Upload | Release management information only. |
| `Universal_Prompt_Architect_Pro/Archive/` | Class F | ❌ Never Upload | Historical repository content. |
| `.github/` | Class D | ❌ Never Upload | GitHub administration and workflow automation. |

---

# 4. Root Repository Files

| File | Upload Status | Reason |
|------|---------------|--------|
| `README.md` | 🟡 Upload When Required | Project overview and orientation. |
| `REPOSITORY_MANIFEST.md` | 🟟 Upload When Required | Repository inventory and navigation reference. |
| `CHANGELOG.md` | ❌ Never Upload | Version history only. |
| `LICENSE` | ❌ Never Upload | Legal repository document. |
| `CONTRIBUTING.md` | ❌ Never Upload | Contributor workflow only. |
| `CODE_OF_CONDUCT.md` | ❌ Never Upload | Community governance. |
| `SECURITY.md` | ❌ Never Upload | Repository security guidance. |
| `.gitignore` | ❌ Never Upload | Git repository configuration. |

---

# 5. Recommended Gemini Knowledge Package

For normal Gemini operation, upload only:

- `01_Runtime/`
- `02_Governance/`
- `03_Behavior/`
- `04_Knowledge/`

These directories represent the minimum recommended production knowledge set.

---

# 6. Extended Knowledge Package

When advanced reasoning or project maintenance is required, additionally upload:

- `00_Project_Documentation/`
- `07_Validation/`

This extended package provides supplementary context without introducing repository administration artifacts.

---

# 7. Deployment Package

For deployment, migration, or certification activities, temporarily include:

- `05_Deployment/`

Remove deployment-specific knowledge after the deployment process is complete to maintain a lean operational knowledge base.

---

# 8. Excluded Repository Assets

The following repository areas shall remain outside Gemini knowledge uploads:

- `.github/`
- `06_Release/`
- `Archive/`
- Release history
- GitHub workflow configuration
- Repository administration documents
- Legal and community governance files

These assets support repository management but do not improve Gemini reasoning.

---

# 9. Upload Order

When creating or updating a Gemini Gem, upload repository content in the following order:

1. `01_Runtime/`
2. `02_Governance/`
3. `03_Behavior/`
4. `04_Knowledge/`
5. Optional supporting knowledge
6. Deployment knowledge (only if required)

---

# 10. Maintenance Rules

Whenever the repository is updated:

1. Synchronize the repository.
2. Review affected knowledge assets.
3. Replace outdated uploads.
4. Validate Gemini behaviour.
5. Record the deployment version.
6. Remove temporary deployment knowledge if it was uploaded.

---

# 11. Ownership

Owner:
Project Maintainer

Approval:
Repository Certification

Status:
Production Baseline
