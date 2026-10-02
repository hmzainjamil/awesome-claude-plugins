# Security and plugin review

Plugins can access connected accounts, invoke tools, send messages, change files, or transmit data to external services. A marketplace listing is not a security review.

Before installing a plugin:

- Read its manifest, instructions, scripts, MCP registrations, and network destinations.
- Confirm the source owner, update status, license, and required permissions.
- Use separate test accounts and non-sensitive data first.
- Limit OAuth scopes and review external actions before authorizing them.
- Remove access promptly when a plugin is no longer needed.

Do not publish credentials, private prompts, customer information, or exploit details in public issues. Report vulnerabilities through GitHub private reporting if enabled or notify the affected upstream maintainer privately.

No individual plugin audit or security guarantee is made by this repository.
