# OctoAcme — Documentation Guidelines

A short guide for maintaining process and product documentation.

## Owner model & review cadence
- Every document in docs/ must have an owner (person or team).
- Suggested review cadence: quarterly for living process docs, monthly for active-release docs.
- Owners are responsible for keeping metadata current and signposting changes.

## Required metadata (top of file)
- Author: @github-username
- Owner: @team-or-person
- Last-updated: YYYY-MM-DD
- Scope: short description (public/internal)
- Related: links to issue/PR or other docs

## Where to store templates
- Process docs: `docs/`
- Working drafts / Copilot context: `.copilot/`
- Templates and reusable snippets: `docs/templates/` or `.copilot/`

## PR description template for documentation changes
Include in the PR body:
- Summary of change
- Files changed
- Owner and requested reviewers
- Acceptance criteria (what success looks like)
- See: related issue(s) (e.g., See #4)

Example PR description snippet:
```
- Summary: Update roles and add release checklist
- Files: docs/octoacme-roles-and-personas.md, docs/octoacme-release-checklist.md
- Owner: @technical-writer
- Acceptance criteria:
  - All persona sections added
  - Release checklist maps owners
  - Docs placed under docs/
- See #4
```

## Technical Writer responsibilities
- Ensure docs include required metadata and are discoverable
- Coordinate reviews and keep a changelog for major edits
- Produce release notes and onboarding materials
- Mentor other contributors on doc style and PR expectations
- Review documentation PRs for clarity, consistency, and completeness
