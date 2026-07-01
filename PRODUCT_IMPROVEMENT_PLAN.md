# Product Improvement Plan

Last updated: 2026-07-01

## Customer-language correction

Do not position this product as an AI detector. Customer language points to a
different problem: people want to protect voice, process, and credibility when
writing sounds generic, over-processed, or falsely accused of being AI-written.

Use language such as:

- prose-risk review;
- authorship-confidence support;
- pattern highlighting, not verdict scoring;
- false-positive caution;
- voice-preserving edits;
- separate "sounds generic" from "is AI."

## Product gap

The current package is useful as a prose-pattern checker, but the feature set
should make the non-detector stance impossible to miss. The product should help
users inspect visible writing patterns and improve the text without claiming to
prove how it was written.

## Capability backlog

1. Add a false-positive and authorship-boundary note to the README.
2. Expand `detector-settings.md` with separate modes for prose risk, voice
   preservation, and authorship-confidence review.
3. Add a process-evidence checklist for users who need to defend original work
   with version history, sources, drafts, or notes.
4. Update examples to show pattern highlighting without accusatory authorship
   claims.
5. Add before/after samples for professional writing, portfolio copy, resumes,
   and client-facing drafts.

## Acceptance criteria

- The product never claims that it can prove AI authorship.
- Flag output names visible prose patterns and gives exact excerpts.
- Rewrite output preserves facts, voice, and domain specificity.
- Examples show false-positive caution and process evidence.
- Public copy avoids "detect AI with accuracy" style claims.
