# Awesome Claude Plugins

A Claude Code plugin marketplace manifest maintained in this repository. The manifest declares 24 plugins with local source paths; examples include `connect-apps` and `frontend-design`. Each plugin has its own author, behavior, permissions, and data flow. The marketplace listing does not certify every plugin as safe, current, production-ready, or endorsed.

## Browse and install

See the [documentation index](docs/README.md) for nested module README files.

- [Marketplace manifest](.claude-plugin/marketplace.json): source paths and descriptions for listed plugins.
- [Legacy catalog](marketplace.json): category, description, author, and tags.
- [connect-apps manifest](connect-apps/.claude-plugin/plugin.json): plugin-specific metadata.
- [frontend-design manifest](frontend-design/.claude-plugin/plugin.json): plugin-specific metadata.

Use Claude Code's current plugin marketplace documentation to add this marketplace and select plugins. Review the selected plugin files and upstream owner before enabling it. Some listed plugins can send messages, create issues, access app accounts, or modify code. Approve only the capabilities you need.

The catalog also contains paths to folders without a separate README at the checked location. Use the manifests and source files as the authoritative description of what is present.

## Trust and source boundaries

The marketplace metadata names multiple authors, including Composio and Anthropic. A name in metadata is attribution, not proof of endorsement or of current upstream synchronization. Verify origin, version, license, and update status for each plugin.

No root license or security policy was found at the checked paths. Confirm the applicable license before redistribution.

See [SECURITY.md](SECURITY.md) for review guidance and [CONTENT_REVIEW.md](CONTENT_REVIEW.md) for removed README claims.
