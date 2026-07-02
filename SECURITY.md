# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| latest `main` | Yes |

Only the current `main` receives security fixes.

## Data Handling

This repository is a Claude Code plugin registry (`.claude-plugin/` manifests
plus documentation). It contains no executable service, imports no credentials,
and makes no network calls of its own. Installing a plugin from this registry
runs that plugin's own code — review a plugin before installing it.

## Scope

The security surface is the plugin manifest metadata served from this registry.
No user data is processed here.

## Reporting a Vulnerability

Report security issues **privately** via GitHub's private vulnerability reporting:
the **Security** tab → **Report a vulnerability** on
<https://github.com/neckarshore-skills/neckarshore-plugins/security/advisories>.
This keeps the report confidential until a fix ships.

Include what you found, how to reproduce it, and the impact.

**Response time:** Best-effort — this is a solo-maintained project, not an SLA-backed service.
