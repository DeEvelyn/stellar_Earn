# Governance Document Archival Policy

## Purpose

This document defines the policy for archiving deprecated or superseded governance documents within the Governance/ folder. This ensures historical context is preserved while keeping the active documentation clear and current.

## Scope

This policy applies to all Markdown files within the Governance/ directory that are part of the official project governance structure.

## Archival Criteria

A governance document should be archived when:

1. It has been explicitly superseded by a new document (e.g., a new Charter or updated Roles definition).
2. It is no longer relevant to current project operations.
3. It is referenced as "historical" or "deprecated" in the active documentation.

## Archival Process

1. **Deprecation Notice**: Before archiving, the active document that replaces the old one must include a link to the archived version in a "History" or "Previous Versions" Section.
2. **Renaming**: The archived file should be renamed with a .archived.md suffix (e.g., Charter.archived.md).
3. **Header Update**: Add a deprecation banner at the top of the archived file:

   ``markdown
   > **Deprecated**: This document has been archived. See [Current Document](./CurrentDocument.md) for the active policy.
  ` ``
4. **Index Update**: Ensure the README.md no longer links to the archived file directly, but may reference it in a historical context if needed.

## Archive Location

Archived files remain in the Governance/ folder but are excluded from active navigation. They are not moved to a separate directory to maintain a single source of truth for governance history.

## Review

Archival changes follow the same governance review process as new documents:
- Scoped to a maximum of two files (the archived file and the README or replacing document.)
- Reviewed and approved by the relevant governance body.
