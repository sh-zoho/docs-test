---
title: "Acme Security Guide — Custom SEO Title"
description: "This is a custom meta description set via Git frontmatter for TC-25."
---

# Security

## Data encryption

"TC-24 cache test — timestamp noted" - 16:13

All data transmitted to and from the Acme API is encrypted using TLS 1.3.
Data at rest is encrypted using AES-256.

## API key security

- Rotate API keys every 90 days
- Use separate keys for development, staging, and production
- Never commit API keys to version control

## IP allowlisting

Enterprise accounts can restrict API access to specific IP addresses or CIDR ranges.
Configure this in Settings → Security → IP Allowlist.

## Compliance

Acme is compliant with SOC 2 Type II, GDPR, and CCPA.
Contact security@acme.com for compliance documentation.

TC-26 large PR test
