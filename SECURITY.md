# Security Policy

## Supported Versions

We release patches for security vulnerabilities for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 0.1.x   | :white_check_mark: |
| < 0.1   | :x:                |

## Reporting a Vulnerability

We take the security of Vibing seriously. If you believe you have found a security vulnerability, please report it to us as described below.

### Where to Report

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them via email to: security@vibingjustspeakit.com

If you prefer, you can also use GitHub's private vulnerability reporting feature:
1. Go to the [Security tab](https://github.com/VibingJustSpeakIt/Vibing/security)
2. Click "Report a vulnerability"
3. Fill out the form with details

### What to Include

Please include the following information in your report:

- Type of vulnerability
- Full paths of source file(s) related to the vulnerability
- Location of the affected source code (tag/branch/commit or direct URL)
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit it

### Response Timeline

- **Initial Response**: Within 48 hours
- **Status Update**: Within 7 days with an initial assessment
- **Resolution**: Depends on severity and complexity

### What to Expect

1. We will acknowledge receipt of your vulnerability report
2. We will confirm the vulnerability and determine its impact
3. We will release a fix as soon as possible, depending on complexity
4. We will communicate the vulnerability and fix in our release notes

### Disclosure Policy

- Please give us reasonable time to fix the vulnerability before public disclosure
- We will credit you in the security advisory (unless you prefer to remain anonymous)
- We aim to disclose vulnerabilities within 90 days of the initial report

## Security Best Practices for Users

### For macOS Users

- Only download from official sources (GitHub releases or our website)
- Verify the app is properly notarized by Apple
- Grant only necessary permissions (accessibility, microphone, screen recording)
- Keep the app updated to the latest version

### For Windows Users

- Download from Microsoft Store or official GitHub releases
- Verify the publisher before installation
- Grant only necessary permissions
- Keep the app updated to the latest version

### Privacy Considerations

- Audio and context data is sent to our servers for processing
- Data is not stored or used for training after processing
- Review our privacy policy in the README
- Avoid using Vibing for sensitive or confidential information

## Known Security Considerations

### Data Transmission

- Audio recordings are transmitted to remote servers for transcription
- Screenshots and context information may be sent for better results
- All transmission should occur over encrypted connections

### Permissions

The app requires elevated permissions on both macOS and Windows:
- **Accessibility**: To detect active applications and input fields
- **Microphone**: To capture voice input
- **Screen Recording**: To capture context for better transcription

Only grant these permissions if you trust the application.

## Security Updates

Security updates will be released as soon as possible after a vulnerability is confirmed. Users will be notified through:

- GitHub Security Advisories
- Release notes
- README updates

## Questions?

If you have questions about this security policy, please open a discussion or contact us via email.

---

**Last Updated**: April 2026
