---
name: Implementation task
about: One buildable unit of work, built whole by one pull request and judged by its scenarios
title: ""
labels: []
assignees: []
---

## Problem

<!-- What is wrong or missing, and why it matters, for a reader who was not
there when it was discussed. Say what, never how: where the code goes and how
it is built are the builder's to decide. -->

## Traces to

<!-- The requirement this builds, its revision and the criteria in scope:
`FR-XXX-000 rev N [criteria: id, id]`. For untraced defect work: `none (defect)`. -->

## Feature file

<!-- Where the acceptance scenarios live, mirroring the source tree: the
scenario for behaviour whose entry point is `src/a/b.rs` lives at
`tests/a/b.feature`. Generated from the requirement, never hand-edited; its
header carries the requirement id and revision. -->

## Acceptance criteria

<!-- Traced work: do not restate the requirement. Done when its scenarios for
the criteria in scope pass. List only what a scenario cannot carry, by
evidence kind:
  - event: the real occurrence that proves it, and who records it
  - artifact: the file and the text checked at the pull request's head
  - research: the toy it waits on
Untraced defect: one Gherkin scenario per criterion, at the observable level,
tagged @criterion-<n>. Steps name only what a cited contract exposes, never
endpoints, fields, tables or invented example data.

Every criterion is checkable against this issue's own pull request. Nothing is
deferred to another issue, another pull request or a release; when this issue
needs another's work, that issue comes first. Steps the gates already record
(tests, review, verify) do not belong here. -->

- [ ]

## Out of scope

<!-- What this deliberately does not do, and where that work lives. -->

## Notes

<!-- Evidence, links, prior art. -->
