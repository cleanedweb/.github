# Security policy

This policy covers every public repository in the [cleanedweb](https://github.com/cleanedweb) organization
(SDKs, integrations, the MCP server proxy, the GitHub Action and examples) and the CleanedWeb service they call.

## Report a vulnerability

Email **info@cleanedweb.com** privately. Please do not open a public issue or pull request for a security problem.

Include:

- the affected repository and version, or the affected URL;
- a short description and the time you observed it;
- a minimal reproduction using your own account and data.

Send non-secret identifiers, not credentials. If an API key was exposed, revoke it in the
[console](https://app.cleanedweb.com/?utm_source=github&utm_medium=security-policy) and give its non-secret identifier.
Do not access another customer's data while testing.

## Supported versions

Fixes go into the latest release of each package (PyPI, npm, Go module, GitHub Action major tag). Upgrade to the
latest version before reporting.

More: [Security and access](https://cleanedweb.com/docs/security/?utm_source=github&utm_medium=security-policy) ·
[security.txt](https://cleanedweb.com/.well-known/security.txt)
