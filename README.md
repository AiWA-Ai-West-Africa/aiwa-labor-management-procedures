# AIWA Labor Management Procedures (LMP)

Machine-readable Labor Management Procedures for AI West Africa (AIWA), authored in Markdown and version-controlled in GitHub.

## Repository Structure

- `lmp/` - Primary LMP source documents in Markdown
- `docs/` - Reference documents (to be added over time)
- `.github/workflows/` - Automation for document generation

## Authoring Model

1. Write and update the LMP in Markdown (`.md`)
2. Commit and collaborate through normal GitHub workflows
3. On every push to `main` and on pull requests, GitHub Actions generates:
   - PDF (`.pdf`)
   - Word (`.docx`) for Google Workspace compatibility

Generated files are attached as workflow artifacts in GitHub Actions.
