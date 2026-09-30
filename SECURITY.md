# Security Policy

## Supported Versions

Only the latest release of Relent Tracker receives security fixes.

| Version | Supported |
| ------- | --------- |
| Latest release | ✅ |
| Older releases | ❌ |

## Reporting a Vulnerability

If you find a security issue, please **do not open a public issue**.

Instead, use GitHub's private vulnerability reporting:

1. Go to the repo's **Security** tab
2. Click **Advisories** → **Report a vulnerability**
3. Describe the issue and how to reproduce it

I'll review reports as soon as I can and aim to respond within a few days.

## Notes

- The app stores your study data in your own Firebase project / local storage - treat your Firebase config and keys as sensitive
- Never commit your keystore, keystore passwords, or Firebase secrets to the repo
