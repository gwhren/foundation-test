## Goal

Add a `CONTRIBUTING.md` with a short how-to-run section, as requested by tracker item “Add documentation.” The item is done when the file exists at the repository root and gives contributors concise, accurate guidance on running what this repository provides.

The current clone contains only `README.md` and `.gitignore`; it has no application code, build configuration, or runnable entry point. The documentation should explain that there is currently no application to run, rather than inventing setup commands or dependencies.

## Approach

1. Check the repository's tracked files and `README.md` again at implementation time to confirm whether a runnable entry point or documented workflow has been added.
2. Create root-level `CONTRIBUTING.md` with a brief introduction describing the repository's Foundation testing purpose and a short “How to run” section. If the repository remains documentation-only, state that no application startup or build step is available. If an entry point exists, document only commands supported by the repository.
3. Review the Markdown for clarity and verify that any stated commands match the repository. Confirm the diff contains only the intended documentation change; runtime tests are unnecessary for this documentation-only item.
4. Leave the result in the run clone for the required human review. Do not push or open a pull request.

Files touched: `CONTRIBUTING.md` (new). This stage creates only `plan.md`; implementation of the contributing guide belongs to the subsequent stage.
