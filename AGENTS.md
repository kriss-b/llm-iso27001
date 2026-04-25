# AGENTS.md

Read the entire repository before taking any action.

---

## Rules

**Changelog.** Every document ends with a Changelog. When editing a document, bump the version number and add a changelog entry.

**Relative links.** All cross-references between documents use relative markdown links. Update them if files are moved or renamed.

**SoA is the single source of truth for control coverage.** There are two SoAs: `statement_of_applicability.md` (ISO 27001) and `iso42001/statement_of_applicability_iso42001.md` (ISO 42001). Never mark a control as implemented in either without a document to back it up.

**SoA status changes require explicit human approval.** Never update a control status autonomously — propose the change and wait for confirmation.

**No redundancy.** Before creating a new document, check whether the content already exists elsewhere. Extend existing documents rather than creating new ones.

**Git is the audit trail.** Every change to any document must be committed and pushed immediately. Commit messages should describe what changed and why. Never batch unrelated changes into a single commit.

**Template content is a starting point, not ground truth.** All existing content — scope, context, risks, roles, controls — was written for a generic placeholder company. When working with a real company, treat everything as a draft: question it, challenge it, and propose rewording wherever the content doesn't accurately reflect the company's actual situation.
