# Event App
Mobile application for organizing events.
## Features
- Create events
- Manage participants

## Setup Instructions
1. Clone the repository from GitHub.
2. Open `src/index.html` in a web browser.

## Remote Sync
Remote changes are received asynchronously: Fetch first, review, then Pull.


## Project Structure
- `src/index.html` - main HTML page of the application.
- `docs/readme.md` - project documentation.
- `docs/contributors.md` - list of contributors.
- `commits.txt` - exported commit history.

## Git Workflow in VS Code
1. Repository initialized via Source Control (Initialize Repository) and published to GitHub.
2. Each task is developed in a separate branch: `feature-style` (design), `feature-docs` (documentation).
3. Changes are staged with "+", committed with the check mark and pushed with Sync/Publish.
4. Remote changes are received with Fetch first, then Pull.
5. Branches are merged into `main`; conflicts are resolved in the Merge Editor.
6. Mistakes are fixed with Revert Commit, Undo Last Commit or Discard Changes.
7. Single commits are copied between branches with `git cherry-pick`.

## Resilience
Alternative path: revert to restore previous state.