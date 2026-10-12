# Integration standards

- Define ownership, authentication, payload schema, versioning, and failure behavior for each interface.
- Prefer supported APIs and events; avoid undocumented internal endpoints.
- Make retry behavior safe through idempotency or deduplication where applicable.
- Set timeouts and handle transient failures explicitly; surface actionable operational errors.
- Protect credentials and sensitive payloads, and document monitoring and support ownership.
