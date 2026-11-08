# Security policy

This policy covers every public repository under [ohallord](https://github.com/ohallord) that does not have its own `SECURITY.md`.

## Reporting a vulnerability

**Do not open a public issue, pull request, or discussion.** Report privately with GitHub's private vulnerability reporting: open the affected repository, go to **Security → Report a vulnerability**, or use `https://github.com/ohallord/<repository>/security/advisories/new`.

Include:

- the repository, the affected component, and the version or commit
- steps to reproduce, or a proof of concept
- the impact as you understand it

What to expect:

- acknowledgement within **5 business days**
- an initial assessment and severity within **14 days**
- a fix or mitigation plan, with credit in the advisory unless you prefer to stay anonymous

Give the maintainer a reasonable chance to fix the issue before you disclose it publicly. The aim is to release fixes within 90 days of the report.

## Supported versions

Security fixes go to the latest release and the default branch only.

## Scope

In scope: the code, install scripts, container images, and deployment manifests published in the repository.

Out of scope:

- third-party products and services a project talks to; report those to their maintainers
- deployments that ignore the project's install guidance, such as exposing an admin interface without authentication
- issues already documented as known limits in the repository's README
