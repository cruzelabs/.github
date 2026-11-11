# Contributing

These rules apply to every repository in this organization unless a repository says otherwise in its own files.

## How a change lands

1. Start from an issue. Planned work lives in Linear; link the issue in your pull request.
2. Branch from `main`. Keep one purpose per branch.
3. Open a pull request. Say what changed, why, and how you tested it.
4. Wait for the checks to pass and for a review from the team that owns the code.
5. Merge. Nobody pushes directly to `main`.

## Before you open a pull request

- Run the repository's own checks locally. Each repository lists them in its `AGENTS.md` or `README.md`.
- Never commit a secret, a token, a credentialed URL or personal data. Every repository scans for these on each pull request; turn on the local hook once per clone with `git config core.hooksPath .githooks`.
- Keep changes small enough to review in one sitting.

## Reviews

- The owning team reviews: Computer Vision for models, cameras and the driver app; IT for the API, portals, infrastructure and security.
- A change to a workflow file, a deploy script or a database migration needs a second look from a team lead.
- Reviewers check that the description matches the diff and that the stated test actually covers the change.

## Reporting a security problem

Do not open a public issue. Follow [SECURITY.md](SECURITY.md).
