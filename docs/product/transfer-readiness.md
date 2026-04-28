# Public Repository Readiness

This repository is the public open-source target for Nexgit. Use this checklist before announcing the project broadly or running a contributor onboarding push.

## Repository Target

Public GitHub target:

```text
Codelab-Davis/nexgit
```

History policy:

```text
Use a clean initial commit in this repository. Do not preserve test-repo churn.
```

## Required Before Public Announcement

- Product planning docs exist and are linked.
- Contributor MVP milestone is atomic and understandable.
- Issue templates are ready.
- Labels are synced.
- Discussions are enabled.
- Branch protection is active.
- GitHub Actions pass on `main`.
- Dependabot is configured.
- CODEOWNERS is present.
- License, security policy, governance, code of conduct, and contributing docs are present.
- No test-only issues or comments are open.
- Maintainer permissions are confirmed.
- Secrets are absent from the repo and not required for public CI.

## Setup Steps

1. Confirm `main` is clean and CI is green.
2. Push the clean initial commit to `Codelab-Davis/nexgit`.
3. Recreate GitHub-side settings: labels, milestones, Discussions, branch protection, and seeded issues.
4. Confirm public CI passes.
5. Make the repo public when contributor-facing setup is complete.
6. Announce the project with links to onboarding and the Contributor MVP milestone.

## Completed Before Initial Commit

1. Finish founder/control planning.
2. Confirm `main` is clean and CI is green.
3. Copy the final working tree into this repository, excluding `.git`, build output, dependencies, and local caches.
4. Commit the clean initial project setup.

## Final Public Check

Before public announcement, verify:

- A new contributor can find the setup docs.
- A designer can find the design contribution path.
- A maintainer can find transfer, dependency, and protocol decisions.
- A first-time issue can be opened, labeled, and left unassigned.
- A pull request receives required checks and reviewer routing.
