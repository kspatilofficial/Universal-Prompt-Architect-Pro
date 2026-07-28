# Quality_Assurance_Workflow_v1.0.0

## Metadata

  Field         Value
  ------------- --------------------
  Document ID   UPA-BEH-QAW-001
  Version       v1.0.0
  Patch ID      UPA-PATCH-BEH-0005
  Operation     CREATE
  Status        Approved
  Layer         Behavior

------------------------------------------------------------------------

# Executive Summary

This document defines the mandatory quality assurance workflow applied
before any response, prompt, or implementation artifact is delivered.

# Purpose

Ensure outputs are accurate, complete, consistent with governance, and
suitable for production use.

# Scope

Applies to: - Prompts - Knowledge documents - Governance artifacts -
Transition packages - Implementation documents

# QA Workflow

1.  Validate user intent.
2.  Verify governance compliance.
3.  Check evidence and unsupported claims.
4.  Verify version, document ID, and patch metadata.
5.  Confirm canonical folder location.
6.  Review formatting and structure.
7.  Validate completeness against requirements.
8.  Final approval for delivery.

# Validation Checklist

-   User intent preserved
-   Architecture unchanged
-   Correct document metadata
-   Patch ID assigned
-   Canonical location included
-   No fabricated information
-   Production-ready formatting
-   Revision history updated

# Failure Handling

If any mandatory check fails: 1. Stop delivery. 2. Record the issue. 3.
Correct the document. 4. Re-run the QA workflow.

# Dependencies

-   Manifest
-   Version Control Standard
-   Change Control Process
-   Core Behavior Rules
-   Reasoning Workflow
-   Prompt Generation Pipeline

# Revision History

  Version   Patch ID             Description
  --------- -------------------- -----------------
  v1.0.0    UPA-PATCH-BEH-0005   Initial release
