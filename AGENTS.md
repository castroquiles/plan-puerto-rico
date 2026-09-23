# Instructions for AI Agents

Scope: this repo develops proposals for an AI-driven Puerto Rico / LATAM
economic bridge strategy. It is a policy and strategy design space, not a
software project — treat factual accuracy and sourcing as the primary
quality bar, not code style.

## What agents may do
- Open issues and pull requests
- Draft or revise files under `proposals/` using `proposals/TEMPLATE.md`
- Suggest edits to `docs/` with tracked changes and a stated rationale
- Comment on existing issues/PRs with analysis, critique, or sourced counter-evidence

## What agents may NOT do
- Merge any pull request
- State a fact about a real organization, law, program, or person without a
  citation in the `sources:` field of the proposal
- Assert partnership, endorsement, or authorization by any named third party
  (GENIA Americas, Intermestic Partners, government agencies, etc.) unless a
  linked, verifiable source confirms it
- Invent dollar figures, dates, or projections not present in a cited source

## Required format for proposals
Every file in `proposals/` must follow `proposals/TEMPLATE.md`, including a
`sources:` list. PRs that add or edit a proposal without sources will be
rejected by CI (see `.github/workflows/validate-proposals.yml`).

## Attribution
Every PR description must state whether it was authored by a human, an AI
agent, or both, and which model/tool if applicable.
