# Roly JobTalent downloads

This repository hosts Windows x64 installers and update metadata for Roly JobTalent. Application source is maintained in a separate private repository.

[Download the latest release](https://github.com/isvidabogdan/roly-jobtalent-updates/releases/latest).

The installed app will let an operator check for a new version, download it, and explicitly choose Install and restart. Release metadata and installer integrity are verified before an update is installed. No GitHub account or token is required to download public releases.

Google Chrome is required for provider sign-in and selected-day read-only analysis. Node, Bun and a source checkout are not required by operators. Payroll databases, exports, browser profiles and credentials are stored locally and are never release assets.

Releases are built locally on Windows. No paid build service or hosted backend is required. Windows installers are currently unsigned; the separate update signature is not a Windows code-signing certificate.
