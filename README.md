# Business Central AL workspace

This repository is organized into capability-based Business Central AL apps, shared integration assets, analytics, deployment guidance, and engineering documentation.

## Repository map

- `apps/` contains AL extensions grouped by business capability.
- `docs/` describes architecture, business capabilities, development standards, environments, and runbooks.
- `integrations/` holds API contracts, events, connectors, and mappings.
- `analytics/` contains semantic models, data products, and reconciliation guidance.
- `deployment/` documents pipelines, environments, and releases.
- `tests/` contains shared test data and performance and end-to-end test guidance.
- `tools/` and `templates/` provide development utilities and reusable starting points.

Each AL app should be independently buildable and versioned. Add its `app.json`, source, tests, and project-specific instructions when implementation begins. Keep dependency direction explicit and prefer stable interfaces between apps.

## Getting started

Install the AL Language extension for Visual Studio Code, open the relevant app folder, configure its Business Central target in `launch.json`, and download symbols before building. See [AL development standards](docs/standards/al-development.md) and the relevant capability README.

## Contribution and security

Read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting changes and follow the reporting process in [SECURITY.md](SECURITY.md).
