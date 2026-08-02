# Markdown Documentation Standard

**Project:** Universal Prompt Architect Pro (UPAP)

**Module:** 00_Project_Documentation

**Repository Version:** v1.0.0 RC1

**Repository Certification:** RC1.1

**Status:** Production

---

# 1. Purpose

This document defines the official Markdown documentation standard for Universal Prompt Architect Pro (UPAP).

Its purpose is to ensure that repository documentation remains:

- Consistent
- Readable
- Maintainable
- Searchable
- GitHub-friendly
- Suitable for long-term engineering maintenance

---

# 2. Scope

This standard applies to:

- All Markdown (*.md) files
- New documentation
- Existing documentation undergoing modification
- Repository indexes
- Governance documentation
- Knowledge documentation
- Deployment documentation
- Validation documentation
- Release documentation

---

# 3. Standard Document Structure

Every standalone Markdown document should follow this structure:

```markdown
# Document Title

**Project:** Universal Prompt Architect Pro (UPAP)

**Module:**

**Repository Version:**

**Repository Certification:**

**Status:**

---

# Purpose

...

---

# Main Content

...

---

# Related Documentation

...

---

# Ownership

...
```

---

# 4. H1 Heading Policy

## Standalone Documents

Every standalone document shall contain exactly one primary H1 heading.

Example:

```markdown
# Prompt Version Manifest
```

---

## Exceptions

The following files may intentionally omit an H1 heading:

- Markdown include files
- Generated fragments
- Embedded documentation
- Template snippets
- Documentation partials

These files shall be clearly identified within their parent document or generation process.

---

# 5. Heading Hierarchy

Recommended hierarchy:

```
# H1

## H2

### H3

#### H4 (only when necessary)
```

Avoid heading levels deeper than H4 unless there is a compelling reason.

---

# 6. Metadata Standard

Standalone documents should include:

- Project
- Module
- Repository Version
- Repository Certification
- Status

Metadata should appear immediately below the H1 heading.

---

# 7. File Naming Standard

Markdown filenames should:

- Use uppercase words separated by underscores.
- Be descriptive.
- Avoid abbreviations unless they are established project terminology.
- Remain stable after certification.

Example:

```
PROMPT_VERSION_MANIFEST.md
```

---

# 8. Cross-Reference Standard

When referencing another repository document:

- Use the exact filename.
- Avoid abbreviated names.
- Avoid outdated filenames.
- Update references whenever documents are renamed.

---

# 9. Review Checklist

Before approving documentation:

- [ ] H1 heading present (unless exception applies)
- [ ] Metadata complete
- [ ] Heading hierarchy consistent
- [ ] Cross-references verified
- [ ] Repository version current
- [ ] Certification current
- [ ] Related documentation updated

---

# 10. Related Documentation

This standard supplements:

- PROMPT_DOCUMENTATION_AND_FILE_STANDARDS.md
- VERSION_MANIFEST.md
- GEM_DEVELOPMENT_GOVERNANCE_POLICY.md
- VERSIONING_AND_CHANGE_MANAGEMENT_RULES.md

---

# 11. Ownership

Owner:

Project Maintainer

Approval:

Repository Certification Authority

Status:

Production Baseline
