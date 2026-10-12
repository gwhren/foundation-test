## Decisions

1. Add `CONTRIBUTING.md` at the repository root as the planned implementation's only changed file.
2. Keep the guide brief: a short introduction explaining the repository's Foundation testing purpose and a clearly labeled “How to run” section.
3. Base run guidance on the repository's actual contents. The current clone has no application code, build configuration, or runnable entry point, so describe that there is currently no application startup or build step. Recheck the repository during implementation and document supported commands if a runnable workflow has appeared.
4. Verify the guide by reviewing its Markdown, checking factual claims and any commands against repository files, and inspecting the change scope. Runtime tests are unnecessary while the change is documentation-only and there is no runnable application.

## Rationale

1. A root-level `CONTRIBUTING.md` directly satisfies the tracker request and gives contributors a conventional place to find guidance. Expanding `README.md` instead was set aside because the request specifically names a contributing guide; unrelated file changes add no value to this item.
2. A concise introduction provides context for the run section without exceeding the requested small documentation change. A comprehensive contribution policy, coding standards, and detailed setup tutorial were set aside because the request and repository do not establish a need for them.
3. Accurate guidance is more useful than speculative setup steps. The README identifies this repository as a Foundation testing repository, and the inspected clone contains no runnable project. Invented dependency installation, build, or startup commands were set aside because there is no evidence supporting them. Rechecking at implementation time keeps the guidance accurate if the repository changes.
4. Content and scope review address the risks of this change: misleading guidance and unintended edits. Adding a test harness or runtime checks was set aside because neither would validate a brief guide in the current repository.

This stage produces only `decisions.md`. The planned guide remains for the implementation stage, and these decisions are ready for the required human review.
