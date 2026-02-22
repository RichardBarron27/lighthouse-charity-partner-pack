# Security Information

## Reporting a Vulnerability

If you discover a security issue with Lighthouse, please report it responsibly.

**Email:** richard@red-specter.co.uk

Please include:

- A description of the issue
- Steps to reproduce it (if possible)
- Your name (if you would like to be credited)

We take all reports seriously and will respond within 48 hours. We will not take legal action against anyone who reports a genuine security issue in good faith.

---

## Verifying File Integrity

When you receive the Lighthouse Charity Partner Pack, you can verify that the files have not been tampered with using the SHA-256 hashes provided in `SHA256SUMS.txt`.

### How to Check (Windows)

1. Open **Command Prompt** or **PowerShell**
2. Navigate to the folder containing the files
3. Run this command:

```
certutil -hashfile lighthouse-still-here.zip SHA256
```

4. Compare the output to the hash in `SHA256SUMS.txt`. They should match exactly.

### How to Check (Mac or Linux)

1. Open **Terminal**
2. Navigate to the folder containing the files
3. Run this command:

```
sha256sum lighthouse-still-here.zip
```

4. Compare the output to the hash in `SHA256SUMS.txt`. They should match exactly.

If the hashes do not match, the file may have been altered. Do not install it. Contact us at **richard@red-specter.co.uk**.

---

## How Lighthouse Protects Users

### No data leaves the device

All pattern matching happens locally in the browser. There are no API calls, no telemetry, no analytics, and no network requests of any kind. You can verify this using your browser's Developer Tools (F12 > Network tab).

### Shadow DOM isolation

The helpline overlay uses a Shadow DOM, which means its styling and behaviour are completely isolated from the host website. The chatbot website cannot detect, modify, or interfere with the overlay.

### No persistent storage of conversations

Messages are analyzed in memory and immediately discarded. The only data persisted to local storage is a snooze timestamp (a single number).

### Minimal permissions

Lighthouse requests only the `storage` permission and access to 12 specific chatbot domains. It does not request access to browsing history, downloads, notifications, clipboard, camera, microphone, or all websites.

### Open source

The entire source code is included in the extension. There is no build step, no minification, and no obfuscation. Every line of JavaScript can be read and audited.

---

## Responsible Disclosure

We follow responsible disclosure principles. If a vulnerability is reported:

1. We acknowledge receipt within 48 hours
2. We investigate and develop a fix
3. We release the fix and notify affected partners
4. We credit the reporter (with their permission)

---

## Contact

**Security reports:** richard@red-specter.co.uk
**General enquiries:** richard@red-specter.co.uk
**Web:** red-specter.co.uk

Red Specter Security Research
