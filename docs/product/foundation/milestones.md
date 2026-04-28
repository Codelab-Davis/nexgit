# Milestone Model

GitHub milestones are the live planning surface. These milestone definitions explain the intended arc without creating a second planning board.

## v0.1.0 - Contributor MVP

Goal: prove the architecture and contribution model.

Done when:

- Real repo status flows through Rust core, CLI, app-server, TUI, and desktop.
- Contributors can pick up atomic issues without being assigned by default.
- Maintainers have visible dependency, protocol, and transfer-readiness decisions.

## v0.2.0 - Local Stack Model

Goal: understand local branch stacks.

Expected work:

- Detect branches and parent relationships.
- Represent stack shape in shared Rust types.
- Show stack state in CLI and TUI.
- Prepare the desktop app for visual stack workflows.

## v0.3.0 - GitHub Workflow Core

Goal: connect local repo work to GitHub context.

Expected work:

- GitHub auth and remote detection.
- Issue and PR lookup.
- CI and review status.
- Headless commands that make GitHub workflows easier than raw `gh` scripting for common repo-maintainer tasks.

## v0.4.0 - Visual Workflow App

Goal: make the desktop and TUI useful workflow surfaces.

Expected work:

- Visual stack and branch state.
- PR, review, and CI context.
- Contributor next actions.
- Maintainer queue visibility.

## v1.0.0 - Open Source Repo Workflow Manager

Goal: a stable local-first workflow system for Git, GitHub, maintainers, contributors, and agent-friendly automation.

Expected work:

- Stable CLI command shapes.
- Stable app-server protocol versioning.
- Documented install and release process.
- Reliable packaging for CLI and desktop.
- Clear governance and maintainer operations.

## Planning Rule

Do not add broad implementation issues when atomic tickets are possible. Broad issues may exist only as maintainer-owned planning or design context.

Student-facing issues should be concrete enough to claim without a planning
meeting. Every task needs a definition of done and a verification section that
names the command, manual check, screenshot, or acceptance criteria maintainers
will use during review.
