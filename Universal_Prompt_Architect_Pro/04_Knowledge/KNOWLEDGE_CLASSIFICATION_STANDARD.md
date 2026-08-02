# Knowledge Classification Standard

**Project:** Universal Prompt Architect Pro (UPAP)

**Version:** v1.0.0 RC1.1

**Status:** Production

---

# 1. Purpose

This document defines the official classification system used to determine whether repository assets should be uploaded into a Gemini Gem.

Every repository file shall belong to exactly one Knowledge Classification.

---

# 2. Classification Categories

## Class A — Core Runtime Knowledge

Description:

Essential knowledge that directly affects Gemini reasoning and behaviour.

Upload Status:

✅ Always Upload

Examples:

- Runtime rules
- Behaviour specifications
- Canonical prompt assets
- Core knowledge documents

---

## Class B — Supporting Knowledge

Description:

Useful reference material that improves reasoning but is not mandatory.

Upload Status:

🟡 Upload When Required

Examples:

- Reference guides
- Optional documentation
- Extended examples
- Supplemental specifications

---

## Class C — Deployment Knowledge

Description:

Knowledge required only during deployment or configuration.

Upload Status:

🟡 Upload Only During Deployment

Examples:

- Deployment instructions
- Environment setup
- Migration guidance
- Configuration manuals

---

## Class D — Repository Governance

Description:

Repository management documents.

Upload Status:

❌ Never Upload

Examples:

- CONTRIBUTING.md
- CODE_OF_CONDUCT.md
- SECURITY.md
- GitHub workflow documentation

---

## Class E — Release Assets

Description:

Version management documents.

Upload Status:

❌ Never Upload

Examples:

- CHANGELOG
- Release notes
- Version manifests

---

## Class F — Archive

Description:

Historical repository content.

Upload Status:

❌ Never Upload

Examples:

- Legacy documents
- Deprecated specifications
- Archived releases

---

# 3. Classification Rules

Each repository asset shall have only one primary classification.

If uncertainty exists, classify according to the document's primary purpose rather than its filename or location.

---

# 4. Upload Decision Rules

The following priority shall be applied:

1. Class A
2. Class B
3. Class C

Classes D, E, and F are excluded from Gemini knowledge uploads.

---

# 5. Review Requirements

The classification of repository assets shall be reviewed:

- before each major release
- after structural repository changes
- after certification updates

---

# 6. Change Control

Any modification to a file's classification must be documented and approved through the repository governance process.

---

# 7. Ownership

Owner:
Project Maintainer

Approval:
Repository Certification

Status:
Production Baseline
