# Security

## Reporting a Vulnerability

Please report security vulnerabilities through **GitHub private vulnerability reporting** (Security tab → Report a vulnerability) when available.

Do **not** open public issues with secrets, credentials, or sensitive client material.

## Guidelines

- Never commit secrets, API keys, tokens, or passwords. Use environment variables and keep real values only in local `.env` files (which must be gitignored).
- Rotate any accidentally disclosed credentials immediately and remove them from Git history before publishing.
- Treat any executable content (scripts, HTML, templates) with care. Run untrusted contributions only in isolated environments.
- Prefer the principle of least privilege for tokens and access rights.

## Dependencies

This repository uses Dependabot for dependency updates. Keep alerts and security updates enabled in repository settings.
