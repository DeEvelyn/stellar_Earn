## Governance Document Archival Policy

### Purpose
This document defines the policy for archiving superseded or deprecated governance documents to maintain clarity and prevent confusion while preserving historical context.

### Archival Criteria
A governance document should be archived when:
1. It has been explicitly superseded by a new document.
2. It is no longer relevant to current project operations.
3. It is referenced as "deprecated" in the parent document.

### Archival Process
1. **Deprecation Notice**: The document must be marked as deprecated in its header with a link to the replacement document.
2. **Renaming**: Rename the file by prepending `ARCHIVED_` to the filename (e.g., `ARCHIVED_OLD_POLICY.md`).
3. **Index Update**: Update the `README.md` to remove the link to the active document and optionally add a note in an "Archived Documents" section if necessary.

### Archive Location
Archived documents remain in the `Governance/` folder but are prefixed with `ARCHIVED_`. They are not moved to a separate directory to maintain a single source of truth for governance history.

### Maintenance
- Regular reviews should be conducted to identify documents eligible for archival.
- Archived documents must not be deleted; they serve as a historical record.