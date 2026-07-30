# GitHub Operational Best Practices

**Project:** Universal Prompt Architect Pro (UPAP)  
**Document Type:** Operational Guideline  
**Version:** 1.0.0  
**Status:** Production  
**Maintainer:** Repository Owner

---

# Purpose

This document defines the operational standards for maintaining the Universal Prompt Architect Pro GitHub repository.

The objective is to ensure long-term consistency, maintainability, governance compliance, and repository integrity.

---

# Core Principles

The repository shall always follow these principles:

- Canonical Repository First
- Documentation Before Implementation
- Governance Before Modification
- Validation Before Release
- Version Control for Significant Changes
- Non-Destructive Updates
- Single Source of Truth

---

# Repository Maintenance

Before making any repository changes:

- Review the relevant documentation.
- Verify the correct canonical folder.
- Check for duplicate content.
- Confirm governance compliance.
- Ensure the change is necessary.

---

# Document Management

## Creating Documents

Before creating a new document:

1. Search the repository.
2. Verify the information does not already exist.
3. Update existing documentation where appropriate.
4. Create a new document only when necessary.

---

## Canonical Locations

Documents should always remain within their designated canonical folders.

Do not move documents without updating repository documentation and governance references.

---

## Archiving

When replacing documents:

- Move superseded versions into the `Archive/` folder if historical retention is required.
- Remove obsolete files only when approved by repository governance.

---

# Version Control

Maintain version history by:

- Updating `CHANGELOG.md`
- Using meaningful Git commit messages
- Tagging official releases
- Avoiding unnecessary version increments

---

# Documentation Standards

Every document should be:

- Accurate
- Concise
- Consistent
- Well-structured
- Reviewed
- Free from duplicate information

Use:

- Headings
- Numbered sections
- Tables where appropriate
- Clear terminology

---

# Governance Compliance

Before approving repository changes, verify:

- Repository structure remains unchanged unless approved.
- Governance documentation is followed.
- Validation requirements are satisfied.
- Canonical documents remain authoritative.

---

# Knowledge Maintenance

When updating knowledge resources:

- Preserve original meaning.
- Cite authoritative sources where appropriate.
- Avoid mixing unrelated topics.
- Update the repository manifest if structural changes occur.

---

# Runtime Documentation

Changes affecting runtime specifications should:

- Be documented.
- Explain the reason for change.
- Identify affected components.
- Be validated before release.

---

# AI-Assisted Development

When using AI systems:

- Treat repository documentation as the primary source of truth.
- Verify all AI-generated content.
- Reject unsupported or unverifiable information.
- Preserve canonical terminology.
- Avoid restructuring without approval.

AI should assist human review—not replace it.

---

# GitHub Workflow

Use GitHub features appropriately:

- Issues for tracking work
- Pull Requests for review
- Releases for versioning
- Discussions for collaboration
- Projects for planning

Avoid direct commits to the protected default branch whenever possible.

---

# Release Preparation Checklist

Before creating a release:

- Repository structure verified
- Documentation reviewed
- CHANGELOG updated
- Validation completed
- Outstanding critical issues resolved
- Version confirmed
- Release notes prepared

---

# Backup Strategy

Maintain backups of:

- Canonical repository
- Release packages
- Governance documentation
- Validation reports

Backups should be stored separately from the working repository.

---

# Repository Health Review

Perform periodic health checks covering:

- Folder structure
- Documentation consistency
- Outdated documents
- Open issues
- Governance compliance
- Validation status

---

# Change Approval Workflow

```
Identify Need
      │
      ▼
Review Governance
      │
      ▼
Plan Change
      │
      ▼
Implement
      │
      ▼
Validate
      │
      ▼
Update Documentation
      │
      ▼
Update CHANGELOG
      │
      ▼
Release (if applicable)
```

---

# Long-Term Maintenance Policy

The repository shall remain:

- Modular
- Version-controlled
- Documentation-driven
- Governance-led
- Validation-supported
- Easy for humans and AI systems to navigate

---

# Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0.0 | 2026-07-30 | Initial production release. |
