# Development repository

Project Time Platform Dev is an independent repository for development and hardening of the existing Project Time Platform application.

- Source repository: [ahmedadeyemi-cts/project-time-platform](https://github.com/ahmedadeyemi-cts/project-time-platform).
- Imported revision: [`3f30bf1c6b56a5fe49116834e16b4ec2c1e13ea3`](https://github.com/ahmedadeyemi-cts/project-time-platform/commit/3f30bf1c6b56a5fe49116834e16b4ec2c1e13ea3), the source `main` revision selected on 2026-09-28.
- Import method: public source archive, without the original Git history.
- Independent identity: `ahmedadeyemi-cts/project-time-platform-dev`, locked in [`.verity/identity.json`](../.verity/identity.json).
- Image prefix reserved by the identity: `ghcr.io/ahmedadeyemi-cts/project-time-platform-dev`. No images have been published by this bootstrap.

No deployments, repository secrets, or deployment environments are configured for this development repository by the bootstrap. Imported deployment scripts and operational documents describe the source application and must be reviewed before use here.

Inherited workflows are retained for review. Bootstrap activation is restricted to `projectpulse-ci.yml` (application CI) and `ci.yml` (Verity hygiene and project gates). Other inherited workflows, including deployment, scheduled runtime checks and corporate mirroring, are disabled through repository settings. Retaining a workflow does not establish that its credentials, environment, or runtime target are configured for this repository.

The Verity scaffold adds a hygiene workflow and gate runner. Application gate definitions remain the architect role's responsibility. Until `.verity/gates.json` is defined, the scaffold's gate job fails explicitly; this bootstrap makes no claim that the imported application or its full CI suite is green.

The hygiene secret scan retains Gitleaks default rules. `.gitleaks.toml` records individually reviewed non-secret legacy matches, each restricted to its exact path and exact match; it does not exempt whole files or directories.
