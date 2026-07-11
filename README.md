# Anis — Releases · أنيس

**You speak, we write.**

[Anis (أنيس)](https://anis-site.pages.dev) is a speech‑to‑text desktop app by
**ADAMAX**. You dictate, Anis transcribes, and **Commands (أوامر)** decide what
happens to your words next — clean them up, translate them, and paste the result
straight where your cursor is.

This repository is the **official public home for Anis downloads and the
auto‑update feed**. The application's source code is developed privately by
ADAMAX; only signed release artifacts are published here.

---

## Download

Get the latest installer from the **[Releases](https://github.com/Adamax-AI/anis-releases/releases/latest)** page.

| Platform | File | Notes |
| --- | --- | --- |
| Windows 10 / 11 (x64) | `Anis_<version>_x64-setup.exe` | NSIS installer |

> Anis is currently in **beta**. Expect frequent updates.

## Automatic updates

You don't need to return here for new versions. Anis checks for updates on launch
and periodically while running. Every update is:

- **Signed** with ADAMAX's [minisign](https://jedisct1.github.io/minisign/) key and
  **verified on your machine** before it is installed, and
- delivered through this repository's `latest.json` update feed.

If a newer signed build is available, Anis downloads and installs it for you.

## Reporting a problem

Because the source lives in a private repository, **this repo is where you file
bugs and request features**. Please use the
**[Issues](https://github.com/Adamax-AI/anis-releases/issues)** tab and pick the
matching template. Include your Anis version (Settings → About) and your Windows
version so we can reproduce it quickly.

For security issues, **do not open a public issue** — see
[SECURITY.md](SECURITY.md).

## Support & links

- Website — https://anis-site.pages.dev
- Support — support@anis.app

---

© ADAMAX. All rights reserved. Anis is proprietary software. This repository
hosts distributable binaries and update metadata only; it does not grant any
license to the application's source code.
