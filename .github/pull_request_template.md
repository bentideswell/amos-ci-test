<!--
PR TITLE: Conventional Commits format — <type>: <short description>
  e.g. feat: add invoice export to datahub module
  Types: feat / fix / chore / docs / test / refactor / perf
  (hotfix: / patch: are reserved for hotfix branches on uat/main — see the
  Git Branching & Workflow Standard)
This drives the automatic version bump. Don't skip the prefix.
-->

## What & why

<!-- One or two sentences: what changed, and why. -->



Basecamp card: <!-- optional link, if there is one -->

---

## Release Notes

<!--
INTERNAL — read verbatim by the build pipeline for the deployment manager.
Keep the heading exactly as "## Release Notes"; the pipeline parses it literally.
Delete whichever subsections don't apply. Delete this whole section only if
the PR is a pure promotion/backport with nothing new to log — otherwise fill
it in, even briefly.
Audience is internal/ops — file, module or component names are fine here if
they're useful context. Still describe the change itself, not "how", though.
-->

### Added
-

### Changed
-

### Fixed
-

---

## Client Impact

<!--
CLIENT-FACING — read by the release-notes plugin when drafting a client note.
One sentence, in words a client's admin/HR/registry staff would use — not
developer language. No ticket numbers, no repo/branch/table/column/function
names, no developer names.
If this has no client-visible effect (refactor, tests, CI, tooling, dependency
bump, internal-only change), write "Client impact: none".
-->

Client impact:

---

### Before merging

- [ ] PR title follows Conventional Commits
- [ ] `## Release Notes` filled in (or intentionally omitted for a pure promotion/backport)
- [ ] `Client impact:` line filled in
- [ ] `client-facing` label applied, if the Client impact line describes something a client would notice
- [ ] Instructional comments above deleted
