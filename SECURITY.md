# Security Policy

This repository hosts the release artifacts and update manifest for
Project Succession. The source code lives in a private repository; this
is the right place to report vulnerabilities in any part of the product.

Project Succession is developed and maintained by a single developer
(Jeremias Meister, CG-JM). Security reports are read and handled
personally.

## Reporting a Vulnerability

Please report vulnerabilities privately through either channel:

- **GitHub**: use [Private Vulnerability Reporting](https://github.com/JeremiasMeister/succession-releases/security/advisories/new) on this repository
- **Email**: contact@cg-jm.com — start the subject line with `SECURITY`

Please do not disclose vulnerabilities through public GitHub issues,
social media, or the community Discord.

Machine-readable contact information: https://cg-jm.com/.well-known/security.txt

### What to include

- The product component affected (desktop app, CLI, a DCC plugin, the
  website, or the backend) and the version you tested
- Steps to reproduce, or a proof of concept
- The impact you believe the issue has
- Your name or handle if you would like credit in the release notes

### Response targets

| Stage | Target |
|-------|--------|
| Acknowledgement | 3 business days |
| Initial assessment (severity, affected versions) | 14 days |
| Fix or mitigation plan communicated | 30 days |

These targets reflect a one-person team. Actively exploited
vulnerabilities are prioritized ahead of everything else and are
additionally reported to the relevant EU authorities as required by the
Cyber Resilience Act.

## Scope

In scope: the Project Succession desktop application and CLI, the
bundled DCC integrations, the update and licensing backend, and the
website cg-jm.com including checkout.

Out of scope: denial of service through volume alone, findings requiring
a compromised local machine or physical access, vulnerabilities in
third-party DCC tools themselves, and social engineering.

## Safe Harbor

Good-faith security research on the products and services above is
welcome. If you make a genuine effort to comply with this policy during
your research, I will consider it authorized, will not pursue legal
action against you, and will work with you to understand and resolve the
issue quickly. Do not access, modify, or delete data that is not yours;
if you encounter someone else's data, stop and report the issue.

## Supported Versions

Only the latest released version receives security fixes. Please update
before reporting an issue that may already be fixed.

## Disclosure

Coordinated disclosure: please allow a fix to ship before publishing
details. Reporters are credited in the release notes unless they prefer
otherwise.
