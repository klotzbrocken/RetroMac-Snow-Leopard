# Security Policy

RetroMac Snow Leopard is distributed as a signed and notarized macOS app. Only the latest release receives security fixes.

| Version | Supported          |
| ------- | ------------------ |
| 3.0.x   | :white_check_mark: |
| < 3.0   | :x:                |

## What the app does on your Mac

- It asks for no permissions (no Accessibility, no Screen Recording, no Automation).
- It makes no network requests of its own; it has no update check, no analytics and no account.
- It changes two things you can undo by hand at any time: the desktop picture and the auto-hide of the macOS Dock. Quitting puts both back.

## Reporting a vulnerability

Please report security issues **privately**, not as a public issue.

Preferred: the **Security** tab of this repository → **Report a vulnerability**.
Alternatively, email **maik.klotz@gmail.com** with a description, steps to reproduce, and the app and macOS versions.

- **Acknowledgement:** within 5 business days.
- **Status update:** within 10 business days.
- **Credit:** in the release notes once a fix ships, if you wish.

The source lives in the [RetroMac repository](https://github.com/klotzbrocken/RetroMac/tree/single-click-app); reports about shared code may also be filed there.
