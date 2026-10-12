# Proposed PR: Add contributing guide with run guidance

## Summary

Tracker item `82cf7699-041b-41d6-80e9-46a9823adb14` (Add documentation) requests a `CONTRIBUTING.md` with a short how-to-run section.

The implementation adds root-level `CONTRIBUTING.md`, introducing the repository's purpose of testing Foundation agents, rights, roles, and sandboxes. Its “How to run” section explains that there is currently no application to run and no startup or build step. This matches the inspected repository, which contains documentation and no runnable entry point or build configuration.

The proposed project change is the new guide. Planning and evidence files are run artifacts. `CONTRIBUTING.md` is currently untracked in this clone; the tracked-file diff is empty.

## Validation

- Prior evidence in `evidence/test-summary.md` reports five passing content checks: file presence, introduction, run heading and guidance, factual accuracy, and Markdown clarity/whitespace.
- That evidence reports an overall **FAIL** because the implementation scope check lacks the historical before/after records needed to complete verification. It found no content defect.
- This stage reviewed the guide, README, prior-stage deliverables, and repository inventory. All five prior deliverable hashes match the artifacts recorded in `prior.json`, and `git diff --check` passes for tracked changes. These checks do not resolve the missing implementation baseline or check untracked Markdown through Git.
- Runtime tests are not applicable: this is a documentation-only change with no runnable application or test suite.

## Human review

Review the guide and the incomplete scope verification recorded in `evidence/test-summary.md` before advancing the run. The implementation notes claim that only the guide and implementation notes were added, but the evidence stage could not independently establish the full historical scope.

This stage adds only `evidence/pr-summary.md`. No pull request has been opened and nothing has been pushed. Human review remains required; this summary does not advance the gate.
