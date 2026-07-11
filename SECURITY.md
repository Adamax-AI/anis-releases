# Security Policy

## Supported versions

Anis is under active beta development. Only the **latest release** published on the
[Releases](https://github.com/Adamax-AI/anis-releases/releases/latest) page
receives security fixes. Please update before reporting an issue.

## Reporting a vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, email **support@anis.app** with:

- a description of the vulnerability and its impact,
- the Anis version (Settings → About) and your operating system, and
- steps to reproduce, or a proof of concept, if you have one.

We aim to acknowledge reports within a few business days and will keep you
informed as we work on a fix. Please give us a reasonable window to release a
patch before any public disclosure.

## Update integrity

Anis updates are cryptographically signed with ADAMAX's minisign key and verified
on the user's device before installation. Only artifacts published to this
repository's releases and referenced by the signed `latest.json` feed are trusted
by the app.
