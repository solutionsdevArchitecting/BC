# Contributing

## Before you start

- Review the architecture principles and the standards under `docs/`.
- Confirm the owning capability and intended app before adding AL objects.
- Keep changes focused, document externally visible behavior, and add automated tests for business logic.

## AL changes

- Open and build the individual app project rather than combining unrelated apps.
- Use the repository's AL formatting, analyzer, naming, and object-ID conventions.
- Keep app dependencies minimal and communicate across app boundaries through documented interfaces.
- Include test coverage and update relevant documentation when behavior or interfaces change.

## Pull requests

Describe the business problem, the affected apps, validation performed, and any upgrade or deployment considerations. Do not include secrets, customer data, or environment-specific credentials.
