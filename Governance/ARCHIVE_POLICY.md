# Governance Document Archival Policy

## Purpose

This document defines the policy for archiving superseded or deprecated governance
documents. The goal is to maintain a clean, navigable documentation structure
while preserving historical context for auditability and reference.

## Scope

This policy applies to all Markdown files within the `Governance/` directory
that are marked as deprecated, superseded, or no longer actively maintained.

## Archival Process

1. **Deprecation**: When a governance document is superseded by a new version,
   the original document should be marked as deprecated. This is typically done
   by adding a deprecation notice at the top of the file and updating the
   `Governance/README.md` to point to the new document.

2. **Archival Location**: Deprecated documents are not deleted. Instead, they
   are moved to the `Governance/archive/` directory. If the directory does not
   exist, it should be created.

3. **Naming Convention**: Archived files should retain their original filename
   but be prefixed with the date of archival in `YYYY-MM-DD-` format to ensure
   chronological ordering and uniqueness. For example:
   `Governance/archive/2023-10-27-old-policy.md`

4. **Link Updates**: The `Governance/README.md` index must be updated to remove
   links to archived documents and ensure that any internal links within other
   active governance documents are updated to point to the current active
   documents.

## Maintenance

- Archival is performed as part of the pull request that introduces the
  superseding document.
- No automated archival is currently in place; this is a manual process
  enforced by code review.
- Archived documents are considered read-only and should not be modified
  unless correcting critical errors in historical record.

## References

- [Governance README](../README.md)
- [Decision-Making Process](./decision-making.md)