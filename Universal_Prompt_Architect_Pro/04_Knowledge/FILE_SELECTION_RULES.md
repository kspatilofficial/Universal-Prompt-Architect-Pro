# Repository File Selection Rules

**Project:** Universal Prompt Architect Pro (UPAP)

**Version:** v1.0.0 RC1.1

**Status:** Production

---

# 1. Purpose

This document defines the mandatory rules used to determine whether an individual repository file is eligible for upload into a Google Gemini Gem.

These rules supplement:

- KNOWLEDGE_UPLOAD_POLICY.md
- KNOWLEDGE_CLASSIFICATION_STANDARD.md
- KNOWLEDGE_UPLOAD_MATRIX.md

---

# 2. Guiding Principle

Every uploaded file must contribute directly to Gemini's reasoning, behaviour, or execution quality.

If a file does not improve Gemini performance, it should remain in the repository.

---

# 3. Mandatory Selection Criteria

A file is eligible for upload only if all of the following conditions are met:

- It belongs to an approved repository area.
- It represents the current certified version.
- It is not archived.
- It is not deprecated.
- It is not duplicated elsewhere.
- It contains finalized content.
- It is intended for Gemini reasoning or runtime behaviour.

---

# 4. Files That Must Always Be Uploaded

Upload files that define:

- Runtime behaviour
- AI operating rules
- Governance rules
- Behaviour specifications
- Canonical prompt assets
- Core knowledge documents
- Engineering standards required during normal operation

---

# 5. Files That May Be Uploaded

Upload only when relevant:

- Reference guides
- Technical explanations
- Validation procedures
- Supporting examples
- Project documentation
- Deployment guidance

These files provide additional context but are not required for routine operation.

---

# 6. Files That Must Never Be Uploaded

Do not upload:

- Draft documents
- Temporary notes
- Archived content
- Deprecated files
- GitHub workflow files
- Release notes
- Changelogs
- Licenses
- Community governance documents
- Contributor documentation
- Repository configuration files

---

# 7. Duplicate Content Rule

Only one canonical version of a document may be uploaded.

If multiple files describe the same subject:

- Upload the certified version.
- Exclude superseded or duplicated versions.

---

# 8. Version Rule

Never mix repository versions.

All uploaded files must originate from the same certified repository release.

---

# 9. Naming Rule

Do not rename repository files before upload.

Repository filenames are considered canonical identifiers.

---

# 10. Integrity Rule

Do not edit repository files solely to reduce upload size.

Repository content must remain identical to the certified version.

---

# 11. Review Checklist

Before uploading a file, verify:

- Correct repository version
- Correct folder classification
- File is finalized
- No duplicate exists
- No newer certified version exists
- File improves Gemini reasoning
- File complies with the upload policy

---

# 12. Approval

Every production knowledge upload should be reviewed against this document before deployment.

---

# 13. Ownership

Owner:
Project Maintainer

Approval:
Repository Certification

Status:
Production Baseline
